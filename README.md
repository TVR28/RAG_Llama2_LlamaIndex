# Advanced RAG System with Llama2 & LlamaIndex

The Advanced Retrieval Augmented Generation (RAG) System leverages Open Source Llama2 and LlamaIndex, along with HuggingFace, to offer a powerful solution for querying large collections of PDF documents. This README provides comprehensive setup and usage instructions to help you harness the full potential of this system.

## Table of Contents

- [Introduction](#advanced-rag-system-with-llama2--llamaindex)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before setting up the RAG system, ensure you have:

- Python 3.8 or higher
- A T4 GPU or better (for optimal performance)
- An active HuggingFace account for API access

## Installation

To install and set up the RAG system:

1. Clone the repository:

   \```bash
   git clone https://github.com/your-username/rag-system-repo.git
   cd rag-system-repo
   \```

2. Install the required Python packages:

   \```bash
   pip install -r requirements.txt
   \```

3. Log in to your HuggingFace account to access models:

   \```bash
   huggingface-cli login
   \```

   Follow the prompts to enter your API key.

## Getting Started

To initialize the system:

1. Prepare your PDF documents in a directory named `data`.
2. Run the main Python script to start indexing:

   \```bash
   python rag_llm_llama2_llamaindex.py
   \```

## Usage

Query your indexed PDF documents using natural language:

- Input your questions or search terms in the provided query interface.
- The system retrieves relevant information from your document collection based on the queries.

## Features

- **Efficient Document Indexing**: Uses LlamaIndex for fast, scalable indexing of large document sets.
- **Powerful Query Capabilities**: Employs the Llama2 model for understanding and processing natural language queries.
- **Flexible Integration**: Designed for seamless operation with HuggingFace's transformers and other ML libraries.
- **GPU Optimization**: Optimized for T4 GPUs and above for high-speed processing and retrieval.

## Contributing

To contribute to the RAG system:

1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

