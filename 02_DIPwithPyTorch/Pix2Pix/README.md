
## 实现[Pix2Pix]

这个存储库是黄晓远对DIP的Assignment_02的实现。

<img src="pics/result_1.png" alt="alt text" width="800"> 

## Requirements

To install requirements:

```setup
python -3.10 pip install -r requirements.txt
```

## Running

想要进行训练:

```basic
python train.py
```

## Results
200轮以后损失无明显下降，故在470轮时停止。
### 测试集结果
<img src="pics/result_1.png" alt="alt text" width="800"> 
<img src="pics/result_2.png" alt="alt text" width="800"> 
<img src="pics/result_3.png" alt="alt text" width="800"> 
<img src="pics/result_4.png" alt="alt text" width="800"> 
<img src="pics/result_5.png" alt="alt text" width="800"> 

## Resources:
- [Paper: Poisson Image Editing](https://www.cs.jhu.edu/~misha/Fall07/Papers/Perez03.pdf)
- [Paper: Image-to-Image Translation with Conditional Adversarial Nets](https://phillipi.github.io/pix2pix/)
- [Paper: Fully Convolutional Networks for Semantic Segmentation](https://arxiv.org/abs/1411.4038)
