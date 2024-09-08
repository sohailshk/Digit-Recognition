# Handwritten Digit Recognition Project

## Overview
This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits with an impressive 98.7% accuracy. It includes a web-based interface for real-time digit recognition, allowing users to draw digits and receive instant predictions.

## Features
- Interactive web-based drawing interface
- Real-time digit recognition
- High accuracy (98.7%) on the MNIST dataset
- Responsive design for various devices
- Easy-to-use clear and predict functionality

## Technologies Used
- Python 3.8+
- TensorFlow 2.x
- Keras
- OpenCV
- NumPy
- Matplotlib
- HTML5 Canvas
- JavaScript
- 
## Model Architecture
The CNN model consists of:
- 2 Convolutional layers with ReLU activation
- 2 MaxPooling layers
- Flatten layer
- Dropout layer (0.25 rate)
- Dense output layer with 10 units (one for each digit)
- OPtimized Dense layer rather than using softmax activation directly used optimized softmax for more accuracy

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/sohailshk/Digit-Recognition.git
   ```
2. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
3.run the noteobook on Google Collab

## Usage
3. Draw a digit on the canvas using mouse
5. Click "Predict" to see the model's prediction
6. Interactive Interface

## Training the Model
The model was trained on the MNIST dataset using data augmentation techniques. To retrain the model:
1. Ensure you have the MNIST dataset
2. Run the training script:
   ```
   python train_model.py
   ```

## Performance
- Accuracy on test set: 98.7%
- Training time: Approximately 2 minutes on Google Colab GPU

##SCREENSHOT
![image](https://github.com/user-attachments/assets/7e10aaa1-f83b-45c4-b1ff-904621a89222)



## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- The MNIST dataset providers
- TensorFlow and Keras documentation
- OpenCV community

## Contact
For any queries, please reach out to [Sohail] at [sohailsaif504@gmail.com].
