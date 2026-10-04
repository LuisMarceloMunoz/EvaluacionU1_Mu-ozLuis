# EvaluacionU1_Mu-ozLuis
Evaluacion N1 Herramientas computacionales 2 

Análisis de Viga Simplemente Apoyada

Este repositorio contiene el análisis carga-deflexión de una viga de sección rectangular, contrastando datos empíricos con la teoría de Euler-Bernoulli.

## Justificación de la Estructura del Repositorio
Para garantizar la reproducibilidad y trazabilidad, el proyecto se organizó en 4 directorios lógicos:
1. **Datos de origen:** Contiene los archivos base inmutables (`datos_viga (1).csv`, `parametros_viga.xlsx`, `esquema_viga.png`, `README_datos (1)`, `Checklist_entrega_Hito1 (1)`). No sufren ninguna alteración.
2. **Procesos:** Contiene la hoja de cálculo (`analisis_viga.xlsx`) con las transformaciones, conversiones de unidades y cálculos de la deflexión teórica y diferencias relativas.
3. **Resultados:** Contiene los entregables finales (`main.tex`, PDF compilado y el gráfico `carga_deflexion.png`).
4. **Documentacion:** Almacena la declaración de uso de IA).

## Supuestos y Limitaciones
- **Unidades:** Se asume que las unidades declaradas en los archivos base (kN para carga, mm para deflexión, GPa para módulo elástico) son correctas y consistentes con la recolección de los datos sintéticos.
- **Material y Geometría:** Se asume que el material es homogéneo e isotrópico, y que la sección transversal se mantiene constante a lo largo de los 4 metros de luz.
- **Limitación del Modelo:** El modelo ideal asume apoyos perfectos sin fricción ni deformación local. Cualquier diferencia empírica a cargas bajas (como el error del 4% a 5 kN) se asume como un límite de precisión instrumental o un acomodo inicial de los apoyos reales que la ecuación no contempla.
