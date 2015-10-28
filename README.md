#Sticky Menu jQuery plugin

Версия: **1.1.0**

###Для чего плагин?
* Плагин постоянно отображает на экране указанное меню, его иначе называют "Липким меню".

##Зависимости
* **JQuery** - необходимая библиотека для работы модуля

##Установка с помощью Bower
```{engine='sh'}
$> bower install jquery-stickymenu --save
```
Происходит установка плагина. В текущем пакете есть зависимость jquery. Если jquery не были установлены через bower, он установится вместе с плагином ScrollToTop. 


###Как подключить плагин

Подключите файлы в HTML проект:
```html
// Stickymenu плагин
<script src="url-to-module/jquery-stickymenu/dist/jquery.stickymenu.min.js"></script>

// JQuery
<script src="http://code.jquery.com/jquery-2.1.4.min.js"></script>

```

##Описание параметров
```js
$.stickymenu ({object}); 
```
Тип входящих данных: JSON:

* object_id
* standoff
* standoff_object_id

