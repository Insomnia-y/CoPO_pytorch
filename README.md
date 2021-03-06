# An Unofficial Pytorch Implementation of CoPO

This is an unofficial Pytorch implementation of CoPO in paper ["Learning to Simulate Self-driven Particles System with Coordinated Policy Optimization"](https://proceedings.neurips.cc/paper/2021/file/594ca7adb3277c51a998252e2d4c906e-Paper.pdf).

[Here is the official repository](https://github.com/decisionforce/CoPO)

## How to use

### Installation

same as the official implementation.

### Training

Put folder `algo_yyx_copo_tc` and `round` into the official repository's path `copo_code/copo`.

```python
cd copo_code/copo/
python round/train_copo_torch.py
```

## Result

Prove that the implementation is correct.

![image-20220121195645313](https://gitee.com/insomnia-y/my-figure-bed/raw/master/img/202202161501685.png)

## Citation

```
@article{peng2021learning,
  title={Learning to Simulate Self-Driven Particles System with Coordinated Policy Optimization},
  author={Peng, Zhenghao and Hui, Ka Ming and Liu, Chunxiao and Zhou, Bolei and others},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
```



