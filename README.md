# SmartChessAI

__SmartChessAI__ for Chess Piece Recognition leverages advanced artificial intelligence to accurately identify and classify chess pieces under various conditions. This project aims to enhance applications such as digital chessboards, automated game analysis, and more, ensuring precise and efficient recognition.

## Features
- __Accurate Chess Piece Identification:__ Utilizes state-of-the-art deep learning models to recognize and classify chess pieces with high precision.
- __Deep Learning model:__ Utilizes the ResNetV2 architecture as the backbone for feature extraction and classification.
- __Preprocessing:__ Includes preprocessing steps such as image normalization and augmentation to enhance model performance.
- __Versatile Application:__ Adaptable to different chessboard designs, lighting conditions, and angles.
- __User-Friendly Integration:__ Easy to integrate with other systems and user interfaces.

## Model Architecture
The project uses the ___InceptionResNetV2___ model as the backbone, fine-tuned for the specific task of chess piece recognition. This pre-trained model, known for its high performance on image classification tasks, is further enhanced for our dataset.

![](https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMWw3MzdiNzh5M2MzZGhtaGt3dnEwdGpxYzNtYWZzc2JnY2lqY2hmayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xSi0vyq0FI6Os/giphy.webp)


## Dataset
Our dataset includes labeled images of all types of chess pieces (pawn, knight, bishop, rook, queen, king) in both black and white colors, collected from various sources. The dataset is split into training, validation, and test sets for effective model training and evaluation.

## Installation
### Prerequisites
  - Python 3.x
  - Jupyter Notebook
### Steps
  - Clone the repository:
    
        git clone https://github.com/Ayushverma135/SmartChessAI.git
        cd SmartChessAI
  - Install dependencies:
    
        pip install -r requirements.txt
  - Launch Jupyter Notebook:
  - Open and run the __Chess_Piece_Identification.ipynb__ notebook.

## Results
The model achieves high accuracy on the test dataset, demonstrating its effectiveness in recognizing chess pieces under various conditions. Detailed evaluation metrics and model performance charts are provided in the results directory.

## Contributing
We welcome contributions to improve the project! Please fork the repository and submit pull requests with your enhancements.
