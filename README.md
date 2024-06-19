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

## Usage :
* Download my Repository
* Open your Command Prompt or Terminal and change directory to the folder where all the files are present.
* Detecting Gender and Age of face in Image Use Command :
  `python detect.py --image <image_name>`
Note: The Image should be present in same folder where all the files are present

* Detecting Gender and Age of face through webcam Use Command :
  `python detect.py`
* Press Ctrl + C to stop the program execution.

## WORKING:
![harshini](https://github.com/cheetihi/Age-Gender-Detection/assets/168654422/9247a25c-b632-4215-b2d0-0c87a25ba40c)
This is the screenshot of the real time video..


## Project Structure
detect.py: Main script for running the age and gender detection.
models/: Directory containing the pre-trained Caffe models.
requirements.txt: File listing all required Python packages.
README.md: This readme file.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements.

