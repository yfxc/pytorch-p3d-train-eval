# pytorch-p3d-train-eval
This is a complement version of ‘pseudo-3d-pytorch’ realized by [qijiezhao](https://github.com/qijiezhao/pseudo-3d-pytorch).
## Note that:
- Aiming at training and testing P3D model using my own dataset,I added a few parts including **1.Data Fetching Cell**,
**2.Training Cell**,and**3.Evaling Cell**.
- The input of P3D model should be **preprocessing**,more details about preprocessing dataset :
https://github.com/yfxc/pseudo-3d-tensorflow(You can add data augmentation cell with refering to 'DataAugmenter.py')
- Using Pytorch,remember executing **model.train()** when you train model,while **model.eval()** for testing,especially
when you have BatchNorm Layers.
