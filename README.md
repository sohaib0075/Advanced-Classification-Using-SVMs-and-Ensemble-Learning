# Advanced Classification Using SVMs and Ensemble Learning

A machine learning project that applies **Support Vector Machines (SVMs)** and **Ensemble Learning** techniques to classify pulsar stars from radio frequency data.

---

## Overview

Pulsars are a rare type of neutron star that emit detectable radio waves. This project uses advanced classification algorithms to distinguish real pulsars from noise/interference in the dataset.

---

## Dataset

| File | Description |
|------|-------------|
| `pulsar_data_train.csv` | Training data |
| `pulsar_data_test.csv` | Test data |
| `svm_pulsar_predictions.csv` | Model predictions output |

---

## Project Structure

```
├── code.ipynb                  # Main Jupyter notebook
├── pulsar_data_train.csv       # Training dataset
├── pulsar_data_test.csv        # Test dataset
├── svm_pulsar_predictions.csv  # Predictions output
├── report.pdf                  # Project report
└── README.md
```

---

## Models Used

- **Support Vector Machine (SVM)** — with various kernels (linear, RBF, polynomial)
- **Ensemble Methods** — combining multiple classifiers for improved accuracy

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sohaib0075/Advanced-Classification-Using-SVMs-and-Ensemble-Learning.git
   ```

2. Install dependencies:
   ```bash
   pip install numpy pandas scikit-learn matplotlib jupyter
   ```

3. Open the notebook:
   ```bash
   jupyter notebook code.ipynb
   ```

---

## Results

> See `report.pdf` for detailed results, evaluation metrics, and model comparisons.

---

## Tech Stack

- Python
- Scikit-learn
- Pandas & NumPy
- Jupyter Notebook
- Matplotlib

---

## Author

**Sohaib Shahzad** — [@sohaib0075](https://github.com/sohaib0075)

---

## License

This project is open source and available under the [MIT License](LICENSE).
