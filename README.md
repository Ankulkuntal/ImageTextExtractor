

# ImageTextExtractor

*ImageTextExtractor* is an Optical Character Recognition (OCR) tool that enables users to upload images and extract text in both *English* and *Hindi*. Built with **EasyOCR** for text recognition and *Gradio* for an interactive interface, the app supports keyword searches and highlights specified keywords within the extracted text.

## Features
- Extracts text from images in English and Hindi using *EasyOCR*.
- Allows keyword search and highlights the specified keywords in the extracted text.
- Simple and interactive web-based interface built with *Gradio*.

## Installation and Setup

To run *ImageTextExtractor* locally, follow these steps:

### 1. Clone the Repository:
```bash
git clone https://github.com/your-username/imagetextextractor.git
cd imagetextextractor
```

### 2. Install Required Dependencies:
Install the necessary libraries by running the following command:
```bash
pip install transformers torch easyocr gradio
```

### 3. Install Additional Requirements:
The *EasyOCR* model for *English* and *Hindi* will be automatically downloaded when you first run the application.

## How to Run the Application Locally

### 1. Run the Python Script:
After installing all dependencies, run the main script:
```bash
python main.py
```

### 2. Access the Application:
Once the server starts, *Gradio* will generate a local URL (e.g., http://127.0.0.1:7860/). Open this URL in your browser to access the *ImageTextExtractor* application.

### 3. Usage:
1. **Upload an Image**: Upload an image containing text (supports common formats like PNG, JPEG).
2. **Keyword Search**: Enter one or more keywords, separated by commas, to highlight specific words in the extracted text.
3. The text from the image will be displayed with your keywords highlighted in *red*.

## Deployment
The application can be easily deployed on platforms like *Hugging Face Spaces* or *Streamlit Sharing*. Follow the deployment instructions specific to the platform you choose.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## About
*ImageTextExtractor* is an Optical Character Recognition (OCR) tool that allows users to upload images and extract text in both *English* and *Hindi*. Built with **EasyOCR** for text recognition and *Gradio* for an interactive web interface, it supports keyword searches to highlight specified keywords within the extracted text.
