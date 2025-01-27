# CNN From Scratch Using NumPy  

This repository demonstrates how to build a Convolutional Neural Network (CNN) from scratch using only NumPy. By avoiding established deep learning frameworks like TensorFlow or PyTorch, the project dives into the foundational mechanics of CNNs, providing a deep understanding of their inner workings.  

## Overview  

The project includes:  
- Implementation of gradient checking to ensure the correctness of backpropagation computations.  
- Step-by-step backpropagation logic tailored for convolutional layers and fully connected layers.  
- Testing the CNN with sample images classified into three categories:  
  - **Benign**  
  - **Benign Without Callback**  
  - **Malignant**  

The data for testing purposes is sourced from the [CBIS-DDSM collection](https://www.cancerimagingarchive.net/collection/cbis-ddsm/).  

## Notebooks  

### 1. `gradient_checking.ipynb`  
This notebook performs gradient checking to verify the accuracy of the gradients computed during backpropagation. Gradient checking helps ensure that the numerical gradients closely match the analytical gradients, thus validating the implementation.  

### 2. `backpropagation.ipynb`  
This notebook contains the implementation of backpropagation for the CNN. It walks through the mathematical details and the computational graph for convolutional layers, activation functions, pooling layers, and fully connected layers.  

## Images  

Three sample images are included in this repository for **testing purposes only**:  
- **Benign**: A benign example image.  
- **Benign Without Callback**: A benign sample image without specific callback indicators.  
- **Malignant**: A malignant example image used for testing the model's inference capabilities.  

These images serve as a demonstration to evaluate the CNN's performance and are not used for training.  

## Features  

- **Pure NumPy Implementation**: All computations, from forward propagation to backpropagation, are implemented using NumPy, offering a transparent view of CNN operations.  
- **Hands-on Gradient Checking**: Debug and verify the backpropagation process with numerical gradient checking.  
- **Testing with Real-World Data**: Uses sample images from the CBIS-DDSM collection for testing classification outcomes.  

## Getting Started  

1. Clone the repository:  
   ```bash  
   git clone <repository_url>  
   cd <repository_name>  
2. Install dependencies
   ```bash
   pip install numpy notebook
3. Launch Jupyter Notebook and explore the notebooks
   ```bash
   jupyter notebook

## Data Source  

The test images in this repository are sourced from the [CBIS-DDSM collection](https://www.cancerimagingarchive.net/collection/cbis-ddsm/), a publicly available database of mammography images for research purposes.  

## Contributing  

Contributions are welcome! Feel free to open issues or submit pull requests if you'd like to improve or expand this project.  
