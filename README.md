# Language-Classification
The classification based ML model presents a thorough approach to handling and categorizing text samples across multiple languages. With this model, users can confidently determine the language of new text data, rendering it a valuable tool for tasks within the realm of natural language processing.

This project is a tool, for classifying languages based on text. It uses machine learning techniques to analyze and categorize text samples. The process involves steps, including data preprocessing, feature engineering, model training and evaluation. To run this project you will need Python. Its recommended to use Jupyter Notebook for an interactive experience. Make sure to install the Python libraries such as NumPy, pandas, scikit learn, Matplotlib, seaborn and pickle. Once you have cloned the repository and navigated to the project directory you can execute the code either through the 'language_classification.ipynb' Jupyter Notebook Python script. Detailed explanations for each step are provided in the code comments.

The project starts by loading and preprocessing the data. This includes creating features based on characters and words. The dataset is then divided into training and test sets with data standardized using StandardScaler. To reduce feature dimensionality, Principal Component Analysis (PCA) is applied. A Decision Tree Classifier is trained on the data for language classification purposes with the resulting model saved as 'decision_tree_model.pkl' for future use. Model performance is evaluated using test data.

This versatile tool serves as a foundation that can be customized for text classification tasks. It provides insights, to natural language processing applications.
