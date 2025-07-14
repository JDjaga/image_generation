# Segment Anything & Stable Diffusion Inpainting

![download](https://github.com/user-attachments/assets/ae217f10-20ad-47f0-921c-b1570b4c4903)
## Overview
This project utilizes the Segment Anything Model (SAM) and Stable Diffusion Inpainting Pipeline to enable users to segment and inpaint parts of images based on custom prompts. The pipeline is designed to take an input image, generate segmentation masks, and then apply inpainting based on specified prompts, providing an interactive and customizable experience.
Features
1. **Image Segmentation**: Automatically segments objects within an image using the Segment Anything Model.
2. **Inpainting**: Uses the Stable Diffusion Inpainting Pipeline to generate inpainted images based on the segmented masks and user prompts.
3. **Interactive Interface**: Built with Gradio for easy interaction with the model.
4. **Customizable Prompts**: Users can provide custom prompts to guide the inpainting process.

## Architecture
- **Segment Anything Model**: Used to segment objects in an image to create masks for inpainting.
- **Stable Diffusion Inpainting**: Utilizes the pre-trained Stable Diffusion model to generate inpainted images based on user-provided prompts and selected masks.
SAM Model
- The SAM model is initialized with a checkpoint and a specific model type (e.g., `vit_h`), and is used to generate segmentation masks from an image.

## Acknowledgments

- Meta AI for the Segment Anything Model
- Stability AI for Stable Diffusion
- Hugging Face for model hosting and diffusers library

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
