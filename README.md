# DarkLighter: Light up the Darkness for UAV Tracking

Code and demo videos of DarkLighter---a low-light enhancer towards facilitating UAV tracking in the dark.


# Abstract 
>Recent years have witnessed the fast evolution and promising performance of the convolutional neural network (CNN)-based trackers, which aims at imitating biological visual systems. However, current CNN-based trackers can hardly generalize well to low-light scenes that are commonly lacked in the existing training set. In indistinguishable night scenarios frequently encountered in tracking-based applications on unmanned aerial vehicle (UAV), the robustness of the state-of-the-art trackers drops significantly. To facilitate aerial tracking in the dark through a general fashion, this work proposes an image enhancer namely DarkLighter, which dedicates to alleviate the impact of poor illumination conditions and noises iteratively. A lightweight network, i.e., LE-Net, is trained to efficiently estimate illumination layers and noise layers jointly. Experiments are conducted with several SOTA trackers on numerous UAV dark tracking scenarios. Exhaustive evaluations demonstrate the reliability and universality of DarkLighter, with high efficiency. Moreover, DarkLighter has further been implemented onboard a typical UAV system, real-world UAV tracking tests at night verify its practicability and dependability.

# Demo video

<iframe 
    width="800" 
    height="450" 
    src="https://youtu.be/rJtPST69J60"
    frameborder="0" 
    allowfullscreen>
</iframe>

# Publication and citation

DarkLighter is proposed in our paper for IROS 2021. Detailed explanation of our method can be found in the paper:

Junjie Ye, Changhong Fu, Guangze Zheng, Ziang Cao, and Bowen Li

DarkLighter: Light up the Darkness for UAV Tracking

# Contact 
Junjie Ye

Email: ye.jun.jie@tongji.edu.cn

Changhong Fu

Email: changhongfu@tongji.edu.cn

# Demonstration running instructions

### Requirements

1.Python 3.7

2.Pytorch 1.0.0

3.opencv-python

4.torchvision

5.cuda 10.2

>Download the package, extract it and follow two steps:
>
>1. Put test images in data/test/, put training data in data/train/.
>
>2. For testing, run:
>
>     ```
>     python lowlight_test.py
>     ```
>
>3. For training, run:
>
>     ```
>     python lowlight_train.py
>     ```



# Acknowledgements

We thank the contribution of `Chongyi Li`, `Chen Wei` for their previous work Zero-DCE and Retinex-Net.

