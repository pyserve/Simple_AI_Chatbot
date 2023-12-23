# Simple AI Chatbot

## Description
`Simple AI Chatbot` is a Python-based chatbot model implemented using TensorFlow Keras Sequential model. The project includes modules for data extraction, data preprocessing, and a chatbot model. Also, facilitate the prompt-based interaction with chatbot and user.

## Project Structure
- `chatbot_model`: Saved Model
- `data_extraction.py`: Data Extraction
- `data_preprocessor.py`: Data Preprocessor
- `datasets.json`: Dataset JSON File
- `label_encoder.pickle`: Saved Encoder
-  `tokenizer.pickle`: Saved Tokenizer
- `main.py`: Main 
- `model.py`: Model Builder
- `requirements.txt`: Requirements for Project

## Chatbot Features
- Implemented using TensorFlow Keras Sequential model.
- Supports data extraction and preprocessing for chatbot training.
- Utilizes datasets in JSON format (`datasets.json`) and dialogue data (`dialogs.txt`).
- Includes a self-trained label encoder (`label_encoder.pickle`) and tokenizer (`tokenizer.pickle`).

## Installation
To install and run the Simple AI Chatbot, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/simple-ai-chatbot.git
    cd simple-ai-chatbot
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To use the Simple AI Chatbot, follow these steps:

1. **Run the main script:**
    ```bash
    python main.py
    ```

2. **Interact with the chatbot:**
    - Follow the prompts to engage in a conversation with the Simple AI Chatbot.
    - Explore the chatbot's responses and capabilities.

## Contributing
Contributions are welcome! If you'd like to contribute, please follow the [contribution guidelines](CONTRIBUTING.md).
