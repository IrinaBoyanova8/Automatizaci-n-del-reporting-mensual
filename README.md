# Automatización del reporting mensual de gastos

Este proyecto en Python automatiza la actualización mensual del archivo de reporting financiero, a partir de un archivo descargado del sistema contable.

## 🔧 ¿Qué hace este notebook?

- Importa automáticamente el archivo mensual descargado del sistema contable.
- Elimina columnas innecesarias y columnas con espacios en blanco para evitar errores.
- Guarda una versión limpia en una ruta específica.
- Integra los datos procesados en una hoja concreta de un archivo de Excel de reporting.
- Sustituye el proceso manual de copiar y pegar por un flujo automatizado y reproducible.

## 📁 Estructura

- `Automatización del reporting mensual.py`: Python.

## 💡 Motivación

Este pequeño proyecto surgió de la necesidad de ahorrar tiempo y evitar errores al realizar el reporting mensual de gastos. Antes, el proceso consistía en copiar y pegar manualmente los datos. Ahora, todo se realiza con un solo clic.

## 🛠️ Tecnologías

- Python
- pandas
- openpyxl

## 🚀 Cómo usarlo

1. Coloca el archivo contable descargado en la carpeta de ruta que quieras llamar desde Python.
2. Ejecuta el notebook ajustándolo a tus necesidades, es decir, será necesario que introduzcas las rutas de tus archivos, que actualices o elimines líneas del código en función de las necesidades de tu archivo. Por ejemplo, en mi caso, he eliminado varias columnas y filas ya que estaban en blanco o la información no era necesaria. 
3. El archivo de reporting se actualizará automáticamente.

## 📌 Nota

Este proyecto es adaptable a cualquier otro flujo de reporting en Excel basado en archivos descargados regularmente.
