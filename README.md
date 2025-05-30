﻿# Text-to-Image Generation with Stable Diffusion
------------------------------------------------
This code creates an interactive AI image generation interface (Stable Diffusion XL) directly in a Jupyter or Google Colab notebook. Here's what it does:

Main features:
Loads a powerful AI model:

Uses Stable Diffusion XL 1.0 (the latest Stability AI model)

Optimized for GPU (CUDA) with reduced precision (float 16) calculations

Simple user interface:

Text box to enter a description (e.g., "A cute cat with glasses")

"Generate Image" button to start generation

Real-time progress display

Image generation:

Creates 768x768 pixel images

30 enhancement steps for a good quality/time balance

Automatically saves as PNG

Optimizations:

Uses GPU for fast generation

Automatically cleans up previous output

Example use:
User writes: "A futuristic cityscape in the rain"

Clicks "Generate Image"

After 1-2 minutes :

The image is displayed in the notebook

It is saved as generated_image.png

Technical highlights:
Libraries: Hugging Face Diffusers + PyTorch

Hardware requirements: NVIDIA GPU (for CUDA)

Model size: ~8GB (automatically downloaded)

End result:
A mini AI image generation application directly in your browser, without the need for complex installation.
------------------------------------------------
 Use GPU in Google Colab
 ![image](https://github.com/user-attachments/assets/12c7a4e7-a4da-487c-a4b0-867d0c33e75f)

 ![image](https://github.com/user-attachments/assets/bdd79daf-159a-4c4e-a9ad-1324d1e863a1)
 ![image](https://github.com/user-attachments/assets/3192c331-15cf-4416-9bca-021c70bc6ca9)

 ![image](https://github.com/user-attachments/assets/ed82e471-c57d-441c-be1d-4978e1221bfd)

 ![image](https://github.com/user-attachments/assets/5a5e7608-cc71-4d5b-a49c-be5a71a41b52)





