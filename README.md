# Spam-Ham Classification using Machine Learning and Deep Learning

## Overview
This project focuses on classifying text messages as spam or ham using machine learning and deep learning techniques. The dataset is preprocessed, converted into numerical representations, and trained on multiple models to achieve high accuracy.

## Features
- Converts raw text data into a structured CSV format.
- Implements text preprocessing techniques such as:
  - Removal of non-alphabetic characters using regex
  - Case normalization
  - Tokenization
  - Stemming
  - Stopword removal
- Transforms text into numerical vectors using:
  - TF-IDF (Term Frequency-Inverse Document Frequency)
  - Bag-of-Words (BoW)
  - Word Embeddings
- Trains traditional machine learning models:
  - Random Forest
  - Naïve Bayes (achieved highest accuracy of 97.84%)
- Develops deep learning models:
  - LSTM (97.94% validation accuracy)
  - Bidirectional LSTM (98.83% validation accuracy)

## Technologies Used
- Python
- scikit-learn
- TensorFlow/Keras
- NLTK
- Pandas
- NumPy

  
## Results
| Model               | Accuracy |
|---------------------|----------|
| Naïve Bayes        | 97.84%   |
| LSTM               | 97.94%   |
| Bidirectional LSTM | 98.83%   |

## Contributing
Feel free to contribute to this project by creating a pull request or opening an issue.

## License
This project is licensed under the MIT License.

