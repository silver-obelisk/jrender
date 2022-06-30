# Jrender 



## 介绍

本代码用于对Easyship的渲染


## 使用

使用JRender前需要安装好Jittor，Jittor安装方法在[此处](https://github.com/Jittor/jittor)。

此外安装以下包：

```
jittor
imageio==2.9.0
imageio-ffmpeg==0.4.3
matplotlib==3.3.0
configargparse==1.3
tensorboard==1.14.0
tqdm==4.46.0
opencv-python==4.2.0.34
```


## 计图大赛
安装好jittor和上述其他依赖包后可按照以下命令运行：
```
git clone https://github.com/silver-obelisk/jrender.git
cd jrender
python Easyship.py --config ./configs/Easyship.txt
```


同时，本渲染器内置了N3MR和SoftRas两个可微渲染器，若您在研究中使用了渲染器，请您引用相应的论文。
```
@InProceedings{kato2018renderer
    title={Neural 3D Mesh Renderer},
    author={Kato, Hiroharu and Ushiku, Yoshitaka and Harada, Tatsuya},
    booktitle={The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2018}
}

@article{liu2019softras,
  title={Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning},
  author={Liu, Shichen and Li, Tianye and Chen, Weikai and Li, Hao},
  journal={The IEEE International Conference on Computer Vision (ICCV)},
  month = {Oct},
  year={2019}
}
```
