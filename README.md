# Project esp32 

# Temario

## ¿Que es ESP32?

## Esp32 vs Arduino

## Instalación de ambiente de desarrollo
>   - Instalar Arduino IDE
>   - Configurar JSON de ESP32 en IDE de Arduino
>   - Configurar placa ESP32 en IDE de Arduino
>   - Cable de datos para ESP32
>   - Puertos USB en IDE de Arduino

## Mi primer hola Mundo
>   - Ejemplo de encender LED 2

## WiFi 
>   - Ejemplos WiFi
>   - Servidor WEB en ESP32
>   - Insertar imágenes en el Servidor WEB en la ESP32

## Efecto Hall
>   - Efecto Hall, explicación y ejemplo http://www.sinaptec.alomar.com.ar/2018/06/esp32-desde-cero-tutorial-5-sensor-de.html
>   - Efecto Hall, Youtube https://www.youtube.com/watch?v=XR132WlIENo&list=PL2xmtLUbEugnUoLiRTqwCm5wi2MSzsw3D&index=5

## Bluetooth
>   - Diagrama de bloques del módulo de Bluetooth
>   - Practicas de Bluetooth con ESP32
>   - App en Android para recibir y enviar información por Bluetooth

## Serial
>   - Diagrama de bloques del módulo de RS232-USB
>   - Practicas del puerto Serial con ESP232

## Dual Core 
>   - Practicas con Core 1 y Core 2
>   - Youtube: https://www.youtube.com/watch?v=k_D_Qu0cgu8
>   - ESP32_ShowCore
>   - ESP32_SpeedTest
>   - ESP32_Two_LED_Asynchron
>   - ESP32_Two_LED_Synchron
>   - ESP32_WhichCore

## ESP Now
## RS-232, USB, Comunicación Serial

## Resources on Youtube, some ESP32 topics: https://www.youtube.com/playlist?list=PLUhIV-TEo8VY2srDt0w7BRYnrAOVdg07U
* ESP32.- Instalación de ambiente de desarrollo.
* ESP32_wifi
* ULP1 Deep Sleep esp32 1 de 3
* ULP1 Deep Sleep esp32 2 de 3
* ULP1 Deep Sleep esp32 3 de 3

```
Hi, maybe my could be a strange question because I didn't find anything about it, but maybe I used wrong keywords in my search.
I have a program running on ESP32. This program need a internet connection to run and I use the integrated WiFi for this connection.
The problem is that I need to change SSID and password and every time I need to recompile and reupload the code.
I would like to simplify this operation with a small program (I am a C# developer) where I simply write SSID ad password and, via USB -> COM I change this parameters in the ESP32.
Is there any way to do this? Or could you suggest me something to search?
Thank you very much
``` 

## Cambiar contraseña de WIFI en esp32 con una App
>   - This might be worth looking at to adapt to your purpose: https://youtu.be/VnfX9YJbaU8
>   - Just a thought, you could use this library to achieve your goal: https://github.com/tzapu/WiFiManager
>   - https://github.com/peterjazenga/ESPconfig I wrote it to address that problem while demonstrating how you can build a UI with some icons and color on the ESP Basic function requires only 3 lines of code and includes hotspot, OTA and WPS as part of its standard function library on Arduino IDE

