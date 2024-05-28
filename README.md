# Overview
This script demonstrates basic image processing operations, including loading images, stacking them, displaying individual images from the stack, and creating a collage from multiple images. It utilizes the NumPy library for array manipulation and Matplotlib for image display.

# Prerequisites
Before running the script, ensure you have the following installed:

Python 3.x
NumPy
Matplotlib
Install the required packages using pip:
``` bash
pip install numpy matplotlib
```

# Usage
## Loading and Converting Images
The script loads 10 images from the repics directory and converts them into NumPy arrays.

## Initializing the Stack
A stack is initialized to hold the images, with a predefined size of 10.

## Functions
push(x): Adds an image to the stack. If the stack exceeds its size limit, it prints "Stackoverflow".
stackprint(): Displays an image from the stack based on a user-provided index.
display(): Creates and displays a collage from the first four images in the stack.
### Main Loop
The main loop offers a menu with the following options:

Add images to the stack.
Display a specific image from the stack based on the provided index.
Create and display a collage from the first four images in the stack.
Exit the script.
Running the Script
Ensure all images (dog.1.jpg, dog.2.jpg, ..., dog.10.jpg) are in the repics directory.
## Run the script using a Python interpreter:
``` bash
  python script_name.py
```

## Follow the prompts to add images to the stack, view images, or create a collage. Select options by entering the corresponding number.
### Example Usage
When prompted, you can:

Enter 1 to add images to the stack.
Enter 2 to display an image by its index in the stack.
Enter 3 to create and display a collage from the first four images in the stack.
Enter 4 to exit the script.
## Notes
The stack can hold up to 10 images. Adding more will trigger a "Stackoverflow" message.
Only the first four images are used to create the collage.
Ensure image dimensions are compatible for stacking and collage creation.

This script provides a simple framework for basic image processing tasks and can be extended for more complex operations as needed.
