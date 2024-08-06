# Quote Generator using RNN

This project is a Quote Generator that uses a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) layers to generate text sequences. The model is trained on a text dataset and can generate quotes based on the learned patterns.

## Features
- Uses TensorFlow and Keras for model building and training.
- Implements LSTM layers for handling sequential data.
- Generates text sequences based on the input dataset.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/quote-generator-rnn.git
    ```
2. Navigate to the project directory:
    ```bash
    cd quote-generator-rnn
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Prepare your text dataset and place it in the project directory.
2. Run the training script to train the model:
    ```bash
    python train.py
    ```
3. Generate quotes using the trained model:
    ```bash
    python generate.py
    ```

## Example
```python
print(generate_text(300, 0.5))
```


## License
This project is licensed under the MIT License.
