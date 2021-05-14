# Experiment
Here is our neural networks in iPython notebooks, we experimented with. The models we experimented with are as follows:
- [ResNet152](ResNet152.ipynb)
- [Efficient Net-B2](EfficientNet-B2.ipynb)
- [Visual Transformer](ViT.ipynb)
- [Swin Transformer](SwinT.ipynb)

Each notebook has four training and evaluation section. They are as follows:
- **Multi-Class**: Network trained for classification of `species`, `class`, `phylum`, `sample` and `form`.
- **Class**: Network trained for classification of 7 different `class`
- **Phylum**: Network trained for classification of 5 different `phylum`
- **Species**: Network trained for classification of 16 different `species`

## Citing
```
@misc{rw2019timm,
  author = {Ross Wightman},
  title = {PyTorch Image Models},
  year = {2019},
  publisher = {GitHub},
  journal = {GitHub repository},
  doi = {10.5281/zenodo.4414861},
  howpublished = {\url{https://github.com/rwightman/pytorch-image-models}}
}

```