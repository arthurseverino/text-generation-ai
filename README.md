# Next Word Predictor using LSTM

This project is about creating a next-word prediction model using Natural Language Processing (NLP), Python, TensorFlow, Numpy and Matplotlib. The model is a Recurrent Neural Network (RNN) with Long-Short-Term Memory (LSTM) units.

## Project Description

The goal of this project is to train a model that can predict the next word in a sentence given the previous words. The model is an RNN with LSTM units, a type of architecture that is well-suited for dealing with sequential data like text.

The LSTM unit consists of input, output, forget, and cell states that help the model to remember and forget information over long sequences, making it effective for this task.

The model is trained on the text of Jane Austen's "Pride and Prejudice". Given three words of a sentence, the model should be able to guess the fourth word.

## Technologies Used

- Python: The project is implemented in Python due to its readability and vast library support for machine learning and NLP.
- TensorFlow: TensorFlow's Keras API is used to build and train the LSTM model.
- Numpy: Used for numerical computations.
- Matplotlib: Used to visualize the loss of the model over each epoch

## Concepts Learned

Through this project, I have learned about various concepts in deep learning and NLP, including:

- RNNs and LSTMs: Learned how these architectures work and why they are useful for sequential data.
- Loss functions: Learned how they measure the model's performance and guide the learning process.
- Optimizers: Learned how they adjust the model's parameters to minimize the loss.
- Activation functions: Learned how they introduce non-linearity into the model and help it learn complex patterns.
- Tokenization: Learned how to convert text into a format that can be fed into a model.
- Word embeddings: Learned how they represent words in a way that captures their meanings.


## Example Usage

This section demonstrates how to use the next-word prediction model. The model takes the last three words of the input and predicts the next word.

Here's how it works:

1. **Input**: The user enters a line of text. For example: "however, it may all come to".

2. **Processing**: The model takes the last three words of the input, in this case, "all", "come", "to".

3. **Output**: The model predicts the next word and returns it. In this example, it returns "nothing".

Here are more examples:

- **Input**: "He could not help seeing that you were about five times as"
  - **Processing**: The model takes "five", "times", "as".
  - **Output**: The model predicts "pretty".

- **Input**: "He was quite"
  - **Processing**: The model takes "He", "was", "quite".
  - **Output**: The model predicts "young".

Remember, the model's predictions depend on the text it was trained on. If it was trained on different text, it might make different predictions.
