# grad-cam
## 注意⚠️:
**1.这个项目在苹果的Silicon M1上完美运行。**
**2.由于本项目没有对图像输入进行处理，因此输入图像的尺寸必须是224x224，否则热图效果不理想。**

### 项目文件夹📁介绍

* examples:save input images.
* results:save output images.

### 如何运行该项目

1.搭建一个python的虚拟环境

```python
conda create -n your_env_name python==3.9
```

2.切换到搭建的虚拟环境

* 如果你使用PC平台:

```python
activate your_env_name
```

* 如果你使用Ubuntu or Mac:

```python
source activate your_env_nam
```

3.安装项目所依赖的库

```python
pip install -r requirements.txt
```

4. 如何生成grad_cam图 ？！

```python
python cam.py --image-path path "for inputimage" --method "cam method"
```
举例：

```shell
python get_cam.py --image-path './examples/both.png' --method 'gradcam'
```



### 示例

![image](https://github.com/ElegantAnkster/grad-cam/blob/main/examples/both.png?raw=true)
![image](https://github.com/ElegantNorlin/grad-cam/blob/main/results/both_gradcam.jpg?raw=true)

### 相关链接
* https://github.com/jacobgil/pytorch-grad-cam
* https://zhuanlan.zhihu.com/p/371296750
* https://github.com/jacobgil/pytorch-grad-cam
