# DEPARTAMENTO DE REPARACIONES
## OBJETIVO GENERAL
    proporcionar orientacion para guiar a nuestros lectores, sobre los estandares y procedimientos establecidos en SIEMAV facilitando el aprendizaje, promoviendo la consistencia y minimizando los errores garantizando seguridad, conformidad y calidad de nuestro trabajo.

## INDICE
---
- todas las reparaciones por indicar

- repuesto 

- descarte

# DIAGNOSTICO
Al iniciar el diagnostico de una **tarjeta AMA** siempre se debe energizar con 12 voltios en su bornera grande en el pin **batt+ y batt-** luego segun el problema se puede determinar su reparacion

### SOFTWARE
**ERROR:** no enciende la tarjeta AMA

**REVISION:** estado de los espadines, funcionamiento del programador STLINK

**SOLUCION:** cargar firmware a tarjeta AMA

### INDUCTORES
**ERROR:** no enciende la tarjeta AMA

**REVISION:** 
- verificar que no esten rotos los inductores L1 Y L2
  
**SOLUCION:** cambiar inductores dañados
  
**REPARACION:**
encender la pistola de calor, apuntar sobre la ubicacion del inductor que desea cambiar, calentar hasta que pueda remover el inductor, luego colocar un inductor en buen estado en la posicion del inductor removido, calentar hasta que se suelde con la tarjeta
> [!TIP]
> temperatura de pistola de calor: 400
> velocidad de pistola de calor: 1
### LORA 
**ERROR:** no enciende la tarjeta AMA

**REVISION:** 
- verificar que el voltaje del Lora U5 deben llegar 5 voltios al pin
- verificar con la pistola de calor la temperatura del Lora
- 
**SOLUCION:** cambiar el lora
  
**REPARACION:** 
estañar los pines del lora, colocar la pinza en la parte superior del lora luego calentar con la punta del cautin un lado de los pines del lora y hacer palanca al mismo tiempo, repetir el proceso del otro lado levantando poco a poco el lora hasta desoldar el lado derecho e izquierdo, luego desoldar el lado inferior para remover finalmente limpiar con malla de soldar o la misma punta del cautin el pad de lora removido, colocar el nuevo lora y soldarlo a la tarjeta
> [!TIP]
> temperatura de cautin: 400
> tipo de pinza: ts20(simbolico)
> tipo de punta: ts1200 (simbolico)










### REGULADORES U1 Y U2

**ERROR:** reguladores U1 Y U2 quemados, reventados
**REVISION:**
**SOLUCION:** cambiar el regulador, recostruccion de pista segun su datasheet
**INFO:** [REGULADOR 12V A 5V](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u1%20y%20u2%20ama.jpg) 
### REGULADOR U4
**ERROR:** reguladores U4 quemados, reventados
**SOLUCION:** cambiar el regulador, recostruccion de pista segun su datasheet
**INFO:** [REGULADOR 5V A 3.3V](https://github.com/jfuentesm1/proyecto-manuales/blob/main/img/u4%20ama.jpg) 






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























