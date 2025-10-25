# SpamShield-ML

**SpamShield-ML** is a machine learning project designed to detect and classify spam messages in text data. It uses natural language processing (NLP) techniques and a Naive Bayes classifier to automatically identify spam and ham (non-spam) messages.

## Features
- Uses **TF-IDF vectorization** to convert text into numerical features.
- Trains a **Multinomial Naive Bayes** model for spam detection.
- Evaluates the model with **accuracy, confusion matrix, and classification report**.
- Includes **visualizations**: message distribution, word clouds, and important spam words.
- Allows testing **new messages** for real-time prediction.
- Option to save and reload the trained model for future use.

## Dataset
The dataset `spam_dataset.csv` contains labeled text messages:
- `spam` – unwanted messages
- `ham` – legitimate messages

You can expand the dataset to improve model performance.

## Usage
1. Upload the dataset and notebook to Google Colab or Jupyter.  
2. Run the notebook to train the model and generate visualizations.  
3. Test new messages by providing text input and predicting spam or ham.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib & Seaborn
- WordCloud

## Notes
This project is ideal for beginners learning **machine learning**, **text classification**, and **NLP**. It can be extended with larger datasets, different ML algorithms, or advanced preprocessing for better accuracy.

