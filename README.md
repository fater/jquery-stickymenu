#Sticky Menu jQuery plugin

Версия: **1.0.0**

###Для чего плагин?
* Плагин отображает заданное меню находится постоянно на экране, его иначе называют "Липким меню".

##Зависимости
* **JQuery** - необходимая библиотека для работы модуля

##Установка с помощью Bower
`$> bower install jquery-stickymenu --save` - происходит установка плагина. В текущем пакете есть зависимость jquery. Если jquery не были установлены через bower, он установится вместе с плагином ScrollToTop. 


###Как подключить плагин

Подключите файлы в HTML проект:
```html
// Stickymenu плагин
<script src="url-to-module/jquery-stickymenu/dist/jquery.stickymenu.js"></script>
// Стили
<link rel="stylesheet" href="url-to-module/jquery-stickymenu/dist/jquery.stickymenu.css">

// JQuery
<script src="http://code.jquery.com/jquery-2.1.4.min.js"></script>

```

##Описание параметров
```js
$.stickymenu (['ID элемента']); 
```
Тип входящих данных: Текстовое значение

