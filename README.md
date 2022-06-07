# python-django-tutorial

<img src="https://img.shields.io/badge/django 4.0-092E20?style=flat-square&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/python 3.9-3776AB?style=flat-square&logo=python&logoColor=white"/>

## 프로젝트 만들기
```commandline
django-admin startproject mysite
```

## dev run
```commandline
python3 manage.py runserver
```

## 앱 만들기
```commandline
python3 manage.py startapp polls
```

## 테이블 생성
```commandline
python3 manage.py migrate
```

## 모델 변경 사항 저장
```commandline
python3 manage.py makemigrations polls
```

## migration이 내부적으로 어떤 SQL을 실행하는지 확인
```commandline
python3 manage.py sqlmigrate polls 0001
```

## cli에서 테스트하기
```commandline
python3 manage.py shell
```

## 관리자 생성
```commandline
python3 manage.py createsuperuser
```

## Reference
- `https://docs.djangoproject.com/`