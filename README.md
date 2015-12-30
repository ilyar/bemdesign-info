#bemcustom Install

## bemcustom-blocks + bemcustom-components
Клонируем библиотеку блоков
```
git clone https://github.com/bemcustom/bemcustom-blocks bemcustom
```
 
Устанавливаем все необходимые зависимости
```
npm i 
```

Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
```
export PATH=./node_modules/.bin:$PATH
```
Запускаем сервер
```
bem server
```
Открываем в браузере
```
http://localhost:8080/desktop.bundles/index/index.html
```
    
## Только bemcustom-components    
Если хотим использовать только кастомноую версию БЭМ компонентов, то нужно заменить дефолтную папку libs/bem-components/design в вашем project-stub на:

Все изменяемые параметры вынесенны в переменные custom.styl + colors.styl
```
git clone https://github.com/bemcustom/bemcustom-components --branch custom design
```
В переменые вынесены только цвета colors.styl (Если хотим перекрасить дефолтную тему island, сохранением зависимостей оттенков)
```
git clone https://github.com/bemcustom/bemcustom-components --branch cosmetic design
```

    





