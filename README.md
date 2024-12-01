# SMS-spam-Classifier
Building an SMS spam detection model and detect SMS as Spam or Ham
- Data Gathering & Cleaning :
Dataset obtained from Kaggle .The initial step involved cleaning the dataset by removing any duplicates and handling missing values. This ensures the integrity of the data, which is crucial for accurate model training.
- Exploratory Data Analysis (EDA) :
I conducted EDA to understand the distribution of spam and non-spam messages. This included visualizations such as bar charts to illustrate the class balance and word clouds to identify common words in both categories. EDA helped uncover patterns and provided insights into the text characteristics of spam messages.
- Text Preprocessing :
For effective text analysis, I performed several preprocessing steps, including lowercasing the text, removing punctuation and special characters, tokenization, and eliminating stop words. Additionally, I applied stemming to reduce words to their root forms, enhancing the model's ability to recognize similar words.
- Model Building :
I utilized various machine learning algorithms, such as Logistic Regression, Support Vector Machines, and Random Forest, to build the spam detection model. The dataset was split into training and testing sets to facilitate model training and evaluation.
- Evaluation :
I evaluated model performance using metrics like accuracy, precision, recall, and F1-score. Cross-validation ensured robust performance across different data splits.
- Improvement :
To enhance the model, I implemented techniques such as hyperparameter tuning and ensemble methods, which improved the detection rates of spam messages. Overall, this systematic approach ensured a reliable spam detection model.
