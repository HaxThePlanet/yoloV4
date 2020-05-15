# keras-yolo4

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

A Keras implementation of YOLOv4 (Tensorflow backend) inspired by [https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet).

Frame code from [https://github.com/qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3).

![](yolo4.png)

---

## Quick Start

1. Download YOLOv4 weights from [yolov4.weights](https://drive.google.com/open?id=1cewMfusmPjYWbrnuJRuKhPMwRe_b9PaT).
2. Convert the Darknet YOLOv4 model to a Keras model.
3. Run YOLOv4 detection.

```
python convert.py
```

Running convert.py will get keras yolov4 weight file yolo4_weight.h5.


### Usage

Inference

```
python test.py
```
---

### Todo

Debug train code with CIoU loss. Loss code from [https://github.com/david8862/keras-YOLOv3-model-set](https://github.com/david8862/keras-YOLOv3-model-set).


pip list
Package                         Version             Location
------------------------------- ------------------- ---------------------------------
absl-py                         0.7.1
asgiref                         3.2.7
astor                           0.8.0
astunparse                      1.6.3
attrs                           19.1.0
backcall                        0.1.0
bleach                          3.1.4
cachetools                      4.0.0
certifi                         2019.6.16
chardet                         3.0.4
cloudpickle                     1.3.0
colorama                        0.4.3
configparser                    5.0.0
contextlib2                     0.6.0.post1
cycler                          0.10.0
Cython                          0.29.16
decorator                       4.4.0
defusedxml                      0.6.0
detectron2                      0.1                 c:\users\bob\documents\detectron2
Django                          3.0.5
docutils                        0.16
entrypoints                     0.3
future                          0.18.2
fvcore                          0.1.dev200420
gast                            0.2.2
google-auth                     1.14.1
google-auth-oauthlib            0.4.1
google-colab                    1.0.0
google-pasta                    0.2.0
grpcio                          1.22.0
h5py                            2.10.0
idna                            2.8
image                           1.5.28
imagesize                       1.2.0
importlib-metadata              1.6.0
ipykernel                       5.1.1
ipython                         7.6.1
ipython-genutils                0.2.0
ipywidgets                      7.5.0
jedi                            0.14.0
Jinja2                          2.10.1
joblib                          0.13.2
jsonschema                      3.0.1
jupyter                         1.0.0
jupyter-client                  5.3.0
jupyter-console                 6.0.0
jupyter-core                    4.5.0
Keras                           2.2.4
Keras-Applications              1.0.8
Keras-Preprocessing             1.1.0
keyring                         21.2.0
kiwisolver                      1.1.0
LBExporters                     0.1.1
lxml                            4.5.0
Markdown                        3.1.1
MarkupSafe                      1.1.1
matplotlib                      3.0.3
mistune                         0.8.4
mpmath                          1.1.0
nbconvert                       5.5.0
nbformat                        4.4.0
notebook                        5.7.8
numpy                           1.16.4
oauthlib                        3.1.0
opencv-python                   4.1.0.25
opt-einsum                      3.2.0
pandas                          0.24.2
pandocfilters                   1.4.2
parso                           0.5.0
pexpect                         4.7.0
pickleshare                     0.7.5
Pillow                          6.2.1
pip                             20.1
pkginfo                         1.5.0.1
portalocker                     1.7.0
portpicker                      1.2.0
progressbar2                    3.46.1
prometheus-client               0.7.1
prompt-toolkit                  2.0.9
protobuf                        3.8.0
ptyprocess                      0.6.0
pyasn1                          0.4.8
pyasn1-modules                  0.2.8
pycocotools                     2.0
Pygments                        2.4.2
pyparsing                       2.4.0
pyrsistent                      0.15.3
python-dateutil                 2.8.0
python-utils                    2.4.0
pytz                            2019.1
pywin32                         227
pywin32-ctypes                  0.2.0
pywinpty                        0.5.7
PyYAML                          5.1.1
pyzmq                           18.0.2
qtconsole                       4.5.1
QtPy                            1.9.0
readme-renderer                 25.0
requests                        2.22.0
requests-oauthlib               1.3.0
requests-toolbelt               0.9.1
rsa                             4.0
scikit-learn                    0.21.2
scipy                           1.4.1
Send2Trash                      1.5.0
setuptools                      46.1.3
Shapely                         1.7.0
simplegeneric                   0.8.1
six                             1.12.0
sklearn                         0.0
sqlparse                        0.3.1
style                           1.1.0
sympy                           1.4
tabulate                        0.8.7
tb-nightly                      2.3.0a20200404
tensorboard                     1.15.0
tensorboard-plugin-wit          1.6.0.post2
tensorflow-estimator            1.15.1
tensorflow-gpu                  1.15.0
tensorflow-gpu-estimator        2.2.0
tensorflow-object-detection-api 0.1.1
termcolor                       1.1.0
terminado                       0.8.2
testpath                        0.4.2
tf-estimator-nightly            2.3.0.dev2020040301
torch                           1.5.0
torchvision                     0.6.0
tornado                         6.0.3
tqdm                            4.45.0
traitlets                       4.3.2
twine                           3.1.1
update                          0.0.1
urllib3                         1.25.3
wcwidth                         0.1.7
webencodings                    0.5.1
Werkzeug                        0.15.4
wheel                           0.34.2
widgetsnbextension              3.5.0
wrapt                           1.11.2
yacs                            0.1.6
YOLO3                           1.0
zipp                            3.1.0

