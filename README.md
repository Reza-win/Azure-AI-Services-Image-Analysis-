# Analyze_Images_with_Azure_AI_vision

## Project Description

This project utilizes Microsoft Azure's Computer Vision API to analyze images. The application performs tasks such as language detection, object detection, and background removal. It leverages the Azure AI Vision client to extract valuable insights from images, including captions, tags, and detected objects.

## Features

- Analyze images to extract captions, tags, and detected objects.
- Draw bounding boxes around detected objects and people.
- Remove backgrounds from images using Azure's segmentation capabilities.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine.
- An Azure account with access to the Computer Vision API.
- Required Python packages installed (see Installation section).

## Example Output

Original Image

![street](https://github.com/user-attachments/assets/5e502d0f-13ad-47c3-bf00-6edebbfcaa50)

Detected Image

![street detected](https://github.com/user-attachments/assets/d842f9c5-f966-4355-b560-130ca8ee9c7d)

Street Background Removing

![street background remove](https://github.com/user-attachments/assets/0ae74eec-0700-4d9d-9188-57263c1c1a16)

Foreground Matting

![foreground matting](https://github.com/user-attachments/assets/7d2cdd15-cf8b-4e54-bd58-71d050622c19)

## Setup

## Create a `.env`

Set up your environment variables. Create a `.env` file in the root directory of the project and add your Azure credentials:

AI_SERVICE_ENDPOINT= `<your_azure_endpoint>`

AI_SERVICE_KEY= `<your_azure_key>`

## Acknowledgments

- Microsoft Azure for providing the Computer Vision API.
- Pillow for image processing.
- Matplotlib for visualizing the results.
