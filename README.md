# 🎮 Análisis de Éxito en la Industria de Videojuegos (2012-2016)

## 🎯 Problema
El mercado de videojuegos es altamente volátil. El reto principal fue identificar qué factores (plataforma, región, críticas) determinan el éxito comercial de un título para planificar las inversiones publicitarias y de stock de cara al año 2017.

## 📝 Contexto
Utilizando un dataset histórico, me enfoqué en el periodo más reciente (2012-2016). Este recorte es fundamental porque el comportamiento del consumidor y la tecnología de las consolas cambian drásticamente cada 5 años, invalidando tendencias antiguas.

## 🛠️ ¿Qué hice? (Proceso)
1. **Limpieza de Datos:** Estandarización de nombres de columnas y tratamiento de valores ausentes (imputación de medianas en puntuaciones y eliminación de registros sin año).
2. **Análisis de Ciclo de Vida:** Identificación de plataformas en crecimiento (PS4, Xbox One) frente a las que están en declive.
3. **Estadística Aplicada:** Uso de la librería `scipy.stats` para realizar pruebas de Shapiro-Wilk y validar la distribución de los datos.
4. **Visualización:** Creación de mapas de calor, boxplots y gráficos de dispersión para hallar correlaciones entre reseñas y ventas.

## 📈 Resultados (Insights)
* **El Peso de la Crítica:** Existe una correlación positiva moderada entre el puntaje de la crítica y las ventas; sin embargo, el puntaje de los usuarios no tiene un impacto directo en el éxito comercial.
* **Diversidad Regional:** En Japón, la consola portátil **3DS** domina el mercado, mientras que en Norteamérica y Europa la **PS4** es la líder indiscutible.
* **Rating ESRB:** Los juegos con clasificación **"M" (Mature)** generan mayores ingresos en Occidente, pero en Japón este segmento es mucho menor.

## 💡 Conclusiones y Recomendaciones
* **Acción sugerida:** Priorizar el catálogo de 2017 en plataformas **PS4 y Xbox One**.
* **Gestión de Riesgo:** No basar compras de inventario en "hype" de usuarios, sino en evaluaciones de expertos, ya que estas últimas están más alineadas con la intención de compra real.
* **Segmentación:** Lanzar campañas diferenciadas para el mercado asiático centradas en portabilidad y clasificaciones aptas para todo público.

## 🚀 Impacto en el Mundo Real
Este proyecto sirve para **reducir errores de inversión**. En un contexto empresarial, estos hallazgos permiten:
1. **Reducir pérdidas:** Al no comprar stock de plataformas obsoletas.
2. **Mejorar la calidad de las decisiones:** Basando el presupuesto de marketing en datos estadísticos y no en suposiciones.
3. **Prevenir fallos de producto:** Al entender qué clasificaciones de edad funcionan en cada cultura.

## 🧠 Aprendizajes Profesionales
* Descubrí que la **limpieza de datos** es el paso más crítico; sin tratar los valores "TBD", los promedios de ventas habrían sido erróneos.
* Aprendí a utilizar **VS Code** como entorno profesional para vincular código local con repositorios globales mediante Git.
* Si hiciera el proyecto de nuevo, añadiría un análisis de ventas por estación (verano vs. invierno) para optimizar los lanzamientos mensuales.
