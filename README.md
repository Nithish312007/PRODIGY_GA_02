# Task-02: Image Generation with Pre-trained Models
**Track Code:** GA  
**Intern:** V Nithish  

## Objective
This task demonstrates the generation of images from textual prompts using pre-trained generative models. The goal is to utilize models like **Stable Diffusion** to convert text descriptions into coherent and contextually relevant images.

## Model Used
- **Stable Diffusion Turbo** (`stabilityai/sd-turbo`)
- Lightweight variant of Stable Diffusion for faster CPU/GPU performance

## Prompt Example
A futuristic robot studying in a digital classroom

## Implementation
- Implemented using the `diffusers` library by Hugging Face
- Code is optimized for **CPU execution** with reduced inference steps (`num_inference_steps=4`) to save time
- Safety warnings suppressed for clean output during testing

## Output
- Generated image 
- Image is displayed directly in the notebook using `IPython.display.display()`

