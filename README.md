# SC5002-Lab-Assignment-1

## Repository Contents
| `sc5002_lab_assignment_1.ipynb` | Completed Google Colab notebook containing the code and results for Tasks 2.1, 2.2 and 2.3. |

| `README.md` | Notebook Instructions |

## Notebook Instructions

### Tasks Covered
This Google Colab notebook implements Part 2 of SC5002 Lab Assignment 1:

- **Task 2.1:** Dataset Setup & AI Feature Analysis
- **Task 2.2:** Model Execution & Alpha Tuning 
- **Task 2.3:** Visual Analysis & Overfitting Insights

### How to Run
1. Open `SC5002_Assignment.ipynb` in this repository.
2. Click **Open in Colab** or upload the notebook to [Google Colab](https://colab.research.google.com/).
3. Connect to a runtime and run the code cells sequentially from top to bottom.
4. Review the outputs, cross-validation R² scores and model comparison chart.

### Libraries Used
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Experimental Setup
- Dataset: California Housing
- Sample size: 1,000 records
- Feature scaling: `StandardScaler`
- Evaluation metric: Mean 5-fold cross-validation R² score
- Ridge Regression alpha values: 0.1, 10.0 and 1000.0

The theoretical solutions for Part 1 and the Learn with AI deliverables are documented separately in the assignment report.
