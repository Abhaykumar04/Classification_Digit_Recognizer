# Classification Digit Recognizer

This project implements a digit recognizer using machine learning algorithms, specifically Support Vector Machines (SVM) and Logistic Regression. The goal is to correctly classify handwritten digits from the famous digit dataset using these classification models.

## Dataset

### Seaborn Digit Dataset

The digit dataset used in this project is sourced from Seaborn, a Python data visualization library. It provides a preprocessed version of the well-known MNIST dataset, which consists of 70,000 grayscale images of handwritten digits (0 to 9) with a resolution of 28x28 pixels.

## Installation

To run the digit recognizer locally, follow these steps:

### 1. Clone the Repository

```
git clone https://github.com/your-username/digit-recognizer.git
```

### 2. Set Up Dependencies

- Make sure you have Python 3.7 or above installed on your machine.
- Install the required dependencies by running the following command:

```
pip install numpy pandas seaborn scikit-learn
```

## Usage

To use the digit recognizer, follow these steps:

### 1. Navigate to the Project Directory

```
cd digit-recognizer
```

### 2. Run the Script

```
python digit_recognizer.ipynb
```

The script will train the SVM and logistic regression models on the digit dataset and evaluate their performance. Additionally, it will generate a set of misclassified images with their corresponding labels, providing insights into the models' weaknesses.

## Results

After running the `digit_recognizer.ipynb` script, the following results will be displayed:

- Accuracy of the SVM model: 98%
- Accuracy of the logistic regression model: 96%

The misclassified images will be saved in the `misclassified_images` directory, allowing you to visually inspect the cases where the models failed to correctly classify the digits.

![image](https://github.com/Abhaykumar04/Classification_Digit_Recognizer/assets/112232080/05505759-326d-4710-bfaf-89908f48da7e)

## Contributing

Contributions to this digit recognizer project are welcome! If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. Your feedback and contributions will be greatly appreciated.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- The digit dataset used in this project is sourced from Seaborn.
- Special thanks to the scikit-learn library for providing the SVM and logistic regression implementations.

Feel free to modify this README file to suit your project structure and specific details.
