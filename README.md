# Newspaper Reader

## Description

The Newspaper Reader project utilizes advanced techniques, including YOLOv8, to enable automated reading of newspapers. It employs a combination of computer vision and natural language processing to identify and process different components within newspaper images or videos. By detecting headings, subheadings, text bodies, and images, the system converts the content into an audio file for convenient listening. The project ensures that the information is read in the correct order, following the hierarchical structure of the newspaper, starting from headings, then subheadings (if present), and finally the main text.

### 1. Component Identification:

Using the YOLOv8 model, a custom dataset is trained to accurately detect and classify various components within a newspaper, including headings, subheadings, text bodies, and images.

### 2. Determining Reading Order:

Custom algorithms are implemented to establish the correct order of reading. The system starts with the headings, followed by subheadings (if applicable), and then progresses to the main text.

### 3. Image-to-text conversion:

The project employs Tesseract OCR, a powerful optical character recognition tool, to extract text from newspaper images and convert it into digital text.

### 4. Text-to-audio conversion:

The extracted text is transformed into an audio file using GTTS (Google Text-to-Speech), facilitating easy and convenient listening.

## How to Run

To use the Newspaper Reader project, you can utilize the provided pre-trained model and the accompanying Colab/Jupyter notebook.

If you only wish to use the YOLO model, you can skip the training section of the notebook and proceed directly to the "Test" section. However, ensure that you modify the code according to your specific requirements in the "Read Order" part.

Please note that you might need to adjust the input and output locations within the code to match your setup. By default, the locations are set to my Google Drive.

## Train your own model:

If you prefer to train your own YOLO model, please refer to the "Training" section of the notebook provided.

To create your own training dataset, capture images of newspapers and use any annotation software to annotate the images in a YOLO-compatible format.

Ensure that you carefully follow the instructions and adjust the code to suit your specific needs.

Feel free to customize and enhance the project description based on the specific details and requirements of your own project.
