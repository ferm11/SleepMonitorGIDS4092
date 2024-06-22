# SleepMonitorGIDS4092

## Integrantes del equipo
- Cárdenas Baeza Diego Emmanuel
- Mendoza García Fernando
- Ortega Amaro Angel de Jesús

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
| 9  |sensor DHT11|Dispositivo que detecta la temperatura y humedad ambiente.|![image]()|   1      |    85        |

Batería 9 voltios

## Epicas del proyecto
- El proyecto debe detectar si hay alcohol en el ambiente
- El proyecto debe medir el porcentaje de alcohol que existe en el ambiente (Al soplarlo)
- El proyecto debe dar una alerta con la ayuda de los leds cuando se rebasa cierto limite en el porcentaje de alcohol
- El proyecto debe dar una alerta en la aplicación con los detalles acerca del porcentaje de alcohol detectado

## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  | Funcionalidad del proyecto                    |  Alta         | 0.5           |Realizar prubas correspondientes con alguna detección de gas para comprobar que su funcionamiento sea el correcto.            |Integrantes de equipo             |
| 2  |Funcionalidad del sensor de gas MQ 3   | Alta          | 0.5          | Realizar prueba con algún gas posible de verificar el funcionamiento del mismo.             | Integrantes de equipo |
| 3  | Funcionalidad de los leds             | Media         |  0.3          | Realizar prueba segun el nivel del gas se encenderan             |   integrantes del equipo          |

## Prototipo en dibujo

![image](https://user-images.githubusercontent.com/99991865/192936794-274c5f21-6002-47d9-a9e5-a5c583eff731.png)
![image](https://user-images.githubusercontent.com/99991865/192936778-39b2fe11-2343-4a57-9932-fb1ba8ae76d1.png)

