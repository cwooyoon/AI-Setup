# Python 환경 venv setup

https://techexpert.tips/ko/windows-ko/%EC%9C%88%EB%8F%84%EC%9A%B0%EC%97%90-%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EA%B0%80%EC%83%81-%ED%99%98%EA%B2%BD-%EC%84%A4%EC%B9%98/

## pip upgrade
```
$ pip --version
$ python -m pip install --user -U pip
```
파이썬 가상 환경 프로젝트를 저장하는 디렉터리를 만듭니다.
```
mkdir C:\virtual 
cd C:\virtual
```
파이썬 가상 환경을 만듭니다.
```
python -m venv project01
```
가상 환경 디렉터리의 내용을 확인합니다.
```
dir project01
```
파이썬 3 가상 환경을 사용하 시작합니다.
```
project01\Scripts\activate
```
명령줄 프롬프트가 변경되어야 합니다.
```
C:\virtual>
(project01) C:\virtual>
```
가상 환경에서 사용되는 Python 버전을 확인합니다.
```
python --version
where python
```
파이썬 가상 환경을 중지합니다.
```
deactivate
```

```

```

```

```
