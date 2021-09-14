# Prueba Técnica - Programador (Back-end) (LARAVEL)
La siguiente es una prueba para evaluar a los postulantes a programador **Back-end** (**LARAVEL**).

## INTRODUCCIÓN
Este repositorio contiene una serie de requerimientos de un Caso Práctico, que busca evaluar las capacidades técnicas del candidato con respecto a las principales funciones y responsabilidades que se requieren dentro del área de Desarrollo de Tecnología de _Rezglo_.

#### ¿Qué se busca evaluar?
Principalmente los siguientes aspectos:
* Creatividad para resolver los requerimientos,
* Calidad del código entregado (estructura y buenas prácticas),
* Eficiencia de los algoritmos entregados,
* Familiaridad con Frameworks y plataformas de desarrollo.

## IMPORTANTE
1. **Se exige utilizar el framework de php (LARAVEL)**
2. Recomendamos emplear un máximo de **4 (cuatro) horas** y enviar todo lo que puedas.
3. Se requiere de una **cuenta de GitHub** para realizar este ejercicio.
4. **Al finalizar**, para entregar su proyecto:
    * Se debe subir el proyecto para un repositorio publico que creen en su cuenta de github y enviar detalles (dirección del repositorio) a la siguiente dirección de correo electrónico [cvrecruitment74@gmail.com](mailto:cvrecruitment74@gmail.com).

## EJERCICIOS

### Ejercicio #
Se desea administrar el acceso de vehículos a un estacionamiento de pago. El estacionamiento no se encuentra automatizado, por lo que existe un empleado encargado de registrar las entradas y salidas de vehículos.

Los vehículos se identifican por su número de placa. Cuando un vehículo entra en el estacionamiento el empleado registra su entrada y al salir registra su salida y cobra el importe correspondiente por el tiempo de estacionamiento.

El importe cobrado depende del tipo de vehículo:
* Los clientes pagan a la salida del estacionamiento a razón de $0.5 por minuto.
Se prevé que en el futuro puedan incluirse nuevos tipos de vehículos, por lo que la aplicación desarrollada deberá ser fácilmente extensible en ese aspecto.


A continuación se describen los casos de uso. No se entra en detalles de la interacción entre el empleado y la aplicación (punto 1 de cada caso de uso), puesto que no va a ser tarea de este ejercicio desarrollar esa parte.

###### **Caso de uso "Registra entrada"**
1. El empleado elige la opción "registrar entrada" e introduce el número de placa del coche que entra.
2. La aplicación apunta la hora de entrada del vehículo.

###### **Caso de uso "Registra salida"**
1. El empleado elige la opción "registrar salida" e introduce el número de placa del coche que sale.
2. La aplicación realiza las acciones correspondientes al tipo de vehículo:
    * Clientes: obtiene el importe a pagar


###### **Caso de uso "Listado de clientes"**
1. El empleado elige la opción "Ver informe de clientes". El formato del archivo será el mostrado a continuación:

```
Núm. placa 	Tiempo estacionado (min.) 	Pagado
T1247B 	        20134 			        1006.70
ABT893	        4896			        244.80
... 	        ..... 			        .....
```

2. Mostrar listado de chapas de los 3 vehiculos que más usan el estacionamiento. 


##### Persistencia de datos
La información de cada una de las estancias de los vehículos será almacenada en una base de datos. El manejador de base de datos puede ser modificado en cualquier momento.

##### Puntos que se deben desarrollar
** La aplicación debe brindar las funcionalidades desde un API construida para ustedes (deben enviar junto al proyecto una simple documentación de como se llama cada endpoint de API).

** No es necesario construir una interfaz visual.



