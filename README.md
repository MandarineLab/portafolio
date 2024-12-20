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

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23357ebd.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Modelos de predicción](https://img.shields.io/badge/Modelos_de_predicción-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Cómo se distribuyen las empresas activas en comercio exterior en los departamentos de la región Costa?
2. ¿Qué diferencias existen en el número promedio de trabajadores según el tipo de facturación y contabilidad?
3. ¿Qué patrones se observan entre el número de trabajadores y el estado del comercio exterior `comercio_resumen` en los departamentos de la Costa?

### Metodología
- **Preprocesamiento de datos:**
- Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- Se filtraron los datos para incluir solo los departamentos de la región Costa: Lima, Callao, Piura, Lambayeque, Tumbes, Ica y La Libertad.
- **Explorartory Data Analysis (EDA):**
- Se realizó un análisis descriptivo para explorar el número de empresas activas e inactivas en comercio exterior por departamento.
- Se calcularon medidas estadísticas (promedio, mediana, percentiles) del número de trabajadores según comercio_resumen, tipofacturacion y tipocontabilidad.
- **Automatización para el procesamiento de información:**
- Se diseñó una función en *Python* para automatizar la carga, filtrado, procesamiento y limpieza del padrón RUC.
- Se aplicó la función a la base del siguiente periodo (agosto 2024).

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
