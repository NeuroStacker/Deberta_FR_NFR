# Project Overview

This project leverages the DeBERTa (Decoding-enhanced BERT with disentangled attention) model for natural language processing (NLP) tasks. The workspace is structured to facilitate experimentation, training, and evaluation of the model.

**Model Performance:**

* Achieved **90% accuracy** on the classification task.

## Workspace Structure

```
├── deberta.ipynb        # Jupyter Notebook for experiments and exploration
├── FR_NFR_Dataset.xlsx  # Dataset file in Excel format for training and evaluation
├── test.py              # Python script to test specific functionalities
└── deberta_model/       # Directory containing model files and configurations
    ├── added_tokens.json
    ├── config.json
    ├── model.safetensors
    └── checkpoint-2756/ # Checkpoint files for resuming training or inference
```

## Getting Started

### Prerequisites

* Python 3.7 or higher
* (Optional) Virtual environment tool such as `venv` or `conda`

### Installation

1. Clone the repository or download the project files:

   ```bash
   git clone https://github.com/NeuroStacker/Deberta_FR_NFR
   ```
2. Navigate to the project directory:

   ```bash
   cd 
   ```
3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook and open `deberta.ipynb` to explore and run experiments:

   ```bash
   jupyter notebook deberta.ipynb
   ```
2. Execute cells to train, evaluate, and analyze the DeBERTa model.
3. Use `test.py` to run unit tests or specific functionality checks:

   ```bash
   python test.py
   ```
4. Adjust model configurations in `deberta_model/config.json` or update tokenizer settings as needed.

## Notes

* The `FR_NFR_Dataset.xlsx` file contains labeled data for functional requirement (FR) vs. non-functional requirement (NFR) classification.
* Use the checkpoint files in `deberta_model/checkpoint-2756/` to resume training or perform inference without retraining from scratch.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your branch.
4. Open a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
