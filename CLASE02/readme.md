# Clase 2: IA Generativa
---
## ¿Qué es la Inteligencia Artificial?

La Inteligencia Artificial opera mediante algoritmos que procesan grandes volúmenes de datos a través de un **procedimiento estocástico avanzado en un espacio vectorial de alta dimensión**, generando así resultados probabilísticos.

### Proceso de Funcionamiento:

1. **Tokenización (Discretización del Lenguaje):**
   * Proceso de muestreo y cuantización del texto.
   * *Nota:* Archivos como Microsoft Word consumen más tokens debido a los códigos de formato ocultos que contienen. El formato **Markdown** es el que menor consumo de tokens requiere.

2. **Embeddings (Espacio Vectorial):**
   * Cada token se convierte en un vector denso.
   * La arquitectura **Transformer** no lee el texto de forma secuencial, sino que procesa y relaciona todo el contexto de manera conjunta.

3. **Generación (Proceso Estocástico):**
   * Cálculo de probabilidades para predecir el token siguiente.
   * **Temperatura ($T$):** Al aumentar la temperatura en el cálculo, la búsqueda se expande a un rango mayor de posibilidades, permitiendo respuestas más creativas o variadas. La IA asigna probabilidades, genera un ranking y selecciona resultados bajo esa distribución.

---

## ¿Cómo utilizar la IA Generativa?

* **Ponderación del Prompt:** La precisión y estructura de la instrucción condicionan la calidad de la respuesta.
* **Tono y Lenguaje:** Evitar muletillas como *"Por favor"* si se buscan respuestas estrictamente técnicas y directas.
* **Criterio Humano:** La decisión final y la validación del contenido siguen siendo responsabilidad del usuario.

---

## Estructura de un Prompt Eficiente

### 1. Para Texto e Instrucciones:
* **Rol esperado:** Desde qué perspectiva o perfil debe responder la herramienta.
* **Objetivo:** Declaración clara del propósito de la consulta.
* **Datos disponibles:** Información exacta, especificaciones y contexto técnico necesario.
* **Restricciones:** Límites, reglas o condiciones del alcance.
* **Producto a obtener:** Resultado concreto esperado.
* **Formato de salida:** Forma de presentación (ejemplos, listas, tablas, referencias).

### 2. Para Generación de Imágenes:
* **Objetivo o Escena:** Sujeto principal de la imagen.
* **Acción o Situación:** Qué está sucediendo en la imagen.
* **Contexto o Entorno:** Fondo, iluminación o lugar.
* **Atributos Visuales:** Detalles, colores, texturas.
* **Estilo Visual:** Fotográfico, ilustración 3D, óleo, etc.
* **Composición:** Ángulo de cámara, encuadre, plano.

---
 
