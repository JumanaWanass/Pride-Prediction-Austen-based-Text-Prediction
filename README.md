# Pride & Prediction

Pride & Prediction is an AI text generation project inspired by Jane Austen's works. Using N-gram models, the project generates sentences reminiscent of the author's style and themes, providing an interactive experience for users to explore the language of Austen's classic works.

## Features

- **N-gram Model**: Utilizes N-gram models to predict the next words based on input text, capturing the essence of Jane Austen's writing style.
- **Add-One Smoothing**: Implements add-one smoothing to handle unseen contexts and improve the robustness of the text generation model.
- **End-of-Text Token Handling**: Ensures coherence by considering end-of-text tokens for the last word in generated sentences.
- **Dynamic Prediction**: Continuously generates words to create coherent sentences, even when encountering unfamiliar contexts.

## Usage

1. **Setup**: Ensure you have the required dependencies installed, including NLTK and other necessary libraries.
2. **Data Preprocessing**: Clean and filter the text data, preparing it for training the N-gram model.
3. **Model Training**: Train the N-gram model on the preprocessed text data, specifying the desired N-gram order.
4. **Text Generation**: Use the trained model to generate text by providing an initial input sentence and specifying the number of words to generate.

## Requirements

- Python 3.x
- NLTK (Natural Language Toolkit)
- Other dependencies as specified in the project files
