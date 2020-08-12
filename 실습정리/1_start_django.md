# 3_new_django
#### 200812
## 1. Django 시작
----------
### 1. 가상환경 생성

- 가상환경 생성 : python -m venv 가상환경명
- 가상환경 들어가기 : 
  - . 가상환경명/Scripts/activate
  - source 가상환경명/Scripts/activate
  - Linux, Max : source 가상환경명/bin/activate
- 가상환경 끄기 : deactivate

### 2. Django 설치
- Django 설치 : pip install django
- pip 업데이트 : python -m pip install --upgrade pip

### 3. Django - project, app 생성
- Django project 만들기 : django-admin startproject \<프로젝트명>
  - .(온점)을 붙이면 새로운 폴더가 생기지 않음
    - cd \<프로젝트명> 으로 해서 들어가서 다음을 진행하면 됨

![온점을붙인경우](/img/온점을 붙인경우.PNG)

    - 온점을 붙인 경우


![온점을안붙인경우](/img/온점을 안 붙인경우.PNG)
    - 온점을 안 붙인 경우

- Django App 생성 : python manage.py startapp \<App 이름>