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

1.  **Modelos Transformer:** Exploración de arquitecturas más avanzadas como **BERT** para capturar matices lingüísticos más complejos
