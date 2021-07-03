[paper](https://arxiv.org/pdf/1703.06870.pdf)

[code](https://github.com/facebookresearch/Detectron)

## 摘要

Mask R-CNN 是一种简单、灵活且通用的框架，其在Faster R-CNN 上进行改进，通过在检测框回归分支外额外增加掩膜预测分支，实现同时对目标包围框与目标掩膜的预测。

算法优势:

* 容易训练(同时使用掩膜分支损失与包围框分支损失，可取得更佳的训练效果)，且相较Faster R-CNN只增加了一个分支，计算量增长不大,fps 5.(速度与Faster R-CNN相当)

* 泛化性强，可应用于其他类似领域，如目标跟踪(Siamese->SiamRPN->SiamMask)

* 性能优越，在多个任务上超越已有算法(2016以前)

## 引言



## 相关工作


## 实现


## 实验


## 总结


## 读后感