## [ 仅 paddle 参数更多 ] torch.Tensor

### [torch.Tensor](https://pytorch.org/docs/stable/tensors.html)

```python
torch.Tensor(data)
```

### [paddle.to_tensor](https://www.paddlepaddle.org.cn/documentation/docs/zh/develop/api/paddle/to_tensor_cn.html#to-tensor)

```python
paddle.to_tensor(data, dtype=None, place=None, stop_gradient=True)
```

Paddle 比 PyTorch 支持更多参数，具体如下：

### 参数映射

| PyTorch | PaddlePaddle | 备注                                                        |
| ------- | ------------ | ----------------------------------------------------------- |
| data    | data         | 要转换的数据。 |
| -       | dtype        | Tensor 的数据类型，PyTorch 无此参数，Paddle 保持默认即可。   |
| -       | place        | Tensor 的设备，PyTorch 无此参数，Paddle 需设置为 'cpu' 。         |
| -       | stop_gradient | 是否阻断 Autograd 的梯度传导。PyTorch 无此参数，Paddle 保持默认即可。     |
