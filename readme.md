# 킥라니 멈춰! 

This is the repository that contain the code run on the **jetson nano** to detect the scooter rider on the road with **YOLOv5 object detection**.



## Environment

- jetson nano 2GB developer kit
- jetpack 4.4.1



## Preinstall

### ubuntu update

```shell
sudo apt update
sudo apt upgrade
sudo apt-get install python3-pip
```



### install pytorch

```shell
wget https://nvidia.box.com/shared/static/p57jwntv436lfrd78inwl7iml6p13fzh.whl -O torch-1.8.0-cp36-cp36m-linux_aarch64.whl
sudo apt-get install python3-pip libopenblas-base libopenmpi-dev 
pip3 install Cython
pip3 install numpy torch-1.8.0-cp36-cp36m-linux_aarch64.whl
```



### install torchvision

```shell
$ sudo apt-get install libjpeg-dev zlib1g-dev libpython3-dev libavcodec-dev libavformat-dev libswscale-dev
$ git clone --branch v0.9.0 https://github.com/pytorch/vision torchvision
$ cd torchvision
$ export BUILD_VERSION=0.9.0 
$ python3 setup.py install --user
```



### library install

```shell
sudo python3 -m pip install -U pip
sudo python3 -m pip install -U setuptools

pip3 install tqdm
pip3 install matplotlib
pip3 install seaborn
pip3 install PyYAML
sudo apt-get install gfortran libopenblas-dev liblapack-dev
pip3 install scipy
pip3 install seaborn
pip3 install tensorboard
pip3 install opencv-python
```



