# Matemática en Julia UNED: Lógica, Conjuntos y Números

> **Intuition Compiled: Semantics and programming first, axioms and proofs later.**

Este repositorio no es un libro de matemáticas convencional. La enseñanza tradicional suele sepultar el significado de los conceptos bajo pesadas capas de notación y axiomas abstractos, asumiendo que la intuición aparecerá mágicamente tras memorizar teoremas. Aquí invertimos esa carga cognitiva. 

Defendemos un enfoque computacional y semántico: nadie entiende realmente un concepto matemático hasta que es capaz de programarlo y hacerlo funcionar. A través de `Julia`, utilizamos el código como un laboratorio epistemológico. Traducimos proposiciones abstractas en expresiones booleanas y estructuras iterativas tangibles. Si el código se ejecuta sin errores, significa que hemos comprendido la ontología subyacente del problema; nos hemos ensuciado las manos con la mecánica real de la matemática.

## 🧠 La Filosofía

**1. Ontología antes que sintaxis**
Antes de introducir un símbolo abstracto o una demostración compleja, desgranamos qué significa exactamente la entidad matemática con la que estamos tratando. Priorizamos el significado conceptual sobre la manipulación de símbolos vacíos.

**2. El código como validador de intuición**
Una demostración formal puede ser engañosa si se sigue mecánicamente, pero el compilador es implacable. Utilizamos bloques de código reales para modelar axiomas. Comprobamos la verdad matemática construyendo condiciones lógicas que fallarán inmediatamente si nuestra comprensión del axioma es defectuosa.

**3. Abstracción progresiva**
El rigor formal no se descarta, se pospone hasta que el cerebro esté preparado. Primero construimos la intuición visual y semántica; luego la modelamos mediante código ejecutable; finalmente, cuando el concepto es evidente por sí mismo, presentamos la formulación axiomática clásica como la consecuencia natural (y no como el punto de partida).

## 🚀 Dinámica de los Notebooks

Cada *notebook* está estructurado para romper la barrera entre la teoría pura y la experimentación aplicada. No encontrarás muros de texto inescrutables. En su lugar, el flujo de aprendizaje sigue esta arquitectura:

* **Contexto e Intuición:** Explicación coloquial y directa del problema geométrico, lógico o numérico a resolver.
* **Modelado Computacional:** Traducción del concepto a estructuras de control y evaluación de expresiones lógicas puras en `Julia`. 
* **Formalización:** Consolidación del conocimiento empírico en la notación axiomática estricta estándar.

## 📂 Arquitectura del Repositorio

El material se organiza en una progresión lógica, comenzando por los bloques de construcción más fundamentales del pensamiento racional hasta llegar a las estructuras algebraicas básicas.

```text
📁 notebooks/
   ├── 1. Logica.ipynb   # Tablas de verdad, compuertas y evaluación booleana
   ├── 2. Conjuntos.ipynb         # 
   ├── 3. Relaciones.ipynb             
   ├── 4. Aplicaciones.ipynb    
   └── ...
📁 src/                               # Core functions & types dependencies (Julia)
📁 assets/                            # Static visualizations and dependency graphs

```

## 🧰 Stack Tecnológico

* **Language:** Julia (elegido por su cercanía a la sintaxis matemática pura y su alto rendimiento computacional).
* **Environment:** Jupyter Notebooks interactivos vía `IJulia`.

## 📜 Licencia

Este proyecto se distribuye bajo la licencia **MIT**. Eres libre de bifurcar este repositorio, romper el código, reescribir los *loops* y descubrir por ti mismo por qué la matemática tiene sentido cuando la obligas a compilar.
