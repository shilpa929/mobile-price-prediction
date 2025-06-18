# Mobile Phone Price Range Prediction

**Author:** Shilpa Roy

## Description

This project predicts the price range of mobile phones based on various features using machine learning (Random Forest Classifier).

## How to Run

1. Ensure you have Python 3.x installed.
2. Install the required libraries:
   ```
   pip install pandas numpy scikit-learn matplotlib seaborn joblib
   ```
3. Place `dataset.csv` in the project folder.
4. Run the Jupyter notebook (`project_notebook.ipynb`) step by step.

## Files

- `project_notebook.ipynb`: Main notebook with all code and explanations.
- `dataset.csv`: Dataset used for training and testing.
- `rf_model.pkl`, `scaler.pkl`: Saved model and scaler files.
- `EDA.py`, `model_training.py`, `predict_newph.py`: Python scripts for different stages.
- `report.pdf` (or `.docx`): Detailed project report.

## Tech Stack
- Python 3.x
- scikit-learn
- pandas, numpy
- seaborn, matplotlib
- joblib


## Example Result

- Best model accuracy: 0.88 (Random Forest)
- Most important feature: RAM

## License

For academic use only.
