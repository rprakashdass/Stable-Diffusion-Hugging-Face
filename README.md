# Stable-Diffusion-Hugging-Face
Assignment on Stable diffusion -HUGGING FACE - Model. 
Hugging Face model...
Trained Model on GenerativeAI principles the Model will serve as text-image AI. This stable diffusion model helps to get started with hugging face model.
Github : prakash72716@gmail.com
Linkedin : https://www.linkedin.com/in/prakash-dass-r-97577725b<br>
Documentation :https://docs.google.com/document/d/1Rw1UpYrDvMyM6yhf-7zlGhJZUfzl5RYUXKogtqOlZ8s/edit?usp=sharing



FIRST block of code it will ask for your token from Hugging Face.

If you don't have an account you can make one here: https://huggingface.co/join

Before you can do this you need to accept the license agreement for the model, which you can do here: https://huggingface.co/CompVis/stable-diffusion-v1-4

On the token page select "new token" and ask for a "read" token (you can name it anything you want).
The above codes sets up a Stable Diffusion Pipeline for a pretrained model with the specified model_id. The pipeline is initialized with a scheduler, a tensor data type (torch.float16), and a revision (fp16). The remove_safety variable can be set to True to remove safety checks in the pipeline. Finally, the pipeline is moved to the specified device.

AT LAST, Where you can actually make images. Change the "prompt" to whatever you want to try and then change "num_images" if you want more than one image generated. You can re-run this cell without having to re-run everything before it, just FYI.
To get the token , you need to run this code then a link will available to you then. There you can get new token.
DOWN HERE YOU NEED TO ENTER THE TOKEN NUMBER AND THEN GIVE Y.THEN YOU CAN SEE THE MESSAGE "LOGIN SUCCESFUL". MOVE ON.

Some code of lines are the classes from the diffusers library. It creates a new 'PNDMScheduler' object and sets the starting and ending values for the beta parameter. The 'PNDMScheduler' class is used to define a scheduler for the Stable Diffusion Model, which controls the diffusion process and determines how much noise is added at each step.

Those codes help us to import necessary libraries at last and classes for the Stable Diffusion Pipeline, including mediapy, torch, autocast, and StableDiffusionPipeline.