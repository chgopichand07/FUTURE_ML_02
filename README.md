# 🎫 Support Ticket Classification & Prioritization using Machine Learning

## 📌 Project Overview

This project was developed as **Task 2** of the **Future Interns Machine Learning Internship**.

The goal of this project is to build an intelligent system that automatically classifies customer support tickets into predefined categories and assigns priority levels using **Natural Language Processing (NLP)** and **Machine Learning** techniques.

Customer support teams receive hundreds of tickets every day. Manually sorting these tickets is time-consuming and inefficient. This project automates the process by analyzing ticket text, predicting the appropriate category, and assigning a priority level, helping businesses respond faster and improve customer satisfaction.

---

# 🚀 Features

- Automatic Support Ticket Classification
- Automatic Priority Prediction (High / Medium / Low)
- Text Cleaning and Preprocessing
- Tokenization and Stopword Removal
- TF-IDF Feature Extraction
- Logistic Regression Classification
- Naive Bayes Classification
- Model Performance Evaluation
- Confusion Matrix Visualization
- Accuracy Comparison Charts
- Ticket Category Distribution
- Priority Distribution
- Top Frequent Words Analysis
- Custom Ticket Prediction
- Export Predictions to CSV
- Business Insights Generation

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Regular Expressions (Regex)

---

# 📂 Dataset

The project uses a synthetic dataset generated within the Python program.

The dataset contains customer support tickets from four categories:

- Billing
- Technical
- Account
- General

Each ticket is assigned a priority level.

| Category | Priority |
|-----------|----------|
| Billing | High |
| Technical | High |
| Account | Medium |
| General | Low |

A total of **1000 support tickets** are generated automatically for training and testing the machine learning models.

---

# ⚙️ Project Workflow

## Step 1 – Dataset Generation

A synthetic dataset of customer support tickets is created.

Each ticket contains:

- Ticket Text
- Category
- Priority

---

## Step 2 – Text Preprocessing

The text data is cleaned using NLP techniques.

The preprocessing includes:

- Convert text to lowercase
- Remove punctuation
- Remove special characters
- Remove English stopwords
- Generate cleaned ticket text

---

## Step 3 – Feature Extraction

The cleaned text is converted into numerical vectors using **TF-IDF (Term Frequency-Inverse Document Frequency)**.

This allows machine learning algorithms to understand textual data.

---

## Step 4 – Train-Test Split

The dataset is divided into:

- 80% Training Data
- 20% Testing Data

Separate datasets are prepared for:

- Category Prediction
- Priority Prediction

---

## Step 5 – Model Training

Two Machine Learning algorithms are used.

### Logistic Regression

Used for:

- Category Classification
- Priority Classification

### Multinomial Naive Bayes

Used as a comparison model for both prediction tasks.

---

## Step 6 – Model Evaluation

Both models are evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

The comparison helps identify the better-performing model.

---

## Step 7 – Data Visualization

The project generates several visualizations:

- Confusion Matrix
- Model Accuracy Comparison
- Ticket Category Distribution
- Priority Distribution
- Top 10 Frequent Words

These visualizations help understand the performance of the classification models and the distribution of support tickets.

---

## Step 8 – Custom Ticket Prediction

Users can enter their own support ticket.

Example:

```
Payment failed but amount deducted
```

The system predicts:

- Ticket Category
- Ticket Priority

---

## Step 9 – Export Predictions

Predicted ticket summaries are exported as:

```
Predicted_Tickets.csv
```

This file can be used for further analysis or business reporting.

---

# 🤖 Machine Learning Models

## Logistic Regression

Logistic Regression is used as the primary classification algorithm.

Advantages:

- Fast training
- High accuracy
- Works well with TF-IDF features
- Suitable for text classification

---

## Multinomial Naive Bayes

Naive Bayes is widely used for Natural Language Processing tasks.

Advantages:

- Lightweight
- Fast
- Effective for text classification
- Good baseline model

---

# 📈 Evaluation Metrics

The project evaluates model performance using:

### Accuracy

Measures the percentage of correctly predicted tickets.

### Classification Report

Provides:

- Precision
- Recall
- F1 Score

### Confusion Matrix

Shows correct and incorrect classifications visually.

---

# 📊 Output Visualizations

The project generates the following outputs:

- Confusion Matrix
- Accuracy Comparison Bar Chart
- Ticket Category Distribution
- Priority Distribution Pie Chart
- Top 10 Frequent Words
- Prediction Summary Table
- Exported CSV File

---

# 💼 Business Benefits

This project helps businesses by:

- Automatically categorizing support tickets
- Assigning priority levels instantly
- Reducing manual effort
- Improving customer response time
- Enhancing customer satisfaction
- Optimizing support team workload
- Enabling AI-powered ticket management
- Supporting faster issue resolution

---

# 📁 Project Structure

```
Support-Ticket-Classification/
│
├── support_ticket_classification.py
├── Predicted_Tickets.csv
├── README.md
└── Output Screenshots/
```

---

# ▶️ Installation

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib nltk scikit-learn
```

---

# ▶️ How to Run

1. Install all required libraries.
2. Run the Python script.
3. Wait for dataset generation.
4. Train the machine learning models.
5. View model evaluation metrics.
6. Enter your own support ticket.
7. Receive predicted category and priority.
8. View generated charts.
9. Export predictions as a CSV file.

---

# 📌 Sample Prediction

### Input

```
Payment failed but amount deducted
```

### Output

```
Predicted Category : Billing
Predicted Priority : High
```

---

# 🎯 Learning Outcomes

Through this project, the following concepts were learned:

- Natural Language Processing (NLP)
- Text Cleaning
- Stopword Removal
- Tokenization
- TF-IDF Vectorization
- Logistic Regression
- Naive Bayes Classification
- Machine Learning Model Evaluation
- Data Visualization
- Business Analytics
- AI-powered Customer Support Automation

---

# 🌟 Future Enhancements

Some possible improvements include:

- Using real-world customer support datasets
- Deploying the model as a web application using Flask or Streamlit
- Integrating deep learning models such as LSTM or BERT
- Supporting multilingual ticket classification
- Adding email and chatbot integration
- Real-time ticket prediction using APIs

---

# 🙏 Acknowledgement

This project was successfully completed as part of the **Future Interns Machine Learning Internship – Task 2: Support Ticket Classification & Prioritization**. It demonstrates the practical application of **Natural Language Processing (NLP)** and **Machine Learning** to automate customer support operations, improve ticket routing, prioritize critical issues, and enhance overall service efficiency.

---

## 👨‍💻 Author

**CHINTALA GOPI CHAND**  
B.Tech – Computer Science & Engineering (AI & ML)  
Web Development Enthusiast | Python Enthusiast | Machine Learning Learner | Quantum Computing Minor Student

⭐ *Thank you for exploring this project! If you found it helpful, consider giving it a ⭐ on GitHub.*
