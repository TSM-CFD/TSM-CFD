# TSM-PDE

Parts of the codebase is adapted from [google/jax-cfd](https://github.com/google/jax-cfd).

## Setup

```bash
conda env create -f environment.yml
conda activate cfd
cd jax-cfd
pip install jaxlib
pip install -e ".[complete]"
cd ..
```

## Data

Both the training and evluation data can be deterministically generated.
Please see the [data_generation](data_generation.md) for more details.

## Reproduction

Please check the [reproducing_scripts](reproducing_scripts.md) for more details.

## Pretrained Checkpoints

Please download the pretrained model checkpoints from [here](https://drive.google.com/drive/folders/19dVHw8G8-0RCK2Y7p-oGlG2lzfKJwQ8S?usp=share_link).

