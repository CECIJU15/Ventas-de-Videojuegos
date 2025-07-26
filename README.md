# Análisis Exploratorio de Ventas de Videojuegos - Ice Games
## 📝Descripción del proyecto
Ice Games es una tienda online que distribuye videojuegos a nivel mundial, ofreciendo títulos para múltiples plataformas como PlayStation, Xbox, Nintendo y PC. Su catálogo incluye una variedad de lanzamientos.
Este proyecto explora el mercado de videojuegos entre 2010 y 2016, analizando ventas, plataformas, géneros y otros factores clave que influyen en el éxito comercial.

## 📌 Objetivo del proyecto
Examinar una base de datos de ventas de videojuegos desde 1980 hasta 2017, en las regiones de Norteamérica, Europa, Japón y otras áreas del mundo. El propósito es evaluar las tendencias del mercado, identificar patrones de éxito y detectar oportunidades comerciales para videojuegos que están saliendo al mercado.

## 🗂️ Datos utilizados

`games.csv`:  Contiene los datos en bruto extraídos originalmente. Este archivo incluye registros sin procesar que requieren limpieza y transformación antes del análisis.
`games_clean.csv`: Archivo generado tras el proceso de limpieza y transformación de los datos. Contiene únicamente la información relevante, estructurada y lista para su análisis exploratorio.

## 🛠️ Herramientas y tecnologías
- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Jupyter Notebook

## 📈 Análisis realizados
- Limpieza y transformación de datos
- Análisis exploratorio de ventas por año, plataforma y género
- Visualización de tendencias y ciclos de vida de consolas
- Identificación de juegos más exitosos y multiplataforma
- Estudio de cuotas de mercado por región
- Pruebas de hipótesis sobre calificaciones y ventas
- Conclusiones estratégicas para la industria

## ✅ Conclusiones
- **Ciclo de vida promedio** de una plataforma exitosa: ~10 años.
- **Nuevas plataformas** aparecen cada 5-7 años; las antiguas tardan ~3 años en perder relevancia.
- **Géneros populares** varían por región: Action y Shooter dominan en Europa/Norteamérica; Role-Playing en Japón.
- **Más juegos = más ventas:** Las plataformas con mayor catálogo tienden a vender más.
- **Clasificación ESRB** influye en ventas regionales.
- **Correlación positiva** (aunque débil) entre puntuaciones de críticos y ventas.
- **Juegos multiplataforma** suelen tener mejores resultados comerciales.
- **Consumo regional:** Consolas portátiles triunfan en Japón; sobremesa en Europa/Norteamérica.

## 📁 Estructura del proyecto
```
📦 analisis-ventas-videojuegos
├── 📁 data/
│   ├── 📄 games.csv                 # Datos en bruto originales
│   └── 📄 games_clean.csv           # Datos limpios y transformados para el análisis
├── 📄 README.md                     # Este archivo
├── 📄 notebook.ipynb                # Análisis exploratorio y estadístico en Jupyter
├── 📄 requirements.txt              # Librerías necesarias para reproducir el análisis
```
    
### 👤 Autor
Cecilia Juliana Ruiz Carhuamaca
Estudiante de análisis de datos en TripleTen