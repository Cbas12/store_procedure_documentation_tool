# Herramienta de Documentación de Store Procedures SQL 🚀

[English](https://github.com/Cbas12/store_procedure_documentation_tool)

Una solución automatizada diseñada para extraer, analizar y documentar Store Procedures de SQL Server utilizando Python e IA Generativa.

## 📌 Descripción del Proyecto
En entornos de datos complejos, mantener la documentación de la base de datos actualizada es una lucha constante. Esta herramienta automatiza el proceso recogiendo cualquier tipo y número de archivos de Store Procedures y generando documentación estructurada.

Es particularmente efectiva para sistemas heredados, proyectos de consolidación financiera y entornos con cientos de objetos que requieren explicaciones claras y legibles de la lógica.

## 🚀 Características Principales
- **Análisis Potenciado por IA:** Utiliza Gemini AI para interpretar lógica SQL compleja y explicarla en lenguaje sencillo.
- **Salida Estructurada:** Genera documentación clara y simple incluyendo parámetros de entrada, flujo de lógica y dependencias.
- **Alta Escalabilidad:** Diseñada para procesar por lotes cientos de archivos en minutos.
- **Integración con Jupyter:** Fácil de ejecutar, probar y modificar a través de una interfaz de notebook.

## 💰 Eficiencia de Costo
Esta herramienta está diseñada para procesamiento de alto volumen a un costo mínimo. Durante el desarrollo y las pruebas:
- **Escalabilidad:** Documentó exitosamente **más de 500 Store Procedures**.
- **Costo Total:** Menos de **$3.00 USD** (usando la API de Gemini).
- **Valor:** Documentación de alta velocidad a una fracción del costo del trabajo manual o herramientas empresariales.

## 🛠️ Pila Tecnológica
- **Lenguaje:** Python
- **Orquestación de IA:** API de Google Gemini
- **Manejo de Datos:** Pandas

## 📋 Prerrequisitos
Antes de ejecutar el notebook, asegúrate de tener:
- Python 3.10+
- Una clave de API de Google AI (Gemini).

## ⚙️ Configuración
1. **Clona el repositorio:**
    git clone https://github.com/Cbas12/store_procedure_documentation_tool.git

2. **Configura Credenciales:**
    - Usa el archivo gemini.txt para escribir tu propia clave de API de Gemini. Simplemente copia el texto dentro.

## 📖 Uso
1. Abre *store_procedure_documentation_tool.ipynb* en VS Code o Jupyter.
2. Asegúrate de haber agregado las rutas de entrada y salida:
    - *sp_location:* La ruta de la carpeta que contiene tus archivos de Store Procedures en .sql
    - *docutentation_output_location:* La carpeta donde deseas guardar los archivos de documentación.
3. Antes de ejecutar todas las celdas, se sugiere que verifiques la última sección del archivo de Python *"CHECK FOR ERRORS IN THE STORE PROCEDURE FILES"* para asegurar que ningún archivo tenga errores que puedan impedir la documentación.
4. También se sugiere que, al principio de la sección *"PROCESS THE FILES"* reduzcas el número de archivos procesados al inicio, solo para asegurar que todo vaya de acuerdo a tus expectativas.
4. Ejecuta todas las celdas. La herramienta procesará cada archivo y generará una explicación detallada en lenguaje natural para cada Procedimiento Almacenado.

## 📄 Licencia
Este proyecto es de código abierto. Siéntete libre de clonarlo, descargarlo y adaptarlo a tus propios flujos de trabajo de datos.