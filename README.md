## Amharic CBOW Word Embedding Model

This project implements the Continuous Bag-of-Words (CBOW) word embedding model for the Amharic language. It learns dense vector representations of Amharic words, useful for downstream NLP tasks like text classification, sentiment analysis, and language modeling.

### Features

- **CBOW-Based Word Embeddings**: Uses the Continuous Bag-of-Words approach to predict context words given a target word.
- **Amharic Language Support**: Specifically designed for Amharic's structure and morphology.
- **Pre-trained Embeddings**: Provides pre-trained embeddings on large Amharic corpora.
- **Tokenization**: Implements an Amharic-specific tokenizer for proper word segmentation.
- **Embeddings Visualization**: Supports 2D visualization of word embeddings for better exploration of word relationships.
- **Scalable Design**: Trains on large Amharic corpora for higher-quality embeddings.

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yordanoswuletaw/amharic-cbow-word-embedding.git
   ```
2. Navigate to the project directory:
   ```bash
   cd amharic-cbow-word-embedding
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## Repository Structure

```plaintext
├── .vscode/
│   └── settings.json            # VS Code settings for environment setup
├── .github/
│   └── workflows/
│       ├── unittests.yml        # CI/CD pipeline for unit tests
├── .gitignore                   # Ignored files and folders
├── requirements.txt             # Dependencies for the project
├── README.md                    # Documentation of the repository
├── data/                        # Dataset for training, dev, and testing
├── src/                         # Source code for training and processing
├── notebooks/
│   ├── __init__.py              # Package initialization
│   └── README.md                # Documentation for the notebooks
├── tests/
│   ├── __init__.py              # Test initialization
└── scripts/
    ├── __init__.py              # Scripts package initialization
    └── README.md                # Documentation for scripts
```

## Requirements

- Python 3.8+
- Required Python libraries (see `requirements.txt`)

---

## Future Work

  - Incorporate subword tokenization to better handle complex words.
  - Extend support to additional Amharic linguistic features such as prefixes and suffixes.

---

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to suggest improvements or report bugs.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

Special thanks to:
- The Amharic NLP community for providing open-source datasets and tools.

