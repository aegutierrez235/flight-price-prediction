# ✈️ Predicción de Precios de Vuelos: Business vs Economy

Este proyecto aplica técnicas de **Machine Learning** para predecir el costo de boletos de avión, enfrentando el reto de manejar datasets con distribuciones de precios altamente divergentes debido a la diferencia entre clases sociales de viaje.

---

## 🚀 Aspectos Destacados del Proyecto

* **🛠️ Automatización de ETL:** Diseño de una función de limpieza modular que procesa datasets de distintas clases de vuelo, garantizando la integridad de los datos y eliminando ruidos como caracteres especiales (`\n`, `\t`) y formatos de moneda inconsistentes.
* **🧬 Ingeniería de Variables (Feature Engineering):** Transformación de duraciones de texto a formato numérico/temporal.
    * Extracción de horarios de salida y llegada para capturar la estacionalidad diaria.
* **🤖 Modelado Avanzado:** Comparativa entre modelos de Regresión Lineal, Ridge y **Random Forest Regressor**, optimizando hiperparámetros para reducir el error cuadrático medio.

---

## 📊 Resultados y Conclusiones

> [!IMPORTANT]
> **El modelo Random Forest fue el ganador**, logrando identificar con éxito la brecha de magnitud entre la clase *Business* y *Economy*. Esto permite predecir fluctuaciones estacionales con un margen de error mínimo a pesar de la disparidad de precios.

| Métrica | Resultado |
| :--- | :--- |
| **Modelo Seleccionado** | Random Forest Regressor |
| **Capacidad de Segmentación** | Alta (Detección de nichos Business/Economy) |
| **Estado del Proyecto** | MVP Finalizado / Listo para Producción |

---

## 🛠️ Stack Tecnológico

| Herramienta | Uso |
| :--- | :--- |
| **Python** | Lenguaje principal de análisis |
| **Pandas / Numpy** | Manipulación y limpieza de datos |
| **Scikit-Learn** | Entrenamiento y evaluación de modelos ML |
| **Seaborn / Matplotlib** | Visualización de correlaciones y resultados |
| **Anaconda** | Gestión de entornos y reproducibilidad |

---

## 🔮 Futuras Implementaciones
* [ ] Despliegue de una **API** para predicciones en tiempo real.
* [ ] Creación de una interfaz web con **Streamlit** para consultas de usuario.
* [ ] Integración de variables de equipaje y demanda histórica.

---
**Desarrollado por [aegutierrez235](https://github.com/aegutierrez235)**
