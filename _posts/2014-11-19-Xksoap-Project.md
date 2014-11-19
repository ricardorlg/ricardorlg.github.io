---
layout: post
title: Xksoap Project
published: true
---

###### Proyecto Xksoap 

Junto con [Omar Rodriguez](http://omcaroco.github.io/) hemos iniciado el desarrollo de una librería que facilite el consumo de servicios SOAP en Android utilizando la librería Ksoap2, este proyecto busca reducir el tiempo de codificación necesario para poder consumir este tipos de servicios, está escrito en Xtend debido a las grandes ventajas que ofrece este lenguaje, entre estas su capacidad de generar código java, así como las anotaciones activas; con esto queremos que los desarrolladores no tengan que perder tiempo sobrescribiendo métodos que al final son solo código espagueti, la librería permitirá con una anotación hacer que cualquier bean sea serializable para la librería Ksoap, incluyendo tipos primitivos, listas y Objetos definidos, también se tendrá una anotación en la cual al definir ciertos parámetros generara el código necesario para consumir el servicio, enviando los parámetros definidos por el desarrollador y a su vez llevando a cabo los "casting" necesarios para obtener la respuesta del servicio, sin tener que escribir algún "Marshall" para esto, estas anotaciones satisfarán de manera inicial las configuraciones más generales de la librería Ksoap2 y a su vez permitirán al desarrollador tener libertad  de poder extender o definir sus propios comportamientos. El código del proyecto se encuentra en el siguiente link:
[Ksoap Project](https://github.com/ricardorlg/Xksoap)

A continuación se encuentra la presentacion del proyecto:

<iframe src="//slides.com/omarcamilorodriguezcortes/xdrual/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>