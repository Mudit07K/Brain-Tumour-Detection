Brain Tumor Classification Using CNN

This project builds and trains a Convolutional Neural Network (CNN) to classify brain tumor images. The model processes MRI scan images and predicts whether a tumor is present.
📚 Project Overview
Objective

    Preprocess MRI scan images.
    Split the dataset into training, validation, and test sets.
    Create a CNN model with optimized architecture.
    Train and evaluate the model using accuracy and loss metrics.

🗂️ Dataset Information

    Dataset: MRI Brain Tumor Images
    Classes:
        Tumor
        No Tumor
    Image Format: JPEG/PNG

🧩 Key Project Stages
1. Data Preprocessing

    Loaded image data and applied preprocessing.
    Resized images to a uniform dimension.
    Converted images to arrays and normalized pixel values.
    Split the data into training, validation, and test sets.

2. Dataset Splits

    Train Set: 70% of the data
    Validation Set: 15% of the data
    Test Set: 15% of the data

3. Model Creation

    Designed a CNN architecture with the following layers:
        Conv2D - Extracts features from images.
        MaxPooling2D - Reduces dimensionality.
        Flatten - Converts the matrix to a vector.
        Dense - Fully connected layers for classification.
    Applied Dropout to prevent overfitting.

🎯 Model Evaluation

    Used binary cross-entropy as the loss function.
    Evaluated model performance using:
        Accuracy
        Loss
    Visualized training vs. validation accuracy and loss.

📈 Results and Visualizations

    Displayed accuracy and loss curves.
    Compared predicted labels with true labels on test data.

🔥 Future Enhancements

    Incorporate data augmentation to improve model generalization.
    Explore transfer learning using pre-trained models (e.g., VGG16, ResNet).

🛠️ Dependencies

    Python 3.x
    Key Libraries:
        numpy, matplotlib, seaborn, opencv-python
        tensorflow, keras
        scikit-learn
