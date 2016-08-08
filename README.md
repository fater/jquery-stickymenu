# jQuery Sticky Menu Plugin

[![GitHub version](https://badge.fury.io/gh/fater%2Fjquery-stickymenu.svg)](https://badge.fury.io/gh/fater%2Fjquery-stickymenu)

### Для чего плагин?
* Плагин постоянно отображает на экране указанное меню, его иначе называют "Липким меню".

![jQuery Sticky Menu Plugin](http://files.fater.ru/git/jquery-stickymenu/1.gif)

## Dependencies
* **jQuery** - необходимая библиотека для работы модуля

## Bower installation
```
$> bower install jquery-stickymenu --save
```
Происходит установка плагина. В текущем пакете есть зависимость jQuery. Если jQuery не были установлены через bower, он установится вместе с плагином ScrollToTop. 


### Как подключить плагин

Подключите файлы в HTML проект:
```html
// jQuery common library
<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>

// Sticky Menu Plugin
<script src="url-to-module/jquery-stickymenu/dist/jquery.stickymenu.min.js"></script>
```

### Как использовать плагин
Необходимо разместить следующий HTML код на странице:
```html
<div style="position: relative;">
    <div id="stickymenu">
        ...
    </div>
</div>
```


## Описание параметров
```js
$.stickymenu({params}); 
```
Тип входящих данных: JSON:

Параметр | Описание | По умолчанию
--- | --- | ---
**object_id** | ID объекта плавающего меню | `stickymenu`
**standoff** | Отступ плавающего меню от верхней границы экрана | `0`
**standoff_object_id** | Отступ плавающего меню относительно такого же плавающего меню | d

