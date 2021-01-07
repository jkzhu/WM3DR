# WM3DR
*[Weakly-Supervised Multi-Face 3D Reconstruction](https://arxiv.org/abs/2101.02000)*

![gif](result/out.gif)

## Installation

To run the demo, the following requirements are needed.
```
pytorch >= 1.4
pytorch3d
```

## Model
3DMM model used in this repo is from [Deep3dPytorch](https://github.com/changhongjian/Deep3DFaceReconstruction-pytorch), you should generate mSEmTFK68etc.chj file and put it into './BFM/'

Download the trained model [final.pth](https://drive.google.com/file/d/1Rx76Q2pkinxY8T5EtGHyc8bqlZhSYWtf/view?usp=sharing) in './model/'

## Demo
```
python demo_video.py
```

## Citation

If you find this project useful for your research, please use the following BibTeX entry.

    @misc{zhang2021weaklysupervised,
      title={Weakly-Supervised Multi-Face 3D Reconstruction}, 
      author={Jialiang Zhang and Lixiang Lin and Jianke Zhu and Steven C. H. Hoi},
      year={2021},
      eprint={2101.02000},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
    }
