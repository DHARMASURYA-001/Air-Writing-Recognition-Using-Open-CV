# Air Writing Recognition Enhancement Using OpenCV

## Project Overview

This repository contains the code for the project "Air Writing Recognition Enhancement Using OpenCV." The project aims to recognize characters written in the air using hand movements, leveraging the OpenCV library for image processing, and utilizing masking and contouring techniques to achieve character recognition.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Future Works](#future-works)

## Introduction

Air writing refers to the action of writing characters in the air with finger or hand movements. This project explores gesture writing recognition based on data from hand movements with six degrees of freedom. It utilizes OpenCV for image processing and masking functions to enhance recognition accuracy.

## Installation

To run the code in this repository, you'll need to have Python and some specific libraries installed. Follow these steps to set up your environment:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/air-writing-recognition.git
   cd air-writing-recognition

2. **Create a virtual environment and activate it:**

  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows, use `venv\Scripts\activate

3. **Install the required dependencies:**

  ```bash
  pip install -r requirements.txt

## Usage
Follow these steps to use the air writing recognition system:

1. **Open the Jupyter Notebook:**

  ```bash
  jupyter notebook

2. **Run the Notebook:**

  -> Open the file Air Writing Recognition Using Open CV.ipynb in the Jupyter interface.
  -> Run all the cells in the notebook to start the air writing recognition system.

3. **Interacting with the System:**

  -> The system will activate your webcam.
  -> Ensure you have a blue-colored object (e.g., a pen cap) to write in the air.
  -> The recognized gestures will be displayed on the screen.
  -> Press 's' to save the image as PNG.
  -> Press 'p' to save the image as PDF.
  -> Press 'q' to quit the application.

## Methodology

**Sensing**

Establishes an interaction between the computer and human using hand gesture recognition. The recognized gestures convey valuable information to the computer.

**Spotting**

Employs masking and contouring to create an array of points representing handwriting. The background is highlighted to distinguish the handwriting motion.

**Handwriting**

Displays the recognized gesture writing text similar to 2D pen-based handwriting. The content can be saved as a PNG image or PDF file.

## Results

The system successfully recognizes and displays air-written content. The user can reset or clear the content as needed.

## Future Works

**Future enhancements include:**

  -> Testing hand motions in different lighting and environments.
  -> Adding features like finger recognition, undo, and redo options.
  -> Exploring other potential extensions for gesture writing recognition
