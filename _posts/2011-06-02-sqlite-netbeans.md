---
title: SQLite NetBeans
tags:
thumbnail: http://1.bp.blogspot.com/-Uh4mEjsnmZc/TecrJnVbChI/AAAAAAAAAKQ/jh5bqLy2zkM/s72-c/instant%25C3%25A1nea1.png
blogger_id: tag:blogger.com,1999:blog-3290987933179858425.post-5648991122599032996
blogger_orig_url: http://scot3004.blogspot.com/2011/06/sqlite-netbeans.html
category: dev
---

Como podemos darnos cuenta para tener una aplicación robusta necesitamos un motor de bases de datos,
aunque mysql es el mas usado y el mas optimo para servidores,
al momento de hacer aplicaciones que sean facilmente portables se hace un infierno usarlo,
por eso en estos casos es recomendable usar un motor de bases de datos mas ligero, alli es donde entra a jugar SQLite.
SQLite es un gestor de bases de datos que proporciona gran portabilidad debido a que este funciona a travez de archivos,
ahora bien este permite ademas usar el estandar SQL,
muchos se preguntaran por que usar SQLite si puedo almacenar directamente al archivo
y me ahorro todo lo que tenga que ver con la creacion de la base de datos creando conectors y cosas asi,
si puedo usar un buffer y guardar yo mismo la base de datos en un archivo,
bueno resulta que SQLite te ahorra esa parte,
ademas en caso de querer un motor mas potente,
no te tocara reescribir si creaste un conector abierto a las posibilidades,
como yo XD, en fin.

<!-- more -->

Respecto a los pasos con url las instrucciones de instalación están en la pagina de cada uno

1.  Instalar Netbeans, en caso que no lo tengas instalado [http://www.netbeans.org/"](http://www.netbeans.org/)
2.  Crear tu proyecto en Java Netbeans
3.  Descargar sqlite para crear la base de datos <http://www.sqlite.org/>
4.  Buscar un editor grafico [http://sqliteman.com/](http://sqliteman.com) si no sabes de sql
5.  Crear la base de datos
6.  Descargar Sqlite JDBC <https://bitbucket.org/xerial/sqlite-jdbc>
7.  Guardar  el driver en una carpeta lib o algo asi en la carpeta de tu proyecto
8.  Añadir sqlite JDBC que descargaste en netbeans abriendo el proyecto, luego haces clic derecho en donde dice librerías añadir jar/carpeta y selecciona sqliteJDBC
9.  Para finalizar crea las clases de conexión a la base de datos y los respectivos DAO
10. ya que tienes el driver sqlite instalado y configurado, emocionate viendo que opciones te da tener una base de datos en tu proyecto

por ultimo una vista previa de mi trabajo
hecho en GNU/Linux
![Creación de tabla](//1.bp.blogspot.com/-Uh4mEjsnmZc/TecrJnVbChI/AAAAAAAAAKQ/jh5bqLy2zkM/s1600/instant%25C3%25A1nea1.png)
![Conexión con la base de datos](//3.bp.blogspot.com/-ZPMDat83nvQ/TecrLV8YRxI/AAAAAAAAAKU/LY9L4uVOOlQ/s1600/instant%25C3%25A1nea2.png)
![NetBeans creando](//4.bp.blogspot.com/-qxXGsXJujfg/TecrMatevpI/AAAAAAAAAKY/1XTnmPcWNK8/s1600/instant%25C3%25A1nea3.png)
![Consulta de registros](//3.bp.blogspot.com/-sSOke2IJHco/TecrOLZnoHI/AAAAAAAAAKg/Udnsf2A9_o0/s1600/instant%25C3%25A1nea5.png)
