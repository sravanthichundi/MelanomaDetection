# Project Name: Melanoma Detection Using Convolutional Neural Networks

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- **Background**: Melanoma is one of the most dangerous types of skin cancer, responsible for the majority of skin cancer deaths. Early detection through image analysis can improve survival rates. This project focuses on using **Convolutional Neural Networks (CNNs)** to automatically detect melanoma from skin lesion images.
  
- **Business Problem**: Melanoma detection is traditionally done by dermatologists through visual examination, which can be time-consuming and error-prone. The goal of this project is to automate this process using deep learning to assist healthcare providers and reduce diagnostic time.

- **Dataset**: This project uses the **ISIC (International Skin Imaging Collaboration)** dataset, which contains a wide variety of labeled images of skin lesions, including melanoma, benign tumors, and other skin diseases. The dataset is diverse, making it suitable for training a robust model.

## Conclusions
- **BaseLineModel**:
1. The Baseline Model shows clear signs of overfitting
2. Very high training accuracy (93.47%) but poor validation accuracy (49.44%)
3. Huge gap between training loss (0.11) and validation loss (2.85)
4. This indicates the model memorized the training data but fails to generalize.
  
- **Dynamic Data Augmentation Model**: 
1. More balanced performance between training (54.52%) and validation (51.23%)
2. Similar loss values between training (1.30) and validation (1.34)
3. However, overall accuracy is lower than desired
4. The model avoids overfitting but may be underperforming

- **Data AugmentorLib Model**: 
1. Best Performing model
2. High and relatively close training (86.68%) and validation accuracies (81.66%)
3. This model is able to generalise better while maintaining strong performance

- **Future Work**: Future improvements could include using **transfer learning** with pre-trained models like **VGG16** or **ResNet**, which could help improve model accuracy by leveraging pre-learned features. Additionally, larger datasets and more advanced augmentation techniques may further enhance the model's performance.

## Technologies Used
- **TensorFlow** - Version 2.17.1
- **Keras** - Version 3.5.0
- **Matplotlib** - Version 3.8.0
- **NumPy** - Version 1.26.4
- **Augmentor** - Version 0.2.12

## Acknowledgements
- This project was inspired by the need to improve early detection of melanoma and other skin conditions through automated image analysis.
- The **ISIC dataset** was used for training and testing the model.
- The project and methodology were based on deep learning tutorials for skin cancer detection using Convolutional Neural Networks (CNNs).

## Contact
Created by [@sravanthichundi] !

