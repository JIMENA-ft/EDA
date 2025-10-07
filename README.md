# EDA
# 🚀 Optimización del Proceso Operativo mediante Análisis de Correlación  **Objetivo:** Identificar las **variables más influyentes** en la métrica clave de **éxito del proceso (`computed_success`)** para guiar esfuerzos de optimización y el desarrollo de un modelo predictivo.

### 💡 Conclusiones sobre la Influencia de Variables

El Análisis Exploratorio de Datos (EDA) se centró en la correlación lineal de las variables de entrada con la variable objetivo **`computed_success`**.

**Factores Críticos para el Éxito (Correlación > 0.2):**
Las variables más relevantes están intrínsecamente ligadas a las **dimensiones de los objetos** y la **estrategia de manipulación**.

| Variable | Correlación con `computed_success` | Implicación Operativa |
| :--- | :--- | :--- |
| **`match_output.stowStrategy.rigidInsertionCost`** | **0.268** | Costo asociado a una inserción "rígida" es el predictor más fuerte. |
| `match_risk_features.dloL2` | 0.210 | Dimensiones de los objetos. |
| `match_risk_features.tlo` | 0.207 | Dimensiones totales o límites del objeto. |

**Conclusión Operacional:**
El éxito del proceso está fuertemente relacionado con las **características dimensionales iniciales de los objetos** y el **algoritmo/estrategia de inserción**.

### 🛠️ Tecnologías y Contenido

* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, (Otras librerías de visualización o modelado que usaste).
* **Notebook Principal:** `EDA_Correlacion.ipynb` (Contiene la limpieza de datos y el cálculo de correlación).
