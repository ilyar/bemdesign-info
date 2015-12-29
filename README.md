#Install

1. Клонируем библиотеку блоков
    
```
    git clone https://github.com/bemcustom/bemcustom-blocks bemcustom
```
 
2. Устанавливаем все необходимые зависимости
```
    npm i 
```

3. Открываем парку БЭМ компонентов 
```
    cd bemcustom/libs/bem-components
```

4. Клонируем кастомизированную тему компрнентов
```
    git clone https://github.com/bemcustom/bemcustom-components --branch custom design
```
если хотим только подкрашивать дефолтную тему Island, то клонируем
```
    git clone https://github.com/bemcustom/bemcustom-components --branch cosmetic design
```

5. Устанавливаем все необходимые зависимости
```
    npm i
```

6. Возвращаемся в корневыю дирректорию
```
    cd ../../
```
7. Чтобы не указывать путь к исполняемому файлу (node_modules/.bin/enb) используем:
```
    export PATH=./node_modules/.bin:$PATH
```

8. Запускаем сервер
```
    bem server
```
    
    





