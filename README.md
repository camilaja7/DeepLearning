## Objetivos

Desarrollar, implementar y evaluar diferentes modelos de deep learning para la clasificación binaria de sentimientos en reseñas de texto, utilizando embeddings pre-entrenados GloVe como técnica de transfer learning, con el fin de analizar la capacidad de distintas arquitecturas (Conv1D, LSTM y GRU) para capturar patrones semánticos y contextuales del lenguaje natural y determinar su efectividad en la predicción de opiniones positivas o negativas.

### Objetivos específicos

Preprocesar el texto de las reseñas mediante limpieza, tokenización, padding y construcción del vocabulario.
Incorporar embeddings pre-entrenados GloVe para representar las palabras en un espacio vectorial semántico (transfer learning).
Entrenar y evaluar un modelo con arquitectura Conv1D + GloVe para la clasificación de sentimientos.
Entrenar y evaluar un modelo con arquitectura LSTM + GloVe para la clasificación de sentimientos.
Entrenar y evaluar un modelo con arquitectura GRU + GloVe para la clasificación de sentimientos.
Comparar el desempeño de los modelos utilizando métricas como accuracy, precision, recall y F1-score, analizando sus diferencias y capacidades para capturar información del texto.
