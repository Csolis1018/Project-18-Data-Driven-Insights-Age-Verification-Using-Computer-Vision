# Data-Driven Insights: Age Verification Using Computer Vision

This project evaluates whether computer vision techniques can help Good Seed, a supermarket chain, comply with alcohol sales regulations by automatically verifying customer age at checkout. The goal is to determine if a machine learning model can reliably estimate a person’s age from facial images captured by in-store cameras.

The solution focuses on model accuracy, ethical considerations, and practical feasibility in a retail environment.

# Objective

To test the following hypothesis:

A computer vision model can accurately estimate customer age from images, supporting age verification and reducing the risk of alcohol sales to underage customers.

# 🛠️ Technologies Used

Python: Pandas, NumPy

Deep Learning Frameworks: TensorFlow / Keras

Computer Vision: Convolutional Neural Networks (CNNs)

Jupyter Notebook (GPU): Model training and evaluation

Image Dataset: Labeled facial images with age information

# Key Steps
# Data Description

Loaded and examined the image dataset containing facial photographs and corresponding ages.

Reviewed image dimensions, label distribution, and dataset size.

# Exploratory Data Analysis

Analyzed age distribution to identify potential imbalance.

Visualized sample images to assess data quality and variability.

Evaluated potential biases and challenges in age estimation.

# Model Development

Built a convolutional neural network for age prediction.

Trained the model using GPU acceleration to improve performance.

Applied appropriate loss functions and optimization techniques.

# Model Evaluation

Evaluated model performance using regression-based metrics (e.g., MAE).

Analyzed prediction errors across different age groups.

Assessed model reliability for age verification use cases.

# Conclusions and Practical Implications

Interpreted model results in the context of legal compliance.

Discussed limitations and ethical considerations of automated age estimation.

Evaluated whether the model is suitable as a decision-support tool rather than a fully autonomous system.

# Results

The analysis shows that:

Computer vision models can estimate age with reasonable accuracy.

Prediction errors vary across age groups, with higher uncertainty near legal age thresholds.

The model can serve as a supportive tool to assist human decision-making at checkout.

Automated age verification can reduce compliance risks when used responsibly.

These findings suggest that computer vision can enhance regulatory compliance in retail environments when combined with proper safeguards.
