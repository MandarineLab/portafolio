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
3. ¿Qué patrones se observan entre el número de trabajadores y el estado del comercio exterior (comercio_resumen) en los departamentos de la Costa?

### Metodología
- **Preprocesamiento de datos:**
- Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- Se filtraron los datos para incluir solo los departamentos de la región Costa: Lima, Callao, Piura, Lambayeque, Tumbes, Ica y La Libertad.
- **Explorartory Data Analysis (EDA):**
- Se realizó un análisis descriptivo para explorar el número de empresas activas e inactivas en comercio exterior por departamento.
- Se calcularon medidas estadísticas (promedio, mediana, percentiles) del número de trabajadores según comercio_resumen, tipofacturacion y tipocontabilidad.

### Conclusiones y recomendaciones

#### Factores críticos de retención:
- La proximidad al gimnasio, contratos más largos, la participación en sesiones grupales y mayor frecuencia de visitas están fuertemente asociados con una menor tasa de cancelación.
- Clientes jóvenes, con contratos cortos y baja frecuencia de visitas, tienen mayores tasas de cancelación.

#### Estrategias recomendadas:
- **Extender contratos cortos:** Ofrecer incentivos para ampliar contratos de 1 mes.
- **Promover actividades grupales:** Diseñar campañas que destaquen los beneficios de participar en sesiones grupales.
- **Campañas personalizadas:** Utilizar el modelo predictivo para identificar clientes en riesgo y ofrecer promociones específicas.
- **Segmentación proactiva:** Clasificar clientes nuevos por edad y duración de contrato para diseñar estrategias de retención desde el inicio.

### Visualizaciones destacadas
1. **Distribución de cancelación según duración del contrato:** Observamos que quienes cancelaron suelen contratar en su mayoría 1 mes, al igual que quienes no cancelan. Sin embargo, quienes permanecen suelen también contratar por periodos de 1 año y 6 meses, mientras que los que cancelan en su minoría contratan en dichos periodos.
![distribucion_porcentual_empresas_activas](/assets/img/distribucion_porcentual_empresas_activas.jpg)

3. **Matriz de correlaciones:** Se encontró que Las características `month_to_end_contract` y `contract_period` están altamente correlacionadas (0.9), lo que sugiere que se debe tener cuidado con la multicolinealidad al desarrollar modelos predictivos.
![distribucion_porcentual_tipo_facturacion](/assets/img/distribucion_porcentual_tipo_facturacion.jpg)

4. **Análisis de clústeres:** El dendrograma muestran cómo los clientes se agrupan en segmentos distintos basados en sus características, donde el número óptimo de clústeres sugerido es 4.
![Dendrogram](/assets/img/p01_dendrogram.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/customer-retention-analysis).**
