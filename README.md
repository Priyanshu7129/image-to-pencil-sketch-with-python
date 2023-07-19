# Image to Pencil Sketch with Python

This Python script allows you to convert a regular image into a pencil sketch using basic image processing techniques. The process involves converting the original image to grayscale and then applying a technique known as "dodging and burning" to simulate the effect of a pencil sketch.

## Requirements

- Python (3.x recommended)
- OpenCV library (`cv2`)
- NumPy library (`numpy`)

Make sure you have Python installed on your system. If you don't have the required libraries, you can install them using `pip`:


## Usage

1. Clone this repository or download the Python script (`pencil_sketch.py`) to your local machine.

2. Place the image you want to convert to a pencil sketch in the same directory as the script.

3. After the script runs successfully, you will find the converted pencil sketch image in the same directory as the script.


## How it Works

The script follows these basic steps:

1. Read the input image using OpenCV.

2. Convert the image to grayscale, which simplifies the image and prepares it for the pencil sketch effect.

3. Invert the grayscale image using bitwise_not to create a "negative" of the image.

4. Apply the Dodge blending technique by dividing the inverted grayscale image by the original grayscale image. This step enhances the highlights of the image, giving it a "dodged" effect.

5. The resulting image is the pencil sketch. You can experiment with the parameters to achieve different effects.


## Troubleshooting

- If you encounter any issues running the script, make sure you have installed the required libraries (OpenCV and NumPy).

- Ensure the image file is in the correct format (e.g., JPEG, PNG) and located in the same directory as the script.

- Try using different images with varying levels of complexity to achieve the desired pencil sketch effect.

## Acknowledgments

The script is inspired by various image processing techniques available in OpenCV and tutorials from the computer vision community.

