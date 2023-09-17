# Ejercicio de peso de selectores
*, .container, .container href, h1, #titulo, !important.

👉¿Cuál es el peso de los siguientes selectores de CSS? ¿Cuál pesa más? ¿Cuál pesa menos? Define el peso de cada uno de estos selectores y ordenalos de más específicos a menos específicos. Aunque lo ideal es que lo calcules automáticamente mirando los apuntes, puedes comprobar posteriormente si los resultados son correctos mirando algunos de los TIPS que se detallan más abajo.
1. *: 0,0,0. Es el de menos peso ya que es un selector universal.
2. .container: 0,1,0. Tiene la importancia de una clase, atributo o pseudoclase. 
3. .container href: 0,1,1. Aparte de tener la importancia de una clase, atributo o pseudoclase, también tiene la de un elemento o pseudoelemento.
4. h1: 0,0,1. Tiene la importancia de un elemento o pseudoelemento.
5. #titulo: 1,0,0. Tiene la importancia de un ID.
6. !important: gana a todos.
> El orden sería: !important, #titulo, .container href, .container, h1 y *.
