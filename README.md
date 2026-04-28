# Proyecto: Clon de YouTube - Comparativa de Desarrollo (HTML Puro)

Este repositorio contiene dos versiones de una estructura básica para un clon de la interfaz de YouTube. El objetivo principal de este ejercicio fue experimentar con el maquetado utilizando **exclusivamente HTML y tablas**, sin hacer uso de CSS, para comprender cómo funcionaba la estructura web antes de los estándares modernos.

## 📁 Estructura del Proyecto

El repositorio se divide en dos enfoques de desarrollo para comparar resultados:

### 1. Desarrollo Manual ("Sin IA")
* **Archivo:** `index_sin_ia.html`
* **Descripción:** Esta versión fue creada de forma iterativa y manual. El objetivo fue resolver los problemas de posicionamiento, filas (`rowspan`) y columnas (`colspan`) a través de la lógica pura y prueba-error.
* **Aprendizaje:** Ayudó a entender profundamente cómo los navegadores renderizan tablas anidadas y la importancia de la jerarquía de las etiquetas.

### 2. Desarrollo Asistido ("Con IA")
* **Archivo:** `index_con_ia.html`
* **Descripción:** Esta versión fue optimizada con la asistencia de una Inteligencia Artificial. Se buscó mejorar la estructura del código, la limpieza de las etiquetas y la eficiencia al agrupar los elementos en una tabla maestra más coherente.
* **Aprendizaje:** Demostró cómo la IA puede sugerir estructuras más sólidas (como el uso de una tabla contenedora general) que reducen la redundancia y mejoran la legibilidad del código.

## 🛠️ Tecnologías utilizadas
* **HTML:** Únicamente etiquetas básicas.
* **Tablas (`<table>`):** Usadas como el único método de posicionamiento.
* **Atributos obsoletos:** Se utilizaron atributos como `bgcolor`, `width`, `height` y `align` (con fines estrictamente educativos).

## 💡 Conclusión
Este experimento destaca la diferencia entre "hacer que funcione" (desarrollo manual) y "hacer que sea eficiente y mantenible" (desarrollo asistido). Aunque ambos enfoques logran una interfaz visualmente similar usando la misma tecnología (HTML básico), el enfoque asistido permite una estructura más robusta y menos propensa a errores de anidación.

---
*Creado como ejercicio de aprendizaje sobre maquetación web clásica.*
