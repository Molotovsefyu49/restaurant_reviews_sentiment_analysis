

# Restaurant Review Sentiment Analysis

This project involves sentiment analysis on a dataset of restaurant reviews. The goal is to predict whether a review is positive or negative based on the text content. The project includes data preprocessing, feature extraction, model training, evaluation, and visualization.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Sentiment analysis is a Natural Language Processing (NLP) task that involves determining the sentiment or emotion expressed in a piece of text. In this project, we employ machine learning algorithms to predict whether restaurant reviews are positive or negative. We use techniques such as text preprocessing, feature extraction, and classification models to achieve this task.

## Dataset

The dataset consists of restaurant reviews labeled as positive (1) or negative (0). Each review is associated with a sentiment label. The goal is to build models that can accurately predict the sentiment of unseen reviews.

## Project Structure

The project is organized as follows:

- `data/`: Contains the dataset file(s).
- `notebooks/`: Jupyter notebooks for data preprocessing, model training, and analysis.
- `src/`: Python scripts for functions used throughout the project.
- `requirements.txt`: List of required Python packages.
- `README.md`: Project overview and instructions.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Molotovsefyu49/restaurant_reviews_sentiment_analysis.git
cd restaurant-review-sentiment-analysis
```

2. Install the required packages using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Place your dataset file in the `data/` directory.
2. Open the Jupyter notebooks in the `notebooks/` directory to run data preprocessing, model training, and analysis.
3. Modify and experiment with different algorithms, hyperparameters, and feature extraction techniques.
4. Generate visualizations and reports to analyze the results.

## Results

The project includes the following results:

- Model performance metrics such as accuracy, precision, recall, and F1-score.
- Confusion matrices visualizing the model's true positive, true negative, false positive, and false negative predictions.
- Word clouds displaying the most common words in positive and negative reviews.

## Conclusion

In this project, we applied machine learning techniques to perform sentiment analysis on restaurant reviews. We explored different algorithms, tuned hyperparameters, and evaluated the models' performance. Through the project, we gained insights into the strengths and weaknesses of each model and learned about techniques for text preprocessing and feature extraction.

## Contributing

Contributions are welcome! If you find any issues or improvements, feel free to open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

