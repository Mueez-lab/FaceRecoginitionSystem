🧑‍🦰 Face Recognition using PCA and SVM 📸

This project demonstrates face recognition using Principal Component Analysis (PCA) for dimensionality reduction and Support Vector Machine (SVM) for classification.
📂 Dataset

The project uses the 'face_data.csv' dataset, which contains images of faces. Each row represents an image, and the columns represent pixel values. The 'target' column indicates the identity of the person in the image.
🔧 Methodology
1. Data Loading and Preprocessing 📊

    Load the dataset using Pandas.

    Separate the pixel values (features) from the target labels.

2. Principal Component Analysis (PCA) 🔍

    Apply PCA to reduce the dimensionality of the dataset while retaining most of the variance.

    Determine the optimal number of principal components to keep using the explained variance ratio.

    Visualize the cumulative explained variance to justify the choice of the number of components.

3. Eigenfaces 👤

    Display the eigenfaces, which represent the principal components in the face space.

4. Support Vector Machine (SVM) 🤖

    Train an SVM classifier on the PCA-transformed data.

    Tune the hyperparameters of the SVM (e.g., kernel, C, gamma) for optimal performance.

5. Model Evaluation 📈

    Split the data into training and testing sets.

    Evaluate the model's performance using metrics like accuracy, precision, recall, and F1-score.

    Perform cross-validation to assess the model's generalization ability.

🛠 Requirements

    Python 3.x 🐍

    Libraries:

        NumPy 💡

        Pandas 📊

        Matplotlib 📈

        Scikit-learn 🧠

    Dataset: 'face_data.csv' 🗂️

🏃‍♂️ Usage

  Clone the repository from GitHub: 

    git clone <https://github.com/Mueez-lab/FaceRecoginitionSystem.git>

Install the required libraries:

    pip install -r requirements.txt

  Upload the 'face_data.csv' dataset to your Google Colab environment or local directory.

  Run the code in the provided Jupyter Notebook 📝.


📊 Results

Once you run the code, the following will be printed in the output:

  Classification Report 📃: The performance metrics for accuracy, precision, recall, and F1-score.

  Cross-validation Scores 💯: Evaluating the generalization ability of the model across multiple folds.

🌟 Acknowledgments

    The dataset used in this project is publicly available. 📅

    The code is inspired by various online resources and tutorials on face recognition. 👩‍💻
