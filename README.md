# Pytorch Model Checkpoints
> Reducing memory on torchvision models.


This is a fastai2 exploraton on hooks and pytorch `checkpoint_sequential`.
- Hooks: They let you access the model at training/inference time. (https://pytorch.org/docs/stable/nn.html?highlight=register_forward#torch.nn.Module.register_forward_pre_hook)
- Checkpoints: Stores intermediate parameters to reduce GPU memory usage (https://pytorch.org/docs/stable/checkpoint.html?highlight=checkpoint_sequential#torch.utils.checkpoint.checkpoint_sequential)

You can check how to cut memory usage of your resnet in half.

## Install

You only need fastai2 (and pytorch)

```bash
pip install fastai2
```

## Experiments

Everything is in the `00_core.ipynb` for the moment
