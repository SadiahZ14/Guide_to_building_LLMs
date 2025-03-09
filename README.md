# LLM from Scratch

This repository contains code and resources for building a Language Model from scratch. The project follows Sebastian Raschka's teachings on LLM building, with some variations I might practice as exercises. This project is focused on understanding the fundamentals of language modeling and transformer architecture through hands-on implementation.

## Project Structure

- `LLM_scratch.ipynb`: Main Jupyter notebook containing the implementation and explanations
- `the-verdict.txt`: Sample text dataset used for training and testing

## Features

- Text tokenization and preprocessing
- Vocabulary building
- Simple tokenizer implementation
- Language model architecture (in progress)

## Getting Started

### Prerequisites

- Python 3.12+ (3.12.1 recommended)
- Jupyter Notebook
- Required Python packages:
  - numpy
  - pandas
  - matplotlib
  - torch (PyTorch)
  - re (Regular Expressions)
  - urllib

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/LLM-from-scratch.git
   cd LLM-from-scratch
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install required packages:
   ```
   pip install numpy pandas matplotlib torch
   ```

4. Launch Jupyter Notebook:
   ```
   jupyter notebook
   ```

5. Open `LLM_scratch.ipynb` to explore the implementation

## Resources

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Original Transformer paper
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) - Visual guide to transformers
- [LLMs from Scratch](https://github.com/rasbt/LLMs-from-scratch) - Sebastian Raschka's reference implementation

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- This project includes learning from Sebastian Raschka's teachings on LLM building and some variations I might practice as exercises
- Sample text from "The Verdict" by Edith Wharton 