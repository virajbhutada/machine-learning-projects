

## Image Classification - SVM

**Overview:**
This repository features the implementation of a Support Vector Machine (SVM) model for classifying images of cats and dogs from the Kaggle dataset. The project explores the application of SVMs in handling high-dimensional image data, emphasizing feature extraction, model training, evaluation, and parameter optimization.

**Dataset:**
The training archive comprises 25,000 images of dogs and cats. The project focuses on training the SVM model using these files to enable accurate classification. Subsequently, the trained model predicts labels for test1.zip, differentiating between dogs (1) and cats (0).

Dataset: https://www.kaggle.com/c/dogs-vs-cats/data

**Project Tasks:**

**1. Data Preprocessing:**
- Loaded and processed cat and dog images from the Kaggle dataset.
- Extracted HOG features and created a structured data frame with labels for model training.

**2. Model Training and Evaluation:**
- Built an SVM model using sci-kit-learn, employing a linear kernel for initial training.
- Split the data into training and testing sets, and evaluated the model using accuracy, precision, and recall metrics.

**3. Parameter Optimization:**
- Utilized grid search to find optimal parameters, including the percentage of principal components and the choice of SVM kernel (linear, RBF, poly, sigmoid).
- Identified the best-performing configuration: 90% of principal components and the RBF kernel, achieving an accuracy of approximately 67.57%.

**4. Visualization and Interpretation:**
- Visualized model performance using a confusion matrix, providing insights into true positive and true negative predictions.
- Concluded the project, emphasizing the significance of parameter tuning and feature selection for enhancing classification accuracy.

**Project Outcome:**
- Accuracy: ~67.57%
- Best Parameters: PCA (90% components), SVM Kernel (RBF)
- Conclusion: The optimized SVM model effectively classified cats and dogs images, showcasing the importance of fine-tuning parameters. This achievement sets the stage for future advancements in image recognition and computer vision applications.

**Technologies Used:**
- Python: A programming language for data analysis and model implementation.
- Scikit-Learn: Machine learning library for building and evaluating SVM models.
- Matplotlib and Seaborn: Libraries for data visualization.
- Jupyter Notebook: Interactive platform for running Python code and documenting the project.

