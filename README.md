# NeMF: Inverse Volume Rendering with Neural Microflake Field
### [Project Page](https://youjiazhang.github.io/NeMF/) | [Paper](https://arxiv.org/pdf/2304.00782)

<div align=center>
<img src="imgs/teaser.jpg" width="100%"/>
</div>

> [NeMF: Inverse Volume Rendering with Neural Microflake Field](https://arxiv.org/pdf/2304.00782)  
> Youjia Zhang, Teng Xu, Junqing Yu, Yuteng Ye, Junle Wang, Yanqing Jing, Jingyi Yu, Wei Yang.  
> ICCV 2023

## Installation

We have tested the code on pytorch 1.8.1, while a newer version of pytorch should also work.

```bash
conda create -n object_nerf python=3.8
conda activate object_nerf
conda install pytorch==1.13.1 torchvision cudatoolkit=11.3 -c pytorch -c conda-forge
pip install -r requirements.txt
```
## Data Preparation

Download `nerf_synthetic.zip` from [here](https://drive.google.com/drive/folders/128yBriW1IG_3NJ5Rp7APSTZsJqdJdfc1)
