# NanoGPT - Character-Level Text Generation

NanoGPT is a lightweight and educational project designed to implement a character-level language model, inspired by Andrej Karpathy's work. This project uses the **Tiny Shakespeare dataset**, a text corpus of Shakespeare's plays, to train a model that generates text in a similar style.

## About the Project

The goal of this project is to provide a practical introduction to natural language processing (NLP) and text generation using machine learning. By working at the character level, the project demonstrates how language models can learn patterns in text and produce coherent outputs, even when trained on a small dataset.

## Features

### Dataset Analysis:
- Processes the Tiny Shakespeare dataset consisting of over 1.1 million characters.
- Identifies the unique vocabulary of 65 characters.

### Language Modeling:
- Implements a character-level text generator.
- Trains a simple neural network to learn patterns in the dataset.

### Text Generation:
- Generates new, Shakespeare-like text based on the trained model.

## Workflow

### Data Preprocessing:
- Prepares the Tiny Shakespeare dataset by tokenizing the text into characters and analyzing its structure.

### Model Training:
- A character-level model is trained using the dataset to predict the next character in a sequence.

### Text Generation:
- The trained model generates text by sampling from its learned distributions, producing creative and structured outputs.

## Key Highlights

- **Dataset Size**: 1,115,394 characters.
- **Vocabulary**: 65 unique characters, including letters, punctuation, and spaces.
- **Applications**: Demonstrates foundational concepts of text generation and sequence modeling.

## Acknowledgments

This project is inspired by Andrej Karpathy's [char-rnn](https://github.com/karpathy/char-rnn) and serves as a simplified version for educational purposes.
