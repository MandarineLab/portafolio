# Acerca de mí

Economista y financiera certificada en análisis de datos con sólida experiencia en extracción, limpieza y modelado de datos estratégicos. 

Genero insights accionables que optimizan procesos y apoyan la toma de decisiones estratégicas, logrando ahorros significativos de tiempo mediante la automatización.

### Habilidades tecnológicas
- Análisis y gestión de datos utilizando **Excel / SQL / Python / R**
- Visualización de datos y narración de historias usando **Tableau**

### Habilidades blandas
Análisis de datos | Resolución de problemas | Comunicación efectiva | Trabajo en equipo | Orientación a resultados | Organización | Proactividad | Atención al detalle | Optimización de Procesos

<!-- PARA HACER QUE EL LINK ABRA EN OTRA PESTAÑA
<a href="https://www.linkedin.com/in/marielalegoma/" target="_blank">
  <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>-->
[![LinkedIn](https://img.shields.io/badge/linkedin-%23295F98.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/malegoma/)
[![Outlook](https://img.shields.io/badge/Microsoft_Outlook-295F98?style=for-the-badge&logo=microsoft-outlook&logoColor=white)](mailto:mariel_goma@outlook.com)

* * *

# Proyectos seleccionados

## Análisis de retención de clientes para gimnasio
En todas las industrias, la retención de clientes es fundamental para garantizar **ingresos sostenibles** y **reducir los costos asociados con la adquisición de nuevos clientes**. Identificar los factores clave que influyen en la retención y cancelación permite al gimnasio Model Fitness anticiparse a los riesgos de abandono, **diseñar estrategias de fidelización efectivas** y **personalizar las experiencias para cada cliente**.

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
1. ¿Qué factores demográficos o de comportamiento influyen más en la cancelación?
2. ¿Qué características diferencian a los clientes leales de los que abandonan?
3. ¿Cómo se pueden segmentar los clientes para diseñar estrategias personalizadas?

### Metodología
- **Preprocesamiento de datos:** Se limpiaron y estandarizaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
- **Explorartory Data Analysis (EDA):** Se analizaron características demográficas y de uso, identificando patrones en clientes que permanecen y los que cancelan.
- **Modelado predictivo:** Se entrenaron modelos de regresión logística y bosque aleatorio para predecir la cancelación de clientes con un precisión del 85% y 84%, respectivamente.
- **Clustering:** Se segmentaron los clientes en grupos utilizando K-means para identificar comportamientos similares.

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
![Contract Period Histogram](/assets/img/p01_contract_period_histogram.png)
2. **Matriz de correlaciones:** Se encontró que Las características `month_to_end_contract` y `contract_period` están altamente correlacionadas (0.9), lo que sugiere que se debe tener cuidado con la multicolinealidad al desarrollar modelos predictivos.
![Corr Matrix Churn Data](/assets/img/p01_gym_churn_corr.png)
3. **Análisis de clústeres:** El dendrograma muestran cómo los clientes se agrupan en segmentos distintos basados en sus características, donde el número óptimo de clústeres sugerido es 4.
![Dendrogram](/assets/img/p01_dendrogram.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/customer-retention-analysis).**

## Optimización de gastos de marketing
El objetivo de este proyecto es **optimizar los gastos de marketing** de Y.Afisha mediante el análisis de **datos de visitas, pedidos y costos publicitarios**. El estudio busca comprender el **comportamiento del usuario**, identificar **fuentes de adquisición rentables** y calcular métricas clave como el **Costo de Adquisición de Clientes (CAC)**, el **Valor de Vida del Cliente (LTV)** y el **Retorno de la Inversión en Marketing (ROMI)**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Análisis de cohortes](https://img.shields.io/badge/Análisis_de_cohortes-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Cuántos usuarios activos diarios, semanales y mensuales tiene la aplicación?
2. ¿Cuáles son las principales fuentes de adquisición de clientes y su rentabilidad?
3. ¿Qué métricas de ventas y conversiones se pueden mejorar?
4. ¿Qué tan efectiva es cada fuente de marketing según su ROMI?

### Metodología
- **Preprocesamiento de datos:** Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
- **Análisis del comportamiento de usuarios** Cálculo de métricas como usuarios activos diarios (DAU), semanales (WAU) y mensuales (MAU), duración de sesiones y frecuencia de retorno.
- **Análisis de ventas:** Evaluación del tamaño promedio de compra, pedidos por cliente y LTV.
- **Pruebas de hipótesis:** Cálculo de CAC, ROMI y costos por fuente de adquisición.

### Conclusiones y recomendaciones

#### Comportamiento de usuarios, Ventas y Marketing:
- El 16% de los usuarios regresa semanalmente, pero solo el 4% vuelve mensualmente, indicando una posible necesidad de campañas de retención.
- El tamaño promedio de compra es de $5, con algunos picos en diciembre debido a promociones estacionales. La mayoría de los usuarios realiza un pedido por mes.
- Las fuentes con mayor ROMI es 1, 5 y 9 pues, antes de que las cohortes cumplan el primer mes de edad, el ROMI casi alcanza el 1 en la mayoría de cohortes.
- Destaca la fuente 1 donde, a pesar de ser la segunda fuente en la que menos se gasta, es 3era fuente que más usuarios atrae.

#### Recomendaciones:
- Descontinuar las fuentes 7, 9 y 10 debido a su bajo rendimiento.
- Reducir la inversión en la fuente 3, ya que no genera retornos significativos.
- Invertir en la fuente 1, que sigue siendo una aliada clave con baja inversión y alto rendimiento.

### Visualizaciones destacadas
1. **Usuarios Activos Semanales (WAU):** Se observa una tendencia a la alza a partir de la semana 31 de 2017, con una caída drástica en la semana 53 del mismo año. Se observa una disminución en usuarios en la semana 13, 17 y 18 de 2019.
![WAU Chart](/assets/img/p04_wau_chart.png)
3. **LTV por cohorte:** Cada cliente de la primera cohorte representó un ingreso de $11.88. Además, la cohorte de septiembre de 2017 representó ingresos de $13.44 por cliente.
![LTV Heat Chart](/assets/img/p04_ltv_heat_chart.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/marketing-spending-optimization).**

## Análisis de comportamiento de usuarios y embudo de ventas
Este proyecto analiza el embudo de ventas de la aplicación de una empresa de alimentos para **identificar las etapas con mayores pérdidas de usuarios** y evalúa, mediante un experimento A/A/B, si un nuevo diseño de fuentes puede **mejorar la conversión** en comparación con el diseño actual. El objetivo es proporcionar **insights basados en datos** que guíen **decisiones estratégicas sobre diseño y funcionalidad**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![Plotly](https://img.shields.io/badge/Plotly-%23357ebd.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Tests A/B](https://img.shields.io/badge/Tests_A/B-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Qué eventos del embudo de ventas tienen mayores tasas de abandono?
2. ¿Qué porcentaje de usuarios completa el embudo de ventas desde el inicio hasta el pago?
3. ¿El cambio en el diseño de las fuentes afecta significativamente la conversión?
4. ¿Hay diferencias estadísticas entre los grupos de control y el grupo de prueba?

### Metodología
- **Preprocesamiento de datos:** Se ajustaron los nombres de las columnas, se eliminaron duplicados y se filtraron registros incompletos.
- **Análisis del embudo de ventas:** Se identificaron eventos clave y la proporción de usuarios que avanzan entre etapas.
- **Experimentación A/A/B:** Se compararon conversiones entre grupos de control y prueba mediante pruebas de hipótesis estadísticas.

### Conclusiones y recomendaciones

#### Embudo de ventas:
- El evento OffersScreenAppear es donde más usuarios abandonan (61.9%).
- Solo el 47.7% de los usuarios completa el embudo de ventas hasta el pago exitoso.

#### Resultados del experimento:
- No se encontraron diferencias estadísticas significativas entre los grupos de control y el grupo de prueba.
- Las nuevas fuentes no generan un impacto positivo en la conversión, por lo que no se recomienda implementar este cambio.

#### Recomendaciones:
- Optimizar la pantalla de ofertas para retener más usuarios en esa etapa.
- Priorizar otros cambios en el diseño o funcionalidad de la aplicación con mayor potencial de impacto.

### Visualizaciones destacadas
1. **Embudo de ventas:** La etapa en la que más se pierden usuarios es en el Tutorial, donde solo el 23.7% de los usuarios en la etapa anterior llegan a esta. La siguiente etapa donde se pierden más usuarios es en OfferScreenAppear, donde el 61.9% de los usuarios de la etapa anterior pasan a esta.
![Sales Funner Chart](/assets/img/p03_sales_funnel_chart.png)
2. **Periodo de tiempo de los datos:** Los datos completos están disponibles a partir del 1 de agosto de 2019, por lo que se descartaron fechas anteriores. El periodo actualizado abarca del 1 al 7 de agosto de 2019.
![Time Period Data](/assets/img/p03_time_period_data.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/sales-funnel-analysis).**

## Análisis de ventas de videojuegos
Este proyecto analiza las ventas de videojuegos por región, plataforma y género para identificar patrones clave que permitan a la tienda online Ice **detectar proyectos prometedores** y **planificar campañas publicitarias efectivas**. Al entender las dinámicas de mercado en Norteamérica, Europa y Japón, se busca **optimizar estrategias de marketing** y **maximizar el retorno de inversión en los títulos más prometedores**.

#### Herramientas y tipo de proyecto
![Python](https://img.shields.io/badge/python-357ebd?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23357ebd.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23357ebd.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-357ebd?style=for-the-badge)
![SciPy](https://img.shields.io/badge/SciPy-%23357ebd.svg?style=for-the-badge&logo=scipy&logoColor=white)
![Limpieza de datos](https://img.shields.io/badge/Limpieza_de_datos-295F98?style=for-the-badge)
![Transformación de datos](https://img.shields.io/badge/Transformación_de_datos-295F98?style=for-the-badge)
![Análisis de datos](https://img.shields.io/badge/Análisis_de_datos-295F98?style=for-the-badge)
![Pruebas de hipótesis](https://img.shields.io/badge/Pruebas_de_hipótesis-295F98?style=for-the-badge)
![Visualización de datos](https://img.shields.io/badge/Visualización_de_datos-295F98?style=for-the-badge)

### Preguntas clave
1. ¿Cuáles son las plataformas con mayores ventas globales y cómo varían estas por región?
2. ¿Qué géneros de videojuegos son más populares en Norteamérica, Europa y Japón?
3. ¿Qué relación existe entre las puntuaciones de usuarios/críticos y las ventas globales de videojuegos?
4. ¿Existen diferencias significativas en las calificaciones promedio entre plataformas y géneros?

### Metodología
- **Preprocesamiento de datos:** Limpieza de datos (valores ausentes, duplicados, formatos de columnas, y tipos de datos adecuados).
- **Análisis exploratorio de datos:** Identificación de las plataformas y géneros más populares y evaluación de la correlación entre puntuaciones de usuarios/críticos y ventas.
- **Segmentación regional:** Comparación de preferencias por plataformas y géneros en Norteamérica, Europa y Japón.
- **Pruebas de hipótesis:** Comparación de calificaciones promedio entre plataformas y géneros.

### Conclusiones y recomendaciones

#### Dinámica de ventas por región:
- Norteamérica y Europa prefieren juegos de acción y disparos en consolas como Xbox y PlayStation.
- Japón, en cambio, favorece juegos de rol en plataformas portátiles como Nintendo 3DS.

#### Efecto de las reseñas:
- Las puntuaciones de críticos tienen una correlación moderada positiva con las ventas (coeficiente ≈ 0.41).
- Las puntuaciones de usuarios presentan correlación casi nula, lo que sugiere que los consumidores priorizan otras métricas al elegir juegos.

#### Pruebas de hipótesis:
- Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son iguales.
- Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.

#### Estrategias recomendadas:
- Dado que PS4 y Xbox One se mantienen relevantes en ventas globales, recomendamos enfocar campañas publicitarias en estas plataformas.
- Debido a las preferencias de usuarios en esta región, recomendamos enfocar promociones de RPG en Japón e impulsar títulos de acción y disparos en mercados occidentales.

### Visualizaciones destacadas
1. **Distribución de ventas por género:** Los géneros con mayores ventas son aquellos que pertenecen al género de acción, disparos, juegos de rol y deportes. Mientras que los géneros con menores ventas son los de rompecabezas y estrategia.
![Genre Bar Chart](/assets/img/p02_genre_bar_chart.png)
2. **Comparación de reseñas y ventas:** Hay una correlación positiva mediana entre la puntuación de los críticos y las ventas de videojuegos. Esto podría significar que los usuarios toman en cuenta parcialmente las puntuaciones de los críticos para comprar o no un videojuego.
![Score Scatter Plot](/assets/img/p02_score_scatter_plot.png)
3. **Ventas por plataforma:** El promedio de las ventas difiere en gran cantidad de la mediana de los datos debido a la dispersión de los datos. Por lo mismo, se considera que una mejor medida de tendencia central será la mediana.
![Sales Box Plot](/assets/img/p02_sales_box_plot.png)

**Explora más detalles del proyecto en el [repositorio completo](https://github.com/MaleGoma/video-game-sales-analysis).**
