# AI Assignment 1 – General-Purpose AI Reasoning System

A Python-based AI reasoning system developed as part of an academic assignment at IIT Jodhpur. The project explores logical reasoning, inference, and counterfactual reasoning using multiple benchmark datasets.

## Project Overview

The objective of this project is to build and evaluate an AI reasoning system capable of processing logical statements, applying reasoning rules, and generating conclusions.

The implementation uses a rule-based reasoning approach with logical inference and a basic causal reasoning component.

## Key Features

- Logical fact and rule representation
- Forward-chaining inference
- Rule-based reasoning
- Basic counterfactual reasoning
- Evaluation using multiple reasoning datasets
- Accuracy and inference-time measurement

## Datasets

The system was evaluated using the following datasets:

1. **RuleTaker** – Used to evaluate logical reasoning and inference.
2. **CounterBench** – Used to evaluate counterfactual reasoning.
3. **FOLIO** – Used to evaluate reasoning over first-order logic statements.

## Evaluation Results

The following results are based on the recorded notebook evaluation outputs.

| Dataset | Samples | Accuracy |
|---|---:|---:|
| RuleTaker | 1,500 | 63.87% |
| CounterBench | 1,200 | 51.67% |
| FOLIO | 204 | 33.82% |
| **Overall Average** | **2,904** | **49.79%** |

### Overall Inference Time

**Average inference time:** 0.000226356 seconds per sample.

*Note: Inference time is based on the recorded notebook measurements and may vary depending on the execution environment.*

## Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Logical reasoning and rule-based inference
- Benchmark dataset evaluation

## Repository Structure

```text
AI-Assignment_1/
│
├── AI_Ass1
├── report.pdf
├── submission.csv
└── README.md
```

## How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook.
3. Install the required Python libraries if they are not already installed.
4. Execute the notebook cells in sequence.
5. Review the evaluation results.

## Author

**Junaid Ahmed**  
M.Tech – Robotics  
Indian Institute of Technology Jodhpur

**Roll Number:** M26MER001


