# Fórmula 1 — Predicción de Estrategia de Pit Stop y Rendimiento por Vuelta (ML)

> 🚧 **En construcción:** el código y los materiales de este proyecto se están publicando desde la carpeta de trabajo original. La estructura descrita abajo es la del proyecto completo.


Proyecto de **machine learning** aplicado a datos de Fórmula 1 para predecir la **estrategia de pit stop** y el **rendimiento por vuelta**. Un proyecto que nació de mi gusto personal por la F1 y que uso para practicar modelado predictivo sobre datos de series temporales y telemetría.

## El problema

Durante una carrera, la estrategia de paradas en boxes (cuándo parar, qué compuesto de neumático usar) es determinante en el resultado. La pregunta: *¿podemos predecir la estrategia y el rendimiento por vuelta a partir de datos históricos de carrera?*

## Enfoque

1. **Datos** — Telemetría y resultados históricos de F1 (vueltas, compuestos de neumático, tiempos, posiciones).
2. **Preparación** — Limpieza, ingeniería de características (degradación de neumático, ritmo por stint, condiciones).
3. **Modelado** — Modelos supervisados para (a) predecir la ventana de pit stop y (b) estimar el tiempo/rendimiento por vuelta.
4. **Evaluación** — Métricas de desempeño y análisis de errores.

## Estructura del repositorio

```
f1-ml-pitstop/
├── notebooks/
│   └── ml_pitstop_f1.ipynb   # Análisis y modelado completo
├── requirements.txt
└── README.md
```

## Tecnologías

`Python` · `pandas` · `scikit-learn` · `FastF1` (datos de telemetría) · `matplotlib`

## Datos

Datos **públicos** de F1 obtenidos con la librería `FastF1`. No requiere credenciales.

---
*Autor: Manuel Alejandro González Gallego.*

<!-- COMO_COMPLETAR: arrastra aquí tu notebook de Colab "ML_Predicción de estrategia de pit stop y rendimiento por vuelta en Fórmula 1" (descárgalo como .ipynb) dentro de notebooks/. Antes de subir, en Colab usa Edición > Borrar todas las salidas para que pese menos. -->
