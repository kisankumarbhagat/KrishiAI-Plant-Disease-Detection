# Krishi AI: Plant Disease Detection

Krishi AI is a Flask-based web application that utilizes a Convolutional Neural Network (CNN) model to detect plant diseases from uploaded images. The application provides detailed information about the identified disease and suggests supplements for effective management.

## Features
- **Image Upload**: Upload an image of the plant leaf for disease detection.
- **Disease Detection**: Utilizes a pre-trained CNN model for identifying plant diseases.
- **Disease Information**: Displays the disease name, description, and prevention steps.
- **Supplement Suggestions**: Provides recommendations with supplement names, images, and purchase links.
- **Responsive UI**: Designed to work seamlessly on both desktop and mobile devices.

## Prerequisites
Ensure you have the following installed:
- Python 3.8 or later
- Flask
- PyTorch
- Pandas
- Pillow
- TorchVision

To install all dependencies, run:
```bash
pip install -r requirements.txt

## How It Works
1. **Upload an Image**: Users upload a clear image of a plant leaf.
2. **Image Processing**: The image is preprocessed using OpenCV.
3. **Prediction**: The CNN model analyzes the image and predicts the disease.
4. **Results**: The application displays the disease name and provides prevention/treatment tips.

## Model Details
The CNN model was trained on a diverse dataset of plant leaf images with multiple disease categories. The architecture ensures high accuracy and generalizability across different plant types.

## Future Enhancements
- Expand the dataset to include more plant species and diseases.
- Integrate multi-language support for global reach.
- Deploy the application on cloud platforms for scalability.

![Home](https://github.com/user-attachments/assets/3d6ca446-b42a-4e5f-9b39-ac8cbc7c7b37)

![Home2](https://github.com/user-attachments/assets/65ccc4e0-dec3-4a70-b7d4-b48431f36424)

![Home3](https://github.com/user-attachments/assets/8134a140-ac26-456b-8a6c-c08b2f07c1a1)

![Screenshot (15)](https://github.com/user-attachments/assets/9483a988-2ad0-4943-942f-92881a203768)
