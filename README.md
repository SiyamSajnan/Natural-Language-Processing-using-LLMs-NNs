# Comparative Analysis of RNN, LSTM, and BERT for Sentiment Analysis on Twitter

## Project Description
This project compares the performance of RNN, LSTM, and BERT models in sentiment analysis tasks using Twitter data. Sentiment analysis, a subset of Natural Language Processing (NLP), extracts subjective information from textual data. BERT, built on the transformer architecture, is tested against traditional models like RNN and LSTM to assess its superiority in understanding context and sentiment.

## Models Employed
- **Recurrent Neural Network (RNN)**: Traditional neural network designed for sequential data, known for challenges like vanishing gradients.
- **Long Short-Term Memory (LSTM)**: An improvement over RNN, LSTM handles long-term dependencies with memory states.
- **BERT (Bidirectional Encoder Representations from Transformers)**: A transformer-based model excelling in capturing context and global dependencies in text data.

## Features
- **Data Preprocessing**: Utilized NLTK for text cleaning, stop-word removal, lemmatization, and stemming to prepare the Twitter data.
- **Transfer Learning with BERT**: Leveraged pre-trained BERT with fine-tuning on the Twitter dataset for optimized performance.
- **Evaluation Metrics**: Employed accuracy, precision, and recall to measure model performance, with BERT showing superior results compared to RNN and LSTM.
- **Comparison of Model Capabilities**: The project investigates each model’s handling of context, processing capabilities, and limitations (e.g., vanishing gradient in RNN, memory optimization in LSTM, and contextual embedding in BERT).

## Usage
To reproduce results, use the provided dataset and run the model scripts in Google Colab or a compatible environment. Ensure required libraries like TensorFlow, NLTK, Scikit-Learn, and NumPy are installed.

## Detailed Results
The models achieved the following performance metrics on the Twitter 140 dataset:
- **BERT**: Accuracy of 78%, with the highest precision and recall scores, demonstrating its effectiveness in handling sentiment nuances.
- **LSTM**: Achieved 71.1% accuracy, showing improvements over RNN but lacking BERT’s contextual comprehension.
- **RNN**: Reached 70.2% accuracy, limited by challenges in capturing long-term dependencies and context.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with any enhancements or new features.

