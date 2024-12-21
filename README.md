# Acerca de mí

Economista enfocada en análisis de datos con sólida experiencia en extracción, limpieza y modelado de datos estratégicos. 

Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, logrando ahorros significativos de tiempo mediante la automatización.

### Habilidades tecnológicas
- Análisis y gestión de datos utilizando **Excel / SQL / Python / R**
- Visualización de datos y narración de historias usando **Power Bi**

### Habilidades blandas
Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/marielalegoma/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leydi-conzuelo-chipana-cangana)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chipana.l@pucp.edu.pe)


* * *

# Proyectos seleccionados

## Análisis de patrones en el Padrón RUC
En un contexto económico en constante cambio, el análisis de datos administrativos como el Padrón RUC resulta clave para comprender el **comportamiento** y las **características** de los contribuyentes. Este padrón, administrado por la **SUNAT**, contiene información detallada sobre las actividades económicas, ubicación geográfica y otros aspectos relevantes de las personas naturales y jurídicas inscritas como contribuyentes. 

### Herramientas y tipo de proyecto

![Python](https://img.shields.io/badge/Python-357ebd?style=for-the-badge&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![NumPy](https://img.shields.io/badge/NumPy-%23357ebd.svg?style=for-the-badge&logo=numpy&logoColor=white)  ![Matplotlib](https://img.shields.io/badge/Matplotlib-357ebd?style=for-the-badge)  ![Data Cleaning](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)  ![Data Transformation](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)  ![Data Filtering](https://img.shields.io/badge/Filtrado_por_región-295F98?style=for-the-badge)  ![Automated Processing](https://img.shields.io/badge/Automatización_de_procesos-295F98?style=for-the-badge)  ![RUC Analysis](https://img.shields.io/badge/Análisis_del_Padrón_RUC-295F98?style=for-the-badge)  


### Preguntas clave
1. ¿Cómo se distribuyen las empresas activas en comercio exterior en los departamentos de la región Costa?
2. ¿Qué diferencias existen en el número promedio de trabajadores según el tipo de facturación y contabilidad?
3. ¿Qué patrones se observan entre el número de trabajadores y el estado del comercio exterior `comercio_resumen` en los departamentos de la Costa?

### Metodología
**Preprocesamiento de datos:** Se limpiaron, estandarizaron y filtraron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes. 
**Explorartory Data Analysis (EDA):** Se realizó un análisis descriptivo para explorar el número de empresas activas e inactivas en comercio exterior por departamento. Además, se calcularon medidas estadísticas (promedio, mediana, percentiles) del número de trabajadores según comercio_resumen, tipofacturacion y tipocontabilidad.
**Automatización para el procesamiento de información:** Se diseñó una función en *Python* para automatizar la carga, filtrado, procesamiento y limpieza del padrón RUC. Además, se aplicó la función a la base del siguiente periodo (agosto 2024).

### Conclusiones 

#### Factores críticos de facturación:
- Si sumamos las categorías que incluyen **computarizado** (`computarizado` y `manual/computarizado`), obtenemos el 47.66% Esto significa que casi la mitad de las empresas han adoptado, al menos en parte, métodos computarizados de facturación, lo que refleja una tendencia hacia la digitalización.
- A pesar de esta tendencia, el alto porcentaje de facturación `manual` (50.66%) sugiere que muchas empresas todavía no han dado el salto hacia la modernización completa.

### Visualizaciones destacadas
1. **Distribución porcentual de empresas activas e inactivas por departamento:** Observamos que la mayoría de las empresas activas en el comercio exterior (importación y exportación) en la región costa son Lima y Callao.
![distribucion_porcentual_empresas_activas](/assets/img/distribucion_porcentual_empresas_activas.jpg)

2. **Distribución porcentual de Empresas por Tipo de Facturación:** Facturación `manual` es el tipo más usado, con el 50.66% de las empresas. Asimismo, la facturación por `computarizado` ocupa el tercer lugar (23.18%).
![distribucion_porcentual_tipo_facturacion](/assets/img/distribucion_porcentual_tipo_facturacion.jpg)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/customer-retention-analysis).**

## Análisis de patrones en el Padrón RUC
El análisis del **sistema financiero** es clave para evaluar la estabilidad económica de un país. Este proyecto busca generar una herramienta de inteligencia financiera para Perú que permita a los tomadores de decisiones anticipar cambios en el mercado y tomar decisiones más estratégicas. Se usa información pública del **Banco Central de Reserva del Perú (BCRP)**.

### Preguntas clave
1. ¿Qué patrones pueden observarse en las variables financieras principales al compararlas con el tipo de cambio promedio?
2. ¿Qué resultados arrojan las pruebas estadísticas al comparar los valores reales y estimados de las variables clave?

### Metodología
- **Preprocesamiento de datos:** Se limpiaron, estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes. Además se crearon *variables temporales*: `año` , `mes`, `día` y una columna `fecha` en formato *dd-mm-yy*.
- **Unión de la información:** Se realizó un merge por fecha para consolidar las distintas series procesadas y se calculó el tipo de cambio promedio (`tc_promedio`) como el promedio entre el tipo de cambio de compra y venta.
- **Análisis de información:** Se calculó estadísticas descriptivas y crearon gráficos de línea para cada serie.
- **Modelado econométrico:** Se estimó una regresión lineal simple con el TC Intercambiario proemdio (`tc_promedio`) como variable dependiente. Además, se aplicaron un test de medias y el test de Kolmogorov-Smirnov para comparar los valores reales y estimados de las variables clave.

### Conclusiones

### Resultados del modelo
- El TC interbancario promedio es explicado por las `reservas_internacionales` (Reservas internacionales netas), `tasa_interes` (Tasa de interés interbancaria S/) , `bono_soles` (Rendimiento del Bono del gobierno peruano a 10 años) y el `indice_bvl` (ndice General Bursátil BVL)
- Los tests estadísticos sugieren que los valores predichos y valores reales son signidicativamente iguales en medias y distribución.

#### Interpretación económica:
- El comportamiento del TC interbancario promedio refleja la interacción entre las fuerzas de mercado y las decisiones de política monetaria del BCRP.

### Visualizaciones destacadas
1. **Fluctuación del TC Intercambiario promedio:** El comportamiento del TC promedio muestra una volatilidad entre febrero y octubre. Se observan varios picos que superan el 0.5% de variación porcentual positiva, pero también caídas que alcanzan casi el -1%.
![variaciones_tc](/assets/img/variaciones_tc.jpg)


