# Convolutional Neural Network Project

This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras. The project goes through multiple stages including data preprocessing, CNN architecture creation, training, and evaluation.

## Project Structure

- **Part 1: Data Preprocessing**
    - Preprocessing techniques applied to training and test datasets using `ImageDataGenerator`.
  
- **Part 2: Building the CNN**
    - Layers are defined using Keras, starting with convolutional layers followed by pooling layers, flattening, and dense layers.
  
- **Part 3: Training the CNN**
    - The model is trained on the dataset, with a specified number of epochs, optimizer, and loss function.
  
- **Part 4: Model Evaluation**
    - The trained model is evaluated on a test dataset, and the performance is measured in terms of accuracy and loss.

## Libraries Used

- TensorFlow
- Keras
- NumPy
- Matplotlib (for visualization)

## How to Run the Project

1. Install the necessary libraries:
    ```bash
    pip install tensorflow numpy matplotlib
    ```

2. Load and preprocess the dataset as per the instructions in the notebook.

3. Build and train the CNN model.

4. Evaluate the performance of the model on the test set.

## Notes

- This project uses image data generators to preprocess the images (rescaling, rotating, etc.).
- Ensure that the dataset is properly organized into directories for training and testing.
