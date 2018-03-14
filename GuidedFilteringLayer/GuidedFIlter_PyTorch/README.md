# Fast End-to-End Trainable Guided Filter
[[GitHub]](https://github.com/wuhuikai/DeepGuidedFilter) [[Project]](https://github.com/wuhuikai/DeepGuidedFilter)    [[Paper]](https://github.com/wuhuikai/DeepGuidedFilter)    [[Demo]](https://github.com/wuhuikai/DeepGuidedFilter)    [[Home]](https://github.com/wuhuikai/DeepGuidedFilter)

Official implementation of **Fast End-to-End Trainable Guided Filter**.     
**Faster**, **Better** and **Lighter**  for image processing and dense prediction.

## Paper
**Fast End-to-End Trainable Guided Filter**     
Huikai Wu, Shuai Zheng, Junge Zhang, Kaiqi Huang    
CVPR 2018

## Install
```
pip install guided-filter-pytorch
```
## Usage
```
from guided_filter_pytorch.guided_filter import FastGuidedFilter

hr_y = FastGuidedFilter(r, eps)(lr_x, lr_y, hr_x)
```
```
from guided_filter_pytorch.guided_filter import GuidedFilter

hr_y = GuidedFilter(r, eps)(hr_x, init_hr_y)
``` 
## Citation
```
@inproceedings{wu2017fast,
  title     = {Fast End-to-End Trainable Guided Filter},
  author    = {Wu, Huikai and Zheng, Shuai and Zhang, Junge and Huang, Kaiqi},
  booktitle = {CVPR},
  year = {2018}
}
```