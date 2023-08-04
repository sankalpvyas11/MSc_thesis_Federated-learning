# Privacy Preserving Machine Learning

This repository contains research and implementation for privacy-preserving techniques in machine learning models, specifically focusing on federated learning and its vulnerabilities.

## Project Overview

Federated learning allows machine learning models to be trained directly on decentralized devices, ensuring the data does not need to be shared or transferred. This repository investigates:

1. The development of a federated learning-based machine learning model for privacy preservation.
2. Potential vulnerabilities of federated learning to data poisoning attacks, such as label-flipping attacks.

The HAM10000 dataset, a collection of dermatoscopic images of common pigmented skin lesions, is used for these investigations.

## Technologies

This project leverages several key technologies:

- **Python**: The primary programming language used for the project.
- **PyTorch**: A powerful Python library for scientific computing, particularly targeted towards deep learning.
- **Jupyter Notebook**: An open-source web application that facilitates the creation and sharing of documents containing live code, equations, visualizations, and narrative text.

## Repository Contents

This repository contains a Jupyter Notebook, `HAM10000_flipped_+_final_code.ipynb`, which details the methodology and contains the implemented Python code for creating the federated learning model and demonstrating data poisoning attacks.

## Getting Started

To use this repository:

1. Clone the repository to your local machine.
2. Ensure the necessary software (Python, PyTorch, Jupyter Notebook) is installed.
3. Change the path of the excel file `hmnist_28_28_L.csv` to match the path of the code.
4. Open `HAM10000_flipped_+_final_code.ipynb` in Jupyter Notebook to view the code and related explanations.

## Contributing

Contributions to this research project are welcome. If you have suggestions or encounter issues, please open an issue in this repository.

## License

This project is licensed under the MIT License.
