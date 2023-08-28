# Image_Resizer usin OpenCV

This script uses the OpenCV library to resize an input image and save the resized image to a specified destination. 
It's a simple tool that can be used to quickly resize images by a specified percentage.

## Table of Contents
- [Introduction](#introduction)
- [Usage](#usage)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Example](#example)
- [License](#license)

## Introduction

This script demonstrates how to resize an image using the OpenCV library in Python. It reads an input image,
calculates the dimensions for the resized image based on a given scale percentage, performs the resizing, 
and then saves the resized image to the specified destination.

## Usage

1. Clone the repository or download the script to your local machine.
2. Make sure you have Python and the OpenCV library installed.
3. Replace `'veer.jpg'` with the path to your source image and `'new_image.jpg'` with the desired path for the resized image.
4. Adjust the `scale_percent` variable to the desired percentage by which you want to resize the image.

## Prerequisites

- Python: You need to have Python installed on your system. You can download it from the official [Python website](https://www.python.org/downloads/).
- OpenCV: This script uses the OpenCV library for image manipulation. You can install it using the following command:

  pip install opencv-python

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourrepository.git
   ```

2. Navigate to the repository directory:

   ```bash
   cd yourrepository
   ```

3. Run the script:

   ```bash
   python resize_image.py
   ```

## Example

Suppose you have an image named `veer.jpg` that you want to resize to 50% of its original dimensions. 
You would set the `source` variable to `'veer.jpg'` and the `destination` variable to `'new_image.jpg'`. Then, 
set the `scale_percent` variable to `50`. After running the script, the resized image will be saved as `new_image.jpg`.

## License

This project is licensed under the [MIT License](LICENSE).

Remember to replace placeholders like `'virendra1109'` and `'Image_resizer'` with your actual GitHub username and repository name. 
Also, include the appropriate license file (`LICENSE`) in your repository if you haven't already.


