# 📄 Resumen y Traducción de Contenido con Gemini y LangChain

Este proyecto implementa diferentes enfoques para **extraer, resumir y traducir texto** desde varias fuentes utilizando la API de **Gemini** de Google AI junto con **LangChain**.  

## 🚀 Funcionalidades principales

* **Extracción de contenido web**  
  - Permite ingresar un enlace y obtener su texto.  
  - Resume automáticamente el contenido con el modelo Gemini.  

* **Procesamiento de archivos PDF en Google Colab**  
  - Subida de documentos PDF directamente desde el entorno Colab.  
  - Extracción de texto mediante LangChain.  
  - Generación de resúmenes usando Gemini.  
  - Posibilidad de traducir el resultado a diferentes idiomas con `deep-translator`.  

* **Integración avanzada con Vertex AI**  
  - Autenticación y configuración en Google Cloud.  
  - Uso del modelo **Gemini 1.5 Pro** desde Vertex AI.  
  - Detección automática del idioma del texto con `langdetect`.  
  - Traducción de resúmenes a español cuando el documento está en otro idioma.  

## 📦 Tecnologías utilizadas

- Python
- LangChain
- Google Generative AI (Gemini)
- Google Colab 
- BeautifulSoup4 
- Deep Translator 
- langdetect
- PyPDFLoader

## 🎯 En resumen

El código permite:  

- Resumir **páginas web** con Gemini.  
- Subir y resumir **archivos PDF** en Google Colab.  
- Detectar el idioma del documento automáticamente.  
- Traducir resúmenes a **español** (u otros idiomas según el caso).  
- Integrar Gemini tanto vía API directa como a través de **Vertex AI**.  
