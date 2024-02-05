# DEPARTAMENTO DE REPARACIONES
## OBJETIVO GENERAL
    proporcionar orientacion para guiar a nuestros lectores, sobre los estandares y procedimientos establecidos en SIEMAV facilitando el aprendizaje, promoviendo la consistencia y minimizando los errores garantizando seguridad, conformidad y calidad de nuestro trabajo.

## INDICE
---
- diagnostico

- reparacion

- repuesto 

- descarte
---

# DIAGNOSTICO
Al iniciar el diagnostico de una **tarjeta AMA** siempre se debe energizar con 12 voltios en su bornera grande en el pin **batt+ y batt-** luego segun el problema se puede determinar su reparacion


## No enciende 
### software
la tarjeta necesita un software para su funcionamiento, sino no enciende se procede a cargar el firmware, si la tarjeta no carga firmware se procede a verificar la posicion de programador **STLINK** y su funcionamiento

si la tarjeta no carga firmware se procede a verificar los espadines de la tarjeta esten en optimas condiciones

### daño en inductores
si la tarjeta no enciende se procede a verificar que el estado de los inductores L1 Y L2 sino estan rotos se verifica el voltaje sea 5 voltios en cualquiera de los dos extremos de inductor si estan rotos o no tienen el voltaje correcto, se procede a reparar 

### daño en Lora 
si la tarjeta no enciende verificar que el voltaje del Lora U5 deben llegar 5 voltios al pin (como se muestra en la foto) si no le llega el voltaje correcto se procede a reparar

### daño en reguladores 
**exiten 3 reguladores en la tarjeta ama estos son U1, U2 y U4**

regulador u1 y u2 convierte 12v a 5v, debemos energizar colocando el negativo de la fuente al GND de la tarjeta y el positivo de nuestra fuente regulada a 12 voltios en el pin [VIN](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u1%20y%20u2%20ama.jpg) del regulador y deberia encender la tarjeta sino enciendiende se procede a reparar.

regulador u4 convierte 5v a 3.3v debemos energizar poniendo el negativo de la fuente a GND de la tarjeta y el positivo de nuestra fuente regulada a 5 voltios en el pin [VIN](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u4%20ama.jpg) del regulador y debe encender la tarjeta sino enciende se procede a reparar.

### daño en micro
esta por revisar


---
## led rojo parpadeante 
### daño en IG Y L
con las puntas del multimetro/amperimetro en modo continuidad se debe verificar que entre los espadines IG y L no exista continuidad, si marca continuidad se debe procede a reparar 


### daño en micro
esta por revisar

## daño en el start

## daño en 

# REPARACIONES


### reparacion en micro
### reparacion en IG y L
### reparacion en reguladores
### reparacion en pista
### reparacion en inductores
### reparacion en ...























