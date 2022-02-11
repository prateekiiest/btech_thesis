## Evaluating regrets while joining a community - A Novel Community Detection in Large Networks using Game Theory.

<p>
  <a href="https://aaai.org/Conferences/AAAI-22/">
    <img src="http://img.shields.io/badge/AAAI-2022-red.svg">
  </a>
  <a href="https://openreview.net/pdf?id=xUBHq0OrgeR"><img src="http://img.shields.io/badge/Paper-PDF-brightgreen.svg"></a>
</p>


This is done as part of my Bachelor's thesis with [Prof. Malay Kule](https://www.iiests.ac.in/IIEST/Faculty/cs-malay) and [Prof. Susanta Chakraborty](https://www.iiests.ac.in/IIEST/Faculty/cs-sc).


Attached paper **accepted** at [AAAI MLOR 2021](https://ml4or22.github.io/).

[Would I regret later joining this Community ? Using temporal neighborhood information for community retention in a game theoretic community detection framework](./files/AAAI_MlrOR.pdf)


![](./Btech%20Thesis%20images.svg)

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Customization](#customization)
- [Citation](#citation)


## Features

- Faster convergence than existing game-theoretic based approaches, maintaining the same community structure.
- Proposal of a novel modularity maximization objective that takes into account *community retention*, resulting in faster convergence. 
- Theoretical Gaurantees on Nash equilibria for proposed modularity-maximization metric.
- Real world effectivness. Experimented on datasets
  - *Amazon*
  - *Enron*
  - *Karate*
  - *Football*
  - *Dolphin*
  - *ERDOS992*
  - *fb pages food*
  - *retweet network*
  - *fb pages politician*


## Demo

If you want to run a demo of our code, you can follow the following steps:

### Windows / Ubuntu

#### Via Visual Studio Code

- Open `Visual Studio Code`
- `git clone https://github.com/prateekiiest/btech_thesis.git`
- Follow setup of `Jupyter Notebooks in Visual Studio Code` from this [setup tutorial](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)
- Once you have cloned the repository do `cd btech-thesis/code`
- Open `comm-regret.ipynb` in your Jupyter Kernel.


### Via Anaconda 

- Install Anaconda following this [documentation](https://docs.anaconda.com/anaconda/install/) - [Windows Install](https://docs.anaconda.com/anaconda/install/windows/) , [Linux Install](https://docs.anaconda.com/anaconda/install/linux/)
- `git clone https://github.com/prateekiiest/btech_thesis.git` under your specified designated folder path.
- Open Jupyter Notebook (anaconda installation comes with all features including Jupyter notebook/ Spyder IDE)
- Once the notebook folder view opens, navigate to `btech-thesis/code`
- Open `comm-regret.ipynb` in your Jupyter Kernel.



## Citation

If you use this code for your research, please consider citing the arXiv preprint

```bibtex
@article{chanda2021would,
  title={Would I regret later joining this Community? Using temporal neighborhood information for community retention in a game theoretic community detection framework},
  author={Chanda, Prateek and Chakraborty, Susanta},
  booktitle={AAAI-22 Workshop on Machine Learning for Operations Research},
  year={2021}
}

```
