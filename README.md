# 🥤 Predicción de Ventas de Bebidas con Regresión Polinómica 📈
![Bebidas](https://image.lexica.art/full_webp/0ee73d7c-8b80-408b-ac49-8bfa221934f1)

¡Bienvenido al repositorio de análisis predictivo para ventas de bebidas! Este proyecto utiliza **regresión polinómica** para modelar la relación entre variables de mercado y ventas de productos líquidos. Ideal para retail, manufactura y gestión de inventarios.

## 📋 Tabla de Contenidos
1. [Requisitos](#🔧-requisitos)
2. [Instalación](#⚙️-instalación)
3. [Uso](#🚀-uso)
4. [Estructura del Proyecto](#📂-estructura-del-proyecto)
5. [Datos](#📊-datos)
6. [Resultados](#📈-resultados)
7. [Contribución](#🤝-contribución)
8. [Licencia](#📜-licencia)
9. [Contacto](#📧-contacto)

---

## 🔧 Requisitos
- Python 3.8+
- Bibliotecas: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- (Opcional) Jupyter Notebook para visualización interactiva

## ⚙️ Instalación
```bash
# Clonar repositorio
git clone https://github.com/tuusuario/regresion-ventas-bebidas.git

# Instalar dependencias
pip install -r requirements.txt
```
## 📂 Estructura del Proyecto
├── data/
│   ├── ventas_bebidas.csv           # Dataset histórico de ventas  
│   └── preprocesamiento.py          # Limpieza de datos  
├── modelos/  
│   ├── entrenamiento_polinomico.py  # Script de regresión polinómica  
│   └── prediccion_ventas.py         # Generador de pronósticos  
├── notebooks/  
│   ├── analisis_exploratorio.ipynb  # EDA interactivo  
│   └── optimizacion_grados.ipynb    # Selección grado polinomio  
├── resultados/  
│   ├── modelo_final.pkl             # Modelo serializado  
│   ├── metricas_evaluacion.txt        
│   └── visualizaciones/             # Gráficos 3D y curvas   
└── requirements.txt  

## 📊 Datos

- Variables incluidas en el dataset:

- temperatura (°C promedio diario)

- precio (USD por unidad)

- gasto_publicidad (USD diarios en marketing)

- dia_semana (Lunes=1, Domingo=7)

- promocion (Indicador binario 0/1)

- Target: ventas_diarias (Unidades vendidas)

## 🤝 Contribución
- Sigue este flujo para contribuir:

- Reporta bugs o sugerencias en Issues

- Clona el repositorio

- Crea una nueva rama (git checkout -b mejora/modelo)

- Realiza tus modificaciones

- Ejecuta pruebas con pytest tests/

- Haz push y abre un Pull Request

  ¡Dame una estrella si te parecio bueno! ✨
