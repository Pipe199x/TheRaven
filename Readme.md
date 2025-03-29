# Proyecto: Análisis del Poema "El Cuervo" de Edgar Allan Poe

## Descripción
Este proyecto realiza la extracción y análisis de texto del poema "El Cuervo" de Edgar Allan Poe, utilizando Selenium para la obtención del contenido y librerías de procesamiento de lenguaje natural para su análisis.

## Pasos para Configurar el Ambiente

1. **Crear un ambiente virtual (opcional, pero recomendado):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # En macOS/Linux
   venv\Scripts\activate     # En Windows
   ```

2. **Instalar los requerimientos:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Descargar el modelo de idioma en spaCy:**
   ```sh
   python -m spacy download es_core_news_sm
   ```

4. **Instalar el controlador de Chromium (si es necesario en Linux):**
   ```sh
   apt install -y chromium-chromedriver
   ```

## Archivos en el Proyecto
- `requirements.txt`: Lista de dependencias necesarias.
- `Edgar_Allan_Poe_El_Cuervo.ipynb`: Notebook con el código de extracción y análisis.
- `TheRaven.jpg`: Imagen relacionada con el poema.
- `TheRavenWordCloud.png`: Nube de palabras generada a partir del poema.

## Uso
Ejecuta el notebook en un entorno de Jupyter para procesar y analizar el poema. Puedes visualizar la nube de palabras generada y otros análisis realizados.

## Contacto
Para dudas o mejoras, contáctame o revisa la documentación en el notebook.

---

¡Disfruta explorando el lenguaje del cuervo! 🦅📚

