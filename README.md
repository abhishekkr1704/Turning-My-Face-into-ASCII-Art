# Turning-My-Face-into-ASCII-Art
Convert a human face image into ASCII art using Python and basic image processing

Introduction

ASCII art is a creative way of representing images using only text characters. In this project, I converted my own face image into ASCII art using Python on Google Colab. Instead of using complex graphics or deep learning, this project relies on image processing basics and character mapping to produce visually meaningful text art.

Become a Medium member
This project helped me understand how images are represented as pixel values and how those values can be transformed into creative outputs.

Project Objective

The main objective of this project is to:

Convert a real human face image into ASCII art

Use Python and basic image processing techniques

Run the entire project on Google Colab

Generate a downloadable ASCII text file as output

Tools & Technologies Used


Python

Google Colab

Pillow (PIL) library

NumPy

ASCII Characters

How the Project Works

The project follows a simple and structured workflow:


Upload a face image using Google Colab

Convert the image into grayscale

Resize the image to maintain ASCII clarity

Convert pixel intensity values into ASCII characters

Display the ASCII face in text format

Save the ASCII art into a .txt file

Each pixel in the image is mapped to a specific ASCII character based on brightness — darker pixels use dense characters like @ and %, while lighter pixels use simpler characters like . and spaces.

Implementation Overview

Step 1: Image Upload
The user uploads a clear face image directly into Google Colab.

Step 2: Grayscale Conversion
The image is converted to grayscale so that pixel intensity can be easily processed.

Step 3: Image Resizing
The image is resized to a fixed width to ensure the ASCII output remains readable and proportional.

Step 4: ASCII Mapping
Each pixel’s brightness is converted into an ASCII character using predefined character ranges.

Step 5: Output Generation
The ASCII art is printed on the screen and saved into a downloadable text file.
