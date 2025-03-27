Requirements:
1. Data Merging:
● Merge two datasets provided into a single dataset for analysis. Ensure proper handling
of key fields and address any missing or inconsistent data.
The dataset you require is composed of Multi-class classification problems (benign,
defacement, phishing, malware, spam), The major dataset can be found using the link
Main dataset, But this dataset contains only four classes, for the fifth class you have to
merge another dataset. You may use this dataset for getting 5

th class Helper Data .

2. Preprocessing:
● Handle missing values, if any, using suitable techniques.
● Perform data cleaning, including removing duplicates and outliers.
● Encode categorical variables appropriately for machine learning models and LLM-based
models.
3. Balancing the Dataset:
● Address class imbalance to ensure fair representation of each malicious category using
techniques like oversampling, undersampling, or synthetic data generation (SMOTE,
etc.).

4. Exploratory Data Analysis (EDA):
● Conduct EDA to extract meaningful insights from the dataset.
● Generate descriptive statistics, visualize data distributions, and identify patterns.
● Explore relationships between URL structures, tokens, and malicious behavior.
5. Graphs and Plots:

● Create at least five meaningful graphs or plots that highlight insights obtained from the
dataset.
● Utilize appropriate visualization techniques to enhance data understanding.
6. Feature Extraction.
● Extract structural features from URLs (e.g., length, presence of special characters,
subdomains).
● Apply NLP-based embeddings using TF-IDF, Word2Vec, or transformer-based
embeddings to capture contextual meaning.
● Consider sequence-based feature extraction using character-level models.

7. Machine Learning & LLM-Based Models:
● Apply at least three classification models for predicting malicious URLs, including:
○ Traditional ML models (Random Forest, SVM, XGBoost)
○ Deep Learning models (LSTMs, CNNs)
○ LLM-based approaches (fine-tuned BERT, GPT, or transformer models)
● Ensure that the models achieve a minimum accuracy of 90%.

8. Results Visualization:
● Create visualizations showcasing the results of the ML models, such as confusion
matrices or ROC curves.
● Compare the performance of traditional ML vs. LLM-based models.
