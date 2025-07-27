# Personalized Health Recommendation System

This project provides personalized health suggestions (e.g., Sleep Improvement, Workout) using structured and unstructured user input. It combines traditional machine learning with natural language processing (NLP) to generate multi-label health recommendations based on Seed Synthetic Dataset.


## Technologies Used

- Python, Pandas, NumPy
- Scikit-learn, TensorFlow/Keras
- NLP: BERT
- Jupyter Notebook for development

## Features

-  **Input**: Age, BMI, Sleep Hours, Activity Level, Water Intake, Symptoms (text)
-  **Output**: Multiple health suggestions (e.g., Sleep, Mental Wellness, Exercise, etc)
-  **Dataset**: Seed Synthetic Dataset (Seed Dataset : data/Responses4.xlsx & Synthetic Dataset : data/Synthetic-Dataset.csv)
-  **Multi-label classification** trained on synthetic yet realistic health data
-  Uses structured features + NLP embeddings (like BERT) from symptom descriptions
-  Pre-trained model saved as `Health-Recommendation-System.joblib`



