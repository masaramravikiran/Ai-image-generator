Text-to-Image Generator
Project Overview

The Text-to-Image Generator is a Python application that converts textual prompts into high-quality digital images using OpenAI’s DALL·E API. Users can enter descriptive text, and the program generates and saves an image automatically with a timestamped filename. This project demonstrates practical usage of AI-powered image generation in a simple, interactive Python script.

Features

Converts any descriptive text into a digital image.

Automatically downloads and saves the image locally.

Timestamped filenames to avoid overwriting images.

Easy to run in VS Code with minimal setup.

Technologies Used

Python 3.10+

OpenAI API (DALL·E) for image generation

Pillow for image handling

Requests for downloading images from URLs

Setup Instructions
1. Install Python

Download Python 3.10+: https://www.python.org/downloads/

Ensure “Add Python to PATH” is checked during installation.

2. Install VS Code Extensions

Python

Pylance (optional for better code suggestions)

3. Install Required Libraries

Open VS Code terminal and run:

pip install openai pillow requests

4. Get OpenAI API Key

Sign up at OpenAI

Generate a new API key

Copy it to replace "YOUR_OPENAI_API_KEY" in the script

5. Run the Script

Open text_to_image.py in VS Code

Press F5 or right-click → Run Python File in Terminal

Enter your descriptive text prompt, e.g.:

A futuristic city skyline at sunset, digital painting


The generated image will be saved in the project folder as:

image_YYYYMMDD_HHMMSS.png

Sample Output


(Replace with actual image generated during testing)

Future Enhancements

Support multiple prompts at once.

Allow choice of image size and style.

Add a GUI for interactive prompt input.

Use Stable Diffusion for offline image generation.
