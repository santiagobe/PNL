# Procesamiento de Lenguaje Natural (NLP) - UBA

Repositorio de desafíos prácticos de la materia **Procesamiento de Lenguaje Natural** de la **Universidad Nacional de Buenos Aires (UBA)**.

Cada desafío aborda un aspecto fundamental del procesamiento de lenguaje natural, desde la vectorización de textos hasta la generación de secuencias utilizando modelos de redes neuronales recurrentes.

---

## Tabla de Contenidos

- [Desafío 1: Vectorización y Clasificación de Texto](#desafío-1-vectorización-y-clasificación-de-texto)
- [Desafío 2: Creación de Embeddings Personalizados](#desafío-2-creación-de-embeddings-personalizados)
- [Desafío 3: Modelado de Lenguaje a Nivel de Caracteres](#desafío-3-modelado-de-lenguaje-a-nivel-de-caracteres)
- [Desafío 4: Construcción de un LSTM Bot QA](#desafío-4-construcción-de-un-lstm-bot-qa)

---

## Desafío 1: Vectorización y Clasificación de Texto

**Descripción**:

Clasificación de documentos utilizando el dataset **20 Newsgroups**, con representación vectorial de los textos y modelos Naïve Bayes.

**Objetivos**:
- Cargar y preprocesar el dataset.
- Vectorizar documentos con `TfidfVectorizer` y `CountVectorizer`.
- Medir similitud entre documentos seleccionados.
- Entrenar y comparar modelos MultinomialNB y ComplementNB.
- Evaluar resultados usando F1-score.

🔗 [Notebook - Desafío 1](https://github.com/santiagobe/PNL/blob/main/TP1_Santiago_Bel%C3%A9n.ipynb)

---

## Desafío 2: Creación de Embeddings Personalizados

**Descripción**:

Entrenamiento de embeddings personalizados usando el dataset **MTSamples** de transcripciones médicas, mediante la librería **Gensim**.

**Objetivos**:
- Preprocesar textos médicos.
- Entrenar vectores Word2Vec.
- Analizar similitudes semánticas entre palabras.
- Visualizar embeddings reducidos con PCA.

🔗 [Notebook - Desafío 2](https://github.com/santiagobe/PNL/blob/main/TP2_Santiago_Bel%C3%A9n.ipynb)

---

## Desafío 3: Modelado de Lenguaje a Nivel de Caracteres

**Descripción**:

Entrenamiento de modelos de lenguaje basados en RNNs, utilizando un subconjunto temático del corpus MTSamples (especialidad "Surgery").

**Objetivos**:
- Tokenizar corpus a nivel de caracteres.
- Estructurar datasets de entrenamiento y validación.
- Construir y entrenar modelos SimpleRNN, LSTM y GRU.
- Generar texto utilizando greedy search y beam search.

🔗 [Notebook - Desafío 3](https://github.com/santiagobe/PNL/blob/main/TP3_Santiago_Bel%C3%A9n.ipynb)

---

## Desafío 4: Construcción de un LSTM Bot QA

**Descripción**:

Desarrollo de un bot de preguntas y respuestas basado en una arquitectura **encoder-decoder** utilizando LSTM, entrenado sobre datos de conversaciones humanas reales (**ConvAI2 dataset**).

**Objetivos**:
- Extraer pares de preguntas-respuestas del dataset.
- Tokenizar y transformar secuencias.
- Implementar y entrenar un modelo encoder-decoder.
- Evaluar la generación de respuestas automáticas.

🔗 [Notebook - Desafío 4](https://github.com/santiagobe/PNL/blob/main/TP4_Santiago_Bel%C3%A9n.ipynb)


---
