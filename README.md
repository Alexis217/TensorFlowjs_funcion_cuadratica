# 📈 Predicción con TensorFlow.js – `y = 2x² - 3x + 1`

Este es un proyecto interactivo que utiliza [TensorFlow.js](https://www.tensorflow.org/js) para crear un modelo de red neuronal simple que aprende a predecir el valor de la función cuadrática:

> 🧮 `y = 2x² - 3x + 1`

## 🚀 Características

- 🔧 Entrenamiento en el navegador
- 🔢 Entrada interactiva para valores de `x`
- 📊 Comparación entre valor predicho y valor real
- 🧠 Basado en redes neuronales con `TensorFlow.js`
- 🖥️ Interfaz amigable y minimalista en HTML/CSS

## 🛠️ Tecnologías Usadas

- 🌐 HTML5 + CSS3
- 📦 [TensorFlow.js](https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@latest)
- 💡 JavaScript puro

## ⚙️ Cómo usar

1. 📥 Clona este repositorio o descarga los archivos:

   ```bash
   git clone https://github.com/Alexis217/TensorFlowjs_funcion_cuadratica.git
   ```

2. 🌍 Abre el archivo `index.html` en tu navegador.

3. 🧪 Haz clic en **"Entrenar Modelo"** para comenzar el entrenamiento (esto tomará unos segundos).

4. 🔢 Ingresa un valor de `x` y presiona **"Predecir"** para ver los resultados:

   - Resultado de la red neuronal
   - Valor matemático real
   - Diferencia entre ambos

## 📷 Ejemplo de Uso

```
🧠 Entrenamiento iniciado...
✅ Modelo entrenado
🔍 x = 3
📈 Resultado predicho: 9.5500
✅ Valor real: 10.0000
➖ Diferencia: 0.4500
⚠️ Tenga en cuenta que el modelo hara diferentes predicciones cada vez que se entrene.
🔄 para volver a entrenarlo debera recargar la página
```

## 🧠 Sobre el modelo

- 🔹 Modelo secuencial con una capa oculta `Dense (relu)`
- 🔹 Función de pérdida: `meanSquaredError`
- 🔹 Optimizador: `adam`
- 🔹 Entrenado con 21 puntos de la función cuadrática

---
