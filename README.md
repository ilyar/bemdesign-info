#bemcustom Install

## bemcustom-blocks + bemcustom-components
1. Клонируем библиотеку блоков
 ```
 git clone https://github.com/bemcustom/bemcustom-blocks bemcustom
 ```
 
2. Устанавливаем все необходимые зависимости
 ```
 npm i 
 ```

3. Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
 ```
 export PATH=./node_modules/.bin:$PATH
 ```
 
4. Запускаем сервер
 ```
 bem server
 ```
5. Открываем в браузере
 ```
 http://localhost:8080/desktop.bundles/index/index.html
 ```
    
## Только bemcustom-components    
Если хотим использовать только кастомноую версию БЭМ компонентов, то нужно заменить дефолтную папку libs/bem-components/design в вашем project-stub. 

1. Выбираем один из вариантов:

Все изменяемые параметры вынесенны в переменные custom.styl + colors.styl
 ```
 git clone https://github.com/bemcustom/bemcustom-components --branch custom design
 ```
или

В переменые вынесены только цвета colors.styl (Если хотим перекрасить дефолтную тему island, сохранением зависимостей оттенков)
 ```
 git clone https://github.com/bemcustom/bemcustom-components --branch cosmetic design
```

2. Запускаем сервер
 ```
 bem server
 ```

3. Открываем в браузере
 ```
 http://localhost:8080/desktop.bundles/components/components.html
 ```



    





