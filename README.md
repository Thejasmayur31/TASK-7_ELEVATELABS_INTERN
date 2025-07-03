# TASK-7_ELEVATELABS_INTERN
This project uses Support Vector Machines (SVM) to predict whether a person has sought mental health treatment based on a variety of features like age, gender, family history, work environment, and company culture. The data comes from a publicly available survey focused on mental health in the tech industry.

The objective is to demonstrate how SVM can be used for both linear and non-linear classification problems, along with proper data preprocessing, dimensionality reduction using PCA, model evaluation, and hyperparameter tuning.

The dataset is sourced from the OSMI Mental Health in Tech Survey and includes both categorical and numerical variables. The main target variable is treatment, which indicates whether the individual has ever sought treatment for mental health conditions.

The project workflow includes:

Loading and preprocessing the data – Handling missing values, encoding categorical variables using LabelEncoder, and standardizing the features using StandardScaler.

Training SVM models – We train two SVM classifiers: one using a linear kernel and the other using an RBF (Radial Basis Function) kernel to capture non-linear relationships in the data.

Visualizing the decision boundary – To better understand the classifier's behavior, we reduce the data to two dimensions using PCA and plot the decision boundary of the RBF SVM model.

Hyperparameter tuning – We use GridSearchCV to find the best values for the parameters C and gamma, which control the margin and complexity of the SVM respectively.

Evaluating model performance – We evaluate the trained models using accuracy and 5-fold cross-validation scores to ensure the model generalizes well to unseen data.
