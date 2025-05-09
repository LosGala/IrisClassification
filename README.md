Iris Dataset Classification using SVM (Polynomial Kernel)
This R project applies a Support Vector Machine (SVM) model with a polynomial kernel to the classic Iris dataset. It uses the caret package for preprocessing, training, and evaluating the model.

📂 Project Description
Loads the built-in iris dataset.

Performs a stratified split (80% training / 20% testing).

Trains a polynomial kernel SVM model.

Runs 10-fold cross-validation.

Evaluates performance using confusion matrices.

Displays feature importance.

📦 Libraries Used
r
Copiar
Editar
library(datasets)  # Contains the Iris dataset
library(caret)     # For machine learning model training and evaluation
🚀 How to Run
Open R or RStudio.

Make sure the required packages are installed:

r
Copiar
Editar
install.packages("caret")
Copy and run the full script in your R environment.

Check the printed confusion matrices and the feature importance plot.

🔍 Expected Output
Three confusion matrices: training, testing, and cross-validation.

Feature importance plot highlighting key predictors (e.g., Petal.Length).

Accuracy, sensitivity, and specificity scores of the model.

⚙️ Model Parameters
The SVM model is trained with the following fixed parameters:

degree = 1

scale = 1

C = 1

Data is preprocessed using standardization (center, scale) before training.

📝 Additional Notes
set.seed(100) ensures reproducibility.

The current model is simple and can be improved by hyperparameter tuning.

This script is ideal for beginners learning supervised classification in R.
