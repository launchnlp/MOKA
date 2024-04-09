# MOKA: Moral Knowledge Augmentation for Moral Event Extraction

## Introduction
This repository contains codes and dataset for paper ["MOKA: Moral Knowledge Augmentation for Moral Event Extraction"](https://arxiv.org/pdf/2311.09733.pdf) (NAACL 2024).

**Update**
- [04/09/2024] We released the initial version of MORALITY BANK (Good for model pre-training to inject moral knowledge derived from moral words 🚀).
- [03/13/2024] Our MOKA paper is accepted to NAACL 2024 Main Conference 🌟!
- [01/18/2024] We released the initial version of MoralEvents (Good for downstream moral reasoning capability assessment 🚀).
- [11/15/2023] We released the arXiv version of our [MOKA paper](https://arxiv.org/pdf/2311.09733.pdf).

## Set up
Run the following commands to clone the repository.
```shell script
$ git clone https://github.com/launchnlp/MOKA.git
```

## Data: MoralEvents 
Raw MoralEvents can be found under [MoralEvents](./MoralEvents) directory. Please read README under [MoralEvents](./MoralEvents) directory for more information.

Processed data and the script for data processing will be released soon.

## Pre-training Corpus: MoralEvents 
MORALITY BANK can be found under [MoralityBank](./MoralityBank) directory. Please read README under [MoralityBank](./MoralityBank) directory for more information.

## Model: MOKA
*We are still refactoring and cleaning the codebase, Please stay tuned for more updates.*

## Citation
Please kindly cite our paper if you use our **MoralEvents** dataset:
```
@article{zhang-et-al-2023-moka,
  author       = {Xinliang Frederick Zhang and
                  Winston Wu and
                  Nick Beauchamp and
                  Lu Wang},
  title        = {{MOKA:} Moral Knowledge Augmentation for Moral Event Extraction},
  journal      = {CoRR},
  volume       = {abs/2311.09733},
  year         = {2023},
  url          = {https://doi.org/10.48550/arXiv.2311.09733},
  doi          = {10.48550/ARXIV.2311.09733},
}
```

## Contact
If you have any question, please contact Xinliang Frederick Zhang ```<xlfzhang@umich.edu>``` or create a Github issue.
