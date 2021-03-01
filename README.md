# Multistage-Attention-ResU-Net

In this repository, we re-factor the skip connections in the raw U-Net and design a Multi-stage Attention ResU-Net (MAResU-Net) for semantic segmentation from fine-resolution remote sensing images.

The detailed results can be seen in the [Multi-stage Attention ResU-Net for Semantic Segmentation of Fine-Resolution Remote Sensing Images](https://arxiv.org/ftp/arxiv/papers/2011/2011.14302.pdf).

Please notice that the training code can be seen from the respository [MACU-Net](https://github.com/lironui/MACU-Net). Feel free to contact me if you need any further information: lironui@163.com

If our code is helpful to you, please cite:

`Li, Rui, et al. "Multistage Attention ResU-Net for Semantic Segmentation of Fine-Resolution Remote Sensing Images." IEEE Geoscience and Remote Sensing Letters (2021): 1-5.`


Requirements：
------- 
```
numpy >= 1.16.5
PyTorch >= 1.3.1
sklearn >= 0.20.4
tqdm >= 4.46.1
imageio >= 2.8.0
```

Network:
------- 
![network](https://github.com/lironui/MACU-Net/blob/master/figures/Fig.%201.png)  
Fig. 1.  Comparison of (a) U-Net, (b) U-Net++， and proposed (c) MACU-Net 3+. The depth of each node is presented below the circle. 

Results:
------- 
![Result](https://github.com/lironui/MACU-Net/blob/master/figures/Fig.%204.png)  
Fig. 2. Visualization of results on the WHDLD dataset (the left) and the GID dataset (the right).
