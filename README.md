# TerraLink - Nodo IoT para monitoreo agricola

## Autores
* Linda Orduy
* Erika Quintero
* David Baron
* Paula Ruiz
* Cristian Barbosa


## Introduccion
El sector agrícola a nivel mundial enfrenta desafíos relacionados con la sostenibilidad de los
sistemas de producción de alimentos, la eficiencia en el uso de recursos naturales y la
adaptación al cambio climático. En Colombia y América Latina, los pequeños productores
rurales representan un eje fundamental de la seguridad alimentaria, sin embargo, en la historia
este sector ha tenido acceso limitado a tecnologías que les permitan optimizar sus cultivos,
prever riesgos y tomar decisiones a partir de datos reales.

El agro colombiano enfrenta actualmente brechas críticas que limitan el rendimiento de sus
cultivos. Por un lado, existe una importante degradación de los suelos. El IDEAM estima que
el 40 % del territorio nacional presenta algún grado de erosión, mientras que otro 5 % está
afectado por procesos de salinización, especialmente en la región Caribe. Estas condiciones
reducen la fertilidad del suelo y, según el Ministerio de Ambiente y Desarrollo Sostenible,
conducen a una disminución de la productividad agrícola y a un aumento de la inseguridad
alimentaria.

Al mismo tiempo, la modernización tecnológica del campo resulta insuficiente. De acuerdo
con datos oficiales del Departamento Nacional de Planeación, el 66.7 % de las explotaciones
agropecuarias no cuenta con sistemas de riego, el 83.5 % no recibe asistencia técnica y el
68.4 % no emplea fertilización química.

Desde una perspectiva social, la FAO señala que menos del 10 % de la agricultura familiar
utiliza tecnologías avanzadas, mientras que más del 60 % de los hogares rurales carece de
acceso estable a internet, lo que retrasa significativamente la adopción de soluciones
digitales.

Frente a esta realidad, TerraLink identificó una gran oportunidad de negocio orientada a
aprovechar la tendencia nacional hacia la transformación digital del campo. A partir de este
análisis, se evidenció que, aunque la mayoría de los agricultores dispone de smartphones,
muchos desean mejorar sus decisiones agronómicas, pero carecen de datos fiables sobre las
condiciones de sus suelos.
TerraLink integra sensores IoT de bajo costo que miden pH, humedad y minerales del suelo
en tiempo real, conectados a una aplicación móvil que ofrece recomendaciones técnicas
personalizadas. Este modelo resulta innovador porque sustituye los muestreos esporádicos en
laboratorio por un monitoreo continuo en campo, lo que permite realizar ajustes inmediatos
en fertilización y riego.

## Montaje fisico
AUN FALTA VERIFICAR CONEXIONES 
| Componente | Conexión |
|------------|----------|
| Tarjeta STM32 | |
| Sensor temperatura DHT22 | Data → GPIO xx (pin xx)<br>VCC → 5V (o 3.3V según modelo)<br>GND → GND |
| Sensor de suelo RS485 | Cable cafe → 5V <br>Cable negro → GND <br>Cable amarillo → A+ modulo RS485<br>Cable azul → B- modulo RS485 |
| Modulo RS485 a UART TtL Xy-017 |VCC → 5V (o 3.3V según modelo)<br> TXD →  <br>RXD →  <br> GND →  GND <br> A+ → Cable amarillo snesor <br> B- → Cable azul sensor <br> chino →  <br>|
| LoRa |VCC → 3.3 v <br> MISO →  <br> MOSI →  <br> SLCK →  <br> NSS →  <br> DIO0 →  <br> REST →  <br> GND → GND <br>|
| Panel solar |  |

### Conexion sensor de temperatura DHT22
'
![imager](images/rpimager.jgp)
'
### Calibracion y conexion sensor de suelo

### Conexion LoRa

### Conexion panel solar

## Diseño PCB
## Esquematico


## Integracion con IA

## Pagina web - app

## Diseño 3D


## Conclusiones, recomendaciones, consideraciones...
