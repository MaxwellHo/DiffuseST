Below shows the evolution of the StableDiffusion Model

The First Two iterations of the stable diffusion model uses a two pass system

The 3rd and Final Iteration of the stable diffusion model uses a three pass system to futher refine the style.

The final iteration of the model is what we ended up settling on.

In Order to run any of the models, you must have a content image and you can set the path to that image with the CONTENT_PATH variable.

-If you want to change the style text prompt, simply change the string content in STYLE_PROMPT.

-If you want to have the negative Prompt, simply change the string content in NEGATIVE_PROMPT.

Method: Two-pass image-to-image style transfer

Model Used: Stable Diffusion XL (stabilityai/stable-diffusion-xl-base-1.0)

Model Type: Latent Diffusion Model

Model Input: Image + Text Prompt

Model Output: Stylized Image

Generation Mode: Image-to-image transformation with prompt conditioning

