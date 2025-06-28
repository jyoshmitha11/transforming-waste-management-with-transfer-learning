# transforming-waste-management-with-transfer-learning
♻️ CleanTech: Transforming Waste Management with Transfer Learning
CleanTech is a deep learning project that classifies images of municipal solid waste into three categories — Biodegradable, Recyclable, and Trash — using transfer learning with a pre-trained VGG16 model. The system helps automate waste categorization, contributing to smarter and more efficient waste management solutions.

The model is trained on a Kaggle dataset with techniques such as image augmentation and early stopping to improve accuracy and reduce overfitting. It supports prediction on individual images and saves the trained model for future use.

🔍 Key Features
Preprocessed dataset split into training, validation, and test sets
Data augmentation to boost model generalization
Transfer learning with VGG16 for efficient training
Early stopping to avoid overfitting
Model saved as .h5 for later inference
Predicts waste category from individual images
📦 Dataset
Sourced from: Kaggle - Municipal Solid Waste Dataset

Contains labeled images of waste categorized into:

Biodegradable
Recyclable
Trash
🚀 How to Use
Download the dataset using the Kaggle API.
Run the training script or notebook to train the model.
Use the saved model (internship1.h5) for making predictions on new images.
