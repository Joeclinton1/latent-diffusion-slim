# Latent Diffusion Slim
This is a stripped down version of the full code from "Latent diffusion model" code (https://github.com/CompVis/latent-diffusion). This notebook version was created by me for use in the 2023 Deep Learning coursework by Chris Willocks.

In the LDM paper they experiment between two different regularisation methods for auto-encoders: KL-reg which uses a KL penalty and VQ-reg which uses vector quantisation. VQ-reg doesn't improve image quality much for small images and instead just overcomplicate things, so we stick with KL.
