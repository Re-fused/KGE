# Multi-aspect Enhanced Convolutional Neural Networks for Knowledge Graph Completion

This is the code of paper 
**Multi-aspect Enhanced Convolutional Neural Networks for Knowledge Graph Completion**. 

## Requirements
- python 3.8
- torch 1.9
- dgl 0.8

Available datasets are:
    
    FB15k-237
    WN18RR


## Reproduce the Results
To run a model execute the following command :
- FB15k-237
```bash python run.py ```
- WN18RR
```bash python run.py --th1 0.4 --th2 0.1 --conve_hid_drop 0.2 --num_filt 250 --x_ops p.b.d --r_ops p.b.d```




## Acknowledgement
We refer to the code of [LTE](https://github.com/MIRALab-USTC/GCN4KGC) and [DGL](https://github.com/dmlc/dgl). Thanks for their contributions.
