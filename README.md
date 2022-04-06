# metriplectic_POD-ROM

This is an implementation of the algorithms from:

A. Gruber, M. Gunzburger, L. Ju, and Z. Wang. *Energetically Consistent Model Reduction for Metriplectic Systems*, (under review).  Preprint [available here.](https://arxiv.org/abs/2110.03442#),

which introduces a provably convergent POD-ROM preserving the algebraic structure of the original metriplectic model.

The .ipynb files implement the experiments found in the paper (which can be tweaked as desired or run straight down).  At this time I  have not provided template .py files for out-of-the-box use on other problems, but the structure of the method should be relatively clear from the notebooks.

## Installation
The code was written and tested using Python 3.8 on an M1 Macbook Pro running OSX 12.0.1.  The required dependencies are
* [Numpy](https://numpy.org/)
* [Scipy](https://scipy.org)
* [Matplotlib](https://matplotlib.org/) (for visualization)

## Citation
Please cite [our paper](https://arxiv.org/pdf/2110.03442.pdf) if you find this code useful in your own work:
```
@misc{gruber2021energetically,
  title={Energetically Consistent Model Reduction for Metriplectic Systems},
  author={Anthony Gruber and Max Gunzburger and Lili Ju and Zhu Wang},
  year={2021},
  eprint={2110.03442},
  archivePrefix={arXiv},
  primaryClass={cs.LG}
}
