# [Re] UPINN
**Reproduction** of the UPINN from "<a href="https://openreview.net/forum?id=FREvWGzoRu">Universal Physics-Informed Neural Networks: Symbolic Differential Operator Discovery with Sparse Data</a>" proposed by Lena Podina, Brydon Eastman and Mohammad Kohandel (ICML2023)

## Content
The folders in this repo are organized as follows:
* `imgs/` contains the images included in te report,
* `datasets/` constains two datasets for the burger and Schrödinger equation,
* `misc/` contains a notebook for the PINN tutorial,
* in `upinn_models/` we saved the trained models for both Lotka Volterra and burger equation,
* `LotkaVolterra/` contains the code to train UPINN on Lotka Volterra system. The symbolic regression code can be found in `LotkaVolterra/ai-feynman/`, with the corresponding solutions in `LotkaVolterra/ai-fynman/solutions/`,
* `Burgers_equation/` contains notebooks to run UPINN fo the burger equation,
* `Cell Apostosis/` contains the notebook that implements UPINN for the cell apostosis system,
* additionally, we attempted to solve the Schrödinger and the notebooks can be found in `Schrödinger/notebooks`

## Authors
**Michele Cattaneo**, **Claudio Milanesi**, **Oliver Tryding**

