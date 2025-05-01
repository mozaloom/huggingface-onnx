# HuggingFace ONNX

This repository demonstrates how to export and run Hugging Face models in ONNX format using GitHub Codespaces or a local setup with Conda.

## Repository Structure
```
├── LICENSE                 # License for this project
├── README.md               # This file
├── notebooks               # Jupyter notebooks with examples
│   ├── introduction.ipynb  # Overview of ONNX export workflow
│   └── exporting.ipynb     # Model export and inference examples
└── requirements.yml        # Conda environment specification
```

## Getting Started

### Using GitHub Codespaces
1. Create a new Codespace from this repository.
2. All dependencies will be automatically installed.
3. The notebooks will open ready to run.

### Local Setup via Conda
1. Create and activate a new Conda environment:
   ```bash
   conda env create -f requirements.yml
   conda activate huggingface-onnx
   ```
2. Launch Jupyter Notebook (or Lab):
   ```bash
   jupyter notebook
   ```
3. Open the notebooks in the `notebooks/` folder and select the `huggingface-onnx` environment kernel.

## Notebooks
- **introduction.ipynb**: Overview of ONNX, setup, and basic export workflow.
- **exporting.ipynb**: Step-by-step guide to export a Hugging Face model to ONNX and run inference with ONNX Runtime.

## Challenges
1. Port a different Hugging Face model to ONNX.
2. Explore and enable a model-specific ONNX feature (e.g., dynamic axes, quantization).
3. Load and run inference on your ONNX model using ONNX Runtime.

## Technologies Used
- [Hugging Face Transformers](https://github.com/huggingface/transformers)
- [ONNX](https://onnx.ai)
- [ONNX Runtime](https://github.com/microsoft/onnxruntime)
- GitHub Codespaces
- Conda

## Contributing
Contributions and improvements are welcome! Feel free to open issues or submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).

