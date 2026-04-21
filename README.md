# Dashboard IoT – Monitor y Control de Variables Psicrométricas

### Problema
Los sistemas de secado de alimentos requieren monitoreo constante de variables psicrométricas como temperatura y humedad. Hacerlo manualmente es ineficiente y propenso a errores.
### Solución
Interfaz web desarrollada en HTML y JavaScript que se comunica en tiempo real con un ESP32 vía WiFi usando WebSockets y HTTPS, permitiendo monitorizar y controlar remotamente el emulador de aire sintético del proyecto de residencia.
### Resultado
El operador puede visualizar y ajustar las variables del sistema desde cualquier dispositivo con navegador, sin necesidad de estar físicamente presente frente al hardware.

-----------------------------------------------------------------------------------------------------------------

Segunda parte del Proyecto para Residencia Profesional en el centro de Investigacion Cimav. 
El objetivo es hacer la Instrumentación y el control de un sistema solar de generación de aire sintético para aplicaciones de secado de productos 
agroindustriales.

Esto es el software embebido del micricontrolados 2 de 2 utilizados en el proyecto para recibir los datos de otro microcontrolador para mostrarlos en la pagina web con interfaz  de usuario en la nube.
Se utilizo el microcontrolador de 32 bits ESP32 con el framework de Arduino y Platformio.

Vista previa del prototipo:
![image](https://github.com/Yeray4/Webpage-Cimav-generacion-de-aire-sintetico/assets/94934461/2d2816a5-616a-4647-a2a7-103789d664c2)

Vista previa del prototipo circuito:
![image](https://github.com/Yeray4/Webpage-Cimav-generacion-de-aire-sintetico/assets/94934461/fae251e6-6e85-4391-ac22-939055d2a53c)


Vista previa de pagina web:

![image](https://github.com/Yeray4/Webpage-Cimav-generacion-de-aire-sintetico/assets/94934461/44fd34ab-02a3-4738-a689-cb4167a55489)

![image](https://github.com/Yeray4/Webpage-Cimav-generacion-de-aire-sintetico/assets/94934461/5d2d6fb3-2083-4888-8ffc-fa4364d86ebe)



