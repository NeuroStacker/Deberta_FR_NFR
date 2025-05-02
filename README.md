# Project Overview

This project leverages the DeBERTa (Decoding-enhanced BERT with disentangled attention) model for natural language processing (NLP) tasks. The workspace is structured to facilitate experimentation, training, and evaluation of the model.

## Workspace Structure

- **deberta.ipynb**: A Jupyter Notebook for running experiments and exploring the DeBERTa model.
- **FR_NFR_Dataset.xlsx**: Dataset file in Excel format, used for training and evaluation.
- **test.py**: A Python script for testing specific functionalities of the project.
- **deberta_model/**: Directory containing the DeBERTa model files and configurations.
  - `added_tokens.json`, `config.json`, `model.safetensors`, etc.: Files related to the model and tokenizer.
  - **checkpoint-2756/**: Directory containing checkpoint files for resuming training or inference.

## Getting Started

### Prerequisites

Ensure you have Python installed on your system. It is recommended to use a virtual environment to manage dependencies.

### Installation

1. Clone the repository or download the project files.
2. Navigate to the project directory.
3. Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Usage

1. Open `deberta.ipynb` in Jupyter Notebook to explore and run the model experiments.
2. Use `test.py` to test specific functionalities.
3. Refer to the `deberta_model/` directory for model configurations and checkpoints.

## Notes

- The `FR_NFR_Dataset.xlsx` file contains the dataset used for training and evaluation.
- Checkpoints in `deberta_model/checkpoint-2756/` can be used to resume training or for inference.
- Modify the configurations in `config.json` or other related files as needed for your specific use case.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.