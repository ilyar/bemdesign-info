
#bemcustom Install

## Полный пакет bemcustom-blocks + bemcustom-components
1 Клонируем библиотеку блоков
```
git clone https://github.com/bemcustom/bemcustom-blocks bemcustom
```
 
2 Устанавливаем все необходимые зависимости
```
npm i 
```

3 Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
```
export PATH=./node_modules/.bin:$PATH
```
 
4 Клонируем библиотеку кастомных компонентов (заменяем текущую папку design)
```
cd libs/bem-components/
```
```
sudo rm -r folderName
```
```
git clone https://github.com/bemcustom/bemcustom-components --branch custom design
```
 
5 Запускаем сервер
```
bem server
```

6 Открываем в браузере
```
http://localhost:8080/desktop.bundles/index/index.html
```
