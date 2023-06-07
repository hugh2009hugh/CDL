# DCL

An Implementation of Dual-view Contrastive Learning for Auction Recommendation in PyTorch.


<!-- # Requirements

```
PyTorch 0.4 & Python 3.6
Numpy
TensorboardX
``` -->

## Dataset - eBay

`python ./code/dataloader.py ebay` for data pre-processing.


## Dataset - Swoopoo

`python ./code/dataPrep.py swp` for data filtering.

`python ./code/dataloader.py swp` for data pre-processing.

## Run Model
`python ./code/mrgcn.py ebay 1 1 1 1.0 0.1` for eBay dataset.

`python ./code/mrgcn.py swp 1 1 1 1.0 0.3` for Swoopoo dataset.

<!-- # Dataset

You should execute `python data.py` first to download necessary data and preprocess MovieLens-20M dataset.

[ml-20m.zip Download](https://grouplens.org/datasets/movielens/20m/) -->
