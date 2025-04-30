# Capstone-Project-2-Fake-News-Detection-Using-NLP-and-Machine-Learning
This capstone project applies Natural Language Processing (NLP) techniques and machine learning models to build a binary classifier that can accurately detect fake news based on article text. The project includes full preprocessing, vectorization, and model evaluation steps.
🧾 Dataset
train.csv — Contains labeled news headlines with associated text (columns: title, text, label).

label: 1 for fake, 0 for real news.

🧰 Features & Workflow
1. Data Preprocessing
Removed missing values.

Dropped unnecessary columns like title.

Combined all text columns into a single text body for analysis.

2. Text Cleaning
Removed punctuation and stopwords.

Applied tokenization and lowercasing.

Used nltk for advanced preprocessing steps.

3. Vectorization
Applied TF-IDF Vectorization using TfidfVectorizer from sklearn to convert text to numerical form.

4. Modeling
Trained several classification models:

Logistic Regression

PassiveAggressiveClassifier

Evaluated performance using:

Accuracy score

Confusion matrix

Classification report

5. Evaluation
Visualized confusion matrices.

Analyzed false positives/negatives and overall model efficiency.

🖼️ Visualizations
Confusion matrix using seaborn.

Bar plots for label distribution.

Text length distributions before and after cleaning.
