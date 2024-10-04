# ML_Book_Rating_Project
# Overview
This project uses machine learning techniques to predict book ratings based on various features like the number of pages, language, author, publisher, and ratings count. The project applies different regression models, including Random Forest and Multiple Linear Regression, to evaluate which performs best.

The final model uses Random Forest Regression with hyperparameter tuning and achieves a mean squared error (MSE) of 0.02956 and an R² score of 0.7499.

Repository containing all the files and documents related to the DSTI Machine Learning project for books average rating prediction

#Project Structure
├── Excel Files/                 # Folder containing the dataset
├── Jupyter files/            # Jupyter notebooks used for experimentation
├── models/               # Trained models (optional)
├── src/                  # Python source code for the project
│   ├── data_preprocessing.py
│   ├── model_training.py
│   ├── evaluation.py
│   └── utils.py
├── README.md             # This README file
├── requirements.txt      # Python dependencies
└── LICENSE               # License for the project

#Dataset
The dataset used in this project contains book-related features such as:

Number of pages
Author
Publisher
Ratings count
Text reviews count
Publication date
You can either download the dataset from a known repository or include a placeholder explaining where and how to get it.

#Dataset Preparation
If you're using a custom dataset, you need to place it inside the data/ folder. Make sure to update the paths in the code if necessary.

#Notebooks
The notebooks/ folder contains Jupyter notebooks that were used for experimentation and visualization. You can run the notebooks to explore the data, train the models, and generate visualizations.
