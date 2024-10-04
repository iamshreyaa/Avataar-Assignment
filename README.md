# Avataar-Assignment
Place an object’s image in a text-conditioned scene

In this assignment, libraries and frameworks used are:
PyTorch (torch): A deep learning library for tensor computation and building neural networks.
Hugging Face's Diffusers: A library for working with diffusion models for generating images from text.
Reference from : [Hugging Face Diffusers Introduction](https://colab.research.google.com/github/huggingface/notebooks/blob/main/diffusers/diffusers_intro.ipynb),
[Annotated diffusion](https://huggingface.co/blog/annotated-diffusion),
[Stable diffusion](https://huggingface.co/blog/stable_diffusion) and 
[Img to text using stable diffusion and hugging face](https://www.youtube.com/watch?v=Fa2ajc5AnhI)
Transformers: A library for handling transformer-based models and architectures.
Pillow (PIL): A Python Imaging Library used for image processing tasks.

The Stable Diffusion model is used to generate background images based on text prompts. Then Loaded images and converted them to a format suitable for manipulation (RGBA). A custom function is used to remove the white background from example images. Managed and saved the generated file.
