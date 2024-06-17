# PROYECTO ANALISIS DE DATOS | BANK CALL CENTER | POWER BI | HENRY 



## INTRODUCCIÓN
Un call center es un centro de atención telefónica que se encarga de interactuar con clientes actuales y potenciales, ofreciendo atención de calidad y generando experiencias positivas del cliente.

El baco anónimo que se maneja, pretende mejorar la eficiencia y calidad en el servicio mediante el analisis de los datos que contiene, para ello solicita propuestas de mejora mediante el estudio, tratado y proyección de los mismos, con la finalidad de tomar de decisiones apegada a los resultados.

## OBJETIVOS PERSEGUIDOS
Los objetivos perseguidos en el proyecto son: 
Analizar las operaciones de un Call Center de un Banco, para proponer mejoras en:
* Eficiencia operativa, proponiendo mejoras operativas.
* Mejorar la satisfacción del cliente, cumpliendo los SLA comprometidos.
* Brindar una herramienta para la gestión y la toma de decisiones a los managers del Call Center.

### Preguntas 
* ¿Cuál es el nivel de servicio para los clientes Prioritarios? 
* ¿Damos un mejor servicio que a los clientes normales?
* ¿Qué volumen de llamadas atendemos? 
* ¿Cuáles son los cuellos de botella? ¿En qué días? ¿En qué bandas horarias?
* ¿Cómo es la eficiencia y productividad de nuestros agentes?
* ¿Hay clientes recurrentes en el uso del servicio?
* ¿Cuáles son los tipos de servicio más recurrentes?
* ¿Podemos estimar la dotación necesaria para cumplir con una calidad de servicio determinada?  Ejemplo: si quiero que mi tiempo promedio de espera sea menor a 60 segundos?


## PROPUESTA
Para satisfacer los requerimientos solicitados, se propone la construcción un dashboard que contiene la información relevate de la situación actual en que se encuentra el banco. Este panel debe permitir medir los niveles de calidad de servicio, eficiencia y productividad del Call Center.
Para ello, se propone que definamos los KPIs adecuados para poder medir los objetivos propuestos, y definir nuevos niveles objetivos.
A continuación, encontrarás un análisis exahustivo de datos contenidos en un data set dentro de un archivo csv. En el proceso se llevarón a cabo los siguientes pasos:

1. Importación y analisis de datos en power query con el empleo de EDA, para prepararlos, asimismo se construyerón nuevas columnas requeridas para mostrar información de forma clara.
2. Selección de las visualizaciones a emplear acorde a lo que se quiere comunicar.
3. Calculo de los KPI´s con ayuda de lenguaje DAX 
4. Diseño del panel dahsboard.
5. Cración de las segmentaciones y filtros de datos.


</br >


# RESULTADOS:
![Dashboard](/ScreenShots/12.png)

## 🔎 ¿Qué información proporciona el dashboard?
![Resumen ejecutivo](/ScreenShots/01.png)

1. Cantidad de llamadas: Muestra el número total de llamadas entrantes en un período determinado.
2. Total de llamadas en horas: Tiempo total empleado para llamadas efectivamente atendidas por los agentes.
3. Duración promedio de llamadas: Indica el promedio de duración de las llamadas.
4. Máximo tiempo de espera: Dato que muestra el tiempo que esperó un cliente para ser atendido, aquí se puede observar que existe un problema, puesto que el tiempo máximo en espera es demasiado, pudiendo tratarse de datos outlier.
5. Tota llamadas ignoradas: Llamadas que fueron contestadas pero que por alguna razón fueron ignoradas.
6. Llamadas perdidas: Cantidad de llamadas en las que los clientes colgaron antes de ser atendidos.


## 🔎 ¿cómo se divide la cantidad total de llamadas?
![Resultado de llamadas](/ScreenShots/02.png)

346,742 llamadas fueron atendidas correctamente, sin embargo 87,706 no fueron atendidas


## 🔎 ¿cómo es el nivel de servicio en las llamadas?
![Resultado de llamadas](/ScreenShots/03.png)

Este gráfico fue estimado mediante las llamadas pérdidas e ignoradas


## 🔎 ¿cuáles fueron los servicios más realizados en las llamadas?
![Resultado de llamadas](/ScreenShots/04.png)

El servicio mayormente ofertado en las llamadas fue por actividad regular con 52,758 llamadas
El menos utilizado, fue petición para devolver llamada con 6 llamadas
También se observan datos atípicos con la etiqueta AA, con 5 llamadas


## 🔎 ¿Cómo se distribuyen las llamadas a lo largo del año estudiado?

![Resultado de llamadas](/ScreenShots/07.png)

Se observa que en el mes de diciembre existe una mayor atención con 43,065, seguido de agosto con 42,078 llamadas
En contraste septiembre presenta 31,371 llamadas y le acontece enero  con 31,599


## 🔎 ¿Cómo se distribuyen las llamadas en una semana?
![Resultado de llamadas](/ScreenShots/13.png)
Se observa que los días viernes y sábado se tienen menor cantidad de llamadas, mientras que los demás tienen un conteo muy similar



## 🔎 ¿Cómo se distribuyen las llamadas a lo largo del día?
![Resultado de llamadas](/ScreenShots/08.png)
La hora de mayor tráfico de llamadas sucede 10 am, con un conteo de 40,534
El mayor tráfico sucede entre las 8 am y las 16 horas
Observar con detalle los horarios con cuellos e botella, donde no se presenta gran cantidad de llamadas de 11 pm a 6 am

## 🔎 Filtros y Segmentaciones de datos:
![Resultado de llamadas](/ScreenShots/10.png)
![Resultado de llamadas](/ScreenShots/11.png)
Para un mejor análisis, se incluyen dentro del panel, filtros y segmentaciones de datos
Filtro por Agentes: Estudio de cada agente que atiende a clientes
Filtro por periodos de tiempo: Análisis por periodos de tiempo
Filtro por tipos de clientes: Según los don tipos de clientes existentes



# PROPUESTAS PARA MEJORAR LA EFICIENCIA OPERATIVA
* Reducir la duración promedio de llamadas en un 30 %, es decir de 1:01:10 min a 42:00 min
* Mejorar el nivel del servicio al 85% 
* Reducir el porcentaje de llamadas de 19.73% a un 15%
* Incentivar a la Agente Sharon que tuvo el mayor número de llamadas 27,492 con un 100% de llamadas atendidas y un nivel de servicio del 100%
* Reducir de un 14.21% en llamadas no atendidas a un 10% en la prioridad alta clientes
* Monitorear los VRU (contestadores automáticos) y evaluar su rendimiento
* Seguir un protocolo cuando se conteste una llamada


Nota: Los datos aquí mostrados, son ficticios, todo el procesamiento se llevo a cabo con fines educativos.

# ¡GRACIAS!


Juan Diego Hernández Camacho
