# DSA Question Generation with Test Cases

## Overview
This project demonstrates how to generate Data Structures and Algorithms (DSA) questions along with test cases using the Mistral-7B-Instruct model from Hugging Face.

## Description
This script generates a DSA question based on a randomly selected topic such as Arrays, Linked Lists, Stacks and Queues, or Trees. The generated question includes a problem statement and example test cases to illustrate the problem effectively.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/dsa-question-generation.git
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the Mistral-7B-Instruct model from Hugging Face and place it in the project directory.

## Usage
After running the script, it will generate a DSA question with test cases based on a randomly selected topic. You can modify the script to customize the number of test cases generated or the topics for which questions are generated.

## Requirements
- Python 3.6 or later
- llama-cpp-python library for using the Mistral-7B-Instruct model
- ctypes library for interacting with the Llama model


