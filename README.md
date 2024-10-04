
# Análisis de Sentimientos en Twitter 📊

## Descripción 📄
Este proyecto analiza sentimientos en tweets utilizando técnicas tradicionales de procesamiento de lenguaje natural y modelos de aprendizaje profundo. Incluye comparaciones entre diferentes enfoques para detectar polaridades de sentimiento.

## Estructura del Proyecto 📂
1. **`Codigo_1.ipynb`:** Análisis de sentimiento clásico utilizando técnicas de NLP y clustering de usuarios.
2. **`Codigo_2.ipynb`:** Análisis con `Transformers` para evaluar la complejidad de texto y modelos avanzados.
3. **`results/Resultados.pdf`:** Informe detallado con los resultados del análisis y las conclusiones.

## Fuente de Datos 📁
Para reproducir este análisis, puedes descargar el dataset original desde Kaggle:

- **[Sentiment140 Dataset en Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140)**

Asegúrate de colocar el archivo descargado en la carpeta `data/` dentro del proyecto local con el nombre `training.1600000.processed.noemoticon.csv`.

## Instrucciones de Uso ⚙️
1. **Clonar el repositorio**:
    ```bash
    git clone https://github.com/Davidlopez9811/sentiment_analysis_project.git
    ```
2. **Instalar las dependencias**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Descargar el Dataset** desde [Kaggle](https://www.kaggle.com/datasets/kazanova/sentiment140) y colócalo en la carpeta `data/`.
4. **Ejecutar los notebooks**:
    - `Codigo_1.ipynb` para el análisis clásico.
    - `Codigo_2.ipynb` para el análisis con modelos de Transformers.