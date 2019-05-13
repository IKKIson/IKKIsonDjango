# IKKIson's Django Project

## How to Build

### 0. Devops
- Windows 10
- IDE : PyCharm pro 19.1
- Python 3.7

### 1. Set Anaconda
(1) 아나콘다 다운받기

(2) 아나콘다 설치하기

### 2. Create Virtual Environment With Anaconda

(1) Find Anaconda Installed Directory in My C-Drive
- C드라이브에 설치된 아나콘다 폴더를 찾으세요.

(2) Check And Remember c/.../Anaconda/venv Directory Path
- 아나콘다 폴더에서 venv 이라는 가상환경 폴더를 확인하고 venv 까지의 경로를 확인하세요.

(3) Execute Anaconda Prompt(Anaconda Powershell Prompt)
- 아나콘다 프롬프트(또는 아나콘다 파워셀 프롬프트)를 실행하세요.

(4) Insert Command (pls Follow this Step)
- 밑의 명령어를 차례대로 따라하세요.
    1. 프롬프트에서 아까 확인한 venv 폴더로 이동
    2. 새로운 가상환경 생성하기
    3. 생성한 가상환경 활성화하기
    4. 장고프레임워크와 필요한 모듈, API 설치
    5. 새로운 장고 프로젝트 생성을 위해 원하는 폴더로 이동하기(생성위치 확인해주기!!)
    6. 새로운 장고 프로젝트 생성(생성위치 확인해주기!!)
    7. 장고프로젝트 잘 생성됬나 확인하기 (1) 구성 확인
    8. 장고프로젝트 잘 생성됬나 확인하기 (2) 서버 실행
    9. 가상환경 비활성화하기
    
 
```
    //create venv
> conda create --name [my venv dir name] python=[3.x or your hope] anaoncda

    //activate venv
> conda activate [my venv dir name]

    //install module you needs
    //pip insatll [] or conda install []
> pip install django
> pip install django-rest-framework
> pip install celery
> pip install django-celery
> pip install django-pandas

    //create New Django Project
    //move directory you want
> d: //move c to d drive
> cd [d/.../directory path you want]
> django-admin startproject [project name you want]

    //now Execute pycharm this step and Open My Project
    //Check Directory
IKKIsonDjango   //Directory(=Gir Repository)
    ├ IKKIsonDjango   //project
    │    ├ __init__.py
    │    ├ settings.py
    │    ├ urls.py
    │    └ wsgl.py
    ├ db.sqlite3
    ├ manager.py
    └ READM.md

    //run server(in prompt) - option
> python manage.py runserver
    
    //check 127.0.0.1:8000 localhost in WebBrowser
//http://127.0.0.1:8000/

    //deactivate current venv
> conda deactivate
``` 