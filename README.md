# Breast Cancer Classification Using SVM

This project implements a Support Vector Machine (SVM)-based binary classification model to detect breast cancer using two key features: radius_mean and texture_mean from the Breast Cancer Wisconsin dataset.

Dataset:

The dataset used (breast-cancer.csv) contains features computed from digitized images of fine needle aspirate (FNA) of breast masses. The target variable is diagnosis, which is mapped to:

M → Malignant (1)

B → Benign (0)


Features Used:

radius_mean

texture_mean


Models Used:

Linear SVM (kernel='linear')

RBF SVM (kernel='rbf', gamma=0.5)


Workflow:

1. Load dataset using pandas.


2. Select relevant features and encode target.


3. Split data into training and testing sets.


4. Normalize features using StandardScaler.


5. Train and evaluate both linear and RBF SVM models.


6. Plot decision boundaries for visual comparison.



Output:

Visual decision boundaries for both SVM kernels are plotted using matplotlib.
