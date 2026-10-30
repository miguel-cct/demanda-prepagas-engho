# Análisis de Demanda: Sector de Salud Privado en Argentina 🏥📊

Este repositorio contiene un cuaderno de Jupyter estructurado para analizar la demanda dentro del sector de salud privado en Argentina. El estudio se enfoca en la elección discreta entre dos regímenes: la afiliación a prepaga vía derivación de obra social y la contratación de prepaga voluntaria directa.

El código desarrolla un *pipeline* completo de análisis microeconómico utilizando los microdatos de la **Encuesta Nacional de Gastos de los Hogares (ENGHo) 2017-2018** elaborada por el INDEC.

## 🚀 Características del Proyecto

* **Procesamiento de Datos:** Depuración del universo de análisis (adultos mayores de 18 años) y construcción de variables dependientes jerárquicas junto con regresores sociodemográficos, laborales y de capital humano.
* **Inferencia Estadística Rigurosa:** Implementación de las 200 réplicas *bootstrap* proporcionadas por el INDEC para calcular errores estándar e intervalos de confianza ajustados al diseño muestral complejo.
* **Estadística Descriptiva:** Generación de cuadros comparativos de mercado (distribución poblacional, niveles de ingresos, tramos de edad e inserción laboral).
* **Visualizaciones Académicas:** Funciones matriciales para renderizar gráficos de barras apiladas (ej. composición de la cobertura según quintil de ingreso), configurados para exportación en trabajos de investigación.
* **Modelado Econométrico:** Estructuración final de los datos lista para la estimación de modelos **Logit** y **Logit Multinomial**.

## 🛠️ Herramientas y Tecnologías

* **Lenguaje:** Python 3
* **Librerías principales:** `pandas`, `numpy`
* **Entorno:** Jupyter Notebook
* **Metodología:** Regresión Logística

* ## 📊 Links a las bases de datos
* **Base de hogares:** https://www.indec.gob.ar/ftp/cuadros/menusuperior/engho/engho2018_hogares.zip
* **Base de personas:** https://www.indec.gob.ar/ftp/cuadros/menusuperior/engho/engho2018_personas.zip
* **Basse réplicas:** https://www.indec.gob.ar/ftp/cuadros/menusuperior/engho/engho2018_replicas.zip
    
