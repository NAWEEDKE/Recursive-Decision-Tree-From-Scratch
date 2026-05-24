# Recursive Decision Tree Classifier from Scratch

An end-to-end implementation of a supervised Decision Tree Classifier engineered entirely from scratch using Python and NumPy. This project highlights foundational computer science concepts like tree data structures and recursive binary partitioning, combined with fundamental data science mathematics.

## Features
- **Pure NumPy Logic:** Built entirely without relying on external machine learning frameworks like `scikit-learn` for tree building or predictions.
- **Recursive Partitioning:** Leverages a top-down, greedy recursive function to build out node configurations.
- **Mathematical Splitting:** Uses Shannon Entropy and Information Gain metrics to discover optimal features and numerical thresholds.
- **Algorithmic Inference Engine:** Features a recursive tree-traversal prediction mechanism.
- **Visual Terminal Mapping:** Outputs clean, hierarchical ASCII-art tree structures using box-drawing characters for quick debugging and interpretation.

## Performance Benchmark
When validated against the classic **Fisher's Iris Dataset** using a 70/30 train-test split, the scratch model achieves matching performance metrics with industrial implementations:

- **Custom Scratch Model Accuracy:** 100.00%
- **Scikit-Learn Model Accuracy:** 100.00%

## File Structure
- `Decision_Tree_Classifier_from_Scratch.ipynb` - Core Google Colab notebook containing code blocks, test scripts, and matrix plots.
- `README.md` - Documentation.
