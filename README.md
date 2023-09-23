# Ambiguous Datasets

This repository serves to release our ambiguous datasets for mnist and fashion-mnist. 
The images were created such that they have an unclear ground truth, i.e., such that they are similar to multiple - but not all - of the datasets classes. For details, please see our [paper](https://arxiv.org/abs/2207.10495).

The datasets, in various formats, are available under the "recent releases" (for that reason, the repository appears empty).


## Citation

```
@misc{https://doi.org/10.48550/arxiv.2207.10495,
  doi = {10.48550/ARXIV.2207.10495},
  url = {https://arxiv.org/abs/2207.10495},
  author = {Weiss, Michael and Gómez, André García and Tonella, Paolo},
  title = {A Forgotten Danger in DNN Supervision Testing: Generating and Detecting True Ambiguity},
  publisher = {arXiv},
  year = {2022}
}
```


## Huggingface Datasets

We strongly suggest you use our datasets through 🤗 datasets (`pip install datasets`).
For instructions and a detailed dataset card, please navigate to the corresponding huggingface repos:
- [mnist_ambigous](https://huggingface.co/datasets/mweiss/mnist_ambiguous)
- [fashion_mnist_ambiguous](https://huggingface.co/datasets/mweiss/fashion_mnist_ambiguous)
