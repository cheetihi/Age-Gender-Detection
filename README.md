# Age-Gender-Detection
This project uses deep learning to detect age and gender from facial images. Implemented with Python, OpenCV, and a pre-trained Caffe model, the application processes images to estimate the age range and gender. Ideal for various applications like security systems, marketing analytics, and user demographics analysis.

## Features

- Deep Learning: Utilizes a pre-trained Caffe model for accurate predictions.
- Image Processing: Uses OpenCV for handling and processing images.
- Real-time Detection: Capable of detecting age and gender in real-time.
- Applications: Useful for security, marketing, and demographic studies.

## Technologies Used

- Python: The primary programming language.
- OpenCV: For image processing tasks.
- Caffe: A deep learning framework, used here with a pre-trained model.
- NumPy: For numerical operations and handling arrays.


## Installation
Clone the Repository:
git clone https://github.com/yourusername/age-gender-detection.git
cd age-gender-detection

##Create a Virtual Environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

## Install Dependencies:
pip install -r requirements.txt

## Download Pre-trained Models:
Download the pre-trained age and gender models from the following links and place them in the models directory:

* Age Model
* Gender Model
* Deploy Prototxt
* Deploy Prototxt

## Usage
## Run the Application:
python detect.py --image path_to_your_image.jpg

## or for real-time detection:
python detect.py --video

## Command Line Arguments:
--image: Path to the input image file.
--video: Use the webcam for real-time detection.

## Project Structure
detect.py: Main script for running the age and gender detection.
models/: Directory containing the pre-trained Caffe models.
requirements.txt: File listing all required Python packages.
README.md: This readme file.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

