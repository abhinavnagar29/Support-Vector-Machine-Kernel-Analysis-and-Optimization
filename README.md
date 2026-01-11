# Support-Vector-Machine-Kernel-Analysis-and-Optimization


---

## 🚀 How to Run

### Prerequisites:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Run Notebooks:
```bash
# Open in Jupyter
jupyter notebook SVM.ipynb

# Or use Jupyter Lab
jupyter lab
```

### Execute:
1. Open notebook
2. Click **"Restart & Run All"**
3. Datasets download automatically from UCI
4. All outputs generate in ~2-3 minutes


---

## Notebook Structure:

**Part 1: Data Analysis and Preprocessing**
- Checking Data Quality
- Visualizing the Data

**Part 2: SVM Implementation and Analysis**
- Hyperparameter Optimization
- Running the Grid Search
- Mathematical Analysis: Visualizing the Results

**Part 3: Performance Evaluation**
- Cross-Validation Score Heatmap
- Learning Curves Analysis
- Confusion Matrices
- Visualizing Decision Boundaries

**Part 4: Analysis and Interpretation**
- Dataset-Specific Observations
- Recommendations for Production
- Results Summary

---

## Results Summary

### SVM (Banknote Authentication Dataset)
| Kernel | Parameters | Test Accuracy | Support Vectors |
|--------|------------|---------------|------------------|
| Linear | C=100 | 98.81% | 14 (1.38%) |
| Poly (d=2) | C=10, γ=0.1 | 80.47% | 603 (59.64%) |
| Poly (d=3) | C=100, γ=0.1 | 99.42% | 31 (3.06%) |
| **RBF** | **C=10, γ=0.1** | **100.00%** | **30 (2.97%)** |

**Best Configuration:** RBF kernel with C=10, γ=0.1 (perfect classification)

---




