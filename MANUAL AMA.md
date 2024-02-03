# DEPARTAMENTO DE REPARACIONES
## OBJETIVO GENERAL
    proporcionar orientacion para guiar a nuestros lectores, sobre los estandares y procedimientos establecidos en SIEMAV facilitando el aprendizaje, promoviendo la consistencia y minimizando los errores garantizando seguridad, conformidad y calidad de nuestro trabajo.

### INDICE
---
- diagnostico

- reparacion

- repuesto 

- descarte

## DIAGNOSTICO
---
conectar la tarjeta AMA en su bornera grande para asi energizar la tarjeta luego de esto empezamos el diagnostico

existen varios estados de la tarjeta AMA se pueden dividir en los siguientes 

### estados
existen varios estados de la tarjeta AMA se pueden dividir en los siguientes 

cuando el led no enciende 
cuando el led se pone en verde 
cuando el led se pone en blanco
cuando el led se pone en rojo 
cuando el led se pone en blanco parpadeante
cuando el led se pone en rojo parpadeante

## no enciende 

### software
si la tarjeta no enciende se procede a cargar el firmware
si la tarjeta no carga firmware se procede a verificar los espadines de la tarjeta esten en optimas condiciones
si la tarjeta no carga firmware se procede a verificar la posicion de programador y su funcionamiento

### alimentacion

si la tarjeta no enciende se procede a verificar el que llegen en la bornera grande los 12 voltios en los pines **batt+ y batt-**

si la tarjeta no enciende se procede a verificar que el estado de los INDUCTORES L1 Y L2 este en buenas condiciones sino **repararlos**

si la tarjeta no enciende verificar que el voltaje del LORA U5 deben llegar 5 voltios al pin (como se muestra en la foto) sino **reparalo**


### daño en IG Y L
con las puntas del multimetro/amperimetro en modo continuidad se debe verificar que entre los espadines IG y L no exista continuidad, sino es asi repararlo. 

> [!TIP] 
> se recomienda jorge 

### daño en reguladores 
exiten 3 reguladores en la tarjeta ama estos son U1, U2 y U4
regulares u1 y u2 convierten 12v a 5v estos debemos energizarlos poniendo en negativo de la fuente a GND luego debemos tocar el pin **VIN** del regulador y deberia encender la tarjeta sino enciendiende se procede a reparar.

regulador u4 convierte 5v a 3.3v este debemos energizar poniendo el negativo de la fuente a GND luego debemos tocar el pin **VIN** del regulador y debe encender la tarjeta sino enciende se procede a reparar.




























