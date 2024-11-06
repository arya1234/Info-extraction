# Automated Information Extraction from Clinical Patient Notes

This project aims to develop an automated system for extracting and mapping clinical concepts from patient notes. The objective is to improve the scoring process of patient notes in medical licensing exams, making it faster, more transparent, and reliable by leveraging machine learning and natural language processing.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Model and Analysis](#model-and-analysis)
- [License](#license)

## Project Structure

The repository contains the following structure:

- **code/**: Contains all code files for preprocessing, model training, evaluation, and prediction.
- **model-img-and-analysis/**: Contains images of models, visualizations, and detailed analysis reports.
- **README.md**: This file, providing an overview of the project and instructions.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/arya1234/Info-extraction.git
   cd clinical-concept-mapping
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the model for clinical concept extraction and mapping:

1. Ensure you have all the dependencies installed.
2. Execute the main script in the **code/** directory:
   ```bash
   python code/evaluate.py
   ```
3. Results will be saved in the specified output directory, and analysis visuals will be available in **model-img-and-analysis/**.

## Model and Analysis

The **model-img-and-analysis** folder contains visualizations of the model performance, accuracy metrics, and analysis results. These include representations of feature extraction, concept mapping, and model evaluation. For a deeper understanding of the model and its results, explore this folder.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
