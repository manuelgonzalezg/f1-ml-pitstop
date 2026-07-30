# Fórmula 1 — Predicción de Estrategia de Pit Stop y Rendimiento por Vuelta (ML)

Proyecto de **machine learning** aplicado a datos de Fórmula 1 para predecir la **estrategia de pit stop** y el **rendimiento por vuelta**. Nació de mi gusto personal por la F1 y lo uso para practicar modelado predictivo sobre datos de telemetría y series temporales.

## El problema

Durante una carrera, la estrategia de paradas en boxes (cuándo parar, qué compuesto de neumático usar) es determinante en el resultado. La pregunta: *¿podemos predecir la estrategia y el rendimiento por vuelta a partir de datos históricos de carrera?*

## Enfoque

1. **Datos** — Telemetría y resultados históricos de F1 (vueltas, compuestos de neumático, tiempos, posiciones).
2. **Preparación** — Limpieza e ingeniería de características (degradación de neumático, ritmo por stint, condiciones).
3. **Modelado** — Modelos supervisados para estimar la ventana de pit stop y el rendimiento por vuelta.
4. **Evaluación** — Métricas de desempeño y análisis de errores.

## Estructura del repositorio

```
f1-ml-pitstop/
├── notebook de análisis y modelado (.ipynb)   # Todo el flujo: datos, features, modelos
├── requirements.txt
└── README.md
```

## Tecnologías

`Python` · `pandas` · `scikit-learn` · `FastF1` (telemetría) · `matplotlib`

## Datos

Datos **públicos** de F1 obtenidos con la librería `FastF1`. No requiere credenciales.

---
*Autor: Manuel Alejandro González Gallego.*
