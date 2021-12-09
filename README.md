# grad-cam
A simple script to generate grad-cam.

### Project description

* examples:save input images.
* result:save output images.
* get_cam.py:Batch generation of Grad-CAM  

### usage

build an environment

```python
conda create -n your_env_name python==3.x
```

activate environment

* if your platform is PC:

```python
activate your_env_name
```

* if your platform is Ubuntu:

```python
source activate your_env_nam
```

install dependency

```python
pip install pytorch-grad-cam
```

run get_cam.py to get grad_cam picture!

```python
python cam.py --image-path path "for inputimage" --method "cam method"
```
### example
![image](https://github.com/ElegantAnkster/grad-cam/blob/main/examples/both.png?raw=true)
![image](https://github.com/ElegantAnkster/grad-cam/blob/main/result/both.png_gradcam_cam.jpg?raw=true)
### Reference

* https://zhuanlan.zhihu.com/p/371296750
* https://github.com/jacobgil/pytorch-grad-cam
