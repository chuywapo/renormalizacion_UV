# Renormalización Automatizada a 1-Loop: QED y Sector Oscuro (BSM)

Este repositorio contiene el "Script Maestro" desarrollado en Wolfram Mathematica y FeynCalc para la automatización de cálculos de Teoría Cuántica de Campos a nivel de un bucle (1-loop). 

Este trabajo forma parte de la investigación de tesis para la demostración analítica de la Invariancia de Gauge, la extracción de contra-términos en el esquema de Sustracción Mínima (MS) y la evaluación de correcciones radiativas introducidas por un mediador masivo (Fotón Oscuro).

## 🚀 Características Principales

* **Regularización Dimensional Rigurosa:** Implementación del esquema de 't Hooft-Veltman (BMHV) para el manejo consistente del álgebra de Dirac en $D = 4 - 2\epsilon$ dimensiones.
* **Módulo de Auditoría de Gauge:** Comprobación analítica automatizada de la Identidad de Ward-Takahashi ($\delta Z_1 = \delta Z_2$) y la independencia del calibrado covariante ($R_\xi$).
* **Física del Modelo Estándar (QED):** * Autoenergía del electrón ($\Sigma$).
  * Polarización del vacío ($\Pi^{\mu\nu}$).
  * Corrección de vértice ($\Lambda^\mu$).
* **Física BSM (Sector Oscuro):** Evaluación de la autoenergía del fermión bajo la influencia de un fotón oscuro masivo ($A'$) introducido por mezcla cinética.

## ⚙️ Requisitos y Dependencias

Para ejecutar los notebooks de este repositorio, es necesario contar con:
* **Wolfram Mathematica** (Versión 12.0 o superior recomendada).
* **FeynCalc** (Versión 10.0+). Para instalar FeynCalc en tu núcleo de Mathematica, ejecuta:
  ```mathematica
  Import["[https://raw.githubusercontent.com/FeynCalc/feyncalc/master/install.m](https://raw.githubusercontent.com/FeynCalc/feyncalc/master/install.m)"]
  InstallFeynCalc[]
