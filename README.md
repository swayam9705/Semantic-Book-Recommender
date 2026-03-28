# Semantic Book Recommender

This project is a search tool that allows users to find books based on the **meaning** of their query rather than just keyword matching. It uses natural language processing to understand the context of a search and retrieve the most relevant titles from a dataset.

---

## Features

* **Semantic Search:** Finds books based on themes, emotions, or plot summaries.
* **Vector Embeddings:** Converts book descriptions into numerical vectors for accurate comparison.
* **LangChain Integration:** Uses LangChain to manage the workflow between text processing and the vector store.

---

## Tech Stack

* **Language:** Python
* **Libraries:** LangChain (for tokenization and chain management)
* **Database:** Vector Database for storing and querying embeddings
* **Models:** Text embedding models for semantic representation

---

## Getting Started

### Prerequisites
* Python 3.8 or higher
* An API key for your chosen embedding provider (HuggingFace)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/swayam9705/Semantic-Book-Recommender.git
    cd Semantic-Book-Recommender
    ```

2.  **Create a virtual environment (optional but recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure environment variables:**
    Create a `.env` file in the root directory and add your credentials:
    ```env
    HUGGINGFACEHUB_API_TOKEN=YOUR_API_KEY 🙃
    ```

5.  **Run the application:**
    ```bash
    python main.py
    ```

---

## Usage
Input a natural language query such as *"a story about a lonely robot in space"* or *"dark academia with a mystery,"* and the system will return the top matches based on semantic similarity.