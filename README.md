# SleepMonitorGIDS4092

## Integrantes del equipo
- Cárdenas Baeza Diego Emmanuel
- Mendoza García Fernando
- Ortega Amaro Angel de Jesús

## Visión
Crear un dispositivo portátil que permita a los usuarios obtener información detallada sobre la calidad de su sueño mediante múltiples sensores. Al combinar estos datos con un algoritmo personalizado, el dispositivo proporcionará recomendaciones individuales para mejorar los hábitos de sueño, superando a otros monitores de sueño que solo se enfocan en aspectos básicos.

## Objetivo General
Crear un dispositivo portable (wearable) el cual permita al usuario conocer mas aspectos acerca de que tan bien está durmiendo, esto mediante los multiples sensores elegidos para poder medir aspectos importantes del sueño del humano. De esta forma, combinando los datos obtenidos mediante el dispositivo con un algorimto diseñado para valorar la calidad del sueño en función de los datos obtenidos, se podrán hacer recomendaciones personalizadas por usuario.

### Objetivos específicos
- 1.- Interpretar esquemas eléctricos y realizar el montaje a partir de este, utilizando para ello distintos materiales.
- 2.- Conocer y utilizar los conocimientos previos para poder realizar un algoritmo que interprete los datos obtenidos.
- 3.- Conocer los principios, elementos y aplicaciones básicas de distintos sistemas de control eléctricos.
- 4.- Representar a través de graficos las estadisticas de sueño del usuario.

## Tabla del software utilizado
| id |  Software          |  Versión  |  Tipo  |
|----|--------------------|-----------|--------|
|  1 | Arduino IDE        |  1.71.2   |  IDE   |
|  2 | Visual Studio Code |  2021.3   |  IDE   |
|    |                    |           |        |

## Tabla con el hardware utilizado
| Id | Componente | Descripción |                                          Imagen                                                   | Cantidad | Costo total |
|----|------------|-------------|---------------------------------------------------------------------------------------------------|----------|-------------|
| 1  |   ESP32    | El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos|![image](https://user-images.githubusercontent.com/99991865/192933367-82d60a6b-83a0-4d76-9aa7-742fb42d2d3c.png)|   1      |   165       
| 2  |Led verdes  |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz |![image](https://user-images.githubusercontent.com/99991865/192932983-84794e7e-a316-4e55-825b-cfb9cd3e808a.png)|   1      |   15          |
| 4  |Led amarillo|Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933020-9a90e9b7-8c89-410f-a89d-7dc7f99814ef.png)|   1      |      15     |
| 5  |Led rojo    |Un diodo LED es un dispositivo que permite el paso de corriente en un solo sentido y que al ser polarizado emite un haz de luz|![image](https://user-images.githubusercontent.com/99991865/192933021-f55b80cb-b9ae-44ac-99c5-23cd6ff9bc79.png)|   1      |      15     |
| 6  |Resistencias de 1k|se utilizan en los circuitos para limitar el valor de la corriente o para fijar el valor de la tensión, según la Ley de Ohm|![image](https://user-images.githubusercontent.com/99991865/192933039-0b857725-d306-4ced-ae16-679589196f19.png)|   5      |  10         |
| 7  |Protoboard  |es un tablero con orificios que se encuentran conectados eléctricamente entre sí de manera interna, habitualmente siguiendo patrones de líneas, en el cual se pueden insertar componentes electrónicos, cables para el armado|![image](https://user-images.githubusercontent.com/99991865/192933683-d1955de9-b1fa-4063-8218-b822c8b7eedf.png)|   1      |     110        |
| 8  |Cables     |sirve para conectar todos los compenetes a la protoboard|![image](https://user-images.githubusercontent.com/99991865/192934122-6938a1d7-55a6-4caa-85c9-80a27cf06301.png)|   5      |    55        |
| 9  |sensor DHT11|Dispositivo que detecta la temperatura y humedad ambiente.|![image](https://github.com/AngelOrtega26/SleepMonitorGIDS4092/blob/main/descargar%20(1).jpeg)|   1      |    85        |
| 10 |sensor de pulso|Dispositivo que detecta el pulso de un humano.|![image](https://github.com/AngelOrtega26/SleepMonitorGIDS4092/blob/main/e250cb_379ae2060325444ba1b4c287005a3e40~mv2.jpg)|   1      |    85        |
| 11 |sensor de oxigenacion en sangre|Dispositivo que detecta el nivel de oxigenación en sangre.|![image](https://github.com/AngelOrtega26/SleepMonitorGIDS4092/blob/main/Grove_Gas_Sensor_Oxygen.jpg)|   1      |    85        |
| 12 |Giroscopio|Dispositivo que detecta el movimiento.|![image](https://github.com/AngelOrtega26/SleepMonitorGIDS4092/blob/main/images.jpeg)|   1      |    85        |

## Epicas del proyecto
- El proyecto debe detectar si hay movimiento durante la fase del sueño
- El proyecto debe medir el porcentaje de oxigenación en sangre
- El proyecto debe medir la temperatura del ambiente en el que se está durmiendo
- El proyecto debe combinar estos parámetros para poder mostrar informacion útil posteriormente en la aplicación

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Funcionalidad del proyecto                    |  Alta         | 0.5           |Realizar pruebas correspondientes en un entorno controlado para comprobar que su funcionamiento sea el correcto.            |Integrantes de equipo             |
| 2  |Funcionalidad de los sensores y actuadores   | Alta          | 0.5          | Realizar pruebas con algún usuario para verificar que todo funciona correctamente. | Integrantes de equipo |
| 3  | Funcionalidad de los leds             | Media         |  0.3          | Realizar pruebas en el aplicativo para verificar que el flujo de esta es correcto y útil para el usuario             |   integrantes del equipo          |

## Prototipo en dibujo

![image](https://user-images.githubusercontent.com/99991865/192936794-274c5f21-6002-47d9-a9e5-a5c583eff731.png)

# Video de prueba

![video](https://github.com/AngelOrtega26/SleepMonitorGIDS4092/blob/main/WearablePrototype.mp4)
