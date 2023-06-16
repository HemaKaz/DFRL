# DRFL
Code for DFRL : Dynamic Relational Learning For Few-Shot Knowledge Graph Completion
# Datasets
We adopt Nell and Wiki datasets to evaluate our model.
The orginal datasets and pretrain embeddings are provided from [xiong's repo](https://github.com/xwhan/One-shot-Relational-Learning). 
For convenience, the datasets can be downloaded from [Nell data](https://sites.cs.ucsb.edu/~xwhan/datasets/nell.tar.gz)
and [Wiki data](https://sites.cs.ucsb.edu/~xwhan/datasets/wiki.tar.gz). 
# How to run
To achieve the best performance, pls train the models as follows:
#### Nell

```
python trainer.py --weight_decay 0.0 --prefix nell.5shot
```
To test the trained models, pls run as follows:

#### Nell

```
python trainer.py --weight_decay 0.0 --prefix nell.5shot_best --test
