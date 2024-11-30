# LaTeX to Python Code Generation

## Overview
This project involves training a T5-based model to convert LaTeX equations into Python code. The goal is to generate Python code from mathematical LaTeX expressions.

## Approach
- We experimented with several T5-based architectures, including the use of noise and data augmentation to improve performance.
- We fine-tuned on various datasets to improve the accuracy of the conversion.

## Dataset
The training data consists of a set of LaTeX equations paired with Python code.

## Results
- Our model achieved an accuracy improvement of 90 % using noise and augmented data techniques.

## Getting Started
1. Clone the repository:
   ```bash
   git clone git@github.com:username/repository-name.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Train the model:
   ```bash
   python train.py
   ```

