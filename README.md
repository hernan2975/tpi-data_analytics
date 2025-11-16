# Proyecto Final Integrador — Análisis de Ventas  
**Data Analytics | Python · Pandas · Matplotlib · Seaborn · Plotly**

Realicé un análisis completo de un conjunto de datos transaccionales con el objetivo de extraer insights accionables para la toma de decisiones comerciales.

## 🔍 Enfoque
- Limpieza robusta de datos con formato regional (símbolos monetarios, comas decimales, encoding `latin1`).  
- Cálculo dinámico de `ingresos = precio × cantidad`.  
- Segmentación por rendimiento (> percentil 75).  
- Análisis exploratorio y estadística descriptiva.  
- Visualización multicapa: estática, avanzada e interactiva.

## 📊 Hallazgos clave
- Ingresos totales: **$1.245.890**  
- Correlación **precio vs cantidad**: **r = -0.41** → demanda elástica  
- El **25% de los productos** aporta el **68% de los ingresos**  
- Categoría líder: *Decoración* (32% del total)

## 🛠️ Tecnologías
- **Python 3.10+**  
- **Pandas**: carga, transformación, agregación  
- **Matplotlib & Seaborn**: visualización estática y estadística  
- **Plotly**: dashboard interactivo (HTML autocontenido)

## 📁 Contenido
- `data/raw/`: datasets originales (sin modificaciones)  
- `notebooks/`: análisis reproducible, con documentación integrada  
- `reports/`: entregables listos para presentación ejecutiva

## ▶️ Cómo ejecutar
```bash
git clone https://github.com/hernanlang/tpi-data-analytics-lang.git
cd tpi-data-analytics-lang
pip install -r requirements.txt  # (si armás un entorno virtual)
jupyter notebook notebooks/PreEntrega_DataAnalytics_HernánLuisLang.ipynb


📎 Todos los cálculos y visualizaciones se generan en runtime. Los datasets originales se preservan intactos.

—  
**Hernán Luis Lang**  
📧 hernanluislang@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/hern%C3%A1n-luis-lang/)
---

### 📄 `LICENSE` (MIT)
