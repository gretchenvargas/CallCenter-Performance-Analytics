# Análisis de Eficiencia de Operadores - CallMeMaybe 📞📊

## 📝 Descripción del Proyecto
Este proyecto fue desarrollado para **CallMeMaybe**, un proveedor de telefonía virtual. El objetivo principal es proporcionar a los supervisores una herramienta analítica para identificar a los operadores de call center con bajo desempeño.

Un operador se clasifica como **ineficaz** si presenta:
* Un alto volumen de llamadas entrantes perdidas.
* Tiempos de espera excesivos para los clientes.
* Un bajo número de llamadas salientes realizadas (en perfiles donde esta es su función principal).

## 🚀 Estructura del Repositorio
* `Proyecto_Final.ipynb`: Notebook de Jupyter con el análisis completo (EDA, procesamiento y conclusiones).
* `telecom_dataset_us.csv`: Datos de las llamadas (fechas, duración, dirección, etc.).
* `telecom_clients_us.csv`: Información sobre las tarifas y clientes.

## 🛠️ Metodología
El análisis sigue los siguientes pasos:
1.  **Preprocesamiento de datos:** Limpieza de duplicados, gestión de valores ausentes (especialmente en IDs de operadores) y conversión de tipos de datos.
2.  **Análisis Exploratorio (EDA):** Identificación de patrones de comportamiento en las llamadas entrantes y salientes.
3.  **Definición de Métricas:** Establecimiento de umbrales para medir la ineficacia (tiempos de espera vs. efectividad).
4.  **Segmentación:** Clasificación de operadores en perfiles específicos (ej. Perfeccionistas vs. Sobrecargados).

## 📈 Resultados Clave
* Se identificaron **273 operadores críticos** que requieren intervención.
* La tasa promedio de llamadas perdidas detectada es del **31.55%**.
* **Segmentación de perfiles:**
    * **Tipo A (Lentos/Perfeccionistas):** Bajo tiempo de respuesta pero alta resolución.
    * **Tipo B (Impacientes/Sobrecargados):** Alta tasa de abandono de llamadas por parte del cliente.

## 💻 Tecnologías Utilizadas
* **Python 3.x**
* **Pandas & Numpy:** Manipulación y limpieza de datos.
* **Matplotlib & Seaborn:** Visualización de datos y diagramas estadísticos.
* **Jupyter Notebook:** Entorno de desarrollo.

## 💡 Recomendaciones
Basado en los hallazgos, el proyecto sugiere:
* **Capacitación técnica:** Para los operadores con altos tiempos de espera.
* **Revisión de carga de trabajo:** Para aquellos con alta tasa de llamadas perdidas.
* **Monitoreo de KPIs:** Implementación de un dashboard basado en los resultados de este análisis.

---
Desarrollado como proyecto final de análisis de datos.
