# Proyectos-Universitarios
Practica Libre

Semáforo sencillo

Material necesario:

    Arduino Uno o similar.
    Protoboard.
    Cables.
    Un led rojo, un led amarillo y uno verde.
    3 resistencias de 220 Ω

Para el montaje del esquema colocamos los leds rojo, amarillo y verde en la protoboard, teniendo en cuenta que los vamos a conectar a los pines digitales 10, 9 y 8 de la placa de Arduino UNO. Comprobaremos que la patilla larga del LED está conectada al voltaje positivo, mientras que la pata corta está conectada a la resistencia.
Esquema para el montaje de un semáforo sencillo para Arduino

Programando con el IDE de Arduino.

El código es sencillo: se crea una variable donde almacenar el tiempo de espera. En la función setup() indicamos que los pines 10, 9 y 8 funcionarán como salida.

Lo siguiente será encender el led correspondiente, con un valor HIGHT, y apagarlo cuando queramos, cambiando el valor a LOW. Primero, el rojo estará encendido; cuando el semáforo se ponga verde, el rojo se apagará; y antes de volver a rojo, se encenderá el amarillo y se apaga
