# 🍎🥬🥕 Image Classification - Fruits and Vegetables  
GitHub Repo: [Image Classification](https://github.com/Nithishkaranam2002/Image-Classification-/)

This project uses a Convolutional Neural Network (CNN) built with Keras to classify images of common fruits and vegetables such as apples, bananas, corn, cabbage, and chili peppers. It includes a trained model, sample images, and a simple API built using Flask to serve predictions.

## Project Overview

- Built a custom image classification model to identify different types of produce.
- Trained the model using labeled datasets and exported it as a `.keras` file.
- Developed a Flask API (`app.py`) to handle real-time predictions via image upload.
- Uploaded several sample images to test predictions.

## Model

- Model Type: CNN (Convolutional Neural Network)
- Framework: TensorFlow / Keras
- Output: Predicts class labels such as `apple`, `banana`, `cabbage`, `corn`, `chilli`.

## Project Structure

├── app.py # Flask API to serve model
├── Image_Class_Model.ipynb # Training and evaluation notebook
├── Image_classify.keras # Trained Keras model
├── Apple.jpg, Banana.jpg, etc. # Sample input images
├── Image Classify.jpg # Summary/architecture visual


## Running the Project

### 1. Clone the repository

`bash
git clone https://github.com/Nithishkaranam2002/Image-Classification-.git
cd Image-Classification-

Install dependencies
pip install -r requirements.txt


Run the API
python app.py


API Usage

Endpoint: /predict
Method: POST
Form-Data: Upload an image file as image
Example using curl:

curl -X POST -F image=@Apple.jpg http://localhost:5000/predict


Classes Included

Apple
Banana
Cabbage
Corn
Chilli
Author

Made with ❤️ by Nithish Karanam
GitHub: https://github.com/Nithishkaranam2002


---

You can paste this directly into the `README.md` file on your [repo link](https://github.com/Nithishkaranam2002/Image-Classification-/new/main?filename=README.md). Let me know if you want badges or deployment instructions added!

