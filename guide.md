```
bemcustom-blocks
   ├── desktop.blocks
   │   └── text - https://github.com/bemcustom/bemcustom-typography
   └── libs
       └── bem-components
           └── design 
               ├── colors.sty - https://github.com/bemcustom/bemcustom-components/blob/custom/design/colors.styl
               └── custom.styl - https://github.com/bemcustom/bemcustom-components/blob/custom/design/custom.styl
```

#bemcustom - Гайд по кастомизации
Библиотека **bemcustom** - https://github.com/bemcustom состоит из двух основных составляющих **bemcustom-components** - https://github.com/bemcustom/bemcustom-components и **bemcustom-blocks** - https://github.com/bemcustom/bemcustom-blocks. В свою очередь **bemcustom-components** входит в состав **bemcustom-blocks**. И если вы хотите кастомизировать только основные БЭМ компоненты без использования блоков, то вы легко можете это сделать.


##bemcustom-components
Предусмотренно два вариант кастомизации БЭМ компонентов
* Перекрасшиваем тему Яндекс тему island, с сохранением всех зависимостей оттенков:
	** **bemcustom-colors** - https://github.com/bemcustom/bemcustom-colors
	** **Как проходила кастомизация цвета** - http://codepen.io/koloskof/pen/NGmeGL

* Полная кастомизация всех параметров (цвета, отступы, границы, скругления итд)

#### Текст
**Attach, Button, Checkbox, Input, Link, Radio, Select, Textarea**

* Шрифт
* Размер
* Межстрочечный интервал


### Обертки
**Attach, Button, Checkbox, Input, Link, Radio, Select, Textarea**
* Бордеры (заданные через абсолютное позиционирование внутреннего элемента)
* Бордер-радиус внешних и внутренних блоков + (Первых и последних элементах группы)
* Чекнутые остояния заданные через box-shadow


### Стили для добавочных, внутренних элементов 
**галочка у Checkbox / точка у Radio / стрелка у Select / иконка у Button / иконка у Input / иконка у Menu-item**
	
* Позиционирование
* Ширина / Высота
* Фоновое изображение

	
### Индикаторы
**Spin, Progressbar**

* Размер (активной, неактивной части)
* Цвет (активной, неактивной части)

##bemcustom-typography
Вся типографика умышленно вынесена в отделный компонент. Для кастомизации ключевых параметров нужно поменять значения. Значание s должно совпадать со значениями - bem-components s-size, а значание m должно совпадать со значениями - bem-components l-size.

##bemcustom-blocks
Если вы кастомизировали только компененты и типографику, а затем решили использовать блоки то вам необходимо скопировать design и text в bemcustom-blocks. И можно начинать структурную и более детальную кастомизацию самих блоков.

