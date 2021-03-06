# Argentina COVID-19 informes diarios

## Fuentes

* Principalmente https://www.argentina.gob.ar/coronavirus/informe-diario.
* Noticias de diarios, que no coinciden con los pdfs.
* [Wikipedia](https://es.wikipedia.org/wiki/Pandemia_de_enfermedad_por_coronavirus_de_2020_en_Argentina)

Para extraer los datos a un csv, usar [`make_csv_from_md`](./make_csv_from_md).

### CSV

```
year,month,day,case,place,new
```

## 2020 03 03

### Fuente

* [Wikipedia](https://es.wikipedia.org/wiki/Pandemia_de_enfermedad_por_coronavirus_de_2020_en_Argentina)

### CSV

```
2020,03,03,CONFIRMADO,CABA,1
```

## 2020 03 05

### Fuente

* [Wikipedia](https://es.wikipedia.org/wiki/Pandemia_de_enfermedad_por_coronavirus_de_2020_en_Argentina)

### CSV

```
2020,03,05,CONFIRMADO,CABA,1
```

## 2020 03 06

### Fuente

* [Wikipedia](https://es.wikipedia.org/wiki/Pandemia_de_enfermedad_por_coronavirus_de_2020_en_Argentina)

### CSV

```
2020,03,06,CONFIRMADO,CABA,4
2020,03,06,CONFIRMADO,PCIABSAS,1
2020,03,06,CONFIRMADO,CORDOBA,1
```

## 2020 03 07

### Fuente

* No hay información del ministerio de salud.
* Según [La Nación](https://www.lanacion.com.ar/sociedad/confirman-primer-muerto-coronavirus-argentina-hombre-63-nid2341027) hoy fue la primer muerte y ya había 9 casos en Argentina.
* [Wikipedia](https://es.wikipedia.org/wiki/Pandemia_de_enfermedad_por_coronavirus_de_2020_en_Argentina)
* El caso de muerte no se registró antes como "confirmado". Se agrega.

### CSV

```
2020,03,07,CONFIRMADO,CABA,1
2020,03,07,MUERTE,CABA,1
```

## 2020 03 08

### Fuente

* A la fecha, el Servicio de virosis respiratorias del INEI ANLIS Malbrán analizo 28
  muestras correspondientes a casos sospechosos de COVID-19. Se informa que en tres
  de las 28 se detectó genoma de SARS-COV-2. Son tres (3) nuevos importados
  confirmados de COVID-19. Junto a estos, ya son 12 los casos confirmados de
  coronavirus en el país.
* Se trata de dos pacientes de Ciudad de Buenos Aires y una de la provincia de Buenos
  Aires. Todos se encuentran cumpliendo el aislamiento establecido por las autoridades
  sanitarias.
* El caso de la provincia de Buenos Aires, es una mujer de 53 años de edad que se
  encuentra internada. Comenzó con síntomas el 5 de marzo, y el 7 de marzo consulta a
  una Institución pública de la Provincia. Tiene como antecedente viaje a Europa.
* Otro de los casos es una persona de 71 años, con residencia en Parma, Italia, que
  ingresó al país el 5 de marzo, comenzando ese mismo día con síntomas. El 6 de marzo,
  consultó a un efector público de la Ciudad Autónoma de Buenos Aires, donde se le
  solicitó la muestra para diagnóstico y se le indicó internación para aislamiento.
* El tercer caso, es un paciente joven, sin patología previa, que asistió a un evento en
  Estados Unidos, en donde se confirmaron casos de COIVD-19, motivo por el cual se
  suspendió el evento. Se encuentra en buen estado de salud, internado para su
  aislamiento en una institución privada.
* En todos los casos se trata de personas con antecedente de viaje. Al momento, las dos
  jurisdicciones se encuentran realizando la investigación epidemiológica para detectar
  contactos estrechos y cumplir el aislamiento establecido por protocolo.
* A la fecha, Argentina no registra transmisión local del nuevo coronavirus SARS-Cov-2.

### CSV

```
2020,03,08,CONFIRMADO,CABA,2
2020,03,08,CONFIRMADO,PCIABSAS,1
```

## 2020 03 09

### Fuente

* A la fecha, Argentina no registra transmisión comunitaria del nuevo coronavirus SARS-Cov-2.
* Hoy fueron confirmados 5 nuevos casos de COVID-19 con antecedente de viaje a Europa. Se trata de
  residentes de CABA, San Luis, Chaco (2) y Río Negro. A la fecha, se registran un total de diecisiete
  (17) casos importados confirmados de COVID-19 entre los que se encuentra un (1) fallecido. Los
  pacientes se encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.

### CSV

```
2020,03,09,CONFIRMADO,CABA,1
2020,03,09,CONFIRMADO,SANLUIS,1
2020,03,09,CONFIRMADO,CHACO,2
2020,03,09,CONFIRMADO,RIONEGRO,1
```

## 2020 03 10

### Fuente

* A la fecha, Argentina no registra transmisión comunitaria del nuevo coronavirus SARS-Cov-2
* Hoy fueron confirmados dos (2) nuevos casos de COVID-19 con antecedente de viaje a Europa. Uno
  residente de CABA y otro de Provincia de Buenos Aires. A la fecha, se registran un total de diecinueve
  (19) casos importados confirmados de COVID-19 entre los que se encuentra un (1) fallecido. Los
  pacientes se encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.

### CSV

```
2020,03,10,CONFIRMADO,CABA,1
2020,03,10,CONFIRMADO,PCIABSAS,1
```

## 2020 03 11

### Fuente

* A la fecha, en Argentina sólo se registran casos importados de COVID-19.
* Hoy fueron confirmados dos (2) nuevos casos de COVID-19 con antecedente de viaje a Europa. Uno
  residente de CABA y otro de Provincia de Buenos Aires. A la fecha, se registran un total de veintiún
  (21) casos importados confirmados de COVID-19 entre los que se encuentra un (1) fallecido. Los
  pacientes se encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.

### CSV

```
2020,03,11,CONFIRMADO,CABA,1
2020,03,11,CONFIRMADO,PCIABSAS,1
```

## 2020 03 12

### Fuente

* A la fecha, en Argentna la mayoría de los casos son importados. Se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria.
* Hoy fueron confrmados diez (10) nuevos casos de COVID-19 de Chaco, Córdoba, Buenos Aires y
Ciudad de Buenos Aires, este últmo oriundo de la provincia de Entre Ríos. De los 10 casos, siete (7)
corresponden a casos con antecedentes de viaje a zona de riesgo, mientras que tres (3) de los casos
confrmados son contactos estrechos de casos confrmados. El total de casos confrmados en
Argentna es de treinta y un (31) casos, de los cuales uno (1) falleció. Los pacientes se encuentran
cumpliendo el aislamiento establecido por las autoridades sanitarias
* Distribuición:
  * Cordoba 1: [fuente](https://www.eldiariodecarlospaz.com.ar/nacionales/2020/3/12/coronavirus-los-primeros-casos-autoctonos-en-argentina-uno-en-cordoba-82869.html)
  * Chaco 2: [fuente](https://www.ellitoral.com.ar/corrientes/2020-3-12-17-3-0-confirma-dos-nuevos-casos-de-coronavirus-en-resistencia)
  * Bs As 4: [fuente](https://www.telam.com.ar/notas/202003/440349-detectan-cuatro-nuevos-casos-son-ocho-infectados-coronavirus-buenos-aires.html)

### CSV

```
2020,03,12,CONFIRMADO,CHACO,2
2020,03,12,CONFIRMADO,CORDOBA,1
2020,03,12,CONFIRMADO,PCIABSAS,4
2020,03,12,CONFIRMADO,CABA,3
2020,03,12,ALTA,CABA,1
```

## 2020 03 13

### Fuente

* A la fecha, en Argentina la mayoría de los casos son importados. Se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria.
* Hoy fueron confirmados tres (3) nuevos casos de COVID-19. Uno (1) de Buenos Aires y dos (2) de la
Ciudad de Buenos Aires. De los tres casos, dos corresponden a casos con antecedentes de viaje a
zona de riesgo, mientras que el otro caso confirmado pertenece a un contacto estrecho de casos
confirmados. El total de casos confirmados en Argentina es de treinta y cuatro (34) casos, de los
cuales dos (2) fallecieron. Los pacientes se encuentran cumpliendo el aislamiento establecido por las
autoridades sanitarias.
* En el día de la fecha se confirmó el segundo fallecimiento de un paciente con diagnóstico de COVID-
19. Se trata de hombre de 61 años, residente en la provincia de Chaco. El paciente presentaba
antecedente de viaje a Europa y Egipto.
* 3 Recuperados **en total** y de ellos fue el primer paciente dado de alta:
  * [fuente1](https://www.clarin.com/ciudades/17-casos-coronavirus-confirmados-ciudad-buenos-aires_0_GMcWtBuA.html)
  * [fuente2](https://www.perfil.com/noticias/salud/se-confirmaron-once-nuevos-casos-la-cifra-mas-alta-para-un-solo-dia.phtml)
  * [fuente3](https://www.infobae.com/coronavirus/2020/03/13/radiografia-del-coronavirus-en-la-ciudad-y-la-provincia-de-buenos-aires-dieron-de-alta-a-otros-dos-pacientes-y-estudian-casi-400-posibles-casos/)

### CSV

```
2020,03,13,CONFIRMADO,PCIABSAS,1
2020,03,13,CONFIRMADO,CABA,2
2020,03,13,MUERTE,CHACO,1
2020,03,13,ALTA,CABA,2
```

## 2020 03 14

### Fuente

* A la fecha, en Argentina la mayoría de los casos son importados. Se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria.
* Hoy fueron confirmados once (11) nuevos casos de COVID-19. Pertenecen a la Ciudad de Buenos
Aires, Santa Fe, Chaco, y la Provincia de Buenos Aires. De los once casos, diez corresponden a casos
con antecedentes de viaje a zona de riesgo, mientras que el otro caso confirmado pertenece a un
contacto estrecho de casos confirmados. El total de casos confirmados en Argentina es de cuarenta y
cinco (45), de los cuales dos (2) fallecieron. Los once pacientes se encuentran cumpliendo el
aislamiento establecido por las autoridades sanitarias.
* Distribución inducida a partir de [La Nación](https://www.lanacion.com.ar/sociedad/coronavirus-argentina-se-sumaron-11-casos-nuevos-nid2343459).
* 1 Recuperado [Fuente](https://web.archive.org/web/20200315195812/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
* De las dos fuentes citadas se extrae que habia en ese momento 9 pacientes nuevos en CABA y que dos eran de BSAS, por lo que este dia es correcto contabilizar 7 personas.

### CSV

```
2020,03,14,CONFIRMADO,CABA,7
2020,03,14,CONFIRMADO,SANTAFE,1
2020,03,14,CONFIRMADO,CHACO,1
2020,03,14,CONFIRMADO,PCIABSAS,2
2020,03,13,ALTA,CABA,1
```

## 2020 03 15

### Fuente

* A la fecha, en Argentina la mayoría de los casos son importados. Se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria.
* Hoy fueron confirmados once (11) nuevos casos de COVID-19. Seis (6) de la Ciudad de Buenos Aires,
dos (2 ) en Chaco, dos (2) en Tierra del Fuego y uno (1) en Provincia de Buenos Aires
* De los once casos, ocho corresponden a casos con antecedente de viaje a zona de riesgo, mientras
que los tres (3) restantes son contactos estrechos de casos confirmados. El total de casos
confirmados en Argentina es de cincuenta y seis (56) casos, de los cuales dos (2) fallecieron. Los
pacientes se encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
* 3 Recuperados en CABA: [Fuente](https://web.archive.org/web/20200316210338/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)

### CSV

```
2020,03,15,CONFIRMADO,CABA,6
2020,03,15,CONFIRMADO,CHACO,2
2020,03,15,CONFIRMADO,TIERRADELFUEGO,2
2020,03,15,CONFIRMADO,PCIABSAS,1
2020,03,13,ALTA,CABA,3
```

## 2020 03 16

### Fuente

* A la fecha, en Argentina la mayoría de los casos son importados. Se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria y el país continúa en fase de
contención.
* Hoy fueron confirmados nueve (9) nuevos casos de COVID-19. Se trata de cinco (5) personas en la
Ciudad Autónoma de Buenos Aires, tres (3) en Chaco y uno (1) en Provincia de Buenos Aires. De los 9,
8 corresponden a personas con antecedente de viaje a zona de riesgo, mientras que el restante se
trata de un profesional de la salud de Chaco que trabaja en un establecimiento donde se atendieron
casos confirmados.
* El total de casos confirmados en Argentina es de 65, de los cuales 2 fallecieron. Los pacientes se
encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
* 3 Recuperados en CABA y 1 BSAS: [Fuente](https://web.archive.org/web/20200317172217/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)


### CSV

```
2020,03,16,CONFIRMADO,CABA,5
2020,03,16,CONFIRMADO,CHACO,3
2020,03,16,CONFIRMADO,PCIABSAS,1
2020,03,13,ALTA,CABA,3
2020,03,13,ALTA,PCIABSAS,1
```

## 2020 03 17

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados y se detecta transmisión local en
contactos estrechos, sin evidencia de transmisión comunitaria. El país continúa en fase de
contención.

* Hoy fueron confirmados 14 (13**) nuevos casos de COVID-19:
- 4 en la Ciudad Autónoma de Buenos Aires
- 2 (1**) en Provincia de Buenos Aires
- 2 en Córdoba
- 1 en Chaco
- 1 en Jujuy
- 1 en Salta
- 1 en Río Negro
- 1 en Entre Ríos (de nacionalidad extranjera)
- 1 en Santa Cruz (de nacionalidad extranjera)

* De los 14 casos, 12 corresponden a personas con antecedente de viaje a zona de riesgo, mientras
  que los otros 2 se trata de contactos estrechos de casos confirmados.
* El total de casos confirmados en Argentina es de 79 (78), de los cuales 2 fallecieron. Los pacientes se
  encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
** Cabe aclarar que 1 de los casos notificados en Provincia de Buenos Aires se reclasificó como paciente en seguimiento
y no constituyó un caso nuevo. Se trató de una persona a la que se le realizó un laboratorio para alta médica.
* 1 Recuperado Rio Negro: [Fuente](https://www.infobae.com/coronavirus/2020/03/17/confirmaron-los-primeros-casos-de-coronavirus-en-salta-y-jujuy/)

### CSV

PCIABSAS corregido por información posterior

```
2020,03,17,CONFIRMADO,CABA,4
2020,03,17,CONFIRMADO,PCIABSAS,1
2020,03,17,CONFIRMADO,CORDOBA,2
2020,03,17,CONFIRMADO,CHACO,1
2020,03,17,CONFIRMADO,JUJUY,1
2020,03,17,CONFIRMADO,SALTA,1
2020,03,17,CONFIRMADO,RIONEGRO,1
2020,03,17,CONFIRMADO,ENTRERIOS,1
2020,03,17,CONFIRMADO,SANTACRUZ,1
2020,03,17,ALTA,RIONEGRO,1
```

## 2020 03 18

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados y se detecta transmisión local en
conglomerados. En el país coexisten estrategias de contención y mitigación de mortalidad y
transmisión.

* Hoy fueron confirmados 19 nuevos casos de COVID-19:
- 10 en la Ciudad Autónoma de Buenos Aires
- 1 en Chaco
- 6 en Provincia de Buenos Aires
- 1 en Córdoba
- 1 en Entre Ríos

* De los 19 casos, 13 corresponden a personas con antecedente de viaje a zona de riesgo, mientras
  que los otros 5 se trata de contactos estrechos de casos confirmados, mientras que 1 están en
  investigación para determinar antecedente epidemiológico.
* El total de casos confirmados en Argentina es de 97, de los cuales 2 fallecieron. Los pacientes se
  encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
* Cabe aclarar que 1 de los casos notificados en el día de ayer de Provincia de Buenos Aires se
  reclasificó como paciente en seguimiento y no constituía un caso nuevo. Se trató de una persona a la
  que se le realizó un laboratorio para alta médica.
* 4 Recuperados CABA: [Fuente](https://web.archive.org/web/20200319232546/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)

### CSV

```
2020,03,18,CONFIRMADO,CABA,10
2020,03,18,CONFIRMADO,CHACO,1
2020,03,18,CONFIRMADO,PCIABSAS,6
2020,03,18,CONFIRMADO,CORDOBA,1
2020,03,18,CONFIRMADO,ENTRERIOS,1
2020,03,18,MUERTE,CABA,1
2020,03,18,ALTA,CABA,4
```

## 2020 03 19

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados y se detecta transmisión local en
conglomerados. En Argentina coexisten estrategias de contención y mitigación de mortalidad y
transmisión.

*  Hoy fueron confirmados 31 nuevos casos de COVID-19:
- 15 en Provincia de Buenos Aires
- 8 en la Ciudad Autónoma de Buenos Aires
- 3 en Córdoba
- 2 en Chaco
- 1 en Tucumán
- 1 en Santa Fe
- 1 Rio Negro

* De los 31 casos, 20 corresponden a personas con antecedente de viaje a zona de riesgo, mientras
  que 5 con contactos estrechos de casos confirmados. 6 se encuentran en investigación para
  determinar el antecedente epidemiológico
* El total de casos confirmados en Argentina es de 128, de los cuales 3 fallecieron. Los pacientes se
  encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
* 6 Recuperados CABA: [Fuente](https://web.archive.org/web/20200320011124/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)

### CSV

```
2020,03,19,CONFIRMADO,PCIABSAS,15
2020,03,19,CONFIRMADO,CABA,8
2020,03,19,CONFIRMADO,CORDOBA,3
2020,03,19,CONFIRMADO,CHACO,2
2020,03,19,CONFIRMADO,TUCUMAN,1
2020,03,19,CONFIRMADO,SANTAFE,1
2020,03,19,CONFIRMADO,RIONEGRO,1
2020,03,19,ALTA,CABA,6
```

## 2020 03 20

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados y se detecta transmisión local en
conglomerados. En Argentina coexisten estrategias de contención y mitigación de mortalidad y
transmisión.
* Hoy fueron confirmados 30 nuevos casos de COVID-19:
- 9 en Provincia de Buenos Aires
- 9 en la Ciudad Autónoma de Buenos Aires
- 5 en Córdoba
- 1 en Chaco
- 1 en Tierra del Fuego
- 1 en Entre Ríos
- 1 Corrientes
- 2 Neuquén
- 1 Santiago del Estero
* De los 30 casos, 22 corresponden a personas con antecedente de viaje a zona de riesgo, mientras
  que 4 con contactos estrechos de casos confirmados. Los otros 4 se encuentran en investigación
  para determinar el antecedente epidemiológico.
* El total de casos confirmados en Argentina es de 158, de los cuales 3 fallecieron. Los pacientes se
  encuentran cumpliendo el aislamiento establecido por las autoridades sanitarias.
* Wikipedia dice que Neuquén 1 y San Luis 1: **PENDIENTE:** revisar.
    * El caso de San Luis fue revisado. Se rtata de un sanlusino que vive en Córdoba.[Fuente](http://agenciasanluis.com/notas/2020/03/21/un-sanluiseno-con-coronavirus-esta-aislado-en-cordoba-el-paciente-nunca-fue-sospechado-por-nuestro-sistema-de-salud-en-san-luis-solo-existen-hoy-tres-casos-sospechosos/)
* 1 Recuperado en BSAS: [Fuente](https://www.gba.gob.ar/saludprovincia/noticias/dan_de_alta_la_primera_paciente_con_coronavirus_atendida_en_la_provincia_de)

### CSV

```
2020,03,20,CONFIRMADO,PCIABSAS,9
2020,03,20,CONFIRMADO,CABA,9
2020,03,20,CONFIRMADO,CORDOBA,5
2020,03,20,CONFIRMADO,CHACO,1
2020,03,20,CONFIRMADO,TIERRADELFUEGO,1
2020,03,20,CONFIRMADO,ENTRERIOS,1
2020,03,20,CONFIRMADO,CORRIENTES,1
2020,03,20,CONFIRMADO,NEUQUEN,2
2020,03,20,CONFIRMADO,SANTIAGODELESTERO,1
2020,03,20,ALTA,PCIABSAS,1
```

## 2020 03 21

* Al momento, en Argentina la mayoría de los casos son importados y se detecta
transmisión local en conglomerados. En Argentina coexisten estrategias de contención y
mitigación de mortalidad y transmisión.

Hoy fueron confirmados 67 nuevos casos de COVID-19:
- 29 en la Ciudad Autónoma de Buenos Aires
- 15 en Provincia de Buenos Aires
- 5 en Chaco
- 5 Mendoza
- 4 Córdoba
- 3 Tierra del Fuego
- 2 Corrientes
- 2 Santa Fe
- 1 Tucumán
- 1 Río Negro

* De los 67 casos, 45 corresponden a personas con antecedente de viaje a zona con
  transmisión comunitaria, mientras que 12 son contactos estrechos de casos confirmados.
  Los otros 10 se encuentran en investigación para determinar el antecedente
  epidemiológico.
* En el día de la fecha, se constató el fallecimiento de una paciente con diagnóstico de
  COVID19. Es el cuarto caso en el país. Se trata de una mujer de 67 años, residente de
  Provincia de Buenos Aires con antecedente de obesidad y enfermedad pulmonar
  obstructiva crónica. Presentaba antecedente de viaje a República Dominicana y crucero en
  el Caribe, desde el 29/2 al 12/3.
* El total de casos confirmados en Argentina es de 225, de los cuales 4 fallecieron. Las
  autoridades sanitarias de las provincias se encuentran realizando la investigación
  epidemiológica de los nuevos casos confirmados, con el fin de detectar los contactos
  estrechos para que cumplan el aislamiento domiciliario con seguimiento diario establecido
  por protocolo.
* 6 Recuperados en CABA: [Fuente](https://web.archive.org/web/20200322011541/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
    * Nota: Este numero es acumulado de los dias 20 y 21. No hay información oficial del día 20 por separado.
### CSV

```
2020,03,21,CONFIRMADO,CABA,29
2020,03,21,CONFIRMADO,PCIABSAS,15
2020,03,21,CONFIRMADO,CHACO,5
2020,03,21,CONFIRMADO,MENDOZA,5
2020,03,21,CONFIRMADO,CORDOBA,4
2020,03,21,CONFIRMADO,TIERRADELFUEGO,3
2020,03,21,CONFIRMADO,CORRIENTES,2
2020,03,21,CONFIRMADO,SANTAFE,2
2020,03,21,CONFIRMADO,TUCUMAN,1
2020,03,21,CONFIRMADO,RIONEGRO,1
2020,03,21,MUERTE,PCIABSAS,1
2020,03,21,ALTA,CABA,6
```

## 2020 03 22

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados, se detecta transmisión local en
conglomerados y se identifica un caso de posible transmisión comunitaria que se encuentra en
investigación. En nuestro país coexisten estrategias de contención y mitigación de mortalidad y
transmisión.

Hoy fueron confirmados 41 nuevos casos de COVID-19:
- 12 en la Ciudad Autónoma de Buenos Aires
- 8 en Provincia de Buenos Aires
- 8 Córdoba
- 7 en Chaco
- 5 Tucumán
- 1 Misiones

De los 41 casos, 17 corresponden a personas con antecedente de viaje a zonas con transmisión
comunitaria, mientras que 11 son contactos estrechos de casos confirmados, 12 se encuentran eninvestigación para determinar el antecedente epidemiológico y un caso de posible transmisión
comunitaria que se encuentra en investigación.
El total de casos confirmados en Argentina es de 266, de los cuales 4 fallecieron. Las autoridades
sanitarias de las provincias se encuentran realizando la investigación epidemiológica de los
nuevos casos confirmados, con el fin de detectar los contactos estrechos para que cumplan el
aislamiento domiciliario con seguimiento diario establecido por protocolo.
* 11 Recuperados en CABA:
    * [Fuente](https://web.archive.org/web/20200323080012/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
    * [Fuente2](https://www.lanacion.com.ar/sociedad/coronavirus-argentina-hay-xx-casos-nuevos-cifra-nid2346297)

### CSV

```
2020,03,22,CONFIRMADO,CABA,12
2020,03,22,CONFIRMADO,PCIABSAS,8
2020,03,22,CONFIRMADO,CORDOBA,8
2020,03,22,CONFIRMADO,CHACO,7
2020,03,22,CONFIRMADO,TUCUMAN,5
2020,03,22,CONFIRMADO,MISIONES,1
2020,03,21,ALTA,CABA,11
```

## 2020 03 23

### Fuente

* Al momento, en Argentina la mayoría de los casos son importados, se detecta transmisión
local en conglomerados y se identifica casos de posible transmisión comunitaria que se
encuentran en investigación. En nuestro país coexisten estrategias de contención y
mitigación de mortalidad y transmisión.

Hoy fueron confirmados 36 nuevos casos de COVID-19:
- 10 en la Ciudad Autónoma de Buenos Aires
- 5 en Provincia de Buenos Aires
- 13 Santa Fe
- 3 Córdoba
- 4 en Chaco

* De los 36 casos, 17 corresponden a personas con antecedente de viaje a zonas con
transmisión comunitaria, mientras que 5 son contactos estrechos de casos confirmados, 14
se encuentran en investigación para determinar el antecedente epidemiológico.
El total de casos confirmados en Argentina es de 301 (**IMPORTANTE**: Debido a la reclasificación de un caso que se encontraba
duplicado), de los cuales 4 fallecieron. Las autoridades sanitarias de las provincias se encuentran realizando la investigación
epidemiológica de los nuevos casos confirmados, con el fin de detectar los contactos
estrechos para que cumplan el aislamiento domiciliario con seguimiento diario establecido
por protocolo.
Del total, el 39,5% son mujeres y el 60,5% son hombres.
Respecto de las franjas etarias afectadas, el 2% de los casos registrados corresponde a
menores de 14 años, el 79% a casos de entre 15 y 59 años; y el 19% a casos de mayores de
60.
Nota: la notificación de los casos por jurisdicción se realiza teniendo en cuenta la residencia
según el Registro Nacional de las Personas. Pudiendo variar en función de la investigación
de la jurisdicción.
* 5 Recuperados en CABA: [Fuente](https://web.archive.org/web/20200324222725/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
* 7 Recuperados: Asignados a BS AS **Revisar**

### CSV

```
2020,03,23,CONFIRMADO,CABA,10
2020,03,23,CONFIRMADO,PCIABSAS,5
2020,03,23,CONFIRMADO,SANTAFE,13
2020,03,23,CONFIRMADO,CORDOBA,3
2020,03,23,CONFIRMADO,CHACO,4
2020,03,23,ALTA,CABA,5
2020,03,23,ALTA,PCIABSAS,7
```


## 2020 03 24

### Fuente
* Hoy fueron confirmados 86 nuevos casos de COVID-19:
  - 30 (28 *) en la Ciudad Autónoma de Buenos Aires
  - 30 en Provincia de Buenos Aires
  - 9 en Chaco
  - 7 en Córdoba
  - 4 en Tierra del Fuego
  - 3 Santa Fe
  - 1 en La Pampa
  - 1 en Neuquén
  - 1 en Santa Cruz
* En el día de hoy se registraron dos personas fallecidas.
* Del total, el 40,9% son mujeres y el 59,1% son hombres.
Respecto de las franjas etarias afectadas, el 2% de los casos registrados corresponde a
menores de 14 años, el 80% a casos de entre 15 y 59 años; el 18% a casos de mayores de
60. En Argentina, en total se han constatado 1453 casos negativos por laboratorio y 1735
casos descartados por investigación epidemiológica.
** Cabe señalar que 2 casos informados se reclasificaron por lo que dejaron de formar parte del total.
* A la fecha, fueron dados de alta 52 casos.
* 10 Recuperados CABA: [Fuente](https://web.archive.org/web/20200325140807/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
* 1 Recuperado Entre Rios: [Fuente](http://noticias.entrerios.gov.ar/notas/dieron-el-alta-a-uno-de-los-pacientes-positivos-para-coronavirus-en-entre-ros.htm)

### CSV

```
2020,03,24,CONFIRMADO,CABA,28
2020,03,24,CONFIRMADO,PCIABSAS,30
2020,03,24,CONFIRMADO,CHACO,9
2020,03,24,CONFIRMADO,CORDOBA,7
2020,03,24,CONFIRMADO,TIERRADELFUEGO,4
2020,03,24,CONFIRMADO,SANTAFE,3
2020,03,24,CONFIRMADO,LAPAMPA,1
2020,03,24,CONFIRMADO,NEUQUEN,1
2020,03,24,CONFIRMADO,SANTACRUZ,1
2020,03,24,MUERTE,CHACO,1
2020,03,24,MUERTE,PCIABSAS,1
2020,03,24,ALTA,CABA,10
2020,03,24,ALTA,ENTRERIOS,1
```


## 2020 03 25

### Fuente

* Hoy fueron confirmados 117 nuevos casos de COVID-19:
- 30 en Provincia de Buenos Aires
- 22 Santa Fe
- 21 en la Ciudad Autónoma de Buenos Aires
- 15 en Córdoba
- 12 en Chaco
- 5 Santa Cruz
- 4 San Luis
- 3 Entre Ríos
- 2 Tucumán
- 1 Mendoza
- 1 en Neuquén
- 1 Tierra del Fuego
* El total de casos confirmados en Argentina a las 19 horas de hoy es de 502, (*), 8
fallecieron.
* En el día de hoy se registraron dos personas fallecidas. Una mujer de 81 años de la
Ciudad de Aires que era un contacto estrecho de un caso confirmado y presentaba
enfermedad neurológica crónica. Una mujer de Chaco de 73 años de Chaco que
presentaba diabetes, hipertensión y obesidad.
A la fecha, fueron dados de alta 63 casos.
* 4 Recuperados CABA: [Fuente](https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
* 1 Recuperado Córdoba: [Fuente](https://prensa.cba.gov.ar/informacion-general/informe-diario-de-casos-covid-19/)
* 4 Recuperados: Asignados a BS AS **Revisar**

### CSV

```
2020,03,25,CONFIRMADO,CABA,30
2020,03,25,CONFIRMADO,SANTAFE,22
2020,03,25,CONFIRMADO,PCIABSAS,21
2020,03,25,CONFIRMADO,CORDOBA,15
2020,03,25,CONFIRMADO,CHACO,12
2020,03,25,CONFIRMADO,SANTACRUZ,5
2020,03,25,CONFIRMADO,SANLUIS,4
2020,03,25,CONFIRMADO,ENTRERIOS,3
2020,03,25,CONFIRMADO,TUCUMAN,2
2020,03,25,CONFIRMADO,MENDOZA,1
2020,03,25,CONFIRMADO,NEUQUEN,1
2020,03,25,CONFIRMADO,TIERRADELFUEGO,1
2020,03,25,MUERTE,CHACO,1
2020,03,25,MUERTE,CABA,1
2020,03,25,ALTA,CABA,4
2020,03,25,ALTA,CORDOBA,1
2020,03,25,ALTA,PCIABSAS,4
```
## 2020 03 26

### Fuente

* Hoy fueron confirmados 87 nuevos casos de COVID-19:
- 30 en la Ciudad Autónoma de Buenos Aires
- 27 en Provincia de Buenos Aires
- 12 Santa Fe
- 3 en Chaco
- 3 en Córdoba
- 3 en Tierra del Fuego
- 3 en Neuquén
- 2 Jujuy
- 2 en Santa Cruz
- 1 Mendoza
- 1 San Luis -> Se contabiliza para la provincia de Cordoba. Ver dia 28/3
* De los 87 casos, 37 corresponden a personas con antecedente de viaje a zonas con
transmisión comunitaria, mientras que 24 son contactos estrechos de casos
confirmados y 26 se encuentran en investigación para determinar el antecedente
epidemiológico.
El total de casos confirmados en Argentina es de 589, de los cuales 12 fallecieron.
Las autoridades sanitarias de las provincias se encuentran realizando la
investigación epidemiológica de los nuevos casos confirmados, con el fin de
detectar los contactos estrechos para que cumplan el aislamiento domiciliario con
seguimiento diario establecido por protocolo.
Los fallecidos pertenecen a Chaco, un hombre de 59 años con antecedente de viaje a
Estados Unidos y comorbilidades en estudio; dos hombres de la provincia de Buenos
Aires, uno de 89 y otro de 78; y una mujer de 82 años, de Ciudad de Buenos Aires.
* A la fecha, fueron dados de alta transitoria 70 casos y 2 pacientes con alta definitiva. Hay 22
pacientes internados (reportado por las jurisdicciones).
* 9 Recuperados CABA: [Fuente](http://web.archive.org/web/20200327221150/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)

### CSV

```
2020,03,26,CONFIRMADO,CABA,30
2020,03,26,CONFIRMADO,SANTAFE,12
2020,03,26,CONFIRMADO,PCIABSAS,27
2020,03,26,CONFIRMADO,CORDOBA,4
2020,03,26,CONFIRMADO,CHACO,3
2020,03,26,CONFIRMADO,TIERRADELFUEGO,3
2020,03,26,CONFIRMADO,NEUQUEN,3
2020,03,26,CONFIRMADO,SANTACRUZ,2
2020,03,26,CONFIRMADO,JUJUY,2
2020,03,26,CONFIRMADO,MENDOZA,1
2020,03,26,MUERTE,CHACO,1
2020,03,26,MUERTE,CABA,1
2020,03,26,MUERTE,PCIABSAS,2
2020,03,26,ALTA,CABA,9
```

## 2020 03 27

### Fuente

* Hoy fueron confirmados 101 nuevos casos de COVID-19 (nuevos y reclasificados*):
- 43 (33)  en la Ciudad Autónoma de Buenos Aires
- 36 (30) en Provincia de Buenos Aires
- 3 en Chaco
- 5 en Córdoba
- 6 en Tucumán
- 9 Santa Fe
- 3 en Entre Ríos
- 4 en Neuquén
- 1 en Mendoza
- 3 en Río Negro
- 2 en Corrientes
- 1 en Santiago del Estero
- 1 en Misiones
* A la fecha, fueron dados de alta transitoria 74 casos y 2 pacientes con alta definitiva.
* **IMPORTANTE**: 16 casos (anteriores) que en el día de ayer figuraban sin localidad de residencia y hoy se agruparon en las
jurisdicciones correspondientes. De loas partes de CABA se estima que le corresponden 10 de estos 16. # son asignados a Buenos aires **Revisar**
* 3 Muertes - CABA, MENDOZA y : [Fuente](https://www.cronista.com/economiapolitica/Coronavirus-Mendoza-sumo-su-primera-victima-y-son-14-los-fallecidos-en-el-pais-20200327-0086.html)
* 2 Muertes: PCIABSAS **Revisar**
* 13 Recuperados CABA: [fuente](http://web.archive.org/web/20200328132335/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)

### CSV

```
2020,03,27,CONFIRMADO,CABA,33
2020,03,27,CONFIRMADO,PCIABSAS,30
2020,03,27,CONFIRMADO,CHACO,3
2020,03,27,CONFIRMADO,CORDOBA,5
2020,03,27,CONFIRMADO,TUCUMAN,6
2020,03,27,CONFIRMADO,SANTAFE,9
2020,03,27,CONFIRMADO,ENTRERIOS,3
2020,03,27,CONFIRMADO,NEUQUEN,4
2020,03,27,CONFIRMADO,MENDOZA,1
2020,03,27,CONFIRMADO,RIONEGRO,3
2020,03,27,CONFIRMADO,CORRIENTES,2
2020,03,27,CONFIRMADO,SANTIAGODELESTERO,1
2020,03,27,CONFIRMADO,MISIONES,1
2020,03,27,MUERTE,RIONEGRO,1
2020,03,27,MUERTE,CABA,1
2020,03,27,MUERTE,MENDOZA,1
2020,03,27,MUERTE,PCIABSAS,2
2020,03,27,ALTA,CABA,13
```

## 2020 03 28

### Fuente
Detalle por provincia
- 18 en la Ciudad Autónoma de Buenos Aires
- 8 en Provincia de Buenos Aires
- 13 Santa Fe
- 5 en Chaco
- 1 en Córdoba -> Es un caso confirmado de San Luis que fue reclasificada la provincia de
residencia a Córdoba. Se contabiliza el dia 26/3
- 4 en Tierra del Fuego
- 2 en Neuquén
- 1 en Mendoza
- 4 en Corrientes
* A la fecha, fueron dados de alta transitoria 78 casos y 2 pacientes con alta definitiva.
En el día de hoy se confirmaron 2 nuevos fallecidos, sumando 19 en total en la
Argentina.

### CSV

```
2020,03,28,CONFIRMADO,CABA,18
2020,03,28,CONFIRMADO,PCIABSAS,8
2020,03,28,CONFIRMADO,CHACO,5
2020,03,28,CONFIRMADO,SANTAFE,13
2020,03,28,CONFIRMADO,NEUQUEN,2
2020,03,28,CONFIRMADO,MENDOZA,1
2020,03,28,CONFIRMADO,CORRIENTES,4
2020,03,28,CONFIRMADO,TIERRADELFUEGO,4
2020,03,28,MUERTE,CABA,1
2020,03,28,MUERTE,PCIABSAS,1
```

## 2020 03 29

### Fuente

* https://www.argentina.gob.ar/sites/default/files/29-03-20_reporte_vespertino_covid_19.pdf
* 7 Recuperados CABA: [fuente](https://web.archive.org/web/20200330163928/https://www.buenosaires.gob.ar/salud/noticias/actualizacion-de-los-casos-coronavirus-en-la-ciudad-buenos-aires)
* A la fecha, el total de altas fue de 91: 84 casos con alta transitoria y 7 pacientes con alta
definitiva.
* 2 Muertes PCIABSAS y TUCUMAN (a última hora del domingo): [Fuente](https://www.infobae.com/politica/2020/03/29/confirmaron-un-nuevo-muerto-y-75-nuevos-casos-de-coronavirus-la-cantidad-de-infectados-ascendio-a-820/)
* NOTA: Los informes diarios si bien indican la existencia de la muerte en TUCUMAN, no la contabilizan y arrastran el error en los informes siguientes.

### CSV

```
2020,03,29,CONFIRMADO,PCIABSAS,16
2020,03,29,CONFIRMADO,CABA,13
2020,03,29,CONFIRMADO,CHACO,4
2020,03,29,CONFIRMADO,SANTAFE,13
2020,03,29,CONFIRMADO,CORDOBA,18
2020,03,29,CONFIRMADO,TIERRADELFUEGO,4
2020,03,29,CONFIRMADO,SANJUAN,1
2020,03,29,CONFIRMADO,CORRIENTES,1
2020,03,29,CONFIRMADO,LAPAMPA,2
2020,03,29,CONFIRMADO,LARIOJA,1
2020,03,29,CONFIRMADO,MENDOZA,1
2020,03,29,CONFIRMADO,MISIONES,1
2020,03,29,MUERTE,PCIABSAS,1
2020,03,29,MUERTE,TUCUMAN,1
2020,03,29,ALTA,CABA,7
```

## 2020 03 30

### Fuente

* https://www.argentina.gob.ar/sites/default/files/30-03-20-reporte-vespertino-covid-19.pdf
* A la fecha, el total de altas es de 228: 219 casos con alta transitoria y 9 pacientes con alta
definitiva.
* 5 Recuperados CABA
* **Revisar** 122 Recuperados sin distribuir por falta de informacion. Asignados a PCIABSAS

### CSV

```
2020,03,30,CONFIRMADO,PCIABSAS,36
2020,03,30,CONFIRMADO,CABA,34
2020,03,30,CONFIRMADO,CHACO,12
2020,03,30,CONFIRMADO,SANTAFE,21
2020,03,30,CONFIRMADO,CORDOBA,8
2020,03,30,CONFIRMADO,TIERRADELFUEGO,11
2020,03,30,CONFIRMADO,CORRIENTES,10
2020,03,30,CONFIRMADO,ENTRERIOS,3
2020,03,30,CONFIRMADO,MENDOZA,3
2020,03,30,CONFIRMADO,NEUQUEN,8
2020,03,30,MUERTE,PCIABSAS,2
2020,03,30,MUERTE,TUCUMAN,1
2020,03,30,MUERTE,NEUQUEN,1
2020,03,30,ALTA,CABA,5
2020,03,30,ALTA,PCIABSAS,122
```


## 2020 03 31

### Fuente

* https://www.argentina.gob.ar/sites/default/files/31-03-20-reporte-vespertino-covid-19.pdf
* A la fecha, el total de altas es de 240 personas. 228 son altas transitorias y 12
definitivas.
* 5 Recuperados CABA
* **Revisar** 7 Recuperados sin distribuir por falta de informacion. Asignados a PCIABSAS

### CSV

```
2020,03,31,CONFIRMADO,PCIABSAS,17
2020,03,31,CONFIRMADO,CABA,19
2020,03,31,CONFIRMADO,CHACO,3
2020,03,31,CONFIRMADO,CORDOBA,14
2020,03,31,CONFIRMADO,CORRIENTES,1
2020,03,31,CONFIRMADO,MENDOZA,2
2020,03,31,CONFIRMADO,MISIONES,1
2020,03,31,CONFIRMADO,RIONEGRO,1
2020,03,31,CONFIRMADO,SANTAFE,22
2020,03,31,CONFIRMADO,TIERRADELFUEGO,7
2020,03,31,CONFIRMADO,TUCUMAN,1
2020,03,31,MUERTE,CHACO,1
2020,03,31,MUERTE,LARIOJA,1
2020,03,31,MUERTE,CORDOBA,1
2020,03,30,ALTA,CABA,5
2020,03,30,ALTA,PCIABSAS,7
```


## 2020 04 01

### Fuente

* https://www.argentina.gob.ar/sites/default/files/01-04-20_reporte_vespertino_covid-19.pdf
* A la fecha, el total de altas es de 248 personas. 218 son altas transitorias y 30 definitivas.

### CSV

```
2020,04,01,CONFIRMADO,PCIABSAS,10
2020,04,01,CONFIRMADO,CABA,10
2020,04,01,CONFIRMADO,CHACO,12
2020,04,01,CONFIRMADO,CORDOBA,6
2020,04,01,CONFIRMADO,CORRIENTES,1
2020,04,01,CONFIRMADO,ENTRERIOS,1
2020,04,01,CONFIRMADO,MENDOZA,10
2020,04,01,CONFIRMADO,NEUQUEN,4
2020,04,01,CONFIRMADO,SALTA,2
2020,04,01,CONFIRMADO,SANLUIS,1
2020,04,01,CONFIRMADO,SANTACRUZ,10
2020,04,01,CONFIRMADO,SANTAFE,11
2020,04,01,CONFIRMADO,TUCUMAN,1
2020,04,01,MUERTE,CABA,1
2020,04,01,MUERTE,PCIABSAS,2
2020,04,01,MUERTE,SANTAFE,1
2020,04,01,MUERTE,NEUQUEN,1
2020,04,01,ALTA,CABA,8
```


## 2020 04 02

### Fuente

* A la fecha, el total de altas es de 256 personas. 220 son altas transitorias y 36 definitivas.
* FIXME: Altas Asignadas a CABA por falta de informacion. (8)

### CSV

```
2020,04,02,CONFIRMADO,PCIABSAS,36
2020,04,02,CONFIRMADO,CABA,24
2020,04,02,CONFIRMADO,CATAMARCA,0
2020,04,02,CONFIRMADO,CHACO,3
2020,04,02,CONFIRMADO,CHUBUT,0
2020,04,02,CONFIRMADO,CORDOBA,16
2020,04,02,CONFIRMADO,CORRIENTES,1
2020,04,02,CONFIRMADO,ENTRERIOS,2
2020,04,02,CONFIRMADO,FORMOSA,0
2020,04,02,CONFIRMADO,JUJUY,2
2020,04,02,CONFIRMADO,LAPAMPA,0
2020,04,02,CONFIRMADO,LARIOJA,3
2020,04,02,CONFIRMADO,MENDOZA,0
2020,04,02,CONFIRMADO,MISIONES,0
2020,04,02,CONFIRMADO,NEUQUEN,4
2020,04,02,CONFIRMADO,RIONEGRO,0
2020,04,02,CONFIRMADO,SALTA,0
2020,04,02,CONFIRMADO,SANJUAN,0
2020,04,02,CONFIRMADO,SANLUIS,2
2020,04,02,CONFIRMADO,SANTACRUZ,2
2020,04,02,CONFIRMADO,SANTAFE,8
2020,04,02,CONFIRMADO,SANTIAGODELESTERO,1
2020,04,02,CONFIRMADO,TIERRADELFUEGO,24
2020,04,02,CONFIRMADO,TUCUMAN,4
2020,04,02,MUERTE,MENDOZA,1
2020,04,02,MUERTE,CHACO,1
2020,04,02,MUERTE,PCIABSAS,2
2020,04,02,ALTA,CABA,8
```


## 2020 04 03

### Fuente

* A la fecha, el total de altas es de 266 personas. 215 son altas transitorias y 51 definitivas.
* FIXME: Altas Asignadas a CABA por falta de informacion. (10)

### CSV

```
2020,04,03,CONFIRMADO,CHACO,8
2020,04,03,CONFIRMADO,CORDOBA,14
2020,04,03,CONFIRMADO,SANTAFE,8
2020,04,03,CONFIRMADO,ENTRERIOS,2
2020,04,03,CONFIRMADO,SANLUIS,1
2020,04,03,CONFIRMADO,MENDOZA,2
2020,04,03,CONFIRMADO,PCIABSAS,22
2020,04,03,CONFIRMADO,CABA,28
2020,04,03,CONFIRMADO,NEUQUEN,1
2020,04,03,CONFIRMADO,RIONEGRO,1
2020,04,03,CONFIRMADO,TIERRADELFUEGO,1
2020,04,03,MUERTE,CHACO,1
2020,04,03,MUERTE,MENDOZA,1
2020,04,03,MUERTE,PCIABSAS,3
2020,04,03,MUERTE,TUCUMAN,1
2020,04,03,ALTA,CABA,10
```

## 2020 04 04

### Fuente

 * A la fecha, el total de altas es de 279personas. Altas transitorias 215 y altas definitivas 64.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (13)

### CSV

```
2020,04,04,CONFIRMADO,CABA,34
2020,04,04,CONFIRMADO,CHACO,8
2020,04,04,CONFIRMADO,CORDOBA,3
2020,04,04,CONFIRMADO,LARIOJA,2
2020,04,04,CONFIRMADO,NEUQUEN,4
2020,04,04,CONFIRMADO,PCIABSAS,26
2020,04,04,CONFIRMADO,RIONEGRO,5
2020,04,04,CONFIRMADO,SANTACRUZ,1
2020,04,04,CONFIRMADO,SANTAFE,5
2020,04,04,CONFIRMADO,SANTIAGODELESTERO,1
2020,04,04,CONFIRMADO,TIERRADELFUEGO,8
2020,04,04,CONFIRMADO,TUCUMAN,1
2020,04,04,MUERTE,PCIABSAS,1
2020,04,04,ALTA,CABA,13
```

## 2020 04 05

### Fuente

 * A la fecha, el total de altas es de 280 personas. Altas transitorias 193 y altas definitivas 83.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (1)

### CSV

```
2020,04,05,CONFIRMADO,CABA,32
2020,04,05,CONFIRMADO,CORDOBA,5
2020,04,05,CONFIRMADO,ENTRERIOS,1
2020,04,05,CONFIRMADO,LARIOJA,2
2020,04,05,CONFIRMADO,MENDOZA,2
2020,04,05,CONFIRMADO,NEUQUEN,11
2020,04,05,CONFIRMADO,PCIABSAS,33
2020,04,05,CONFIRMADO,RIONEGRO,2
2020,04,05,CONFIRMADO,SANTACRUZ,1
2020,04,05,CONFIRMADO,SANTAFE,11
2020,04,05,CONFIRMADO,TIERRADELFUEGO,3
2020,04,05,MUERTE,CORDOBA,1
2020,04,05,MUERTE,CABA,1
2020,04,05,MUERTE,PCIABSAS,1
2020,04,05,ALTA,CABA,1
```

## 2020 04 06

### Fuente

 * A la fecha, el total de altas es de 325 personas. Altas transitorias 218 y altas definitivas 107.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (45)

### CSV

```
2020,04,06,CONFIRMADO,CABA,17
2020,04,06,CONFIRMADO,CHACO,4
2020,04,06,CONFIRMADO,CORDOBA,7
2020,04,06,CONFIRMADO,CORRIENTES,2
2020,04,06,CONFIRMADO,LARIOJA,1
2020,04,06,CONFIRMADO,MENDOZA,1
2020,04,06,CONFIRMADO,NEUQUEN,6
2020,04,06,CONFIRMADO,PCIABSAS,12
2020,04,06,CONFIRMADO,RIONEGRO,2
2020,04,06,CONFIRMADO,SANLUIS,1
2020,04,06,CONFIRMADO,SANTAFE,8
2020,04,06,CONFIRMADO,SANTIAGODELESTERO,6
2020,04,06,CONFIRMADO,TIERRADELFUEGO,2
2020,04,06,CONFIRMADO,TUCUMAN,5
2020,04,06,MUERTE,CABA,4
2020,04,06,MUERTE,NEUQUEN,1
2020,04,06,MUERTE,PCIABSAS,2
2020,04,06,ALTA,CABA,45
```


## 2020 04 07

### Fuente

 * A la fecha, el total de altas es de 338 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (13)

### CSV

```
2020,04,07,CONFIRMADO,CABA,24
2020,04,07,CONFIRMADO,CHACO,4
2020,04,07,CONFIRMADO,CORDOBA,4
2020,04,07,CONFIRMADO,ENTRERIOS,1
2020,04,07,CONFIRMADO,MENDOZA,2
2020,04,07,CONFIRMADO,NEUQUEN,3
2020,04,07,CONFIRMADO,PCIABSAS,34
2020,04,07,CONFIRMADO,RIONEGRO,2
2020,04,07,CONFIRMADO,SANTACRUZ,8
2020,04,07,CONFIRMADO,SANTAFE,3
2020,04,07,CONFIRMADO,SANTIAGODELESTERO,-1
2020,04,07,CONFIRMADO,TIERRADELFUEGO,2
2020,04,07,CONFIRMADO,TUCUMAN,1
2020,04,07,MUERTE,CABA,2
2020,04,07,MUERTE,MENDOZA,1
2020,04,07,MUERTE,PCIABSAS,4
2020,04,07,ALTA,CABA,13
```


## 2020 04 08

### Fuente

 * A la fecha, el total de altas es de 358 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (20)

### CSV

```
2020,04,08,CONFIRMADO,CABA,18
2020,04,08,CONFIRMADO,CHACO,15
2020,04,08,CONFIRMADO,CORDOBA,1
2020,04,08,CONFIRMADO,LAPAMPA,1
2020,04,08,CONFIRMADO,MENDOZA,6
2020,04,08,CONFIRMADO,NEUQUEN,17
2020,04,08,CONFIRMADO,PCIABSAS,17
2020,04,08,CONFIRMADO,RIONEGRO,1
2020,04,08,CONFIRMADO,SANTAFE,2
2020,04,08,CONFIRMADO,TIERRADELFUEGO,2
2020,04,08,MUERTE,CABA,2
2020,04,08,MUERTE,NEUQUEN,1
2020,04,08,MUERTE,PCIABSAS,1
2020,04,08,MUERTE,TUCUMAN,1
2020,04,08,ALTA,CABA,20
```


## 2020 04 09

### Fuente

 * A la fecha, el total de altas es de 365 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (7)

### CSV

```
2020,04,09,MUERTE,CABA,5
2020,04,09,MUERTE,CHACO,1
2020,04,09,MUERTE,PCIABSAS,7
2020,04,09,MUERTE,SANTAFE,1
2020,04,09,CONFIRMADO,CABA,23
2020,04,09,CONFIRMADO,CHACO,6
2020,04,09,CONFIRMADO,CORDOBA,5
2020,04,09,CONFIRMADO,ENTRERIOS,2
2020,04,09,CONFIRMADO,LARIOJA,5
2020,04,09,CONFIRMADO,MENDOZA,2
2020,04,09,CONFIRMADO,NEUQUEN,7
2020,04,09,CONFIRMADO,PCIABSAS,28
2020,04,09,CONFIRMADO,RIONEGRO,13
2020,04,09,CONFIRMADO,SANTAFE,7
2020,04,09,CONFIRMADO,TUCUMAN,1
2020,04,09,ALTA,CABA,7
```


## 2020 04 10

### Fuente

 * A la fecha, el total de altas es de 375 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (10)

### CSV

```
2020,04,10,CONFIRMADO,CABA,11
2020,04,10,CONFIRMADO,CHACO,5
2020,04,10,CONFIRMADO,CORDOBA,13
2020,04,10,CONFIRMADO,LAPAMPA,1
2020,04,10,CONFIRMADO,MENDOZA,9
2020,04,10,CONFIRMADO,NEUQUEN,7
2020,04,10,CONFIRMADO,PCIABSAS,19
2020,04,10,CONFIRMADO,RIONEGRO,7
2020,04,10,CONFIRMADO,SANTACRUZ,6
2020,04,10,CONFIRMADO,SANTAFE,1
2020,04,10,CONFIRMADO,TIERRADELFUEGO,2
2020,04,10,MUERTE,CABA,1
2020,04,10,MUERTE,PCIABSAS,1
2020,04,10,MUERTE,RIONEGRO,1
2020,04,10,ALTA,CABA,10
```


## 2020 04 11

### Fuente

 * A la fecha, el total de altas es de 440 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (65)

### CSV

```
2020,04,11,CONFIRMADO,CABA,46
2020,04,11,CONFIRMADO,CORDOBA,32
2020,04,11,CONFIRMADO,LARIOJA,4
2020,04,11,CONFIRMADO,MENDOZA,5
2020,04,11,CONFIRMADO,NEUQUEN,1
2020,04,11,CONFIRMADO,PCIABSAS,37
2020,04,11,CONFIRMADO,RIONEGRO,23
2020,04,11,CONFIRMADO,SANJUAN,1
2020,04,11,CONFIRMADO,SANTACRUZ,3
2020,04,11,CONFIRMADO,SANTAFE,3
2020,04,11,CONFIRMADO,SANTIAGODELESTERO,3
2020,04,11,CONFIRMADO,TIERRADELFUEGO,8
2020,04,11,CONFIRMADO,TUCUMAN,1
2020,04,11,MUERTE,CABA,3
2020,04,11,MUERTE,PCIABSAS,4
2020,04,11,ALTA,CABA,65
```


## 2020 04 12

### Fuente

 * A la fecha, el total de altas es de 468 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (28)

### CSV

```
2020,04,12,CONFIRMADO,CABA,8
2020,04,12,CONFIRMADO,CHACO,1
2020,04,12,CONFIRMADO,CORDOBA,5
2020,04,12,CONFIRMADO,ENTRERIOS,-1
2020,04,12,CONFIRMADO,LARIOJA,1
2020,04,12,CONFIRMADO,MENDOZA,3
2020,04,12,CONFIRMADO,NEUQUEN,1
2020,04,12,CONFIRMADO,PCIABSAS,28
2020,04,12,CONFIRMADO,RIONEGRO,13
2020,04,12,CONFIRMADO,SANTAFE,3
2020,04,12,CONFIRMADO,TIERRADELFUEGO,4
2020,04,12,MUERTE,CABA,1
2020,04,12,MUERTE,CORDOBA,1
2020,04,12,MUERTE,PCIABSAS,4
2020,04,12,ALTA,CABA,28
```


## 2020 04 13

### Fuente

 * A la fecha, el total de altas es de 515 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (47)

### CSV

```
2020,04,13,CONFIRMADO,CABA,10
2020,04,13,CONFIRMADO,CHACO,3
2020,04,13,CONFIRMADO,CORDOBA,4
2020,04,13,CONFIRMADO,CORRIENTES,7
2020,04,13,CONFIRMADO,LARIOJA,3
2020,04,13,CONFIRMADO,MENDOZA,2
2020,04,13,CONFIRMADO,NEUQUEN,2
2020,04,13,CONFIRMADO,PCIABSAS,29
2020,04,13,CONFIRMADO,RIONEGRO,3
2020,04,13,CONFIRMADO,SANTAFE,2
2020,04,13,CONFIRMADO,TIERRADELFUEGO,4
2020,04,13,MUERTE,CABA,1
2020,04,13,MUERTE,CORDOBA,1
2020,04,13,MUERTE,PCIABSAS,1
2020,04,13,ALTA,CABA,47
```

## 2020 04 14

### Fuente

 * A la fecha, el total de altas es de 559 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (44)

### CSV

```
2020,04,14,CONFIRMADO,PCIABSAS,66
2020,04,14,CONFIRMADO,CABA,22
2020,04,14,CONFIRMADO,CHACO,31
2020,04,14,CONFIRMADO,CORDOBA,12
2020,04,14,CONFIRMADO,CORRIENTES,1
2020,04,14,CONFIRMADO,LARIOJA,6
2020,04,14,CONFIRMADO,MENDOZA,3
2020,04,14,CONFIRMADO,NEUQUEN,2
2020,04,14,CONFIRMADO,RIONEGRO,13
2020,04,14,CONFIRMADO,SANTAFE,2
2020,04,14,CONFIRMADO,TIERRADELFUEGO,8
2020,04,14,MUERTE,CABA,2
2020,04,14,MUERTE,CHACO,1
2020,04,14,MUERTE,CORDOBA,1
2020,04,14,MUERTE,RIONEGRO,1
2020,04,14,MUERTE,PCIABSAS,2
2020,04,14,ALTA,CABA,44
```

## 2020 04 15

### Fuente

 * A la fecha, el total de altas es de 596 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (37)

### CSV

```
2020,04,15,CONFIRMADO,PCIABSAS,62
2020,04,15,CONFIRMADO,CABA,30
2020,04,15,CONFIRMADO,CHACO,7
2020,04,15,CONFIRMADO,CHUBUT,1
2020,04,15,CONFIRMADO,CORDOBA,6
2020,04,15,CONFIRMADO,CORRIENTES,-1
2020,04,15,CONFIRMADO,LARIOJA,3
2020,04,15,CONFIRMADO,MENDOZA,1
2020,04,15,CONFIRMADO,NEUQUEN,1
2020,04,15,CONFIRMADO,RIONEGRO,12
2020,04,15,CONFIRMADO,SALTA,1
2020,04,15,CONFIRMADO,SANTAFE,2
2020,04,15,CONFIRMADO,TIERRADELFUEGO,3
2020,04,15,MUERTE,CABA,4
2020,04,15,MUERTE,LARIOJA,1
2020,04,15,MUERTE,CORDOBA,1
2020,04,15,MUERTE,PCIABSAS,1
2020,04,15,ALTA,CABA,37
```

## 2020 04 16

### Fuente

 * A la fecha, el total de altas es de 631 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (35)

### CSV

```
2020,04,16,CONFIRMADO,PCIABSAS,30
2020,04,16,CONFIRMADO,CABA,15
2020,04,16,CONFIRMADO,CHACO,11
2020,04,16,CONFIRMADO,CHUBUT,1
2020,04,16,CONFIRMADO,CORDOBA,13
2020,04,16,CONFIRMADO,ENTRERIOS,1
2020,04,16,CONFIRMADO,LARIOJA,3
2020,04,16,CONFIRMADO,MENDOZA,5
2020,04,16,CONFIRMADO,NEUQUEN,1
2020,04,16,CONFIRMADO,RIONEGRO,9
2020,04,16,CONFIRMADO,SALTA,-1
2020,04,16,CONFIRMADO,SANTAFE,3
2020,04,16,CONFIRMADO,TIERRADELFUEGO,7
2020,04,16,MUERTE,CABA,3
2020,04,16,MUERTE,PCIABSAS,5
2020,04,16,MUERTE,MENDOZA,1
2020,04,16,MUERTE,CHACO,1
2020,04,16,ALTA,CABA,35
```


## 2020 04 17

### Fuente

 * A la fecha, el total de altas es de 666 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (35)
 * Un caso reportado ayer por la provincia de Chubut, fue reclasificado por domicilio real a Provincia de Buenos Aires. Se agrega a Buenos Aires.

### CSV

```
2020,04,17,CONFIRMADO,PCIABSAS,35
2020,04,17,CONFIRMADO,CABA,14
2020,04,17,CONFIRMADO,CHACO,22
2020,04,17,CONFIRMADO,CHUBUT,-1
2020,04,17,CONFIRMADO,CORDOBA,6
2020,04,17,CONFIRMADO,LARIOJA,1
2020,04,17,CONFIRMADO,MENDOZA,1
2020,04,17,CONFIRMADO,MISIONES,1
2020,04,17,CONFIRMADO,NEUQUEN,1
2020,04,17,CONFIRMADO,RIONEGRO,1
2020,04,17,CONFIRMADO,SANTAFE,6
2020,04,17,CONFIRMADO,TIERRADELFUEGO,2
2020,04,17,MUERTE,CABA,1
2020,04,17,MUERTE,PCIABSAS,3
2020,04,17,MUERTE,MENDOZA,2
2020,04,17,MUERTE,LARIOJA,1
2020,04,17,ALTA,CABA,35
```

## 2020 04 18

### Fuente

 * A la fecha, el total de altas es de 685 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (19)

 ### CSV

```
2020,04,18,CONFIRMADO,PCIABSAS,31
2020,04,18,CONFIRMADO,CABA,14
2020,04,18,CONFIRMADO,CHACO,24
2020,04,18,CONFIRMADO,CORDOBA,2
2020,04,18,CONFIRMADO,MISIONES,1
2020,04,18,CONFIRMADO,NEUQUEN,3
2020,04,18,CONFIRMADO,RIONEGRO,3
2020,04,18,CONFIRMADO,SANTAFE,3
2020,04,18,MUERTE,CABA,1
2020,04,18,MUERTE,PCIABSAS,2
2020,04,18,ALTA,CABA,19
```

## 2020 04 19

### Fuente

 * A la fecha, el total de altas es de 709 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (24)
 * Este dia se contabilizan 6 muertes pero el

 ### CSV

```
2020,04,19,CONFIRMADO,PCIABSAS,48
2020,04,19,CONFIRMADO,CABA,15
2020,04,19,CONFIRMADO,CHACO,5
2020,04,19,CONFIRMADO,CHUBUT,1
2020,04,19,CONFIRMADO,CORDOBA,11
2020,04,19,CONFIRMADO,LARIOJA,4
2020,04,19,CONFIRMADO,MENDOZA,3
2020,04,19,CONFIRMADO,NEUQUEN,3
2020,04,19,CONFIRMADO,RIONEGRO,8
2020,04,19,CONFIRMADO,SANTAFE,1
2020,04,19,CONFIRMADO,TIERRADELFUEGO,3
2020,04,19,MUERTE,CORDOBA,1
2020,04,19,MUERTE,PCIABSAS,1
2020,04,19,ALTA,CABA,24
```

# 2020 04 20

### Fuente

 * A la fecha, el total de altas es de 737 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (28)

 ### CSV

```
2020,04,20,CONFIRMADO,PCIABSAS,42
2020,04,20,CONFIRMADO,CABA,22
2020,04,20,CONFIRMADO,CHACO,5
2020,04,20,CONFIRMADO,CORRIENTES,3
2020,04,20,CONFIRMADO,MENDOZA,1
2020,04,20,CONFIRMADO,NEUQUEN,3
2020,04,20,CONFIRMADO,RIONEGRO,10
2020,04,20,CONFIRMADO,SANTACRUZ,1
2020,04,20,CONFIRMADO,SANTAFE,2
2020,04,20,CONFIRMADO,TUCUMAN,1
2020,04,20,MUERTE,CORDOBA,2
2020,04,20,MUERTE,CABA,1
2020,04,20,MUERTE,RIONEGRO,3
2020,04,20,MUERTE,CHACO,1
2020,04,20,MUERTE,MENDOZA,1
2020,04,20,ALTA,CABA,28
```

# 2020 04 21

### Fuente

 * A la fecha, el total de altas es de 840 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (103)
 * Aca se suma un caso confirmado en el informe pero no matchea con los casos del dia.

 ### CSV

```
2020,04,21,CONFIRMADO,PCIABSAS,60
2020,04,21,CONFIRMADO,CABA,33
2020,04,21,CONFIRMADO,CHACO,5
2020,04,21,CONFIRMADO,LARIOJA,1
2020,04,21,CONFIRMADO,RIONEGRO,11
2020,04,21,CONFIRMADO,SANTAFE,1
2020,04,21,CONFIRMADO,TIERRADELFUEGO,1
2020,04,21,MUERTE,PCIABSAS,4
2020,04,21,MUERTE,LARIOJA,2
2020,04,21,MUERTE,CABA,3
2020,04,21,ALTA,CABA,103
```

# 2020 04 22

### Fuente

 * A la fecha, el total de altas es de 872 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (32)

 ### CSV

```
2020,04,22,CONFIRMADO,PCIABSAS,61
2020,04,22,CONFIRMADO,CABA,39
2020,04,22,CONFIRMADO,CHACO,7
2020,04,22,CONFIRMADO,CORDOBA,4
2020,04,22,CONFIRMADO,LARIOJA,5
2020,04,22,CONFIRMADO,MENDOZA,1
2020,04,22,CONFIRMADO,NEUQUEN,1
2020,04,22,CONFIRMADO,RIONEGRO,17
2020,04,22,CONFIRMADO,SANTAFE,5
2020,04,22,CONFIRMADO,TUCUMAN,4
2020,04,22,MUERTE,PCIABSAS,5
2020,04,22,MUERTE,CORDOBA,1
2020,04,22,MUERTE,CABA,2
2020,04,22,ALTA,CABA,32
```

# 2020 04 23

### Fuente

 * A la fecha, el total de altas es de 919 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (47)

 ### CSV

```
2020,04,23,CONFIRMADO,PCIABSAS,84
2020,04,23,CONFIRMADO,CABA,37
2020,04,23,CONFIRMADO,CHACO,10
2020,04,23,CONFIRMADO,CORDOBA,2
2020,04,23,CONFIRMADO,CORRIENTES,1
2020,04,23,CONFIRMADO,MENDOZA,1
2020,04,23,CONFIRMADO,NEUQUEN,1
2020,04,23,CONFIRMADO,RIONEGRO,4
2020,04,23,CONFIRMADO,SANTAFE,6
2020,04,23,CONFIRMADO,TIERRADELFUEGO,1
2020,04,23,MUERTE,PCIABSAS,4
2020,04,23,MUERTE,MENDOZA,1
2020,04,23,MUERTE,CABA,1
2020,04,23,ALTA,CABA,47
```

# 2020 04 24

### Fuente

 * A la fecha, el total de altas es de 976 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (57)

 ### CSV

```
2020,04,24,CONFIRMADO,PCIABSAS,61
2020,04,24,CONFIRMADO,CABA,79
2020,04,24,CONFIRMADO,CHACO,7
2020,04,24,CONFIRMADO,CORDOBA,4
2020,04,24,CONFIRMADO,CORRIENTES,4
2020,04,24,CONFIRMADO,LARIOJA,2
2020,04,24,CONFIRMADO,MISIONES,1
2020,04,24,CONFIRMADO,RIONEGRO,11
2020,04,24,CONFIRMADO,SANTACRUZ,1
2020,04,24,CONFIRMADO,SANTAFE,3
2020,04,24,CONFIRMADO,TUCUMAN,-1
2020,04,24,MUERTE,PCIABSAS,4
2020,04,24,MUERTE,CORDOBA,1
2020,04,24,MUERTE,MISIONES,1
2020,04,24,MUERTE,CHACO,1
2020,04,24,MUERTE,CABA,4
2020,04,24,ALTA,CABA,57
```

# 2020 04 25

### Fuente

 * A la fecha, el total de altas es de 1030 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (54)

 ### CSV

```
2020,04,25,CONFIRMADO,PCIABSAS,94
2020,04,25,CONFIRMADO,CABA,55
2020,04,25,CONFIRMADO,CHACO,7
2020,04,25,CONFIRMADO,CORDOBA,1
2020,04,25,CONFIRMADO,CORRIENTES,1
2020,04,25,CONFIRMADO,LARIOJA,3
2020,04,25,CONFIRMADO,RIONEGRO,4
2020,04,25,CONFIRMADO,SANTAFE,3
2020,04,25,CONFIRMADO,SANTIAGODELESTERO,1
2020,04,25,CONFIRMADO,TIERRADELFUEGO,4
2020,04,25,MUERTE,PCIABSAS,2
2020,04,25,MUERTE,RIONEGRO,1
2020,04,25,MUERTE,CORDOBA,1
2020,04,25,MUERTE,LARIOJA,1
2020,04,25,MUERTE,CABA,4
2020,04,25,ALTA,CABA,54
```

# 2020 04 26

### Fuente

 * A la fecha, el total de altas es de 1107 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (77)

 ### CSV

```
2020,04,26,CONFIRMADO,PCIABSAS,56
2020,04,26,CONFIRMADO,CABA,36
2020,04,26,CONFIRMADO,CHACO,3
2020,04,26,CONFIRMADO,CORDOBA,3
2020,04,26,CONFIRMADO,CORRIENTES,6
2020,04,26,CONFIRMADO,ENTRERIOS,1
2020,04,26,CONFIRMADO,NEUQUEN,1
2020,04,26,CONFIRMADO,RIONEGRO,1
2020,04,26,CONFIRMADO,SALTA,1
2020,04,26,CONFIRMADO,SANTACRUZ,1
2020,04,26,CONFIRMADO,SANTAFE,0
2020,04,26,CONFIRMADO,SANTIAGODELESTERO,2
2020,04,26,CONFIRMADO,TUCUMAN,1
2020,04,26,MUERTE,PCIABSAS,2
2020,04,26,MUERTE,CABA,5
2020,04,26,ALTA,CABA,77
```

# 2020 04 27

### Fuente

 * A la fecha, el total de altas es de 1140 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (33)

 ### CSV

```
2020,04,27,CONFIRMADO,PCIABSAS,50
2020,04,27,CONFIRMADO,CABA,32
2020,04,27,CONFIRMADO,CHACO,10
2020,04,27,CONFIRMADO,MISIONES,2
2020,04,27,CONFIRMADO,NEUQUEN,3
2020,04,27,CONFIRMADO,RIONEGRO,8
2020,04,27,CONFIRMADO,SANTACRUZ,5
2020,04,27,CONFIRMADO,TIERRADELFUEGO,1
2020,04,27,MUERTE,PCIABSAS,1
2020,04,27,MUERTE,CORDOBA,1
2020,04,27,MUERTE,CABA,2
2020,04,27,MUERTE,CHACO,1
2020,04,27,ALTA,CABA,33
```

# 2020 04 28

### Fuente

 * A la fecha, el total de altas es de 1162 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (22)

 ### CSV

```
2020,04,28,CONFIRMADO,PCIABSAS,48
2020,04,28,CONFIRMADO,CABA,50
2020,04,28,CONFIRMADO,CORDOBA,2
2020,04,28,CONFIRMADO,CORRIENTES,1
2020,04,28,CONFIRMADO,LARIOJA,1
2020,04,28,CONFIRMADO,MENDOZA,1
2020,04,28,CONFIRMADO,RIONEGRO,13
2020,04,28,CONFIRMADO,SANTAFE,1
2020,04,28,CONFIRMADO,TIERRADELFUEGO,6
2020,04,28,CONFIRMADO,TUCUMAN,1
2020,04,28,MUERTE,PCIABSAS,6
2020,04,28,MUERTE,NEUQUEN,1
2020,04,28,MUERTE,CABA,2
2020,04,28,MUERTE,CORDOBA,1
2020,04,28,ALTA,CABA,22
```

# 2020 04 29

### Fuente

 * A la fecha, el total de altas es de 1192 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (30)

 ### CSV

```
2020,04,29,CONFIRMADO,PCIABSAS,103
2020,04,29,CONFIRMADO,CABA,34
2020,04,29,CONFIRMADO,CHACO,4
2020,04,29,CONFIRMADO,CORDOBA,1
2020,04,29,CONFIRMADO,LARIOJA,1
2020,04,29,CONFIRMADO,MENDOZA,2
2020,04,29,CONFIRMADO,MISIONES,4
2020,04,29,CONFIRMADO,NEUQUEN,1
2020,04,29,CONFIRMADO,RIONEGRO,8
2020,04,29,MUERTE,PCIABSAS,2
2020,04,29,MUERTE,RIONEGRO,1
2020,04,29,MUERTE,CABA,3
2020,04,29,MUERTE,CHACO,1
2020,04,29,ALTA,CABA,30
```

# 2020 04 30

### Fuente

 * A la fecha, el total de altas es de 1256 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (64)

 ### CSV

```
2020,04,30,CONFIRMADO,PCIABSAS,66
2020,04,30,CONFIRMADO,CABA,45
2020,04,30,CONFIRMADO,CHACO,3
2020,04,30,CONFIRMADO,CORDOBA,2
2020,04,30,CONFIRMADO,CORRIENTES,1
2020,04,30,CONFIRMADO,MENDOZA,5
2020,04,30,CONFIRMADO,NEUQUEN,2
2020,04,30,CONFIRMADO,RIONEGRO,14
2020,04,30,CONFIRMADO,SANTACRUZ,1
2020,04,30,CONFIRMADO,TIERRADELFUEGO,2
2020,04,30,CONFIRMADO,TUCUMAN,2
2020,04,30,MUERTE,PCIABSAS,2
2020,04,30,MUERTE,CABA,2
2020,04,30,ALTA,CABA,64
```

# 2020 05 01

### Fuente

 * A la fecha, el total de altas es de 1292 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (36)

 ### CSV

```
2020,05,01,CONFIRMADO,PCIABSAS,34
2020,05,01,CONFIRMADO,CABA,29
2020,05,01,CONFIRMADO,CHACO,12
2020,05,01,CONFIRMADO,CHUBUT,1
2020,05,01,CONFIRMADO,CORDOBA,13
2020,05,01,CONFIRMADO,CORRIENTES,1
2020,05,01,CONFIRMADO,ENTRERIOS,2
2020,05,01,CONFIRMADO,LARIOJA,3
2020,05,01,CONFIRMADO,MENDOZA,1
2020,05,01,CONFIRMADO,RIONEGRO,8
2020,05,01,CONFIRMADO,TIERRADELFUEGO,1
2020,05,01,MUERTE,PCIABSAS,3
2020,05,01,MUERTE,CABA,4
2020,05,01,ALTA,CABA,36
```

# 2020 05 02

### Fuente

 * A la fecha, el total de altas es de 1320 personas.
 * FIXME: Altas Asignadas a CABA por falta de informacion. (28)

 ### CSV

```
2020,05,02,CONFIRMADO,PCIABSAS,45
2020,05,02,CONFIRMADO,CABA,58
2020,05,02,CONFIRMADO,CATAMARCA,0
2020,05,02,CONFIRMADO,CHACO,11
2020,05,02,CONFIRMADO,CHUBUT,1
2020,05,02,CONFIRMADO,CORDOBA,12
2020,05,02,CONFIRMADO,CORRIENTES,0
2020,05,02,CONFIRMADO,ENTRERIOS,0
2020,05,02,CONFIRMADO,FORMOSA,0
2020,05,02,CONFIRMADO,JUJUY,0
2020,05,02,CONFIRMADO,LAPAMPA,0
2020,05,02,CONFIRMADO,LARIOJA,0
2020,05,02,CONFIRMADO,MENDOZA,1
2020,05,02,CONFIRMADO,MISIONES,12
2020,05,02,CONFIRMADO,NEUQUEN,0
2020,05,02,CONFIRMADO,RIONEGRO,6
2020,05,02,CONFIRMADO,SALTA,0
2020,05,02,CONFIRMADO,SANJUAN,0
2020,05,02,CONFIRMADO,SANLUIS,0
2020,05,02,CONFIRMADO,SANTACRUZ,0
2020,05,02,CONFIRMADO,SANTAFE,0
2020,05,02,CONFIRMADO,SANTIAGODELESTERO,0
2020,05,02,CONFIRMADO,TIERRADELFUEGO,3
2020,05,02,CONFIRMADO,TUCUMAN,0
2020,05,02,MUERTE,CABA,6
2020,05,02,MUERTE,CHACO,3
2020,05,02,MUERTE,CORDOBA,1
2020,05,02,MUERTE,PCIABSAS,1
2020,05,02,ALTA,CABA,28
```

# 2020 05 03

### Fuente

 * A la fecha, el total de altas es de 1354 personas.
 *  FIXME: Altas Asignadas a CABA por falta de informacion. (34)

 ### CSV

```
2020,05,03,CONFIRMADO,PCIABSAS,38
2020,05,03,CONFIRMADO,CABA,49
2020,05,03,CONFIRMADO,CHACO,5
2020,05,03,CONFIRMADO,CORDOBA,1
2020,05,03,CONFIRMADO,ENTRERIOS,2
2020,05,03,CONFIRMADO,RIONEGRO,6
2020,05,03,CONFIRMADO,TIERRADELFUEGO,2
2020,05,03,MUERTE,CABA,2
2020,05,03,MUERTE,CORDOBA,2
2020,05,03,MUERTE,RIONEGRO,2
2020,05,03,MUERTE,PCIABSAS,3
2020,05,03,ALTA,CABA,34
```

# 2020 05 04

### Fuente

*  A la fecha, el total de altas es de 1442 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (88)

 ### CSV

```
2020,05,04,CONFIRMADO,PCIABSAS,38
2020,05,04,CONFIRMADO,CABA,43
2020,05,04,CONFIRMADO,CHACO,5
2020,05,04,CONFIRMADO,CORDOBA,6
2020,05,04,CONFIRMADO,LARIOJA,1
2020,05,04,CONFIRMADO,MISIONES,1
2020,05,04,CONFIRMADO,RIONEGRO,7
2020,05,04,CONFIRMADO,TUCUMAN,3
2020,05,04,MUERTE,CABA,4
2020,05,04,MUERTE,CORDOBA,2
2020,05,04,MUERTE,CHACO,1
2020,05,04,MUERTE,PCIABSAS,7
2020,05,04,ALTA,CABA,88
```

# 2020 05 05

### Fuente

*  A la fecha, el total de altas es de 1472 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (30)

### CSV

```
2020,05,05,CONFIRMADO,PCIABSAS,58
2020,05,05,CONFIRMADO,CABA,57
2020,05,05,CONFIRMADO,CHACO,11
2020,05,05,CONFIRMADO,CORDOBA,1
2020,05,05,CONFIRMADO,CORRIENTES,-1
2020,05,05,CONFIRMADO,ENTRERIOS,1
2020,05,05,CONFIRMADO,MENDOZA,1
2020,05,05,CONFIRMADO,RIONEGRO,4
2020,05,05,CONFIRMADO,SANTAFE,1
2020,05,05,MUERTE,CORDOBA,2
2020,05,05,MUERTE,CABA,1
2020,05,05,MUERTE,PCIABSAS,1
2020,05,05,ALTA,CABA,30
```

# 2020 05 06

### Fuente

*  A la fecha, el total de altas es de 1524 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (52)
*  Falta una muerte que no esta especificada

### CSV

```
2020,05,06,CONFIRMADO,PCIABSAS,63
2020,05,06,CONFIRMADO,CABA,102
2020,05,06,CONFIRMADO,CHACO,8
2020,05,06,CONFIRMADO,CORDOBA,5
2020,05,06,CONFIRMADO,CORRIENTES,3
2020,05,06,CONFIRMADO,LARIOJA,1
2020,05,06,CONFIRMADO,RIONEGRO,6
2020,05,06,MUERTE,RIONEGRO,1
2020,05,06,MUERTE,CABA,2
2020,05,06,MUERTE,PCIABSAS,5
2020,05,06,ALTA,CABA,52
```

# 2020 05 07

### Fuente

*  A la fecha, el total de altas es de 1601 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (77)

### CSV

```
2020,05,07,CONFIRMADO,PCIABSAS,50
2020,05,07,CONFIRMADO,CABA,77
2020,05,07,CONFIRMADO,CHACO,26
2020,05,07,CONFIRMADO,CORDOBA,4
2020,05,07,CONFIRMADO,CORRIENTES,1
2020,05,07,CONFIRMADO,LARIOJA,1
2020,05,07,CONFIRMADO,RIONEGRO,3
2020,05,07,CONFIRMADO,SANJUAN,1
2020,05,07,MUERTE,SANTAFE,1
2020,05,07,MUERTE,CABA,2
2020,05,07,MUERTE,PCIABSAS,6
2020,05,07,ALTA,CABA,77
```

# 2020 05 08

### Fuente

*  A la fecha, el total de altas es de 1659 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (58)

### CSV

```
2020,05,08,CONFIRMADO,PCIABSAS,77
2020,05,08,CONFIRMADO,CABA,130
2020,05,08,CONFIRMADO,CHACO,26
2020,05,08,CONFIRMADO,CORDOBA,2
2020,05,08,CONFIRMADO,CORRIENTES,1
2020,05,08,CONFIRMADO,LARIOJA,1
2020,05,08,CONFIRMADO,MENDOZA,1
2020,05,08,CONFIRMADO,RIONEGRO,2
2020,05,08,MUERTE,CABA,6
2020,05,08,MUERTE,PCIABSAS,5
2020,05,08,ALTA,CABA,58
```

# 2020 05 09

### Fuente

*  A la fecha, el total de altas es de 1728 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (69)

### CSV

```
2020,05,09,CONFIRMADO,PCIABSAS,60
2020,05,09,CONFIRMADO,CABA,83
2020,05,09,CONFIRMADO,CHACO,9
2020,05,09,CONFIRMADO,CORDOBA,6
2020,05,09,CONFIRMADO,CORRIENTES,1
2020,05,09,CONFIRMADO,NEUQUEN,1
2020,05,09,CONFIRMADO,RIONEGRO,4
2020,05,09,CONFIRMADO,TIERRADELFUEGO,1
2020,05,09,MUERTE,LARIOJA,1
2020,05,09,MUERTE,CABA,2
2020,05,09,MUERTE,PCIABSAS,4
2020,05,09,ALTA,CABA,69
```

# 2020 05 10

### Fuente

*  A la fecha, el total de altas es de 1757 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (29)

### CSV

```
2020,05,10,CONFIRMADO,PCIABSAS,51
2020,05,10,CONFIRMADO,CABA,165
2020,05,10,CONFIRMADO,CHACO,32
2020,05,10,CONFIRMADO,CORDOBA,5
2020,05,10,CONFIRMADO,RIONEGRO,2
2020,05,10,CONFIRMADO,SANTIAGODELESTERO,1
2020,05,10,CONFIRMADO,TIERRADELFUEGO,2
2020,05,10,MUERTE,CABA,2
2020,05,10,MUERTE,PCIABSAS,3
2020,05,10,ALTA,CABA,29
```

# 2020 05 11

### Fuente

*  A la fecha, el total de altas es de 1837 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (80)

### CSV

```
2020,05,11,CONFIRMADO,PCIABSAS,44
2020,05,11,CONFIRMADO,CABA,137
2020,05,11,CONFIRMADO,CHACO,17
2020,05,11,CONFIRMADO,CORDOBA,14
2020,05,11,CONFIRMADO,CORRIENTES,16
2020,05,11,CONFIRMADO,LARIOJA,1
2020,05,11,CONFIRMADO,MISIONES,1
2020,05,11,CONFIRMADO,RIONEGRO,13
2020,05,11,CONFIRMADO,TUCUMAN,1
2020,05,11,MUERTE,CABA,3
2020,05,11,MUERTE,CHACO,1
2020,05,11,MUERTE,RIONEGRO,1
2020,05,11,MUERTE,PCIABSAS,4
2020,05,11,ALTA,CABA,80
```

# 2020 05 12

### Fuente

*  A la fecha, el total de altas es de 1862 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (25)

### CSV

```
2020,05,12,CONFIRMADO,PCIABSAS,80
2020,05,12,CONFIRMADO,CABA,188
2020,05,12,CONFIRMADO,CHACO,10
2020,05,12,CONFIRMADO,CORDOBA,3
2020,05,12,CONFIRMADO,CORRIENTES,1
2020,05,12,CONFIRMADO,MENDOZA,1
2020,05,12,CONFIRMADO,RIONEGRO,1
2020,05,12,CONFIRMADO,SALTA,1
2020,05,12,MUERTE,CABA,1
2020,05,12,MUERTE,CHACO,1
2020,05,12,MUERTE,CORDOBA,1
2020,05,12,MUERTE,PCIABSAS,2
2020,05,12,ALTA,CABA,25
```

# 2020 05 13

### Fuente

*  A la fecha, el total de altas es de 2266 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (404)

### CSV

```
2020,05,13,CONFIRMADO,PCIABSAS,96
2020,05,13,CONFIRMADO,CABA,178
2020,05,13,CONFIRMADO,CHACO,18
2020,05,13,CONFIRMADO,CORDOBA,11
2020,05,13,CONFIRMADO,CORRIENTES,5
2020,05,13,CONFIRMADO,ENTRERIOS,1
2020,05,13,CONFIRMADO,MENDOZA,1
2020,05,13,CONFIRMADO,NEUQUEN,2
2020,05,13,CONFIRMADO,RIONEGRO,4
2020,05,13,MUERTE,CABA,5
2020,05,13,MUERTE,CHACO,1
2020,05,13,MUERTE,PCIABSAS,4
2020,05,13,ALTA,CABA,404
```

# 2020 05 14

### Fuente

*  A la fecha, el total de altas es de 2385 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (119)

### CSV

```
2020,05,14,CONFIRMADO,PCIABSAS,79
2020,05,14,CONFIRMADO,CABA,153
2020,05,14,CONFIRMADO,CHACO,9
2020,05,14,CONFIRMADO,CORDOBA,5
2020,05,14,CONFIRMADO,CORRIENTES,3
2020,05,14,CONFIRMADO,ENTRERIOS,1
2020,05,14,CONFIRMADO,NEUQUEN,1
2020,05,14,CONFIRMADO,RIONEGRO,4
2020,05,14,MUERTE,CABA,10
2020,05,14,MUERTE,CHACO,1
2020,05,14,MUERTE,CORDOBA,1
2020,05,14,MUERTE,RIONEGRO,1
2020,05,14,MUERTE,PCIABSAS,11
2020,05,14,ALTA,CABA,119
```

# 2020 05 15

### Fuente

*  A la fecha, el total de altas es de 2497 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (112)

### CSV

```
2020,05,15,CONFIRMADO,PCIABSAS,86
2020,05,15,CONFIRMADO,CABA,214
2020,05,15,CONFIRMADO,CHACO,25
2020,05,15,CONFIRMADO,CORDOBA,3
2020,05,15,CONFIRMADO,RIONEGRO,17
2020,05,15,MUERTE,CHACO,1
2020,05,15,MUERTE,PCIABSAS,2
2020,05,15,ALTA,CABA,112
```

# 2020 05 16

### Fuente

*  A la fecha, el total de altas es de 2534 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (37)

### CSV

```
2020,05,16,CONFIRMADO,PCIABSAS,97
2020,05,16,CONFIRMADO,CABA,193
2020,05,16,CONFIRMADO,CHACO,21
2020,05,16,CONFIRMADO,CORDOBA,9
2020,05,16,CONFIRMADO,RIONEGRO,6
2020,05,16,CONFIRMADO,SANTAFE,1
2020,05,16,MUERTE,CABA,4
2020,05,16,MUERTE,CHACO,1
2020,05,16,MUERTE,PCIABSAS,2
2020,05,16,ALTA,CABA,37
```

# 2020 05 17

### Fuente

*  A la fecha, el total de altas es de 2569 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (35)

### CSV

```
2020,05,17,CONFIRMADO,PCIABSAS,74
2020,05,17,CONFIRMADO,CABA,147
2020,05,17,CONFIRMADO,CHACO,19
2020,05,17,CONFIRMADO,CORDOBA,20
2020,05,17,CONFIRMADO,LARIOJA,1
2020,05,17,CONFIRMADO,RIONEGRO,2
2020,05,17,MUERTE,CABA,2
2020,05,17,MUERTE,RIONEGRO,1
2020,05,17,MUERTE,CORDOBA,2
2020,05,17,MUERTE,CHACO,2
2020,05,17,MUERTE,PCIABSAS,3
2020,05,17,ALTA,CABA,35
```

# 2020 05 18

### Fuente

*  A la fecha, el total de altas es de 2625 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (56)

### CSV

```
2020,05,18,CONFIRMADO,PCIABSAS,93
2020,05,18,CONFIRMADO,CABA,169
2020,05,18,CONFIRMADO,CHACO,13
2020,05,18,CONFIRMADO,CORDOBA,20
2020,05,18,CONFIRMADO,CORRIENTES,-1
2020,05,18,CONFIRMADO,LARIOJA,2
2020,05,18,CONFIRMADO,RIONEGRO,2
2020,05,18,CONFIRMADO,SANJUAN,1
2020,05,18,CONFIRMADO,SANTAFE,4
2020,05,18,MUERTE,CABA,5
2020,05,18,MUERTE,CHACO,2
2020,05,18,MUERTE,PCIABSAS,2
2020,05,18,ALTA,CABA,56
```

# 2020 05 19

### Fuente

*  A la fecha, el total de altas es de 2872 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (247)

### CSV

```
2020,05,19,CONFIRMADO,PCIABSAS,157
2020,05,19,CONFIRMADO,CABA,224
2020,05,19,CONFIRMADO,CHACO,34
2020,05,19,CONFIRMADO,CORDOBA,9
2020,05,19,CONFIRMADO,MENDOZA,2
2020,05,19,CONFIRMADO,RIONEGRO,6
2020,05,19,CONFIRMADO,SANTIAGODELESTERO,6
2020,05,19,MUERTE,CHACO,4
2020,05,19,MUERTE,CABA,5
2020,05,19,MUERTE,PCIABSAS,2
2020,05,19,ALTA,CABA,247
```

# 2020 05 20

### Fuente

*  A la fecha, el total de altas es de 2933 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (61)

### CSV

```
2020,05,20,CONFIRMADO,PCIABSAS,178
2020,05,20,CONFIRMADO,CABA,257
2020,05,20,CONFIRMADO,CHACO,35
2020,05,20,CONFIRMADO,CORDOBA,2
2020,05,20,CONFIRMADO,RIONEGRO,2
2020,05,20,MUERTE,CHACO,1
2020,05,20,MUERTE,CABA,2
2020,05,20,MUERTE,CORDOBA,1
2020,05,20,MUERTE,RIONEGRO,1
2020,05,20,MUERTE,PCIABSAS,4
2020,05,20,ALTA,CABA,61
```

# 2020 05 21

### Fuente

*  A la fecha, el total de altas es de 3032 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (99)

### CSV

```
2020,05,21,CONFIRMADO,PCIABSAS,213
2020,05,21,CONFIRMADO,CABA,379
2020,05,21,CONFIRMADO,CHACO,34
2020,05,21,CONFIRMADO,CORDOBA,12
2020,05,21,CONFIRMADO,MENDOZA,1
2020,05,21,CONFIRMADO,RIONEGRO,3
2020,05,21,CONFIRMADO,SANTAFE,5
2020,05,21,CONFIRMADO,TUCUMAN,1
2020,05,21,MUERTE,CHACO,2
2020,05,21,MUERTE,CABA,2
2020,05,21,MUERTE,PCIABSAS,9
2020,05,21,ALTA,CABA,99
```

# 2020 05 22

### Fuente

*  A la fecha, el total de altas es de 3062 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (30)

### CSV

```
2020,05,22,CONFIRMADO,PCIABSAS,266
2020,05,22,CONFIRMADO,CABA,404
2020,05,22,CONFIRMADO,CHACO,27
2020,05,22,CONFIRMADO,CORDOBA,9
2020,05,22,CONFIRMADO,RIONEGRO,6
2020,05,22,CONFIRMADO,SALTA,2
2020,05,22,CONFIRMADO,SANTAFE,4
2020,05,22,MUERTE,CABA,7
2020,05,22,MUERTE,CORDOBA,1
2020,05,22,MUERTE,RIONEGRO,2
2020,05,22,MUERTE,CHACO,2
2020,05,22,MUERTE,PCIABSAS,5
2020,05,22,ALTA,CABA,30
```

# 2020 05 23

### Fuente

*  A la fecha, el total de altas es de 3530 personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (468)

### CSV

```
2020,05,23,CONFIRMADO,PCIABSAS,289
2020,05,23,CONFIRMADO,CABA,400
2020,05,23,CONFIRMADO,CHACO,7
2020,05,23,CONFIRMADO,RIONEGRO,5
2020,05,23,CONFIRMADO,TUCUMAN,3
2020,05,23,MUERTE,CABA,6
2020,05,23,MUERTE,CHACO,2
2020,05,23,MUERTE,PCIABSAS,4
2020,05,23,ALTA,CABA,468
```

# 2020 05 24

### Fuente

*  A la fecha, el total de altas es de xxxx personas.
*  FIXME: Altas Asignadas a CABA por falta de informacion. (xx)

### CSV

#```
#2020,05,24,CONFIRMADO,PCIABSAS,266
#2020,05,24,CONFIRMADO,CABA,404
#2020,05,24,CONFIRMADO,CATAMARCA,0
#2020,05,24,CONFIRMADO,CHACO,27
#2020,05,24,CONFIRMADO,CHUBUT,0
#2020,05,24,CONFIRMADO,CORDOBA,9
#2020,05,24,CONFIRMADO,CORRIENTES,0
#2020,05,24,CONFIRMADO,ENTRERIOS,0
#2020,05,24,CONFIRMADO,FORMOSA,0
#2020,05,24,CONFIRMADO,JUJUY,0
#2020,05,24,CONFIRMADO,LAPAMPA,0
#2020,05,24,CONFIRMADO,LARIOJA,0
#2020,05,24,CONFIRMADO,MENDOZA,0
#2020,05,24,CONFIRMADO,MISIONES,0
#2020,05,24,CONFIRMADO,NEUQUEN,0
#2020,05,24,CONFIRMADO,RIONEGRO,6
#2020,05,24,CONFIRMADO,SALTA,2
#2020,05,24,CONFIRMADO,SANJUAN,0
#2020,05,24,CONFIRMADO,SANLUIS,0
#2020,05,24,CONFIRMADO,SANTACRUZ,0
#2020,05,24,CONFIRMADO,SANTAFE,4
#2020,05,24,CONFIRMADO,SANTIAGODELESTERO,0
#2020,05,24,CONFIRMADO,TIERRADELFUEGO,0
#2020,05,24,CONFIRMADO,TUCUMAN,0
#2020,05,24,MUERTE,CABA,7
#2020,05,24,ALTA,CABA,30
#```