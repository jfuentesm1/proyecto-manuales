# DEPARTAMENTO DE REPARACIONES
## OBJETIVO GENERAL
    proporcionar orientacion para guiar a nuestros lectores, sobre los estandares y procedimientos establecidos en SIEMAV facilitando el aprendizaje, promoviendo la consistencia y minimizando los errores garantizando seguridad, conformidad y calidad de nuestro trabajo.

## INDICE
---
- diagnostico y reparacion 

- repuesto 

- descarte
---

# DIAGNOSTICO
Al iniciar el diagnostico de una **tarjeta AMA** siempre se debe energizar con 12 voltios en su bornera grande en el pin **batt+ y batt-** luego segun el problema se puede determinar su reparacion


### software
ERROR: no enciende la tarjeta AMA
SOLUCION: cargar firmware a tarjeta AMA
REVISION: 
- [ ] estado de los espadines 
- [ ] funcionamiento del programador STLINK


### daño en inductores
ERROR: no enciende la tarjeta AMA
REVISION: 
- [ ] verificar que no esten rotos los inductores L1 Y L2 luego 
- [ ] verifica que el voltaje sea 5 voltios en cualquiera de los dos extremos de inductor  
SOLUCION: cambiar inductores dañados
REPARACION: 


### daño en Lora 
ERROR: no enciende la tarjeta AMA

DIAGNOSTICO: verificar que el voltaje del Lora U5 deben llegar 5 voltios al pin (como se muestra en la foto) si no le llega el voltaje correcto se procede a reparar 

SOLUCION: cambiar el lora 

REPARACION:


### daño en reguladores 
**regulador U1 Y U2**
ERROR: reguladores U1 Y U2 quemados, reventadoss
REVISION:
SOLUCION: cambiar el regulador, recostruccion de pista segun su datasheet 
INFO: [REGULADOR 12V A 5V](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u1%20y%20u2%20ama.jpg) 

**regulador U4**
ERROR: reguladores U4 quemados, reventados
SOLUCION: cambiar el regulador, recostruccion de pista segun su datasheet 
INFO: [REGULADOR 5V A 3.3V](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u4%20ama.jpg) 

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


### reparacion en lora
### reparacion en IG y L
### reparacion en reguladores
### reparacion en pista
### reparacion en inductores
### reparacion en ...























