### Proyecto Individual 2: 
## Accidentes de Tránsito de la Ciudad Autónoma de Buenos Aires, Argentina, 2016-2021. 

### Amelia Herrera Briceño - melinnicri@gmail.com 
### Junio, 2024
 

<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Accidentes.jpg"></p>


## Trabajo rol de Data analyst acerca de los accidentes de tránsito ocurridos entre los años 2016 - 2021, de la Ciudad Autónoma de Buenos Aires, Argentina. 

Los accidentes de tránsito son una de las principales causas de muerte y lesiones en la ciudad. Según el gobierno porteño, los factores que contribuyen a los accidentes son el incumplimiento de la ley de tránsito, el exceso de velocidad, el no respetar las señales de tránsito, el no usar cinturón de seguridad o apoya cabezas y el conducir con cansancio. Además, los medios de transporte más involucrados en los accidentes son las motos, seguidas por los autos y los colectivos. Los accidentes de tránsito generan un alto costo social y económico, así como un impacto negativo en la calidad de vida de las personas.

Se entregan bases de datos con información acerca de los homicidios y víctimas (data desde páginas oficiales argentinas). 
Se realiza un ETL y EDA, respectivamente, utilizando Studio Visual Code notebook, librerías Panda, Numpy, Matplotlib, y su presentación final en PowerBI.

## KPIs solicitadas: 

1) Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior (semestre año 2021-2020). 

Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100.000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100.000. 

2) Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior (año 2021-2020). 

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100.
 
3) Teniendo en cuenta los dos KPIs existentes, que se enfocan en la reducción de la tasa de homicidios en siniestros viales y la cantidad de accidentes mortales de motociclistas, se propone un tercer KPI que complemente estos esfuerzos y abarque una perspectiva más amplia de la seguridad vial en CABA:

Reducir en un 10% la tasa de lesiones graves (que no fallecen) por siniestros viales en CABA, en comparación con el año anterior (año 2020 – 2021).

Definición: La tasa de lesiones graves por siniestros viales se define como el número de personas que sufren lesiones graves en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico.

Fórmula: (Número de lesiones graves en siniestros viales / Población total) * 100,000

## Explicación:

Las lesiones graves se consideran aquellas que ponen en riesgo la vida o generan una discapacidad permanente.
Incluir este KPI permite abordar la seguridad vial desde una perspectiva más integral, ya que no solo se centra en las víctimas fatales, sino también en aquellas que sufren consecuencias graves y duraderas a causa de los siniestros.
Al reducir la tasa de lesiones graves, se contribuye a disminuir la carga sobre el sistema de salud y mejorar la calidad de vida de las personas afectadas.

## Consideraciones:
El valor de X (porcentaje de reducción) debe establecerse en función de un análisis previo de los datos históricos y considerando metas realistas y alcanzables.
Es importante recopilar datos precisos y confiables sobre las lesiones graves en siniestros viales, lo que puede requerir la colaboración de diversas entidades, como hospitales, centros de salud y organismos gubernamentales.

Al igual que los otros dos KPIs, este indicador debe ser monitoreado y evaluado periódicamente para medir su impacto y realizar los ajustes necesarios en las estrategias de seguridad vial.

## Beneficios de incluir este tercer KPI:
Permite tener una visión más completa de la situación de la seguridad vial en CABA.
Ayuda a identificar áreas donde se pueden tomar medidas para reducir la gravedad de los siniestros viales.
Sensibiliza a la población sobre la importancia de la seguridad vial y las consecuencias de los accidentes de tránsito.
Contribuye a mejorar la calidad de vida de las personas afectadas por los siniestros viales.

## En conjunto, estos tres KPIs:
Proporcionan una base sólida para evaluar la efectividad de las políticas y programas de seguridad vial en CABA.
Permiten enfocar los esfuerzos en diferentes aspectos de la seguridad vial, desde la prevención de muertes hasta la reducción de las lesiones graves.
Contribuyen a crear un entorno vial más seguro para todos los usuarios, incluyendo conductores, motociclistas, ciclistas y peatones.

*Las 15 comunas de Ciudad Autónoma de Buenos Aires: 
- COMUNA 1: Retiro, San Nicolás, Puerto Madero, San Telmo, Montserrat y Constitución. 
- COMUNA 2: Recoleta. 
- COMUNA 3: Balvanera y San Cristóbal. 
- COMUNA 4: La Boca, Barracas, Parque Patricios y Nueva Pompeya. 
- COMUNA 5: Almagro y Boedo. 
- COMUNA 6: Caballito. 
- COMUNA 7: Flores y Parque Chacabuco. 
- COMUNA 8: Villa Soldati, Villa Riachuelo y Villa Lugano. 
- COMUNA 9: Liniers, Mataderos y Parque Avellaneda. 
- COMUNA 10: Villa Real, Monte Castro, Versalles, Floresta, Vélez Sarsfield y Villa Luro. 
- COMUNA 11: Villa General Mitre, Villa Devoto, Villa del Parque y Villa Santa Rita. 
- COMUNA 12: Coghlan, Saavedra, Villa Urquiza y Villa Pueyrredón. 
- COMUNA 13: Núñez, Belgrano y Colegiales. 
- COMUNA 14: Palermo. 
- COMUNA 15: Chacarita, Villa Crespo, La Paternal, Villa Ortúzar, Agronomía y Parque Chas.


## Archivos: 

BaseDatos (Diccionario de datos Siniestros, homicidios, lesiones, PobCABA);   ["Notebook Accidentes"](https://github.com/melinnicri/Accidentes_transito/blob/main/Accidentes.ipynb)
EDA (dfs de homicidios, lesiones, EDA.ipynb, espec_homicidios, espec_lesion);
Gráficos en images (gráficos de Lesiones, Fallecidos);
KPIs (las distintas dfs para confeccionar las KPIs);
OtraData (OtraData.ipynb, data de homicidios y lesiones en específico);
Panel (en png);
Readme;
“accidentesPBI.pbix”;
“homicidios.ipynb”;
“lesionados.ipynb”.


## Panel:

## Gráficos extras:


 
<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Evol_fallec_agno.png"></p>   
* Aquí muestra los lesionados que fallecen ya que fueron de gravedad.

* Se aplicó una prueba de Normalidad:
- Total de fallecidos por año:
- Estadística de prueba: Agno_fallec    0.986769
- Name: W, dtype: float64
- Valor p: Agno_fallec    0.422251
- Name: pval, dtype: float64

- Hipótesis nula (𝐻0): Los datos siguen una distribución normal (pval>0.05) 

- Resultado:
- Estadística de prueba (W):
- La estadística de prueba (W) es un valor calculado por la prueba de normalidad. En este caso, el valor de W es aproximadamente 0.9868 para la columna “Agno_fallec” (año fallecido).
- Esta estadística se utiliza para evaluar si los datos siguen una distribución normal. Cuanto más cercano esté W a 1, más se asemejarán los datos a una distribución normal. Y pval = 0,42.
- En otras palabras, los datos podrían seguir una distribución normal.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Fallec_agno.png"></p>
* Estos son víctimas fatales por accidentes de tránsito por año.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Fallec_edad.png"></p>
* Aunque no se pueden ver los números, la edad donde más frecuenta fallecidos son 20-30 años a lo largo de los años.

 
<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Fall_sex_agno.png"></p>
* También a lo largo de los años, los fallecidos concentrados son de sexo masculino.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/motos_agnos.png"></p>
* La moto, al ser un poco más accesible que un auto, concentra la mayor cantidad de accidentes de tránsito mortales.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Vict_tipo_calle.png"></p>   
* Avenida es el tipo de calle que más se repite en los accidentes mortales de tránsito.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Lesion_agno.png"></p>
* En cuanto a los lesionados por año son muchos más que las víctimas fatales, pero no menos importantes por la inhabilidad que pueden provocar y los costos de salud asociados.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Lesio_sex_agno.png"></p>
* Los lesionados nuevamente son mayoría masculinos a través de los años.


<p align="center"><img src="https://github.com/melinnicri/AccidTransitoCABA/blob/main/images/Lesion_eda_agno.png"></p>
* Los lesionados a través de los años 2020 y 2021, mayoritariamente se encuentran en el rango 20-30 años (“el riesgo de la juventud”).


## Conclusiones: 

De acuerdo con los resultados obtenidos en PowerBI, podemos concluir que: 

-	Entre los años 2016 y 2021, en CABA, los accidentes de tránsito tendieron a disminuir, en parte por la pandemia (restricción movilización) y nuevamente aumentaron saliendo de este encierro.

-	Es llamativo que en las mañanas hubiese más accidentes (6-7 horas), se suponen “descansados”.

-	La tasa de mortalidad promedio por cada 100.000 habitantes entre los años 2016 y 2021 es de 1,95 (696 víctimas fallecidas en total).

-	Los meses de Noviembre y Diciembre, concentra la mayor cantidad de Víctimas fatales.

-	Las comunas que más tienen víctimas lesionadas graves son la 1 (Retiro, San Nicolás, Puerto Madero, San Telmo, Montserrat y Constitución), la 4 (La Boca, Barracas, Parque Patricios y Nueva Pompeya), la 12 (Coghlan, Saavedra, Villa Urquiza y Villa Pueyrredón). 

-	El modo de transporte de los lesionados graves son dato desconocido, moto, bicicleta; mientras que las víctimas fatales fueron moto y siendo peatones.

-	Las edades entre víctimas fatales y lesionados en general (los que son más) rondan entre los 20-30 años, y el sexo es la mitad femenino.


## Los índices KPIs:
 
1)	Hay una reducción más allá del 10% de la tasa de mortalidad en el primer semestre del 2020 (-30,52%) y segundo semestre del 2021 (-26,79%); entremedio, no ocurrió.

2)	En cuanto a la reducción de la Tasa de mortalidad por moto, hubo una disminución del 13,79% de un año a otro (2020-2021), por lo que se logra reducir en más del 7%.

3)	En cuanto a la reducción de la Tasa de morbilidad por accidentes de tránsito con lesiones graves, no se redujo, se duplicó inclusive (2021).


## Recomendaciones:
- Mientras más tránsito vehicular, más accidentes, por lo que tomar las medidas de precaución, como respetar las señales de tránsito, transitar a una velocidad prudente, mantener el cinturón de seguridad como el uso de cascos y ropa apropiada para motos (cuero antidesforramiento), cruzar en zona habilitada, descansar lo necesario para conducir vehículos, no beber alcohol, ni consumir drogas psicotrópicas que afecten la conducción, por lo que se recomienda:

•	Respetar las señales de tránsito: Las señales de tránsito están diseñadas para mantener el orden en las carreteras y garantizar la seguridad de los conductores y peatones. Es importante respetar estas señales para evitar accidentes.
•	Mantener el vehículo en buen estado: es importante realizar un mantenimiento preventivo cada cierto tiempo.
•	Transitar a una velocidad prudente: Conducir a una velocidad adecuada es fundamental para evitar accidentes. La velocidad debe ser ajustada a las condiciones del tráfico y del clima.
•	Mantener el cinturón de seguridad como el uso de cascos y ropa apropiada para motos (cuero antidesforramiento): El uso del cinturón de seguridad y de cascos es obligatorio en muchos países. Estos elementos de seguridad pueden salvar vidas en caso de accidentes. Además, es importante usar ropa adecuada para motos, como cuero antidesforramiento, para protegerse en caso de caídas, y reflectantes.
•	Cruzar en zona habilitada: Los peatones deben cruzar la calle en las zonas habilitadas para ello. Cruzar la calle en lugares no autorizados puede ser peligroso y aumentar el riesgo de accidentes.
•	Descansar lo necesario para conducir vehículos: Conducir cansado o con sueño puede ser peligroso. Es importante descansar lo suficiente antes de conducir para evitar accidentes.
•	No beber alcohol, ni consumir drogas psicotrópicas que afecten la conducción: El alcohol y las drogas psicotrópicas pueden afectar la capacidad de conducción y aumentar el riesgo de accidentes. Es importante evitar su consumo antes de conducir.
### FIN…_@v

