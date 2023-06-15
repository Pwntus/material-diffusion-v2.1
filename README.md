# A fork of the Stable Diffusion Cog model that outputs tileable images for use in 3D applications such as [Monaverse](https://monaverse.com)

[![Replicate](https://replicate.com/pwntus/material-diffusion-v2.1/badge)](https://replicate.com/pwntus/material-diffusion-v2.1)

This is an implementation of the [Diffusers Stable Diffusion v2.1](https://huggingface.co/stabilityai/stable-diffusion-2-1) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i prompt="monkey scuba diving"
