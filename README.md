# Setup

Setup related infos & sites

## Python

[장고걸스 튜토리얼 (Django Girls Tutorial)](https://tutorial.djangogirls.org/ko/installation/)

### Python 가상환경

myenv 라는 이름의 가상환경 생성(linux)

```
$ python3 -m venv myvenv
```

윈도우에서 virtualenv를 생성하려면 콘솔 창을 열고,  C:\Python35\python -m venv myvenv를 실행


## Anaconda 가상환경 setup

* conda create --name E7003 --clone base


### My Virtual Env

* YTGP37 : Python=3.7, Tensorflow-gpu=2.1.0, Keras=2.3.1

## 한글환경

### Jupyter Notebook 한글 쓰기
* plt.rc('font', family='Malgun Gothic')
* plt.rc('axes', unicode_minus=False)
* https://mindscale.kr/course/python-visualization-basic/font

## Warning 없애기

```
import warnings
warnings.filterwarnings(action='ignore') 
```


