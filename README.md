# grad-cam
* The project works perfectly on Apple's Silicon M1. *

### Project description

* examples:save input images.
* results:save output images.

### usage

1.build an environment

```python
conda create -n your_env_name python==3.9
```

2.activate environment

* if your platform is PC:

```python
activate your_env_name
```

* if your platform is Ubuntu or Mac:

```python
source activate your_env_nam
```

3.install dependency

```python
pip install -r requirements.txt
```

4.How to get grad_cam picture ？！

```python
python cam.py --image-path path "for inputimage" --method "cam method"
```
for example

```shell
python get_cam.py --image-path './examples/both.png' --method 'gradcam'
```



### example image

![image](https://github.com/ElegantAnkster/grad-cam/blob/main/examples/both.png?raw=true)
![image](https://github.com/ElegantNorlin/grad-cam/blob/main/results/both_gradcam.jpg?raw=true)

### Reference
* https://github.com/jacobgil/pytorch-grad-cam
* https://zhuanlan.zhihu.com/p/371296750
* https://github.com/jacobgil/pytorch-grad-cam
