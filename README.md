# NLP Chatbot Using Seq2Seq Model

# NLP Chatbot using Seq2Seq Model

## Project Description
This project involves building a chatbot using a Seq2Seq (Sequence-to-Sequence) model, trained on a dataset of movie dialogue lines. The chatbot can engage in text-based conversations by generating responses to user input. The model is implemented in Python using TensorFlow.

## Project Files
- **Data** - https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html
- **chatbot.py:** This is the main Python script that contains the code for training the chatbot and running conversations. It includes data preprocessing, model architecture, and training loop.
- **movie_lines.txt:** A dataset containing movie dialogue lines used for training the chatbot.
- **movie_conversations.txt:** A dataset containing information about conversations in the form of dialogue IDs.
- **chatbot_weights.ckpt:** Checkpoint file that stores the trained model's weights and parameters.
- **README.md:** This readme file providing an overview of the project.

## Dependencies
To run the chatbot code, you'll need the following Python libraries:
- TensorFlow
- NumPy
- Regular expressions (re)

## How to Run:
Clone the repository to your local machine.
Ensure you have the required dependencies installed.
Run the chatbot.py script to train the chatbot and start conversations.
The chatbot will initialize and be ready to respond to your input.

## Chatbot Training:
The chatbot uses a Seq2Seq model with attention mechanisms to generate responses. Training involves optimizing the model's weights to minimize the sequence loss error. Training parameters such as batch size, learning rate, and model hyperparameters are defined in the code.
