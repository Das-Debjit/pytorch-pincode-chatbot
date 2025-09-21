# PyTorch NLP Chatbot

A PyTorch-based chatbot with entity extraction for handling general queries and pincode lookups. This project was developed as part of an NLP exploration.

## 🌟 Features

-   **Intent Classification:** Built with a PyTorch LSTM-based neural network to understand user intents.
-   **Entity Extraction:** Uses regular expressions (`re`) to extract key information like pincodes and product names from user queries.
-   **Pincode Lookup:** Integrated with an Indian postal code dataset to verify delivery availability.
-   **Interactive UI:** Uses `ipywidgets` to create a simple, interactive chat interface within a Jupyter Notebook.

## 🛠️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/pytorch-nlp-chatbot.git](https://github.com/your-username/pytorch-nlp-chatbot.git)
    cd pytorch-nlp-chatbot
    ```
2.  **Install dependencies:**
    It's recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```
3.  **Download NLTK data:**
    Run Python and enter the following:
    ```python
    import nltk
    nltk.download('punkt')
    ```
4.  **Open and run the notebook:**
    Launch Jupyter Notebook and open `CHATBOT_NLP (1).ipynb`. Run the cells in order to train the model and start the chat interface.

## 📋 Requirements

You can generate a `requirements.txt` file by running this command in your terminal after installing all packages in your environment:

```bash
pip freeze > requirements.txt
```

Then, upload that `requirements.txt` file to your repository.
