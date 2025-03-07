# Actividad BackendI Semana 2

## Preguntas

### 1.	¿Qué representa esta clase? ¿Qué información contiene?
Representa un Jugador que contienen características como Nombre, Edad, Posición, Numero de camiseta y Equipo. 

### 2.	¿Por qué es importante inicializar los atributos al crear un objeto? ¿Qué pasaría si no usáramos un constructor?
Inicializar los atributos permite verificar que los objetos presenten valores validos y coherentes a lo que se ha referenciado, de lo contrario se podría asignar un valor arbitrario que podría derivar en un error.
El constructor permite inicializar los atributos, el no uso de este pueda dejar nuestros atributos marcados como “None” o “0”, trayendo consigo errores a la hora de implementar los códigos.

### 3.	¿Por qué no accedemos directamente a los atributos desde otras clases? ¿Qué ventajas tiene usar getters y setters
Acceder mediante getters y setters a la información permite no violar el principio de encapsulamiento, además aplica restricciones a los valores ingresados y si se decide cambiar la implementación interna de los métodos estos no se verán afectados cuando se registre  información.

### 4.	¿Qué otros métodos podrían ser útiles para la clase Jugador? ¿Cómo podríamos mejorar este método?
Para comenzar, es importante conocer el deporte que practica el jugador, este puede ser considerado uno de los aspectos claves, ya que a partir de este se pueden definir otros atributos. Adicionalmente, los atributos spring, velocidad y regate, pueden proporcionarnos datos valiosos sobre el jugador, que finalmente puede ser transformados en información en la toma de decisiones

### 5.	¿Qué aprendiste al crear y utilizar objetos? ¿Cómo cambia el estado de un objeto cuando usamos métodos set
Los objetos permiten establecer características particulares en cada registro, lo que nos permite acceder a información valiosa, optimizando el uso de memoria para lograr mejorar la eficacia del proyecto. Del mismo modo es posible modificar y consultar la información de los atributos a lo largo de su vida útil. Las creación de un objeto, permite plasmar los atributos de una manera correcto ya que se instancian los datos para no cometer errores. El método Set, permite realizar un reemplazo de información posterior a la declaración del método correspondiente dentro de una clase.


![CESDE](https://plancastor.com/wp-content/uploads/2021/01/Mesa-de-trabajo-1_58-e1672774182304.png)

