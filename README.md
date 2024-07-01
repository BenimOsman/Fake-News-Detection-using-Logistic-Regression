# Fake-News-Detection-using-Logistic-Regression
Trained Datasets using Logistic Regression with high accuracy (training: 98.66 %, testing: 97.91 %) discerning <br>
real from fake.


**Drive Link:**  <br>
https://drive.google.com/drive/folders/1hTg3VIX2Z7gY8oxfgb6PAWHjo0rbegTK?usp=sharing

**Libraries Used:**
1. Pandas: For Data Manipulation and Analysis.
2. NumPy: Provides support for numerical operations on arrays and matrices, which is useful for mathematical computations.
3. Scikit-learn: Provides features for Feature Extraction, Model Training and Model Evaluation.
4. NLTK: For NLP tasks such as Tokenization and other text preprocessing steps.
5. MatPlotLib & Seaborn: For Data Visualization, to create plots and charts to understand the data and the model's performance better.

**Methodology of Fake-News Detection Model:**

1. Data Preprocessing:
   * The Dataset conataining news articles is loaded by removing irrelevant characters, punctuations, and stop words to clean the tect data.
   * Breaking down the text into individual words or tokens for better analysis.
     
2. Feature Extraction:
   * Transforming text data into numerical features.
   * It helps in converting text data into a format that can be fed into machine learning models.

3. Model Training:
   * The dataset is split into training and testing sets to evaluate the model's performance.
   * The chosen models are trained on the training dataset to learn patterns and features associated with fake news.

4. Model Evaluation:
   * The trained models are evaluated on the testing set using metrics like accuracy, precision, recall, and F1-score to determine their effectiveness.

5. Model Prediction:
   * The final model is used to predict whether new, unseen news articles are fake or real.
   
