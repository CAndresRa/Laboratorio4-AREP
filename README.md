# Laboratorio4-AREP

### Autor: Carlos Andrés Ramírez Torres
### Fecha: Viernes, 28 de Agosto del 2020

## Uso 

Para el desarrollo del proyecto se utilizo **Maven** como una herramienta para la construccion y gestion del mismo, el codigo fue desarrollado con el lenguaje de programación **Java**.

* Utilizar `mvn package` para la generacion del fichero .jar con los .class compilados.

* Una vez verificado mediante el `mvn package` ingresar el siguiente comando en el terminal para iniciar el servidor:

`java -cp target/classes co.edu.escuelaing.sparkd.microspring.MicroSpringBoot co.edu.escuelaing.sparkd.microspring.component.HelloController`

* Ingresar mediante el browser al localhost:36000

Los recursos disponibles se encuentran en:

* http://localhost:36000/Apps/hello
* http://localhost:36000/Apps/pi
* http://localhost:36000/Apps/webapp

## Diagrama de arquitectura generado.

![](https://github.com/CAndresRa/Laboratorio4-AREP/blob/master/A.png)

El siguiente diagrama muestra la implementacion de un servidor HTTP, el cual recibe solicitudes mediante el browser, estas solicitudes son enviadas a un endpoint definido en la clase HelloController y se le envia al cliente el recurso solicitado.
