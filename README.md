# Simple Chatbot
This is a basic chatbot implemented in Python using TensorFlow and Keras. The chatbot is trained to recognize user input and respond based on predefined patterns and intents. The model is built using a Bidirectional LSTM architecture for natural language understanding.

## Project Structure
* `intents.json`: Contains predefined patterns, responses, and intents used for training the chatbot.
* `basic_chatbot.ipynb`: Python notebook for training the chatbot model. It reads data from intents.json, preprocesses the data, and builds a Bidirectional LSTM model for training. You can interact with the trained chatbot. It loads the trained model, tokenizer, and label encoder to respond to user input.

## Dependencies
* TensorFlow
* Keras
* scikit-learn
* colorama (for colored console output)

## Additional Notes
* The model architecture includes an Embedding layer, Bidirectional LSTM layers, and Dense layers.
* Error handling is implemented to handle cases where the chatbot doesn't understand the user's input. The error responses are defined in the "error" intent in intents.json.
* Feel free to extend the intents, add more training data, or experiment with different model architectures to enhance the chatbot's capabilities.






