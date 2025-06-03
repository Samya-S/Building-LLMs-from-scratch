# Building Large Language Models from Scratch

A practical guide to building and understanding Large Language Models (LLMs) from the ground up. This repository implements the concepts from Sebastian Raschka's work, providing hands-on experience with real code implementations for anyone interested in learning about large language models.

## Project Chapters and Learning Path

The repository is organized into chapters, each focusing on different aspects of building and understanding LLMs:

- **[Chapter 1: Understanding LLMs](Chapter%201%20-%20Understanding%20LLMs/)** - Fundamental concepts and theory
- **[Chapter 2: Working with text data](Chapter%202%20-%20Working%20with%20text%20data/)** - Data preprocessing and handling
- **[Chapter 3: Coding attention mechanisms](Chapter%203%20-%20Coding%20attention%20mechanisms/)** - Implementation of attention mechanisms
- **[Chapter 4: Implementing a GPT model from scratch](Chapter%204%20-%20Implementing%20a%20GPT%20model%20from%20scratch%20to%20generate%20text/)** - Building a basic GPT model
- **[Chapter 5: Pretraining on unlabeled data](Chapter%205%20-%20Pretraining%20on%20unlabeled%20data/)** - Training the model on raw text
- **[Chapter 6: Fine-tuning for classification](Chapter%206%20-%20Fine-tuning%20for%20classification/)** - Adapting the model for specific tasks
- **[Chapter 7: Fine-tuning to follow instructions](Chapter%207%20-%20Fine-tuning%20to%20follow%20instructions/)** - Instruction tuning and alignment

## Resources

- [`Building LLMs from scratch.ipynb`](Building%20LLMs%20from%20scratch.ipynb): Main Jupyter notebook containing the implementation
- [`Build a Large Language Model (From Scratch) - Sebastian Raschka.pdf`](Build%20a%20Large%20Language%20Model%20%28From%20Scratch%29%20-%20Sebastian%20Raschka.pdf): Reference book
- [`Original LLMs-from-scratch repository`](https://github.com/rasbt/LLMs-from-scratch): Sebastian Raschka's official repository

## Getting Started

1. Clone this repository
2. Install Python 3.x if not already installed:
   - Download from [python.org](https://www.python.org/downloads/)
   - Or use your system's package manager
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Requirements

The project requires the following main dependencies (see [`requirements.txt`](requirements.txt)):

- Python 3.x
- PyTorch
- tiktoken
- numpy
- matplotlib
- pandas
- tensorflow (>=2.15.0)
- tqdm (>=4.66)

## License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Acknowledgments

- Based on the work of [Sebastian Raschka](https://sebastianraschka.com/)
- Special thanks to [Vizuara's YouTube playlist](https://www.youtube.com/playlist?list=PLPTV0NXA_ZSgsLAr8YCgCwhPIJNNtexWu) on Building LLMs from scratch