# Stable diffusion for Macbook M1, GPU support

[High-performance image generation using Stable Diffusion in KerasCV](https://keras.io/guides/keras_cv/generate_images_with_stable_diffusion/) with support for GPU for Macbook M1Pro and M1Max. All rights belong to its creators.

First, you need to install a Python distribution that supports arm64 (Apple Silicon) architecture. I use `mambaforge`, but `miniforge` is likely to work as well, see <https://github.com/conda-forge/miniforge>.

Or using [brew](https://brew.sh/):

```
brew install --cask mambaforge
```

Then

```
git clone git@github.com:stared/stable-diffusion-keras-m1-gpu.git
cd stable-diffusion-keras-m1-gpu
mamba env create -f  tf-macos-m1-gpu.yaml
mamba activate tf-macos-m1-gpu
```

Instruction adapted from [What is the proper way to install TensorFlow on Apple M1 in 2022 - StackOverlow](https://stackoverflow.com/questions/72964800/what-is-the-proper-way-to-install-tensorflow-on-apple-m1-in-2022).
