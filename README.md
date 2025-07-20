# Classification of Diabetic Retinopathy Disease Levels by Extracting Topological Features Using Graph Neural Networks

## What is Diabetic Retinopathy?

Diabetic Retinopathy (DR) is an eye disease caused by high blood sugar levels in diabetic patients. It damages the small blood vessels in the retina (the light-sensitive part of the eye), which can lead to blurred vision or even blindness if not treated early. Detecting DR at the right time is important for preventing vision loss.

## Project Overview

This project uses deep learning techniques to detect and classify the severity level of Diabetic Retinopathy from retinal images.

We use two models:

**GraphCNN:** Converts retinal images into graphs and looks at the structure and patterns inside the image. It is good at understanding relationships between different parts of the image.

**DenseNet121:** A well-known deep learning model that extracts important features from images to make predictions.

By comparing both models, we aim to find a more accurate and reliable method to detect DR.

**Developed For**
Medical professionals and researchers aiming to improve early detection and grading of diabetic retinopathy using AI-based tools.

## How to run

1. Clone the repository.
2. Install all required dependencies listed in ```requirements.txt```.
3. Upload the EyePacs dataset into the designated folder.
4. Run the main script (```main.py```) to launch the application.
5. Follow the interface prompts to preprocess, train, evaluate, and test models.
