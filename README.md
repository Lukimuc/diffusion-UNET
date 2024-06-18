# Generating Animals using a Diffusion Model based on UNET

---- 
- **Chosen Paper:** [Diffusion Models Beat GANs on Image Synthesis [Dhariwal, Nichol, 2021]](https://openreview.net/pdf?id=AAWuCvzaVt)
- **Published at:** NeurIPS21
- **Reason for selection:** The reason for choosing this paper is because it had a big impact on how images are generated. The study showed that a diffusion model can produce better results than Generative Adversarial Networks (GANs). This discovery led to a significant change in how researchers approach image generation. By demonstrating better performance in creating images, the paper questioned the dominance of GANs, which have been the main method for making realistic images. This change not only drew a lot of interest from academics but also encouraged more study into diffusion models and how they could be used in different areas besides image generation. Overall, the paper provides important insights and has sparked new ideas for research in visual media and artificial intelligence.


----------
**Other Sources:**
- Used Dataset ([102 Category Flower Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/))
- Used Tutorials ([Diffusion Models - Live Coding Tutorial](https://youtu.be/S_il77Ttrmg),[Diffusion models from scratch in PyTorch](https://www.youtube.com/watch?v=a4Yfz2FxXiY))
- Used Repositories ([Denoising Diffusion Pytorch](https://github.com/lucidrains/denoising-diffusion-pytorch), [The Annotated Diffusion Model](https://colab.research.google.com/github/huggingface/notebooks/blob/main/examples/annotated_diffusion.ipynb#scrollTo=3a159023), [Diffusion Model](https://colab.research.google.com/drive/1sjy9odlSSy0RBVgMTgP7s99NXsqglsUL?usp=sharing))

-------
**Modification Overview:**
- Dataset Change: Updated to the 102Flower Dataset.
- Code Adjustments and Comments: Made specific changes to improve code efficiency, readability, and maintainability, while adding explanatory comments.
- Changed Order and Structure of Code Blocks: Reorganized code blocks to enhance logical flow.
- Tested Different Hyperparameters: Experimented with various hyperparameters to find optimal settings.
- Added Weight Saving and Resuming Mechanism: Implemented functionality to save model weights periodically during training and resume training from the saved checkpoint if interrupted.

--------
