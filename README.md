# Resumen-Skills
Resumen Skills



Modelamiento de datos basado en. :  

    TABLAS FACT SON EVENTOS MEDIDOS ( VISITAS , QUEJAS,ASISTENCIA,CALIFICACIONES,VENTAS ,DEVOLUCIONES) SIEMPRE SON POCAS COLUMNAS

    TABLAS DIMENSIONES (SON UTILIZADAS PARA SEGMENTAR QUE, QUIEN ,COMO ,CUANDO DONDE SUCEDIO EL EVENTO)
    
    
    DAX = DATA ANALUSIS EXPRESSIONS 
    
    
    1 lo primero que hemos realizado ha sido cargar las bases de datos desde access

2 hemos organizado las tablas intentando primero realizar un modelo estrella para este projecto pero  este projecto requiere otro tipo de modelamiento donde existan en la parte superior las dimensiones y en la parte inferios las tablas de FACT


![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc915466-9598-43a5-9cfb-df9279a04ac6/Untitled.png)

1 analizaremos ventas x producto

2 las ventas van desde el ano 2007 hasta el ano 2009

3 dejaremos de actualizar ciertas tablas para optimizar el trabajo 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bc915466-9598-43a5-9cfb-df9279a04ac6/Untitled.png)

Buscar dimensiones  para analizar en este caso analizaremos las ventas por categoria comparando las ventas del ano anterior con el presente, ademas de calgular los ingresos son descuentos Utilizando la funcion SUMX


![image](https://user-images.githubusercontent.com/112581327/196499753-e6e93937-3092-4412-81a4-ec55257b88d9.png)

En este graphico resumen se pueden obtener las ventas, costos y utilizad por ano , ademas de analizar cada uno de los item por continente , por categoria o subcateoria 

![image](https://user-images.githubusercontent.com/112581327/196500267-c23b8927-2a36-4bdc-80bb-b83af7d96853.png)


Ademas con la informacion obtenida en la base de datos es posible crear escenarios creando a traves de dax una funcion calculada que me permite generar una variacion % del precio unitario, Siempre y cuando los costos se mantengan igual, de esta manera podemos obtener diferentes escenarios puntos de equilibro  que sran utiles para crear escenarios y planes de contingencia

![image](https://user-images.githubusercontent.com/112581327/196502031-eada1b6c-4908-43d1-9c9b-662a7d348cf0.png)






