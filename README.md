# Financial Sentiment Analysis

## Project Overview
This project aims to perform sentiment analysis on financial news articles and market reports using Natural Language Processing (NLP) techniques. By leveraging fine-tuned models from the Hugging Face Transformers library, we will create a customized solution tailored to the financial domain. The goal is to analyze the sentiment (positive, negative, or neutral) of financial texts to provide actionable insights for market trends and investor decision-making.

## Objectives
- Utilize the Financial PhraseBank dataset to perform sentiment analysis on financial texts.
- Fine-tune and optimize the `DistilRoBERTa` model for accurate financial sentiment classification.
- Deliver insights into market trends and financial narratives using sentiment analysis.
- Develop a reusable and scalable solution for financial data sentiment analysis.

## Dataset Overview
The project utilizes the **Financial PhraseBank** dataset, which contains approximately 5,000 sentences from financial news and reports, each labeled as positive, negative, or neutral based on their impact on financial market perspectives. This dataset is well-regarded in financial sentiment analysis tasks and serves as a strong foundation for developing a robust model.

## Data Preprocessing
The data preprocessing steps include:
- Text cleaning (e.g., removing special characters, lowercasing text).
- Tokenization and input formatting for model compatibility.
- Splitting the dataset into training, validation, and test sets for effective model evaluation.

## Model Architecture
This project leverages a fine-tuned version of the **DistilRoBERTa** model from the Hugging Face Transformers library. This lightweight model retains the robust performance of RoBERTa while providing faster inference times and lower computational costs. The model is trained on the Financial PhraseBank dataset to accurately classify financial text sentiments.

## Evaluation Metrics
Model performance is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score

## Setup and Installation
To get started with this project, follow the steps below:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/financial-sentiment-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd financial-sentiment-analysis
    ```
3. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Technologies Used
- Python
- Hugging Face Transformers
- Pandas, NumPy
- Matplotlib, Seaborn for data visualization
- Scikit-learn (for data splitting and evaluation)

## Future Work & Improvements
- Expand the dataset with additional financial texts to enhance model generalizability.
- Experiment with different Transformer-based models for potential performance improvements.
- Explore multi-class sentiment classification and more granular sentiment categories.

