# Text Classification 
This project uses an Bidirectional LSTM based approach to perform sentiment or emotion analysis on a dataset. The notebook covers essential steps such as data preprocessing, visualizations, and model training and Evaluation.
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Emotion Categories](#emotion-categories)
- [Visualizations](#visualizations)
- [Output](#output)
- [Contributing](#contributing)
## Installation
To run this project, you'll need Python and the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `tensorflow` or `keras`
- `wordcloud`
- `nltk`
- `seaborn`
- `scikit-learn`

This assignment was developed and tested using:

### Python Version
- Python: **3.10.12**

### Third-Party Libraries
| Library           | Version   |
|-------------------|-----------|
| `pandas`          | 2.2.2     |
| `numpy`           | 1.26.4    |
| `matplotlib`      | 3.8.0     |
| `wordcloud`       | 1.9.4     |
| `nltk`            | 3.9.1     |
| `seaborn`         | 0.13.2    |
| `tensorflow`      | 2.17.1     |
| `scikit-learn`    | 1.6.0     |

## Usage
### Environment Setup
- Ensure you have Python 3.10+ installed.
- Install the required libraries using pip:
```bash
pip install pandas numpy matplotlib tensorflow wordcloud nltk seaborn scikit-learn
```
**Note** After installing nltk, download the required datasets using the following code
```bash
nltk.download('stopwords')
nltk.download('wordnet')
```
- `Download Dataset`
Provide the required dataset from the following link(https://www.kaggle.com/datasets/nelgiriyewithana/emotions). 
- `Enable GPU Acceleration`
If using Google Colab, navigate to Runtime > Change runtime type and select GPU as the hardware accelerator.
- `Run the Notebook`
Open the notebook FINAL_ASSIGNMENT_2.ipynb in Google Colab or Jupyter Notebook.
Execute all cells step by step.
## Features
- `Dataset Handling`: Importing data, handling missing values,duplicate rows and text preprocessing.
- `Emotion Mapping`: Mapping labels to emotion categories (e.g., Sadness, Joy, Love, etc.).
- `Visualization`: Generating pie charts and other visual tools to analyze data distribution.
- `Model Training`: Using Bidirectional LSTM for text-based sentiment/emotion classification.
## Emotion Categories
The emotions in the dataset are mapped as follows:
Sadness: 0
Joy: 1
Love: 2
Anger: 3
Fear: 4
Surprise: 5
## Visualizations 📊
The notebook includes visualizations to help understand the dataset:
- Pie charts showing emotion distribution.
- Text samples for each emotion category.
- Confusion Matrix to see the detailed breakdown of the model's predictions compared to the actual outcomes
- ROC curve to evaluate the performance of the model
## Output
The trained model categorizes text inputs into one of the six emotion types. Metrics such as accuracy, confusion matrix, and classification reports are provided to evaluate performance.
## Contributing
Contributions are welcome!😊 Feel free to fork the repository, make changes, and submit a pull request
