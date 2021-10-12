# Sky-Segmentation-and-Post-processing
This is a C++ implementation from this paper https://arxiv.org/abs/2006.10172 that public on 2020, the repo is for sky mask post-processing. but I didn't implemente the "Density Estimation" mentioned in the paper

About Sky segmentation, I trained the sky-segmentation model by U-2-Net, the result looks good. please refer to https://github.com/xuebinqin/U-2-Net about training detail

Dependency：OpenCV

The Sky-mask Post-Processing show a good performence in the scene of tree as below. it retain much more details

![vis2](https://github.com/xiongzhu666/Sky-Segmentation-and-Post-processing/blob/main/vis2.png)

![vis1](https://github.com/xiongzhu666/Sky-Segmentation-and-Post-processing/blob/main/vis1.png)

but it also has some defect：in the scene of building, some detail of building will be considered as sky by mistake

![vis3](https://github.com/xiongzhu666/Sky-Segmentation-and-Post-processing/blob/main/vis3.png)

