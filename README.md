# LIMPIA PARABRISAS

## Autores
- ManuelArgibay
- AlexY0916

## Versión - v1.01 Curso - Asignatura de Diseño de PCBs con KiCad - Curso 2024 - 2025

## Objectivo, Descripción breve del objectivo del proyecto.
Diseñar una placa PCB que desarrolle la función de limpiaparabrisas de un automóvil, mediante la detección de lluvia y accionamiento de motores, bombas de agua y un calefactor. Con el objetivo de mantener el parabrisas limpio y libre de objetos que puedan dificultar la visibilidad y evitar accidentes 

## Requisitos y especificaciones
- 2 motores con finales de carrera
- 2 bombas de líquido limpia parabrisas
- Sensor digital de lluvia
- Calefactor del vidrio

## Diagrama de bloques




## Tabla de componentes
| Descripción | Manufacturer Number | Package | Datasheet | Proveedor | Unidades |
| Microcontrolador | PIC18F258 | SOIC-28 | https://www.mouser.es/ProductDetail/Microchip-Technology/PIC18F258-I-SP?qs=uMUszenkLLIixFKqjRA69Q%3D%3D&srsltid=AfmBOopKXQlyaGkKwKApGVeNytftWyBSKV1Xqn-g4o59TgY9E8kJ9XiY | Mouser | 1 |
|Transceptor|MCP2551|SOIC-8|https://ww1.microchip.com/downloads/en/devicedoc/20001667g.pdf|Microchip|1|
|Amplificador operacional|LT1716|SOIC-5|https://www.mouser.es/datasheet/2/609/LT1716-1716222.pdf|Mouser|2|
|Regulador de tensión|LM117|TO-220|https://www.ti.com/lit/ds/symlink/lm1117.pdf?ts=1742942595976&ref_url=https%253A%252F%252Fbr.mouser.com%252F|Mouser|1|
|Puente H|DRV8871DDA|DDA|https://www.ti.com/lit/ds/symlink/drv8871-q1.pdf?ts=1742988697362&ref_url=https%253A%252F%252Fwww.ti.com%252Fproduct%252FDRV8871-Q1||2|

## Funcionalidades
- Control de motores de limpiaparabrisas, bomba de agua y calefactor
- Detección de lluvia mediante sensor
- Botonera de acción manual

## Historial de cambios | Fecha | Autor | Branch | Descripción |
|1|25/03/2025|ManuelArgibay|main|Creación del proyecto|
|2|25/03/2025|ManuelArgibay|main|Cambio titulo del proyecto|
|3|25/03/2025|ManuelArgibay|main|Modificación del esquemático y pptx|
|4|25/03/2025|ManuelArgibay|main|Agrego net classes, proyecto y presentación |
|5|25/03/2025|AlexY0916|main|Modifico net classes, fc, GNDPWR, separación botonera|
|6|26/03/2025|AlexY0916|main|Separacion del circuito|
|7|29/03/2025|ManuelArgibay|main|Agrego presentaciones y archivos|
|8|29/03/2025|ManuelArgibay|main|Modifico simulaciones del comparador y arreglo esquematico|
|9|30/03/2025|AlexY0916|main|Ordenar esquematico|
|10|30/03/2025|AlexY0916|main|Footprint|
|11|30/03/2025|AlexY0916|main|Arreglar errores con los esquematicos|
|12|30/03/2025|AlexY0916|main|Empezando a añadir el sensor|
|13|31/03/2025|AlexY0916|main|Sensor|
|14|31/03/2025|AlexY0916|main|ICSP|
|15|31/03/2025|ManuelArgibay|main|Arreglo net classes y agrego DB-9|
|16|31/03/2025|ManuelArgibay|main|Empiezo layout, cambio footprints y arreglo esquematico|
|17|01/04/2025|ManuelArgibay|main|Termino layout|
|18|01/04/2025|ManuelArgibay|main|Arreglo nodos no conectados|
|19|01/04/2025|AlexY0916|main|Cambio el cristal|
|20|01/04/2025|AlexY0916|main|Cambio de presentacion, minimas correcciones en el esquematico|
|21|01/04/2025|AlexY0916|main|Nombrar etiqueta PCB|
|22|01/04/2025|AlexY0916|main|Cambio en la presentacion|
|23|02/04/2025|ManuelArgibay|main|Arreglo errores y cambio conector|
|24|02/04/2025|ManuelArgibay|main|Arreglo errores del DRC. Falta arreglar errores del GNDPWR|
|25|02/04/2025|ManuelArgibay|main|Preentrega final|
|26|02/04/2025|ManuelArgibay|main|Agrego cambios|
|27|07/04/2025|ManuelArgibay|main|Arreglo layout y esquematico con las correcciones pasadas|
|28|07/04/2025|AlexY0916|main|Separacion de la botonera|
|29|07/04/2025|AlexY0916|main|Cambio de valor los condensadores del oscilador|
|30|07/04/2025|AlexY0916|main|Cambio diagrama de bloques|
|31|08/04/2025|AlexY0916|main|Reglas de diseño|
|32|08/04/2025|AlexY0916|main|Cambiar esquematico|
|33|08/04/2025|AlexY0916|main|Cambio de la PCB (cambio de conectores)|
|34|09/04/2025|AlexY0916|main|Layout|
|35|09/04/2025|AlexY0916|main|Cambio del sensor|
|36|23/04/2025|ManuelArgibay|main|Arreglo layout y esquematico (DRC correcto)|

