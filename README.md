# chatting_backbm

# Django project setting

- python 설치

- (mac 기준) poetry 설치
> brew install poetry
> poetry --version

- poetry를 사용하여 가상환경 설정
> mkdir 폴더이름
> cd 폴더이름
> poetry init
  => pyproject.toml 생성

- 가상환경에 Django 설치
> poetry add Django
  => poetry.lock 생성

- 가상환경에서 Django 실행
> poetry shell # 가상환경으로 접속
> django-admin # 가상환경의 django 실행

- Django project 생성
> django-admin startproject config . 
  => 현재 폴더에서 프로젝트 생성 ( . 은 현재 경로)
  => config 파일 생성
  
# 초기 설정

- python manage.py makemigrations
- python manage.py migrate
- python manage.py runserver 

- python manage.py createsuperuser

- python manage.py startapp 폴더이름 => 폴더 
