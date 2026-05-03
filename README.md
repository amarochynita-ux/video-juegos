# 🎮 Análisis de Éxito en la Industria de Videojuegos (2012-2016)

## 🎯 Problema
En un mercado saturado, las distribuidoras enfrentan el riesgo de invertir en plataformas obsoletas o géneros en declive. Este proyecto analiza el comportamiento de la industria entre 2012 y 2016 para predecir las tendencias de éxito hacia 2017.

## 📝 Contexto
Utilizando un dataset histórico, me enfoqué en el periodo más reciente (2012-2016). Este recorte es fundamental porque el comportamiento del consumidor y la tecnología de las consolas cambian drásticamente cada 5 años, invalidando tendencias antiguas.

## 🛠️ (Proceso)
1. **Limpieza de Datos:** Estandarización de nombres de columnas y tratamiento de valores ausentes (imputación de medianas en puntuaciones y eliminación de registros sin año).
2. **Análisis de Ciclo de Vida:** Identificación de plataformas en crecimiento (PS4, Xbox One) frente a las que están en declive.
3. **Estadística Aplicada:** Uso de la librería `scipy.stats` para realizar pruebas de Shapiro-Wilk y validar la distribución de los datos.
4. **Visualización:** Creación de mapas de calor, boxplots y gráficos de dispersión para hallar correlaciones entre reseñas y ventas.

## 📊 Hallazgos & ConclusionesDominio 
* **Regional: Identifiqué que el mercado japonés es fundamentalmente distinto (liderado por 3DS), mientras que Occidente prefiere consolas de alto rendimiento (PS4/XOne).
* **Influencia de la Crítica: Las ventas tienen una correlación significativamente mayor con las reseñas de expertos que con las de usuarios.
* **Eficiencia de Género: Los Shooters presentan ventas promedio más altas, a pesar de que el género de Acción tiene más títulos publicados.

## 🚀 Impacto en el Mundo Real
Este proyecto sirve para **reducir errores de inversión**. En un contexto empresarial, estos hallazgos permiten:
1. **Reducir pérdidas:** Al no comprar stock de plataformas obsoletas.
2. **Mejorar la calidad de las decisiones:** Basando el presupuesto de marketing en datos estadísticos y no en suposiciones.
3. **Prevenir fallos de producto:** Al entender qué clasificaciones de edad funcionan en cada cultura.

##🌱 Aprendizajes
* **Aprendí a identificar sesgos en datos de ventas globales y la importancia de analizar promedios por título para no ser engañado por volúmenes totales.
