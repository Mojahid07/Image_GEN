# Dynamic Image Generation using YOLO and Stable Diffusion

This project utilizes the YOLO (You Only Look Once) object detection model and the Stable Diffusion model for generating visually captivating images based on user-defined prompts. 

## Overview

The project allows users to input prompts describing the desired scene and generates a series of images showcasing the described scenario. The images feature dynamic compositions, diverse lighting conditions, and innovative angles, aimed at creating visually appealing content.

## Technologies Used

- **YOLO (You Only Look Once)**: A real-time object detection system that identifies objects in images or video streams.
- **Stable Diffusion Model**: Utilized for image generation based on textual prompts. The model generates high-quality images that match the given textual input.
- **Python Libraries**: The project utilizes various Python libraries such as `torch`, `ultralytics`, `PIL`, `matplotlib`, `diffusers`, and `transformers` for deep learning, image processing, and visualization tasks.

## Workflow

1. **User Input**: Users provide prompts describing the desired scene they want to generate images for.
2. **Image Generation**: The program utilizes the Stable Diffusion model to generate images based on the provided prompts.
3. **Object Detection**: The YOLO model is applied to the generated images to detect and highlight objects such as laptops, people, etc.
4. **Visualization**: The generated images, along with the detected objects, are displayed to the user for review.

## Usage

1. Clone the repository and install the required dependencies.
2. Run the provided script, providing prompts and the number of images to generate.
3. Review the generated images showcasing the dynamic photo shoot scenarios.

## Note

This project is primarily intended for personal use and experimentation with image-generation techniques. The generated images may vary based on the provided prompts and model configurations.

For detailed information about the code implementation and underlying models, refer to the source code files.

**Disclaimer**: The generated images and object detection results may not always be accurate and should be reviewed for suitability before use in any context.
