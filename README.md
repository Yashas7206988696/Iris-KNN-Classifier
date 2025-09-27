# Iris-KNN-Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yashas7206988696/Iris-KNN-Classifier/blob/main/code.ipynb)

## Project Overview

This project implements a **K-Nearest Neighbors (KNN) classifier** for the famous Iris flower dataset. The implementation demonstrates machine learning fundamentals including data preprocessing, model training, evaluation, and visualization using Python and scikit-learn.

## KNN Methodology

The K-Nearest Neighbors algorithm is a simple, yet powerful supervised learning algorithm:

- **Algorithm Type**: Instance-based learning (lazy learning)
- **Decision Rule**: Classifies data points based on the majority class of k nearest neighbors
- **Distance Metric**: Euclidean distance used to find nearest neighbors
- **K Value**: Default k=3 neighbors considered for classification
- **Training**: No explicit training phase - stores all training data
- **Prediction**: For each test point, finds k closest training points and assigns majority class

### Key Features:
- Non-parametric algorithm (no assumptions about data distribution)
- Simple yet effective for many classification problems
- Performance can be optimized by tuning the k parameter
- Works well with small to medium-sized datasets

## Dataset Overview

The **Iris dataset** is one of the most famous datasets in machine learning:

- **Samples**: 150 flower samples
- **Classes**: 3 species (Setosa, Versicolor, Virginica) - 50 samples each
- **Features**: 4 measurements per flower:
  - Sepal Length (cm)
  - Sepal Width (cm) 
  - Petal Length (cm)
  - Petal Width (cm)
- **Balance**: Perfectly balanced dataset with equal class distribution
- **Linearity**: Classes are linearly separable with good feature separation

## Code Features

This implementation includes:

### ✨ Core Functionality
- **Data Loading**: Automatic loading of Iris dataset from scikit-learn
- **Data Splitting**: 80/20 train-test split with stratification
- **KNN Training**: Implementation with default k=3 neighbors
- **Model Evaluation**: Comprehensive performance metrics

### 📊 Analysis & Visualization
- **Accuracy Calculation**: Overall model performance measurement
- **Confusion Matrix**: Detailed classification results breakdown
- **Classification Report**: Precision, recall, and F1-scores per class
- **Scatter Plot Visualization**: Sepal length vs width with species coloring
- **Performance Summary**: Clear output of all metrics

### 🔧 Technical Features
- Clean, well-commented Python code
- Modular structure for easy understanding
- Error handling and data validation
- Reproducible results with random state control
- Compatible with Google Colab and Jupyter notebooks

## Requirements

Ensure you have the following Python packages installed:

```bash
pip install scikit-learn pandas matplotlib numpy
```

### Package Versions
- `scikit-learn >= 0.24.0`
- `pandas >= 1.2.0`
- `matplotlib >= 3.3.0`
- `numpy >= 1.19.0`

## Quick Start

### Option 1: Run in Google Colab (Recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yashas7206988696/Iris-KNN-Classifier/blob/main/code.ipynb)

### Option 2: Local Setup

```bash
git clone https://github.com/Yashas7206988696/Iris-KNN-Classifier.git
cd Iris-KNN-Classifier
pip install scikit-learn pandas matplotlib numpy
```

Then run the Jupyter notebook.

## Results

The KNN classifier typically achieves:
- **Accuracy**: ~95-98% on test data
- **Perfect Classification**: Often 100% accuracy on Setosa class
- **Good Separation**: Clear decision boundaries between species
- **Fast Training**: Instant model preparation
- **Quick Prediction**: Efficient classification of new samples

## 🚀 Google Colab Integration

This project is optimized for Google Colab with zero setup required. Click the Colab badge to start immediately!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Yashas7206988696/Iris-KNN-Classifier/blob/main/code.ipynb)

## Learning Outcomes

After running this project, you'll understand:
- How KNN algorithm works in practice
- Data preprocessing and train-test splitting
- Model evaluation using multiple metrics
- Visualization of classification results
- Using scikit-learn for machine learning tasks
- Interpreting confusion matrices and classification reports

## Next Steps

- Experiment with different k values (k=1, 5, 7, etc.)
- Try different distance metrics (Manhattan, Minkowski)
- Apply feature scaling/normalization
- Compare with other algorithms (SVM, Decision Trees, Random Forest)
- Implement cross-validation for more robust evaluation

## Contributing

Feel free to fork this repository and submit pull requests for improvements!

## License

This project is open source and available under the MIT License.
