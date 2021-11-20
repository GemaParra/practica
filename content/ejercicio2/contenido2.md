---
title: "Diagrama"
date: 2021-11-19T19:58:46+01:00
draft: false
---



 > ## ¿Qué pasa cuando escribes una dirección web en tu navegador?


* Se envía la solicitud al servidor. Este la recibe y comienza el proceso de construir la página web. Si existe código PHP, se ejecuta en este momento, se hacen todas las consultas a la Base de Datos. El resultado es una página con HTML y tal vez Java Script.

* Tu navegador recibe la página, interpreta y usa el HTML para construirla. La tienes en pantalla.

*  Mientras interactúas con la página, todo es procesado por Javascript. Interactuará contigo respondiendo a tus eventos, hasta que cierres la página.

*  Si necesitas una consulta a la BD, para no cargar otra página, se puede utilizar la tecnología AJAX que permite a JavaScript mandar peticiones a scripts de PHP. Javascript recibe como respuesta cadenas de texto, y en base a la respuesta puede dibujar nuevos elementos de la interfaz gráfica o cambiarlos. Tienes una página interactiva.



{{< figure src= "/images/DiagramaOK.png" title="diagrama" >}}  <figcaption> Diagrama proceso carga web </figcaption>
