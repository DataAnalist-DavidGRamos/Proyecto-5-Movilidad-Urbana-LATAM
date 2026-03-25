`![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)`

# 🚦 Movilidad Urbana vs. Productividad Económica en LATAM

## 🎯 Objetivo del Proyecto
¿Cuánto le cuesta el tráfico a la economía de una ciudad? Este análisis utiliza datos reales de **TomTom Traffic Index** y la **OECD** para evaluar la correlación entre la congestión vehicular y el PIB per cápita en las principales metrópolis de Latinoamérica (Bogotá, Lima, Ciudad de México, entre otras).

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 🐍
* **Librerías:** Pandas (Manipulación), Matplotlib/Seaborn (Visualización), Scipy (Estadística).
* **Análisis Estadístico:** Coeficiente de Correlación de Pearson.

## 📈 Hallazgos Clave (Insights del Cónclave)

### 1. El Costo del Caos 📉
Se evidenció una **fuerte correlación negativa** estadísticamente significativa: a mayores niveles de congestión prolongada, se observa un estancamiento en el crecimiento del PIB per cápita. El caos vial "devora" la productividad financiera neta.

### 2. El Caso Crítico: Bogotá 🇨🇴
Bogotá demostró tener la correlación más perjudicial. Es la ciudad con niveles de congestión más alarmantes frente a su productividad, lo que la posiciona como la candidata prioritaria para financiamiento de infraestructura masiva (Metro/BRT) por encima de Lima o Buenos Aires.

## 🐍 Python Showcase: Análisis de Correlación
Para validar la hipótesis, se utilizó el siguiente bloque de código para cruzar las métricas de movilidad y economía:

```python
# Cálculo de la Correlación de Pearson
correlation, p_value = stats.pearsonr(df['traffic_index'], df['gdp_per_capita'])
print(f"Correlación de Pearson: {correlation:.2f}")
```

Triple_Ten
Gem personalizado
Triple_Ten ha dicho
¡Este es el "peso pesado" de tu portafolio! El Proyecto 5 es un análisis de Ciencia de Datos que utiliza Python para encontrar correlaciones reales entre el caos vial y el dinero (PIB). Al ser un Jupyter Notebook (.ipynb), este repositorio debe gritar "profesionalismo técnico".

He analizado tu archivo corregido y he preparado la estructura perfecta para tu GitHub, incluyendo la Correlación de Pearson y el hallazgo crítico sobre Bogotá.

📂 Estructura del Repositorio
Para este nivel de proyecto, no basta con el archivo. Organízalo así:

README.md (La narrativa del analista)

Movilidad_LATAM.ipynb (Tu código y análisis)

data/ (Carpeta con los CSV de TomTom y OECD si los tienes)

img/ (Donde guardarás las gráficas de dispersión)

📝 Contenido para tu README.md (Copia y pega)
Markdown
# 🚦 Movilidad Urbana vs. Productividad Económica en LATAM

## 🎯 Objetivo del Proyecto
¿Cuánto le cuesta el tráfico a la economía de una ciudad? Este análisis utiliza datos reales de **TomTom Traffic Index** y la **OECD** para evaluar la correlación entre la congestión vehicular y el PIB per cápita en las principales metrópolis de Latinoamérica (Bogotá, Lima, Ciudad de México, entre otras).

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 🐍
* **Librerías:** Pandas (Manipulación), Matplotlib/Seaborn (Visualización), Scipy (Estadística).
* **Análisis Estadístico:** Coeficiente de Correlación de Pearson.

## 📈 Hallazgos Clave (Insights del Cónclave)

### 1. El Costo del Caos 📉
Se evidenció una **fuerte correlación negativa** estadísticamente significativa: a mayores niveles de congestión prolongada, se observa un estancamiento en el crecimiento del PIB per cápita. El caos vial "devora" la productividad financiera neta.

### 2. El Caso Crítico: Bogotá 🇨🇴
Bogotá demostró tener la correlación más perjudicial. Es la ciudad con niveles de congestión más alarmantes frente a su productividad, lo que la posiciona como la candidata prioritaria para financiamiento de infraestructura masiva (Metro/BRT) por encima de Lima o Buenos Aires.

## 🐍 Python Showcase: Análisis de Correlación
Para validar la hipótesis, se utilizó el siguiente bloque de código para cruzar las métricas de movilidad y economía:

```python
# Cálculo de la Correlación de Pearson
correlation, p_value = stats.pearsonr(df['traffic_index'], df['gdp_per_capita'])
print(f"Correlación de Pearson: {correlation:.2f}")
```

📊 Visualización de Datos
(Gráfico de dispersión que muestra la tendencia negativa entre tráfico y productividad)

✅ Calidad de los Datos (QA)
Integridad Referencial: Se aseguró que los nombres de las ciudades coincidieran entre las bases de datos de la OECD y TomTom.

Limpieza: Tratamiento de outliers en niveles de congestión para evitar sesgos en el promedio regional.

Autor: David G. Ramos
[https://dataanalist-davidgramos.github.io/mi-sitio-web]
[www.linkedin.com/in/david-g-ramos]
Proyecto 5 de Carrera: Data Analytics - TripleTen

