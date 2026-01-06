# TET Loss
**Official PyTorch implementation of "TET Loss: A Temperature-Entropy Calibrated Transfer Loss for Reliable Medical Image Classification"**.

TET Loss is a manually tuned, static regularization approach that employs fixed temperature scaling and entropy weighting during training. While heuristic and empirically motivated, this formulation is highly practical and effective in real-world settings. Moreover, TET Loss can be interpreted as a static instantiation of our [MiT Loss](https://github.com/JEFfersusu/MiT_loss/tree/main), where the temperature and entropy regularization strength are manually fixed instead of being adaptively calibrated in a data-driven manner.

This study is published by the _Journal of Imaging Informatics in Medicine_: https://link.springer.com/article/10.1007/s10278-025-01816-9.

You can access our article for free through this link: \url{https://rdcu.be/eXGX6}.

**The usage method can be referred to [the ipynb file of MiT_loss](https://github.com/JEFfersusu/MiT_loss/blob/main/Example_of%20_training.ipynb).**

## Citation
If you think that our work is useful to your research, please cite using this BibTeX:
```bibtex
@article{Pan2026,
  author    = {Pan, Weichao},
  title     = {TET Loss: A Temperature-Entropy Calibrated Transfer Loss for Reliable Medical Image Classification},
  journal   = {Journal of Imaging Informatics in Medicine},
  year      = {2026},
  date      = {2026-01-05},
  issn      = {2948-2933},
  doi       = {10.1007/s10278-025-01816-9},
  url       = {https://doi.org/10.1007/s10278-025-01816-9},
}
```

If you have any questions, please contact: panweichao01@outlook.com.
