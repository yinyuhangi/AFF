# [Attentional Feature Fusion](https://arxiv.org/abs/2009.14082)
#### Accepted by WACV 2021，收录到[PytorchNetHub](https://github.com/bobo0810/PytorchNetHub)

## 作用
- 基于注意力机制的特征融合
- 特征融合的统一方式，Short Skip、Long Skip、Same Layer均适用

## 说明
- 非官方
- 2020.11.19 新增AFF、iAFF
- [ ] 支持AFFResNet、AFFResNeXt等

## 使用
```python
from fusion import AFF, iAFF
# x,residual  [B,C,H,W]
fusion_mode = AFF(channels=C)
x = fusion_mode(x, residual)
```

## 算法框架
![](https://github.com/bobo0810/AFF/blob/main/imgs/AFF.png)

## 参考
 [官方MXNet版](https://github.com/YimianDai/open-aff)











