
#bemcustom Install

## Полный пакет bemdesign-blocks + bemdesign-components
1. Клонируем библиотеку блоков
 ```
 git clone https://github.com/bemdesign/bemdesign-blocks --branch master bemdesign
 ```
 
2. Открываем папку и устанавливаем все необходимые зависимости
 ```
 cd bemdesign
 ```
 ```
 npm i 
 ```

3. Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
 ```
 export PATH=./node_modules/.bin:$PATH
 ```
 
4. Клонируем библиотеку кастомных компонентов (заменяем текущую папку design)
 ```
 cd libs/bem-components/
 ```
 ```
 sudo rm -r design
 ```
 ```
 git clone https://github.com/bemdesign/bemdesign-components --branch custom design
```
 
5. Возвращаемся в кореневую директорию и запускаем сервер
 ```
 cd ../../
 ```
 ```
 bem server
 ```

6. Открываем в браузере
 ```
 http://localhost:8080/desktop.bundles/index/index.html
 ```
