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