<!-- HEADER -->
<div align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2a4e,100:0d1b2a&height=180&section=header&text=Call%20Center%20Data%20Analysis&fontSize=36&fontColor=ffffff&fontAlignY=38&desc=Análisis%20exploratorio%20de%20datos%20de%20contact%20center%20con%20Python&descAlignY=58&descSize=15&descColor=a0aec0"/>
</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

</div>

---

## 📌 ¿De qué trata este proyecto?

Análisis exploratorio de datos (EDA) sobre interacciones de un contact center.  
El objetivo es descubrir patrones operativos reales: horas pico, tipos de caso más frecuentes, tiempos de resolución y satisfacción del cliente.

> 💡 **Contexto personal:** Este proyecto nace de mi experiencia trabajando como agente en **ContactPoint360** y **Concentrix**, donde manejé entre 80–100 interacciones diarias. Quise aplicar análisis de datos para entender los patrones que viví en primera persona — ahora desde el lado del analista.

---

## 🎯 Preguntas que responde el análisis

| # | Pregunta |
|---|----------|
| 1 | ¿En qué horas del día hay mayor volumen de interacciones? |
| 2 | ¿Qué tipos de caso o solicitud son más frecuentes? |
| 3 | ¿Cuánto tiempo tarda en resolverse cada tipo de caso? |
| 4 | ¿Cuál es la satisfacción promedio del cliente (CSAT)? |
| 5 | ¿Qué días de la semana tienen mayor carga operativa? |

---

## 📁 Estructura del proyecto

```
CALLCENTER/
│
├── Data/
│   └── callcenter_data.csv       # Dataset (ver instrucciones abajo)
│
├── notebooks/
│   └── Analysis.ipynb               # Script principal de análisis notebook
│
├── outputs/
│   ├── 01_volumen_por_hora.png
│   ├── 02_tipos_de_caso.png
│   ├── 03_tiempo_resolucion.png
│   ├── 04_csat.png
│   └── 05_volumen_por_dia.png
│
├── .gitignore
├── requirements.txt
└── README.md
```

---

## 🚀 Cómo correrlo

**1. Clona el repositorio**
```bash
git clone https://github.com/JhonlunKnox/Analysis-Call-Center.git
cd Analysis-Call-Center
```

**2. Instala dependencias**
```bash
pip install -r requirements.txt
```

**3. Corre el análisis**
```bash
cd notebooks
python analysis.py
```

Las gráficas se exportan automáticamente en la carpeta `outputs/`.

---

## 📊 Visualizaciones generadas

| Gráfica | Descripción |
|---------|-------------|
| `01_volumen_por_hora.png` | Barras — interacciones por hora del día |
| `02_tipos_de_caso.png` | Barras horizontales — top 10 tipos de caso |
| `03_tiempo_resolucion.png` | Histograma + boxplot por tipo de caso |
| `04_csat.png` | Distribución de satisfacción del cliente |
| `05_volumen_por_dia.png` | Interacciones por día de la semana |

---

## 🛠️ Stack

| Herramienta | Uso |
|-------------|-----|
| Python 3.x | Lenguaje principal |
| Pandas | Limpieza y manipulación de datos |
| Matplotlib | Visualizaciones base |
| Seaborn | Visualizaciones estadísticas |
| Jupyter / Script | Entorno de análisis |

---

## 👤 Autor

**Juan Pablo Luna Zuleta**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JhonlunKnox)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juan-pablo-zuleta-967277334/)
[![Portfolio](https://img.shields.io/badge/Portfolio-1a2a4e?style=for-the-badge&logo=firefox&logoColor=white)](https://portafolio-dev-dls.pages.dev/#perfil)

<!-- FOOTER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1b2a,100:1a2a4e&height=120&section=footer"/>
