
# ACE Writer Mini – Matías

Esta es una versión simplificada de ACE Writer Mini diseñada especialmente para Matías. Permite generar capítulos técnicos desde una tabla de referencias, utilizando inteligencia artificial (GPT-4), y exportarlos directamente con formato profesional en Word.

---

## 🧩 ¿Qué permite hacer esta app?

1. Cargar una tabla `.csv` con referencias validadas.
2. Escribir el **capítulo** y **subtema**.
3. Ingresar la clave de OpenAI (API Key).
4. Generar un texto profesional de hasta 1.500 palabras.
5. Descargar el capítulo en formato `.docx` con plantilla aplicada.

---

## 🛠 Cómo usarlo

1. Ingresá en https://share.streamlit.io (con tu usuario)
2. Seleccioná este repositorio y lanzá la app
3. En la barra lateral, ingresá tu `API Key de OpenAI`
4. Cargá el archivo `.csv` de referencias (ej: `Tabla_Referencias.csv`)
5. Escribí el título del capítulo y el subtítulo del subtema
6. Hacé clic en “🧾 Generar redacción del subtema”
7. Revisá el texto, cantidad de palabras y citas detectadas
8. Descargá el `.docx` final con un solo clic

---

## 🧠 Requisitos

Este repo incluye un archivo `requirements.txt` con:

- `streamlit`
- `openai`
- `pandas`
- `python-docx`

No hace falta instalar nada si usás Streamlit Cloud.

---

## 🧑‍💻 Desarrollado para ACE por Vity & GPT-4
