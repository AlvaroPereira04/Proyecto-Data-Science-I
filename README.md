# Proyecto Final — Análisis de Jugadores en las Top 5 Ligas (2023/24)

**Autor:** Álvaro Vargas  
**Stack:** Python · Jupyter/Colab · pandas · NumPy · Matplotlib · Seaborn · scikit-learn · XGBoost

Repositorio del proyecto final con **EDA** y **modelo de clasificación** sobre futbolistas de las **Top 5 ligas europeas**.

## 📦 Datos
- Archivo: `data/Jugadores-Top5Ligas.csv`
- Delimitador: `;`
- Filas/Columnas: **2852** / **19**

**Distribución por liga (conteo):**
- **it Serie A**: 616 jugadores
- **es La Liga**: 609 jugadores
- **eng Premier League**: 580 jugadores
- **fr Ligue 1**: 540 jugadores
- **de Bundesliga**: 507 jugadores

> Carga rápida en pandas:
> ```python
> import pandas as pd
> df = pd.read_csv("data/Jugadores-Top5Ligas.csv", sep=";")
> ```

## 🗂 Estructura del repo
```
.
├─ data/
│  └─ Jugadores-Top5Ligas.csv
├─ notebooks/
│  └─ Proyecto-Final-Alvaro-Vargas.ipynb
├─ requirements.txt
├─ .gitignore
├─ LICENSE
└─ README.md
```

## ▶️ Ejecución
- **Colab:** subí el CSV o montá Drive y ejecutá las celdas en orden.
- **Local (venv):**
  ```bash
  python -m venv .venv
  source .venv/bin/activate  # Windows: .venv\Scripts\activate
  pip install -r requirements.txt
  jupyter lab
  ```

