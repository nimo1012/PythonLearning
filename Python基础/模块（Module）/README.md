# 模块（Module）

## 什么是模块

事实上，在Python中一个.py文件就是一个模块。我们在编写代码时不可能从头开始构建所有的类或函数，而是通过import导入其他模块中已经定义好的类或函数。在Python的安装路径下我们可以找到许多自带的模块，例如*argparse.py*以及*os.py*。我们可以在程序中添加如下代码来导入以上模块中的类和函数：

```python
import argparse
import os
```

在这里要注意，以上代码是将整个模块都导入进来。如果想要调用模块*argparse.py*中的类**ArgumentParser**，需要采用如下的书写方式：

```python
parser = argparse.ArgumentParser()
```
