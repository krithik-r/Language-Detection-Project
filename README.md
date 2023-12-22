# Language-Detection-Project


## Introduction
This project implements a language detection model using the Passive Aggressive Classifier. The goal is to accurately identify the language of a given text input. The model is trained on a diverse dataset that includes sentences in multiple languages.

## Requirements
Make sure to install the required Python libraries before running the code.

## Dataset
The model is trained on a dataset containing sentences in various languages. The dataset includes information such as the sentence ID, language code, and the actual sentence text. Additionally, a JSON file (`lan_to_language.json`) is used for mapping language codes to human-readable language names.

## Data Preprocessing
The dataset undergoes several preprocessing steps, including:
- Removal of punctuation, numbers, and special characters.
- Lemmatization of words to their base forms.
- Handling of null values and duplicate sentences.

## Training
The Passive Aggressive Classifier is used to train the model. The training data is split into training and testing sets, and the model's accuracy is evaluated. 

## Results
The model achieves a high accuracy of 0.9641505 * 100 = 96.41% on the test set, demonstrating its effectiveness in language detection. The total time taken for training and testing is also reported.

## Example
After training the model, you can input a text, and the model will predict the language of the entered text. For example, entering "안녕하세요. 잘 지내죠" results in the prediction "Korean."

Feel free to use and contribute to this language detection model!
