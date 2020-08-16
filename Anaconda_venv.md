# Anaconda Virtual Environment setup

```
Chrome 실행  -> anaconda download
윈도우 부팅  -> etriai04 로긴
    https://www.anaconda.com/products/individual
    64bit graphical installer 선택
    All user로 진행
    Install
Anaconda menu  -> prompt 실행
    conda create -n senior python=3.7
    conda activate senior
Pytorch.org
    conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
Jupyter Notebook 설치
    conda install jupyter notebook
    conda install ipykernel
    python -m ipykernel install --user --name senior --display-name “SeniorAI”
Jupyter Notebook 사용
    Anaconda메뉴에서 Jupyter Notebook(Senior) 선택 사용
    New -> SeniorAI 선택 
Torch GPU 확인
    Import torch
    torch.cuda.get_device_name(0)
    torch.cuda.is_available()
```

