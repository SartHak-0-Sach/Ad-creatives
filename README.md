# Ad-Creatives: An Image Classification Model for Advertisements detection🤖

## Welcome! 👋

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Key Features](#features)
  - [File Structure](#file-structure)
  - [technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Future Improvements](#future-improvements)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This project is focused on building and training a machine learning model that can distinguish between advertisements and non-advertisement images. By leveraging advanced image processing techniques and machine learning algorithms, the model can be used for various applications, such as filtering advertisement images from non-advertisement content.

### The challenge
The goal of this project is to build a machine learning model that can automatically classify images into advertisements or non-advertisements. The challenge involves:

- **Training the model** using labeled data (advertisements vs. non-advertisements).
- **Fine-tuning the model** to optimize performance and accuracy.
- **Deploying the solution** for real-time use in detecting ad content in images.

### Features
- **Advertisement Detection:** Classifies whether an image is an advertisement or not.
- **Pre-trained Model:** A trained model that can be used immediately to predict new images.
- **Customizable:** Can be further trained or tuned with new datasets to improve accuracy.
- **Notebook Implementation:** Jupyter notebook (`ad-creatives.ipynb`) for easy understanding and modification.

### File Structure
```
/root-directory
|-- .github/workflows/           # GitHub workflows for CI/CD
|-- .gitignore                   # Files to be ignored by Git
|-- LICENSE                      # Project license
|-- README.md                    # Project description and instructions
|-- ad-creatives.ipynb            # Jupyter Notebook with model training and testing
|-- info.txt                     # Project information and code description
|-- requirements.txt             # Python dependencies required for the project
```

### Technologies Used
- **Python**
- **TensorFlow/Keras** for machine learning model development
- **Jupyter Notebook** for code execution and visualization
- **OpenCV** for image processing
- **Scikit-learn** for model evaluation

## Setup Instructions

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Basic knowledge of machine learning and image processing

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ad-creatives.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ad-creatives
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter notebook:
   ```bash
   jupyter notebook ad-creatives.ipynb
   ```

### Usage
1. **Model Training:** The Jupyter notebook walks through the steps to load the dataset, train the model, and evaluate its performance.
2. **Model Prediction:** Once the model is trained, you can use it to predict whether a given image is an advertisement.

### Future Improvements
- Add more complex image augmentation techniques to improve model robustness.
- Incorporate more advanced architectures (e.g., transfer learning using pre-trained models).
- Deploy the model as a web application for real-time image classification.

### Useful resources

- [TensorFlow Keras Documentation](https://www.tensorflow.org/guide/keras) - This was immensely helpful in building the model architecture and fine-tuning it for classification tasks.
- [OpenCV Image Processing](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html) - A great guide to getting started with image manipulation techniques using OpenCV.
- [Scikit-learn Model Evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html) - Helped me understand different metrics for evaluating my model’s performance.

## Author

<b><strong>Sarthak Sachdev</strong></b>
- Website - [Sarthak Sachdev](https://itsmesarthak.netlify.app/)
- LinkedIn - [Sarthak Sachdev](https://www.linkedin.com/in/sarthak2004/)
- Twitter - [@sarthak_sach69](https://www.twitter.com/sarthak_sach69)

## Acknowledgments

I’d like to acknowledge the amazing open-source libraries and tools like TensorFlow, OpenCV, and Scikit-learn, which made this project possible. Additionally, a huge thanks to the helpful communities on GitHub and StackOverflow for always providing insightful solutions and advice.

## Got feedback for me?

I’d love to hear your thoughts! Please feel free to email me at saarsaach30[at]gmail[dot]com with any feedback or suggestions.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any new features or fixes.

## License📃
This project is licensed under the BSD 3-Clause License.

Copyright (c) 2024, Sarthak Sachdev

**Happy coding!** 😊🚀
