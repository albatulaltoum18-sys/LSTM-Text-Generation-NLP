Sequence Models and Text Generation using LSTM

This project explores how machines can learn and generate human language using sequence models. A character-level LSTM network was implemented to generate text in the style of Shakespeare.

Overview
The model was built using TensorFlow and trained on Shakespeare’s complete works. The objective was to understand how recurrent neural networks capture sequential patterns in text and how LSTMs handle long-term dependencies.

Methodology
The text dataset was preprocessed by creating a vocabulary of unique characters and mapping each character to an integer. Input-target sequences were generated using a fixed sequence length. The model architecture includes an Embedding layer, an LSTM layer with 1024 units, and a Dense output layer for character prediction. The model was trained for 50 epochs.

Evaluation and Analysis
Model performance was evaluated using loss and perplexity. Perplexity was calculated as the exponential of the loss value. The effect of different sequence lengths was analyzed to understand context learning and training stability. The vanishing gradient problem and the role of LSTM gates were also examined.

Enhancements and Insights
Pre-trained GloVe embeddings were explored to improve semantic representation. GPT-2 was briefly tested as an advanced transformer-based alternative. These extensions demonstrate awareness of modern NLP architectures beyond basic RNN models.

Results
The trained model successfully generated structured text resembling Shakespeare’s writing style. While not perfectly fluent, the output demonstrates learned linguistic patterns and character-level dependencies.

Tools and Technologies
Python
TensorFlow
NumPy
Matplotlib
Jupyter Notebook

Project Files

LSTM_Text_Generation_Shakespeare.ipynb

LSTM_Text_Generation_Report.pdf

How to Run
Open the Jupyter Notebook file and run the cells sequentially after installing the required libraries.

Purpose
This project was built to understand sequence models, language modeling, and text generation using deep learning.

Author
Albatul Altoum