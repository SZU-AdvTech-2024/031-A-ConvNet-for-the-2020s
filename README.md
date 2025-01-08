# 注意事项

注意数据文件路径为：`../dataset/cifar-100-python/train`

CIFAR-100通过datasets.CIFAR100进行下载，具体样例如下：

```python
from torchvision import datasets

dataset = datasets.CIFAR100(args.data_path, train=is_train, transform=transform, download=True)
```



