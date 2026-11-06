# Deep Learning Assignments

A collection of notebook-based deep learning projects covering neural networks, computer vision, sequence modeling, unsupervised learning, autoencoders, and sentiment analysis.

## Projects

| Folder | Project | Concepts |
|---|---|---|
| 01 | Neural Network Fundamentals | Building and training neural networks |
| 02 | CNN CIFAR-10 Image Classification | Convolutional neural networks and image classification |
| 03 | RNN Text Generation | Recurrent networks and sequence generation |
| 04 | SOM Customer Segmentation | Self-organizing maps and unsupervised learning |
| 05 | Autoencoders MNIST | Encoder-decoder networks and reconstruction |
| 06 | Deep Learning Sentiment Analysis Capstone | Text classification and sentiment analysis |

Each project folder includes a Jupyter notebook and its associated assignment brief. PDF instructions are retained with the assignments.

## Technology
- Python
- Jupyter Notebook
- Deep learning framework(s) imported by the individual notebooks
- NumPy, Pandas, and visualization libraries as required

## Requirements
Python 3, Jupyter Notebook/JupyterLab, and the framework versions compatible with each notebook. GPU/CUDA is optional unless a notebook's workload or framework setup specifically requires it.

## Getting started
```bash
git clone https://github.com/Siddharthsingh123456/Deep-Learning.git
cd Deep-Learning
python -m venv .venv
python -m pip install --upgrade pip
python -m pip install jupyter numpy pandas matplotlib
jupyter notebook
```

Install the deep learning framework required by the selected notebook separately, following its official installation instructions. Activate the virtual environment before running notebooks.

## Suggested workflow
1. Read the matching assignment PDF.
2. Inspect notebook cells and required datasets.
3. Set random seeds where supported.
4. Track training and validation metrics.
5. Evaluate on held-out data.
6. Discuss overfitting, class imbalance, and limitations.

## Reproducibility
Deep learning results can vary with random initialization, hardware, framework versions, and training settings. Record the environment and configuration when comparing results.

## License
No license file is currently specified. Contact the repository owner before reuse.
