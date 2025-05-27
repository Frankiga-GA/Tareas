# 📷 Clasificador de Imágenes con MobileNet

Este es un proyecto web sencillo que utiliza las librerías `ml5.js` y `p5.js` para clasificar imágenes de animales usando el modelo preentrenado **MobileNet**. Al hacer clic en una miniatura, la imagen seleccionada se muestra en un canvas y se clasifica mostrando su predicción y nivel de confianza.

---

## 🧩 Funcionalidades Principales

- ✅ Selección de imágenes mediante miniaturas.
- 🖼️ Carga de imagen en un canvas interactivo.
- 🔍 Clasificación con el modelo **MobileNet**.
- 📊 Muestra del resultado y porcentaje de confianza.
- 🎨 Barra de progreso visual para la confianza.

---

## 🛠️ Tecnologías Usadas

- **HTML5**: Estructura del sitio web.
- **CSS3**: Estilos visuales (responsive design).
- **JavaScript**: Lógica del cliente.
- **p5.js**: Para manejo de canvas y carga de imágenes.
- **ml5.js**: Para usar modelos de aprendizaje automático en el navegador.

---

> ⚠️ Asegúrate de tener las imágenes en la carpeta correcta (`/img/`) para que no fallen al cargar.

---

## ▶️ Cómo Ejecutar el Proyecto

1. **Clona o descarga este proyecto** (si está en GitHub) o simplemente guarda el archivo HTML localmente.
2. **Coloca tus imágenes** en la carpeta `/img/`.
3. **Abre el archivo `index.html`** desde un servidor local o directamente en el navegador (algunos navegadores bloquean carga de imágenes locales sin servidor).
4. ¡Haz clic en una miniatura y verás la predicción y nivel de confianza!

> 💡 Recomendación: Usa un servidor local como [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer ) en VS Code si las imágenes no se cargan correctamente.

---

## 📈 Ejemplo de Salida

Cuando haces clic en una miniatura:

- Se muestra la imagen completa en el canvas.
- En la parte inferior aparece:
  - La **etiqueta** identificada por MobileNet (ej: `"leopardo"`).
  - Un porcentaje que indica el **nivel de confianza** del modelo.
  - Una barra de progreso que refleja visualmente esa confianza.

---

## 📌 Notas Importantes

- El modelo usado es **MobileNet**, entrenado con miles de imágenes, pero no es infalible. Puede haber errores en la clasificación.
- Si ves `0%` o no hay resultados, puede deberse a:
  - Ruta incorrecta de la imagen.
  - Modelo aún no cargado completamente.
  - Objeto poco claro o no reconocido por MobileNet.

---

## 📝 Licencia

Este proyecto está bajo la **licencia MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.
