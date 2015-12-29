#Install

Клонируем библиотеку блоков
    
```
    git clone https://github.com/bemcustom/bemcustom-blocks bemcustom
```
 
Устанавливаем все необходимые зависимости
```
    npm i 
```

Открываем парку БЭМ компонентов 
```
    cd bemcustom/libs/bem-components
```

Клонируем кастомизированную тему компрнентов
```
    git clone https://github.com/bemcustom/bemcustom-components --branch custom design
```
если хотим только подкрашивать дефолтную тему Island, то клонируем
```
    git clone https://github.com/bemcustom/bemcustom-components --branch cosmetic design
```

Устанавливаем все необходимые зависимости
```
    npm i
```

Возвращаемся в корневыю дирректорию
```
    cd ../../
```
Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
```
    export PATH=./node_modules/.bin:$PATH
```
Запускаем сервер
```
    bem server
```
    
    





