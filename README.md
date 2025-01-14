# KrishiAI-Plant-Disease-Detection
A Flask-based web application that uses a Convolutional Neural Network (CNN) for plant disease detection from leaf images. Provides real-time predictions and preventive measures, with an integrated marketplace for relevant supplements. Complete end-to-end development from machine learning model deployment to the user interface.

## Features
- **Plant Disease Detection**: Upload images of plant leaves to detect diseases.
- **Actionable Advice**: Provides prevention and treatment recommendations.
- **User-Friendly Interface**: Simple and intuitive design for seamless interaction.

## Technology Stack
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Machine Learning**: Python, TensorFlow, Keras, OpenCV
- **Model Architecture**: Convolutional Neural Networks (CNNs)
- **Database**: SQLite
- **Hosting**: Deployed on a Flask-based server

## How It Works
1. **Upload an Image**: Users upload a clear image of a plant leaf.
2. **Image Processing**: The image is preprocessed using OpenCV.
3. **Prediction**: The CNN model analyzes the image and predicts the disease.
4. **Results**: The application displays the disease name and provides prevention/treatment tips.

## Installation
### Prerequisites
- Python 3.8 or higher
- Virtual Environment (`venv`)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/kisankumarbhagat/KrishiAI-Plant-Disease-Detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd KrishiAI-Plant-Disease-Detection
   ```
3. Create a virtual environment:
   ```bash
   python -m venv myenv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     myenv\Scripts\activate
     ```
   - On Mac/Linux:
     ```bash
     source myenv/bin/activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
6. Run the Flask server:
   ```bash
   python app.py
   ```
7. Open your browser and navigate to `http://127.0.0.1:5000`.

## Usage
- Upload an image of a plant leaf.
- Wait for the model to process and predict the disease.
- Follow the recommendations provided.

## Model Details
The CNN model was trained on a diverse dataset of plant leaf images with multiple disease categories. The architecture ensures high accuracy and generalizability across different plant types.

## Future Enhancements
- Expand the dataset to include more plant species and diseases.
- Integrate multi-language support for global reach.
- Deploy the application on cloud platforms for scalability.

## Contribution
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push the branch.
4. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgments
- TensorFlow and Keras for providing powerful tools for building and training machine learning models.
- Flask for enabling rapid web application development.
- OpenCV for efficient image processing.
![Home](https://github.com/user-attachments/assets/3d6ca446-b42a-4e5f-9b39-ac8cbc7c7b37)

![Home2](https://github.com/user-attachments/assets/65ccc4e0-dec3-4a70-b7d4-b48431f36424)

![Home3](https://github.com/user-attachments/assets/8134a140-ac26-456b-8a6c-c08b2f07c1a1)

![Screenshot (15)](https://github.com/user-attachments/assets/9483a988-2ad0-4943-942f-92881a203768)
