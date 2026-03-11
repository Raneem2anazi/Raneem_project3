# Project 3: Instruction Following and Evaluation

## Project Overview
This project explores how well a language model can follow instructions.

We use the Dolly-15k dataset from Hugging Face, which contains around 15,000 human-written instruction and response pairs.

The goal of this project is to test how a language model responds to instructions using different prompting methods.

## Dataset
Dataset used in this project: Dolly-15k

Each example in the dataset contains:
- Instruction
- Response
- Category

## Model
The model used in this project is FLAN-T5 from Hugging Face.

FLAN-T5 is an instruction-following language model designed to generate responses based on instructions.

## Experiments
In this project we perform the following experiments:

- Exploratory Data Analysis (EDA) to understand the dataset
- Zero-shot prompting
- Few-shot prompting
- Comparing model responses with the true answers

## Tools
Tools used in this project:

- Python
- Hugging Face Transformers
- Pandas
- Matplotlib
- Google Colab

## Repository Structure

instruction_following_project.ipynb → Main notebook containing all experiments

problem_statement.md → Description of the problem

evaluation_report.md → Evaluation of the model results


