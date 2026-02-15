# Generative-AI-Using-LangChain
# 🦜🔗 LangChain & Generative AI Practice

This repository contains a collection of Jupyter Notebooks demonstrating key concepts in **Generative AI** using **LangChain** and **Hugging Face**. The projects cover the end-to-end process of building LLM applications, from data ingestion and embedding to building conversational chatbots.

## 📂 Repository Structure

Here is a breakdown of the modules included in this repository:

| Notebook | Description | Key Concepts |
| :--- | :--- | :--- |
| **`langchain_practice_model.ipynb`** | Introduction to loading and configuring LLMs. | `HuggingFaceEndpoint`, `ChatHuggingFace`, Model Configuration |
| **`langchain_practice_prompt_template.ipynb`** | Mastering prompt engineering with dynamic inputs. | `PromptTemplate`, Dynamic Prompts, Input Variables |
| **`langchain_practice_output_parsers_with_chains.ipynb`** | Structuring unstructured LLM responses into usable data formats. | `OutputParsers`, `LLMChain`, JSON/List Parsing |
| **`langchain_practice_document_loaders.ipynb`** | Techniques for ingesting external data sources into your AI application. | Document Loaders, Data Ingestion |
| **`langchain_practice_embeddings.ipynb`** | converting text into vector representations for semantic search. | `SentenceTransformers`, Vectorization, Semantic Similarity |
| **`langchain_practice_simple_ai_chatbot.ipynb`** | Putting it all together to build a functional conversational agent. | Memory, Chat History, Conversational Retrieval Chains |

## 🛠️ Tech Stack

* **LangChain:** Framework for developing applications powered by language models.
* **Hugging Face Hub:** Access to open-source models (specifically `HuggingFaceH4/zephyr-7b-beta`).
* **Sentence Transformers:** For generating state-of-the-art text embeddings.
* **FAISS (Facebook AI Similarity Search):** For efficient vector storage and similarity search.
* **BitsAndBytes & Accelerate:** For optimizing model loading and inference on GPUs.

## 🚀 Getting Started

### Prerequisites

* Python 3.10+
* A Hugging Face Account & Access Token

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Install the required dependencies:**
    It is recommended to use a virtual environment. You can install the packages used in these notebooks with:
    ```bash
    pip install langchain langchain-huggingface langchain-community sentence-transformers faiss-cpu transformers accelerate bitsandbytes
    ```

3.  **Setup Environment Variables:**
    Create a `.env` file or set your API token in your environment:
    ```python
    import os
    os.environ['HUGGINGFACEHUB_ACCESS_TOKEN'] = "your_access_token_here"
    ```

## 🧠 Model Details

These notebooks primarily utilize the **Zephyr-7b-beta** model via the Hugging Face Inference API. This allows for high-quality text generation without requiring massive local hardware resources, though local execution logic is also explored using quantization.

## 🤝 Contributing

Feel free to fork this repository and submit pull requests if you have improvements or new modules to add!

## 📜 License

This project is open-source and available under the MIT License.
