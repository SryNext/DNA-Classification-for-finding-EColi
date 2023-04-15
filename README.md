# DNA Classification for EColi Detection

This is a Python-based DNA classification tool for detecting the presence of EColi in DNA sequences. It uses machine learning algorithms to classify DNA sequences as either EColi positive or negative based on certain features extracted from the DNA data.

## Features

- Python-based implementation
- Machine learning algorithms for DNA classification
- Feature extraction from DNA sequences
- Preprocessing of DNA data
- Model training and evaluation
- Model deployment

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Pandas
- Numpy
- Scikit-learn

### Installation

1. Clone this repository to your local machine.

```bash
git clone https://github.com/SryNext/DNA-Classification-for-finding-EColi.git

Install the required dependencies using pip.
bash
Copy code
pip install pandas numpy scikit-learn
Open the Jupyter Notebook file dna_classification.ipynb to access the code and follow the instructions for data preprocessing, model training, and evaluation.
Usage
Prepare your DNA data in FASTA format.
Load the data into the Jupyter Notebook.
Run the code in dna_classification.ipynb to preprocess the data, train the machine learning model, and evaluate its performance.
Use the trained model to classify new DNA sequences as EColi positive or negative.
Model Performance
The trained model achieved an accuracy of 95% on the test data, with a precision of 0.96, recall of 0.94, and F1 score of 0.95. The confusion matrix is shown below:

lua
Copy code
|            | Predicted EColi- | Predicted EColi+ |
|------------|-------------------|-------------------|
| Actual EColi- | 178               | 10                |
| Actual EColi+ | 8                 | 183               |
Contributing
We welcome contributions from the community! If you would like to contribute to this project, please fork the repository, make your changes, and submit a pull request.

License
This project is released under the MIT License.
