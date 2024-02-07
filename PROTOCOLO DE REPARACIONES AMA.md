# PROTOCOLO PARA PROBAR AMA
se debe probar el **maximo actual** de tarjetas establecidas por reparador, al final del dia se reporta las tarjetas amas probadas en el banco de pruebas y cada reparador debe notificar su numero de amas probadas hasta las 4:20pm.
## VERIFICAR
- grupo, canal y dispositivo designada a cada reparador
- numero escrito en LORA designado a reparador
- tarjeta limpia y presentable
> [!NOTE]
> maximo actual tarjetas ama: 15 unidades

# USO DE BANCO DE PRUEBAS AMA
## ARNES
- encender la llave del arnes
- conectar la tarjeta ama 
- verificar el switch este apagado
## RED WIFI
- encender la ESTACION BASE MOVIL
- conectarse a la red WIFI: **APP MOVIL**
- ingresar contraseña: **Siemav.2019**
- abrir el navegador y escribir la ip: **174.24.1.1**
## PING 1 
- RSSI: <-100dB
- BATERIA: <= 13.0 V
## ARRANCAR
- enciende el led amarillo 
- servomotor en posicion perpendicular
- enciende el motor de arranque 
## LECTURA DE RPS 
- encender el switch
- encender el variador de frecuencia
## PING 2
- BATERIA: => 14.0 V
- RPS: > 200 RPS
- apagar el variador de frecuencia
## PING 3
- BATERIA: < 13.0 V
- RPS: 0 RPS
## DETENER 
- enciende el led verde 
- servomotor en posicion inicial
- apagar el switch


