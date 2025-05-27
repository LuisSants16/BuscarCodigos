# 🔍 Buscador de Códigos en Archivos Excel y Word

Este proyecto permite buscar códigos o descripciones dentro de múltiples archivos Excel (`.xlsx`, `.xls`) y Word (`.docx`) directamente desde el navegador. Ideal para trabajos donde se manejan grandes volúmenes de documentos y se necesita una búsqueda rápida y efectiva.

## 🚀 Características

- 📁 Carga múltiple de archivos desde una carpeta (`webkitdirectory`)
- 🔍 Búsqueda de códigos específicos en archivos Excel
- 📄 Búsqueda por descripción también disponible
- 📊 Soporte para hojas de cálculo con múltiples hojas
- 📃 Compatibilidad con archivos Word (`.docx`)
- 🔊 Reproduce un sonido cuando la búsqueda finaliza (requiere archivo de audio `terminado.mp3`)
- 🧹 Botón para limpiar los resultados
- ⚠️ Alertas cuando los campos están vacíos

## 📂 Estructura del Proyecto

📁 tu-proyecto/
├── buscar.html
├── terminado.mp3 # (debes agregar este archivo tú mismo)
└── README.md

## 🧠 Cómo usar

1. Abre el archivo `buscar.html` en tu navegador.
2. Selecciona una carpeta que contenga archivos `.xlsx`, `.xls`, o `.docx`.
3. Ingresa un **código** o una **descripción** para buscar.
4. Presiona el botón correspondiente.
5. Al finalizar la búsqueda, se reproducirá un sonido indicando que ha terminado.

## 🛠 Requisitos

No se necesita instalación. Todo se ejecuta directamente en el navegador. Sin embargo, asegúrate de tener acceso a internet porque se usan librerías CDN:

- `xlsx` (para procesar Excel)
- `mammoth.js` (para procesar Word)

## 📦 Librerías utilizadas

- [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs)
- [Mammoth.js](https://github.com/mwilliamson/mammoth.js)

## 🔊 Nota sobre el sonido

Debes agregar manualmente un archivo de sonido llamado `terminado.mp3` en el mismo directorio. Puedes usar cualquier sonido corto que desees, como una notificación o alerta. Por ejemplo, puedes descargar uno desde [https://mixkit.co/free-sound-effects/](https://mixkit.co/free-sound-effects/)

## 📃 Licencia

Este proyecto es de uso libre para fines personales o educativos. Si lo reutilizas o mejoras, se agradece la mención al autor original.
