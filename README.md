# AI Attention Visualizer

## Introduction

AI Attention Visualizer is a simple AI-based application that helps users understand text and attention patterns using visualization techniques. The application also uses OCR (Optical Character Recognition) to extract text from uploaded images.

The project is developed using Python and Streamlit. It provides an easy-to-use interface for uploading images and processing the text using OCR.

## Features

* Upload an image
* Extract text from the image using OCR
* Process the extracted text
* Visualize attention information
* Simple and user-friendly Streamlit interface
* Runs as a web application

## Technologies Used

* Python
* Streamlit
* Pytesseract
* Tesseract OCR
* Pillow
* AI / NLP

## Project Structure

```text
ai-attention-visualizer/
│
├── app.py
├── ocr.py
├── requirements.txt
├── packages.txt
└── README.md
```

## File Description

### app.py

Contains the main Streamlit application and user interface.

### ocr.py

Contains the OCR function used to extract text from images.

### requirements.txt

Contains the Python packages required to run the project.

### packages.txt

Contains the system package required for Tesseract OCR in Streamlit Cloud.

## OCR

OCR stands for Optical Character Recognition. It is used to convert text present in an image into machine-readable text.

This project uses:

```text
Pytesseract
Tesseract OCR
```

## Installation

### Step 1: Clone the Repository

```bash
git clone <repository-url>
```

### Step 2: Open the Project Folder

```bash
cd ai-attention-visualizer
```

### Step 3: Install Python Packages

```bash
pip install -r requirements.txt
```

### Step 4: Install Tesseract OCR

For Windows, install Tesseract OCR on the computer.

For Streamlit Cloud, the `packages.txt` file contains:

```text
tesseract-ocr
```

## Run the Application

Use the following command:

```bash
streamlit run app.py
```

The application will open in the browser.

## Working Process

```text
Upload Image
      ↓
Image Processing
      ↓
OCR using Tesseract
      ↓
Text Extraction
      ↓
AI / Attention Processing
      ↓
Visualization
```

## Example

The user uploads an image containing text.

The application:

1. Reads the uploaded image.
2. Uses Tesseract OCR to detect the text.
3. Extracts the text from the image.
4. Processes the extracted text.
5. Displays the result through the Streamlit application.

## Deployment

The application can be deployed using Streamlit Cloud.

For Streamlit Cloud deployment:

* Add `requirements.txt`
* Add `packages.txt`
* Keep `tesseract-ocr` inside `packages.txt`
* Push the files to GitHub
* Connect the GitHub repository to Streamlit Cloud
* Deploy the application

## Advantages

* Easy to use
* Simple interface
* Extracts text from images
* Uses OCR technology
* Can be accessed through a web browser
* Useful for AI and NLP learning

  https://ai-attention-visualizer-xef4vmdchwkv3vu9k9sres.streamlit.app/

## Conclusion

AI Attention Visualizer is a simple project that combines OCR, AI concepts, and visualization in a Streamlit application. It helps users extract text from images and understand the processed information through a web-based interface. This project also provides practical experience in Python, OCR, AI, and Streamlit deployment.
