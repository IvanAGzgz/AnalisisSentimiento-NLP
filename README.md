# Análisis de Sentimientos en Python

En este notebook realizaremos un análisis de sentimientos en Python utilizando dos técnicas diferentes:

## Técnicas Utilizadas

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)**
   - Enfoque basado en *bag of words*.
   
2. **Modelo preentrenado RoBERTa de Hugging Face**
   - Utilización del pipeline de Hugging Face para realizar análisis de sentimientos.

## Comparación de Métodos
Se comparará el rendimiento del modelo basado en *bag of words* (VADER) con el modelo de *transformers* (RoBERTa) para evaluar sus diferencias en la clasificación de sentimientos.

## Librerias NLP
- `nltk`: Biblioteca para el procesamiento de lenguaje natural.
- `transformers`: Biblioteca de Hugging Face para trabajar con modelos de *transformers*.
- `pipeline`: Herramienta de Hugging Face para simplificar el uso de modelos preentrenados.
