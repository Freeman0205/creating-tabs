# creating-tabs

This code allows you to use tabs so that when you click on them, certain content appears that corresponds to this tab. Interaction takes place using an eventListener.

Данный код позволяет использовать табы, что бы при клике на них появлялся определенный контент, соответствующий данному табу. Взаимодействие происходит с помощью обработчика событий.

let tab = document.querySelectorAll('.info-header-tab'),  //  ('.info-header-tab')  class tabs
        info = document.querySelector('.info-header'),    //  ('.info-header') Parent class tabs (Родительский класс) 
        tabContent = document.querySelectorAll('.info-tabcontent'); //   ('.info-tabcontent') Info content (Непосредственно контент связываемый с табами)
