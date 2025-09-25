A continuación, podremos ver el link de acceso al proyecto: https://colab.research.google.com/drive/1psQkl5XuDt8eXHhWO93iyCEQ2SIHrJcz#scrollTo=RcXdKAVnga5c

# 🏨 Análisis de Experiencias de Usuarios en Hotelería
## Data Science | Procesamiento de Lenguaje Natural (NLP) | Deep Learning

---

## 🎯 Objetivo del Proyecto

El proyecto se centra en el **Análisis de Sentimientos** de reseñas de hoteles en la plataforma **Trip Advisor** para el sector de la **Hotelería y Turismo**.

El objetivo principal es transformar el *feedback* no estructurado de los clientes (reseñas de texto) en **inteligencia de negocio automatizada y procesable**, permitiendo la toma de decisiones estratégicas para mejorar la experiencia del cliente y la reputación online.

---

## ✅ Objetivos Planteados y Logros

| Tipo | Objetivo | Cumplimiento |
| :--- | :--- | :--- |
| **General** | Transformar datos de texto no estructurados en información valiosa y procesable para la toma de decisiones estratégicas en el sector hotelero. | **CUMPLIDO:** Se desarrolló un modelo predictivo robusto (LSTM) con una fiabilidad superior al 90% para clasificar automáticamente el sentimiento de las reseñas. |
| **Específico**| Diseñar un *pipeline* de NLP y Machine Learning para la clasificación de sentimiento (Positivo, Neutro, Negativo). | **CUMPLIDO:** El *pipeline* incluye limpieza de texto, lematización, vectorización (TF-IDF) y la evaluación de cuatro modelos predictivos. |
| **Específico**| Identificar el modelo con mejor rendimiento para automatizar la identificación de opiniones de los clientes. | **CUMPLIDO:** El modelo **LSTM** fue seleccionado como el más óptimo, alcanzando una precisión (Accuracy) del **90.39%**. |

---

## 🚀 Metodología y Logros Clave

Se diseñó e implementó un *pipeline* completo de Data Science para la clasificación de texto:

### 1. Preprocesamiento y Etiquetado
* **Fuente de Datos:** Reseñas de hoteles de Trip Advisor (datos públicos de Kaggle).
* **Clasificación de 3 Clases:** Se etiquetó el sentimiento de las reseñas basándose en la calificación de estrellas (`Review Rating`): **Positiva** (4-5), **Neutra** (3) y **Negativa** (1-2).
* **Limpieza de Texto:** Aplicación rigurosa de técnicas de NLP, incluyendo minúsculas, eliminación de puntuación, *stopwords* (palabras vacías) y lematización para estandarizar el vocabulario.
* **Vectorización:** Uso de **TF-IDF** (Term Frequency-Inverse Document Frequency) y **Bag of Words** para convertir el texto en matrices numéricas aptas para el modelado.

### 2. Modelado y Rendimiento
Se evaluaron múltiples modelos de Machine Learning y Deep Learning para la tarea de clasificación.

| Modelo | Métrica Clave (Accuracy) |
| :--- | :--- |
| **LSTM (Deep Learning)** | **90.39%** |
| Regresión Logística | 86.7% |
| SVC (Kernel Lineal) | 86.4% |
| Random Forest | 85.0% |

El modelo de **Red Neuronal Recurrente LSTM (Long Short-Term Memory)** demostró la **mayor fiabilidad**, confirmando su superioridad para el análisis contextual de secuencias de texto.

---

## 🛠️ Tecnologías y Conocimiento Aplicado

* **Lenguaje:** `Python`
* **Análisis de Datos:** `Pandas`, `NumPy`
* **Procesamiento de Lenguaje Natural (NLP):** `NLTK`, `Scikit-learn`
    * Técnicas: Limpieza de texto, Lematización, TF-IDF, Bag of Words.
* **Machine Learning (Clásicos):** Regresión Logística, SVC, Random Forest.
* **Deep Learning:** `TensorFlow`, `Keras`
    * Arquitectura: Redes Neuronales Recurrentes **LSTM** (capas de *Embedding* y *Dropout*).
* **Visualización:** `Matplotlib`, `Seaborn` (para distribución de datos y resultados del modelo).


## 🛠️ Modelos de Machine Learning Implementados

Se evaluó el rendimiento de cuatro modelos principales para determinar la arquitectura más efectiva en la clasificación de reseñas en tres categorías de sentimiento: Negativa, Neutra y Positiva.

| Modelo Implementado | Tipo de Aprendizaje | Métrica Clave (Accuracy) | Razón de Rendimiento |
| :--- | :--- | :--- | :--- |
| **LSTM (Deep Learning)** | Aprendizaje Profundo | **90.39%** | Maneja la **secuencia y el contexto** del lenguaje, superando a los modelos clásicos. |
| **Regresión Logística** | Machine Learning Clásico | 86.7% | Buen *baseline* para clasificación lineal de texto vectorizado con TF-IDF. |
| **SVC (Kernel Lineal)** | Machine Learning Clásico | 86.4% | Efectivo para encontrar hiperplanos de separación en un espacio de alta dimensión. |
| **Random Forest** | Machine Learning Clásico | 85.0% | Clasificador basado en árboles, útil pero menos efectivo que los modelos secuenciales para NLP. |

---

## 💡 Próximos Pasos (Visión a Futuro)

Para llevar el proyecto al nivel de producción, se planean las siguientes mejoras:

1.  **Modelos Transformer:** Exploración de arquitecturas más avanzadas como **BERT** para capturar matices lingüísticos más complejos.
2.  **Topic Modeling:** Implementación de técnicas (como LDA o NMF) para identificar automáticamente los **temas recurrentes** (ej. "limpieza de habitación", "calidad del desayuno") que impulsan el sentimiento.
3.  **Despliegue (Deployment):** Integración del modelo final en una aplicación web o *dashboard* interactivo para que los equipos de gestión hotelera puedan analizar nuevos datos de forma instantánea.
