
---
### SOFTWARE
**ERROR:** no enciende la tarjeta AMA

**SOLUCION:** cargar firmware a tarjeta AMA

---
### DAÑO DE INDUCTORES
**ERROR:** no enciende la tarjeta AMA, inductores rotos L1 o L2

**SOLUCION:** cambiar inductores dañados
  
**REPARACION:**
encender la pistola de calor, apuntar sobre la ubicacion del componente a cambiar y calentar hasta que pueda remover el componente, luego colocar el componente nuevo en la posicion del removido, calentar hasta que se suelde con la tarjeta

> [!NOTE]
> temperatura de pistola de calor: 400 , velocidad de pistola de calor: 100 , boquilla de pistola: media

---
### FALSA LECTURA DE RPS
**ERROR:** rps mayor a 0 al realizar prueba de ping 
  
**SOLUCION:** cambiar el opam U17
  
**REPARACION:**
encender la pistola de calor, apuntar sobre la ubicacion del componente a caambiar y calentar hasta que pueda remover el componente, luego colocar el componente nuevo en la posicion del removido, calentar hasta que se suelde con la tarjeta

> [!NOTE]
> temperatura de pistola de calor: 400 , velocidad de pistola de calor: 100 , boca de pistola: pequeña

---
### LORA 
**ERROR:** no enciende la tarjeta AMA

**REVISION:** 
- verificar que el voltaje del Lora U5 deben llegar 5 voltios al pin
- verificar con la pistola de calor la temperatura del Lora
**SOLUCION:** cambiar el lora
  
**REPARACION:** 
estañar los pines del lora, colocar la pinza en la parte superior del lora luego calentar con la punta del cautin un lado de los pines del lora y hacer palanca al mismo tiempo, repetir el proceso del otro lado levantando poco a poco el lora hasta desoldar el lado derecho e izquierdo, luego desoldar el lado inferior para remover finalmente limpiar con malla de soldar o la misma punta del cautin el pad de lora removido, colocar el nuevo lora y soldarlo a la tarjeta
> [!TIP]
> temperatura de cautin: 400
> tipo de pinza: ts20(simbolico)
> tipo de punta: ts1200 (simbolico)
---








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

ERROR LED ROJO
cambie el micro, cambie la memoria flash cambie el lora y actualice firmware, alimente directamente en diodio d10 para que funcione

ASP:
ERROR: TARJETA NO ENCIENDE
Revise la continuidad del MOSFET Q4 con el capacitor, una vez revisada esa `pista se detecto que el regulador de 3.3V estaba elevada la temperatura, se reemplazo el regulador de 3.3 (U9) y la tarjeta no encendia, se verificó que el regulador funcione correctamente y se procedio a cargar firmware, lo que hizo que la tarjeta encienda correctamente. 





















