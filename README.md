
# News Classification Project

This project aims to classify news articles into predefined categories using machine learning techniques. It includes data preprocessing, model training, and evaluation.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The News Classification Project is designed to categorize news articles into different topics. The project leverages natural language processing (NLP) and machine learning algorithms to achieve accurate classification.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/vvt2605/News_Classification_Project.git
   cd News_Classification_Project
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing:**

   Run the data preprocessing script to clean and prepare the data:

   ```bash
   python src/data_preprocessing.py
   ```

2. **Model Training:**

   Train the model using the preprocessed data:

   ```bash
   python src/model_training.py
   ```

3. **Model Evaluation:**

   Evaluate the trained model's performance:

   ```bash
   python src/model_evaluation.py
   ```

## Models and Techniques

The project utilizes various machine learning models and techniques, including:

- **Naive Bayes**
- **Support Vector Machines (SVM)**
- **ANN (Artificial Neural Network)**


Natural Language Processing (NLP) techniques such as tokenization, stopword removal, and TF-IDF vectorization are used to preprocess the text data.

## Results

The project evaluates model performance using metrics such as accuracy, precision, recall, and F1-score. The results are visualized in the model_evaluation notebook.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License


