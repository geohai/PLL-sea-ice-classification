# Partial Label Learning With Focal Loss for Sea Ice Classification Based on Ice Charts

This repository contains the code associated with the paper "Partial Label Learning With Focal Loss for Sea Ice Classification Based on Ice Charts," published in the IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing.

## What this code enables:
The code implements a novel deep learning approach for sea ice classification using partial label learning. This technique handles multiple labels and class imbalance in expert-generated sea ice charts. It integrates ice concentration confidence scores and focal loss to train a convolutional neural network (CNN) for sea ice classification in Sentinel-1 dual-polarized SAR images.

Key features include:
- Handling partial labels (multiple ice types) in training data.
- Implementing focal loss for addressing class imbalance.
- Training and testing on Sentinel-1 SAR imagery for improved classification accuracy and F1 scores.

## Citation
If you use this code, please cite the following paper:
```
@ARTICLE{10568501,
  author={Vahedi, Behzad and Lucas, Benjamin and Banaei-Kashani, Farnoush and Barrett, Andrew P. and Meier, Walter N. and Khalsa, Siri Jodha Singh and Karimzadeh, Morteza},
  journal={IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing}, 
  title={Partial Label Learning With Focal Loss for Sea Ice Classification Based on Ice Charts}, 
  year={2024},
  volume={17},
  pages={13616-13633},
  doi={10.1109/JSTARS.2024.3413003}
}
```

For more details, see the paper on [IEEE Xplore](https://ieeexplore.ieee.org/document/10568501).
