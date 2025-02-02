# **Mind Guard: AI-Powered Suicide Ideation Detection**

## **Introduction**  
Mind Guard is an innovative machine learning project focused on detecting suicidal ideation in textual data. Using a fine-tuned BERT model, this project explores the role of AI in early intervention and mental health prevention, offering a tool that could assist in identifying at-risk individuals.

---

## **Project Overview**

**Objective:**  
Develop a BERT-based classifier capable of detecting subtle indicators of suicidal thoughts in text.

**Dataset:**  
The model is trained on a dataset of 6,000 text samples collected from various online platforms, annotated by experienced psychologists to ensure quality and relevance.

**Methodology:**  
The process includes several stages: data preprocessing, model fine-tuning, hyperparameter optimization, and robust validation to ensure reliable predictions.

---

## **Model Architecture**

**BERT-Based Classifier:**  
The model uses BERT-base-uncased for its ability to capture nuanced language patterns, crucial for understanding the subtle cues of suicidal ideation in text.

**Fine-Tuning:**  
The pre-trained BERT model is fine-tuned on the specialized dataset, with a focus on suicide prevention to better recognize indicators of distress.

**Hyperparameter Optimization:**  
Grid search is employed to optimize hyperparameters like learning rate, batch size, and training epochs, ensuring the model performs at its best.

---

## **Evaluation and Validation**

**Metrics:**  
Model performance is assessed through accuracy, precision, recall, and F1-score, offering a comprehensive evaluation of its predictive capabilities.

**Qualitative Analysis:**  
In-depth analysis is conducted to understand the model's decision-making process and gain insights into its ability to detect suicidal ideation effectively.

---

## **Results**

The model demonstrates high validation accuracy, precision, recall, and F1-score, proving its effectiveness in identifying potential signs of suicidal intent. The results underscore its potential as an early warning tool for mental health professionals.

---

## **Limitations and Future Directions**

- **Expanding the Dataset:** The dataset's size and diversity can be improved to increase the model's generalizability across different populations and languages.
- **Model Exploration:** Future work may include experimenting with other model architectures and incorporating additional features to enhance performance.

---

## **Tools and Libraries Used**

- **Google Colab:** Utilized for GPU-powered training to accelerate model development.
- **PyTorch:** The primary framework for building and training the model.
- **Transformers Library:** Essential for implementing the BERT model and fine-tuning it for this task.
- **Pandas, NumPy, Matplotlib:** Used for data manipulation and visualization.
- **scikit-learn:** For data preprocessing and evaluating the model.

---

## **How to Use**

1. Load the dataset.
2. Train the model using the provided code.
3. Watch the magic happen as the model learns to detect subtle cues of suicidal ideation.

---

## **Authors and Acknowledgments**

**Team:**  
- Maha Al-Hayajneh  
- Mira Melhem  
- Mirna AbuDhaim  
- Wasan Hawari  

**Supervision:**  
- Dr. Tamam Al Sarhan, University of Jordan

**Special Thanks:**  
We extend our heartfelt thanks to all contributors and supporters who helped make this project a reality.
