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

![Home](https://github.com/user-attachments/assets/3991961f-c4a5-4634-99df-b0f27c533a87)

![Home2](https://github.com/user-attachments/assets/1f64be19-03e6-4086-b62e-28620)

![Home3](https://github.com/user-attachments/assets/500a11e9-869f-49e7-9639-02e88809fcb2)

![Screenshot (15)](https://github.com/user-attachments/assets/0ecac0fb-4bd5-4436-874a-a16a82e27f16)


