# ELEVATELABS-TASK5
# Task 5: Decision Trees and Random Forests

## Objective:

Learn and apply tree-based models for classification using Decision Tree and Random Forest algorithms.

## Dataset:

The dataset (`heart.csv`) contains patient-level medical data used to predict the presence (`target=1`) or absence (`target=0`) of heart disease.

## Steps Performed:

1. **Loaded and explored dataset** using pandas.
2. **Trained a Decision Tree Classifier** and visualized it using `plot_tree`.
3. **Analyzed overfitting** by comparing training vs. test accuracy and pruning the tree with `max_depth`.
4. **Trained a Random Forest Classifier** and compared accuracy with the decision tree.
5. **Plotted feature importances** for the Random Forest.
6. **Evaluated models using cross-validation** for robust performance metrics.

## Tools Used:

 - Scikit-learn
 - Graphviz
 - Matplotlib
 - Google Colab (execution environment)

## Results:

 - The pruned decision tree generalizes better than the default deep tree.
 - Random Forest outperformed individual decision tree in accuracy.
 - Top features were identified via Random Forest importance plot.
 - Cross-validation ensured performance stability across folds.

## Dependencies:

Make sure to install the following:

 -pip install graphviz
 -apt-get install -y graphviz

