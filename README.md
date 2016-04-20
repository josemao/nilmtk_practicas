# Prácticas NILM

Non-Intrusive Load Monitoring (NILM) es una colección de técnicas y algoritmos de machine learning orientados a desagregar el consumo total de una casa en consumos individuales de electrodomésticos. 

##1 - Python científico 

Aquí explicaremos algunos de los conceptos básicos para el uso de las librerías necesarias de NILM. 


**numpy**: operaciones matemáticas de arrays y matrices 


**matploblib**: para gráficas 


**pandas**: herramienta de análisis de datos a gran escala de manera eficiente

##2 - Introducción a NILMTK

NILMTK es una herramienta de análisis de datasets de NILM. Contiene funciones específicas para el análisis detallado y rápido del consumo eléctrico. Además, sirve de plataforma para los investigadores de NILM para comparar sus algoritmos con métricas estándar sobre varios datasets. 

Aprenderemos los conceptos básicos. Para más información, consultar la documentación en: 
https://github.com/nilmtk/nilmtk

Los datasets que utilizaremos son: 

**REDD**: monitorización del consumo energético de 6 casas diferentes en Estados Unidos: 2 casas a alta frequencia (12KHz de corriente y voltage) y 4 casas a baja frequencia (10 segundos por muestra de la potencia activa)
http://redd.csail.mit.edu/

**UK-DALE** Monitorización de una casa en Inglaterra durante 2 años a alta frequencia y baja frequencia: 16KHz de corriente y voltage y 1 segundo de potencia activa, reactiva y aparente. 
http://www.doc.ic.ac.uk/~dk3810/data/


**IAWE** Monitorización de una en India durante 73 días a 1 segundo. Parámetros: potencias activa, reactiva y aparente, voltage, corriente y factor de potencia. 
http://iawe.github.io/

##3 - Previo a la desagregación: gráficas y estadísticas. 

Antes de realizar la desagregación, podemos analizar el consumo general desde el smart meter para obtener información interesante sobre la actividad en la vivienda. Asímismo, si se tiene información sobre el consumo individual de algunos dispositivos (groundtruth) mediante la instalación de smart-plugs, podemos obtener los patrones de consumo de distintos dispositivos que nos ayude a mejorar nuestro algoritmo. 

##4 - Desagregación: Métodos supervisados y no supervisados. 
 Estudiaremos aquí dos métodos no supervisados de desagregación: cadenas factoriales de Markov (FHMM) y optimización combinatoria (CO); comparándolos mediante el uso del mismo dataset y de las mismas métricas. 
 Se propondrá la realización de un método supervisado de desagregación de un dispositivo. 



#####Nota: 
- Máquina virtual Linux: usr(nilm) y pwd(nilm)
