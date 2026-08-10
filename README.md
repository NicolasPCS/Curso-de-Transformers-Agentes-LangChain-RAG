# Transformers, uso de agentes, LangChain y RAG

## Departamento de Ciencias de la Computación - Universidad de Chile

Repositorio del curso de Transformers, uso de agentes, LangChain y RAG del DCC - U Chile.

Este es el repositorio oficial del curso: **10 clases de 3 horas**, organizadas en **3 módulos**. Cada módulo tiene una parte teórica y una parte práctica (de acuerdo con la estrategia de cada docente).

> **Cómo abrir los notebooks:** haz clic en el badge ![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg). El notebook se abre en modo lectura/playground; para guardar tus cambios usa *Archivo → Guardar una copia en Drive*. Para las clases prácticas se recomienda activar la GPU en *Entorno de ejecución → Cambiar tipo de entorno → GPU*.
>
> **Leyenda:** ✅ disponible · 🚧 en construcción. Los badges 🚧 quedarán activos cuando se suba el notebook correspondiente a la rama `main`.

---

## Estructura del curso

### Clase 1 — Introducción a los Transformers [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase01_introduccion.ipynb?hl=es) ✅

Introducción a la arquitectura **Transformer**, sus componentes principales y la intuición detrás de la atención como mecanismo central para procesar secuencias.

### Clase 2 — Transformers para Lenguaje Natural (LLMs) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase02_nlp.ipynb?hl=es) ✅

Aplicación de Transformers al **procesamiento de lenguaje natural**, incluyendo modelos de lenguaje, tokenización, generación de texto y uso práctico de LLMs.

### Clase 3 — Transformers para Visión Computacional (ViT) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase03_vision.ipynb?hl=es) ✅

Estudio de **Vision Transformers (ViT)** y adaptación de la arquitectura Transformer a imágenes mediante parches, embeddings visuales y tareas de clasificación.

### Clase 4 — Modelos Multimodales y Aprendizaje Auto-Supervisado [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase04_multimodal.ipynb?hl=es) ✅

Introducción a modelos **multimodales** y aprendizaje auto-supervisado para combinar texto, imágenes y representaciones compartidas en sistemas modernos de IA.

### Clase 5 — Cuantización, PEFT/LoRA, QLoRA, Ollama y despliegue de LLMs ✅

Técnicas para hacer LLMs más eficientes mediante **cuantización, PEFT, LoRA y QLoRA**, junto con opciones de inferencia local y despliegue práctico.

- 📖 **Teoría** — [Presentación](Slides/clase05_cuantizacion_peft_despliegue_llms.pdf)
- 💻 **Práctica** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase05_cuantizacion_peft_despliegue_llms.ipynb?hl=es)

### Clase 6 — Aprendizaje por Contexto (In-Context Learning) ✅

Diseño de prompts y técnicas de **aprendizaje por contexto**, incluyendo zero-shot, few-shot, razonamiento guiado, autoconsistencia y salidas estructuradas.

- 📖 **Teoría** — [Presentación](Slides/clase06_aprendizaje_por_contexto.pdf)
- 💻 **Práctica** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase06_aprendizaje_por_contexto.ipynb?hl=es)

### Clase 7 — Retrieval-Augmented Generation (RAG) ✅

Introducción a la arquitectura **Retrieval-Augmented Generation (RAG)** para combinar modelos de lenguaje con bases de conocimiento externas, permitiendo responder preguntas utilizando información específica y actualizada.

- 📖 **Teoría** — [Presentación](Slides/clase07_rag.pdf)
- 💻 **Práctica 1: RAG Básico** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/Clase1_RAG_Simple.ipynb?hl=es)
- 💻 **Práctica 2: RAG Avanzado** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/Clase2_RAG_Avanzado.ipynb?hl=es)


### Clase 8 — Graph RAG y Knowledge Graphs ✅

Extensión de RAG mediante **Knowledge Graphs** para mejorar la recuperación de información y la capacidad de razonamiento, junto con técnicas para evaluar sistemas RAG.

- 📖 **Teoría** — [Presentación](Slides/clase08_graphrag.pdf)
- 💻 **Práctica 1: Evaluación de Sistemas RAG** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/Clase3_Evaluacion_RAG.ipynb?hl=es)
- 💻 **Práctica 2: Graph RAG** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/Clase4_GraphRAG.ipynb?hl=es)

### Clase 9 — Agentes ✅

Construcción de **agentes con herramientas**, memoria y conexión a datos externos, enfatizando validación, trazabilidad y acciones con confirmación humana.

- 📖 **Teoría** — [Presentación](Slides/clase09_agentes.pdf)
- 💻 **Práctica** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase09_agentes_firebase.ipynb)

### Clase 10 — Model Context Protocol (MCP) ✅

Introducción a **Model Context Protocol (MCP)** para exponer tools, resources y prompts mediante un protocolo estándar, usando transportes como `stdio` y Streamable HTTP.

- 📖 **Teoría** — [Presentación](Slides/clase10_mcp.pdf)
- 💻 **Práctica** — [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicolasPCS/Curso-de-Transformers-Agentes-LangChain-RAG/blob/main/Notebooks/clase10_mcp_servidor_herramientas.ipynb)

---

## Recursos

- *Deep Learning*, Goodfellow, Bengio, Courville — https://www.deeplearningbook.org/
- *Neural Networks and Deep Learning*, Nielsen — http://neuralnetworksanddeeplearning.com/
- *Dive into Deep Learning* — https://d2l.ai/
