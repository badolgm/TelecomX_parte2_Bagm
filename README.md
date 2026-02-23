# 📡 TelecomX — Predicción de Evasión de Clientes · Parte 2

### *Challenge 2 · Data Science · Alura Latam + Oracle Next Education*

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.0+-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Status](https://img.shields.io/badge/Status-En%20Desarrollo-F59E0B?style=for-the-badge)

> 🚧 **Proyecto en desarrollo** — Este README se actualiza progresivamente  
> conforme se completan las tarjetas del tablero Trello del challenge.

---

## 📌 Tabla de Contenidos

1. [Sobre el Proyecto](#sec-sobre)
2. [Relación con la Parte 1](#sec-parte1)
3. [Metodología y Tarjetas](#sec-metodologia)
4. [Estructura del Repositorio](#sec-estructura)
5. [Modelos a Implementar](#sec-modelos)
6. [Resultados del Análisis](#sec-resultados)
7. [Conclusiones Estratégicas](#sec-conclusiones)
8. [Tecnologías Utilizadas](#sec-tecnologias)
9. [Instalación y Uso](#sec-instalacion)
10. [Autor](#sec-autor)

---

<a id="sec-sobre"></a>

## 📝 Sobre el Proyecto

> **Objetivo:** Predecir con anticipación qué clientes de Telecom X tienen mayor probabilidad  
> de abandonar el servicio, identificando los factores que más influyen en esa decisión.

Este proyecto es la **Parte 2** del Challenge 2 de Data Science del programa  
**ONE (Oracle Next Education)** en alianza con **Alura Latam**.

Partiendo del dataset limpio generado en la **Parte 1** (pipeline ETL completo),  
se aplican estadística, análisis de correlación y **modelos de Machine Learning**  
para construir un sistema predictivo de churn.

<div align="center">

| 📊 Dataset | 👥 Registros | 🎯 Variable Objetivo | 📈 Tasa de Evasión |
|:---:|:---:|:---:|:---:|
| TelecomX Customers (CSV tratado) | 7.043 clientes | `Evasion_Binaria` (0/1) | ~26.5% |

</div>

---

<a id="sec-parte1"></a>

## 🔗 Relación con la Parte 1

Este proyecto es **continuación directa** del repositorio  
[ChallengeTELECOM-X](https://github.com/badolgm/ChallengeTELECOM-X),  
donde se realizó el pipeline ETL completo:

- ✅ Extracción de datos JSON desde la API pública
- ✅ Limpieza y tratamiento de inconsistencias
- ✅ Feature Engineering (`Cuentas_Diarias`)
- ✅ Estandarización y traducción de columnas al español
- ✅ Análisis Exploratorio de Datos (EDA) completo

El archivo `telecomx_limpio.csv` generado en la Parte 1  
es el **punto de entrada** de este proyecto.

---

<a id="sec-metodologia"></a>

## 🏗️ Metodología y Tarjetas

El proyecto sigue la metodología ágil del **tablero Trello** del challenge,  
con commits individuales por tarjeta completada.

---

### 🛠️ Fase 1 — Preparación de los Datos

| # | Tarjeta | Estado |
|---|---------|--------|
| 1 | Extracción del Archivo Tratado | 🔲 Pendiente |
| 2 | Eliminación de Columnas Irrelevantes | 🔲 Pendiente |
| 3 | Encoding | 🔲 Pendiente |
| 4 | Verificación de la Proporción de Cancelación | 🔲 Pendiente |
| 5 | Normalización o Estandarización | 🔲 Pendiente |

---

### 🎯 Fase 2 — Correlación y Selección de Variables

| # | Tarjeta | Estado |
|---|---------|--------|
| 6 | Análisis de Correlación | 🔲 Pendiente |
| 7 | Análisis Dirigido | 🔲 Pendiente |

---

### 🤖 Fase 3 — Modelado Predictivo

| # | Tarjeta | Estado |
|---|---------|--------|
| 8 | Separación de Datos | 🔲 Pendiente |
| 9 | Creación de Modelos | 🔲 Pendiente |
| 10 | Evaluación de los Modelos | 🔲 Pendiente |

---

### 📋 Fase 4 — Interpretación y Conclusiones

| # | Tarjeta | Estado |
|---|---------|--------|
| 11 | Análisis de Importancia de Variables | 🔲 Pendiente |
| 12 | Conclusión e Informe Final | 🔲 Pendiente |

---

<a id="sec-estructura"></a>

## 📁 Estructura del Repositorio

```
TelecomX_parte2_Bagm/
│
├── 📓 TelecomX_parte2_Bagm.ipynb     ← Notebook principal
├── 📊 telecomx_limpio.csv            ← Dataset de entrada (Parte 1)
├── 📄 README.md
├── 📄 LICENSE
│
└── 📂 assets/                        ← (imagen banner — próximamente)
    └── 📂 images/
```

---

<a id="sec-modelos"></a>

## 🤖 Modelos a Implementar

Se implementarán **dos modelos** con enfoques complementarios:

| Modelo | Normalización | Justificación |
|--------|---------------|---------------|
| **Regresión Logística** | ✅ Sí | Sensible a la escala; coeficientes interpretables como factores de riesgo |
| **Random Forest** | ❌ No | Basado en árboles; captura relaciones no lineales e incluye importancia de variables |

> 📊 *Los resultados y métricas se publicarán aquí al completar la Fase 3.*

---

<a id="sec-resultados"></a>

## 📊 Resultados del Análisis

> 🚧 *Sección en construcción — se completará al finalizar las Fases 2 y 3.*

Los resultados del análisis exploratorio, las correlaciones identificadas  
y las métricas de los modelos estarán disponibles aquí una vez completadas  
las tarjetas correspondientes.

---

<a id="sec-conclusiones"></a>

## 🎯 Conclusiones Estratégicas

> 🚧 *Sección en construcción — se completará al finalizar la Fase 4.*

Las conclusiones, el perfil del cliente en riesgo y las recomendaciones  
estratégicas basadas en los modelos estarán disponibles aquí  
al completar el informe final.

---

<a id="sec-tecnologias"></a>

## 🛠️ Tecnologías Utilizadas

<div align="center">

| Herramienta | Uso |
|:-----------:|:----|
| 🐍 **Python 3.10+** | Lenguaje principal |
| 🐼 **Pandas** | Manipulación y preprocesamiento de datos |
| 🔢 **NumPy** | Operaciones numéricas |
| 📊 **Matplotlib** | Visualización estática |
| 🎨 **Seaborn** | Visualización estadística avanzada |
| 🤖 **Scikit-Learn** | Modelos ML, métricas y preprocesamiento |
| ☁️ **Google Colab** | Entorno de ejecución en la nube |
| 🐙 **GitHub** | Control de versiones |

</div>

---

<a id="sec-instalacion"></a>

## 🚀 Instalación y Uso

### Requisito previo

Tener el archivo `telecomx_limpio.csv` generado en la  
**[Parte 1 del proyecto](https://github.com/badolgm/ChallengeTELECOM-X)**.

### Opción A — Google Colab (Recomendado)

1. Abre [Google Colab](https://colab.research.google.com/)
2. Ve a `Archivo → Abrir cuaderno → GitHub`
3. Pega la URL de este repositorio
4. Selecciona `TelecomX_parte2_Bagm.ipynb`
5. Sube el archivo `telecomx_limpio.csv` cuando se indique
6. Ejecuta las celdas en orden ▶️

### Opción B — Local

```bash
# 1. Clonar el repositorio
git clone https://github.com/badolgm/TelecomX_parte2_Bagm.git
cd TelecomX_parte2_Bagm

# 2. Instalar dependencias
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# 3. Abrir el notebook
jupyter notebook TelecomX_parte2_Bagm.ipynb
```

---

<a id="sec-autor"></a>

## 🎓 Autor

<div align="center">

**Bernardo Adolfo Gómez Montoya**

Desarrollado con ❤️ en el marco de **Alura Latam + Oracle Next Education**

[![Alura Latam](https://img.shields.io/badge/Alura-Latam-1572B6?style=flat-square&logo=alura&logoColor=white)](https://www.aluracursos.com/)
[![Oracle ONE](https://img.shields.io/badge/Oracle-Next%20Education-F80000?style=flat-square&logo=oracle&logoColor=white)](https://www.oracle.com/lad/education/oracle-next-education/)
[![Parte 1](https://img.shields.io/badge/Ver%20Parte%201-ChallengeTELECOM--X-4ECDC4?style=flat-square&logo=github&logoColor=white)](https://github.com/badolgm/ChallengeTELECOM-X)

</div>

---

<div align="center">

📄 Este proyecto está bajo la **Licencia MIT** — ver el archivo
[LICENSE](https://github.com/badolgm/TelecomX_parte2_Bagm/blob/main/LICENSE)
para más detalles.

</div>
