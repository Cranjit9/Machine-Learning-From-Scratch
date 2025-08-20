# Machine Learning from Scratch in R

**ML algorithms implemented from scratch using R**

This repository contains machine learning algorithm implementations built from the ground up in R, focusing on understanding the mathematical foundations and core concepts behind each algorithm.

## Project Goals

- **Learn by Building**: Understand ML algorithms by implementing them from scratch
- **Mathematical Foundation**: Focus on the math and logic behind each algorithm
- **Clean R Code**: Well-documented, readable R implementations
- **Educational Resource**: Serve as a learning tool for ML enthusiasts

## Algorithms Implemented

### Completed
- [ ] **Linear Regression** (Simple & Multiple) 
- [ ] **Logistic Regression**
- [ ] **K-Nearest Neighbors (KNN)**

### Planned Implementations
- [ ] **Naive Bayes**
- [ ] **Decision Tree**
- [ ] **Random Forest**
- [ ] **Support Vector Machine (SVM)**
- [ ] **K-Means Clustering**
- [ ] **Principal Component Analysis (PCA)**
- [ ] **Linear Discriminant Analysis (LDA)**
- [ ] **Perceptron**
- [ ] **AdaBoost**
- [ ] **Neural Network**

## Installation and Dependencies

This project uses the following R packages:

### Core Dependencies
- `tidyverse` - For data manipulation and visualization
- `dplyr` - For data wrangling
- `ggplot2` - For plotting and visualization

### Optional (for testing and data)
- `datasets` - For sample datasets
- `caret` - For model comparison and validation

### Install Dependencies

```r
# Install required packages
install.packages(c("tidyverse", "dplyr", "ggplot2", "datasets", "caret"))

# Or install all at once
packages <- c("tidyverse", "dplyr", "ggplot2", "datasets", "caret")
install.packages(packages)
```

## Usage

### General Structure
Each algorithm is implemented as a function-based approach with the following methods:
- `fit()` - Train the model
- `predict()` - Make predictions
- `evaluate()` - Calculate performance metrics
- `plot()` - Visualize results
- `get_coefficients()` - Extract model parameters

## Learning Resources

This repository is designed for:
- **Students** learning machine learning fundamentals
- **Practitioners** wanting to understand algorithms deeply
- **R Enthusiasts** interested in ML implementation
- **Anyone** curious about the math behind ML

## Contributing

This is a personal learning project, but suggestions and improvements are welcome! Feel free to:
- Open issues for bugs or suggestions
- Submit pull requests for improvements
- Share feedback on implementations

## Notes

**Important**: These implementations are for **educational purposes**.

*Built with R for learning Machine Learning from scratch*
