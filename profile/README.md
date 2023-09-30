<p align="center">
  <img width="240" alt="상명대eat 앱아이콘" src="https://github.com/SMUeat/.github/assets/56509933/22bbdbf8-742c-4207-934f-79b3fde12f09">
</p>

<p align="center">
  <strong>
    - 상명대 eat 🍽️ -
    <br>
    '상명대생 오늘 어디서 먹지?'
    <br>
    상명대학교 주변 식당 순위표 서비스입니다.
  </strong>
</p>
<br>



## 🔍 Introduction

### 주제 선정
학교생활을 하며 매끼니를 뭘 먹을지 고민하는 많은 상명대생들의 고충을 접했습니다. <br>
하지만 기존 식당 리뷰는 외부인이 작성하여 상명대생들의 입맛과는 달랐다고 하였습니다. <br>
이에 상명대생들이 직접 만들어나가는 그들만의 기준이 담긴 식당 순위표를 제공해보자는 생각에 아이디어를 얻었습니다.

### 특징
- 복잡하지 않은 심플한 UI 디자인으로 접근성을 높였습니다.
- 식당과 술집으로 카테고리를 나누어, 목적에 맞춰 쉽게 장소를 찾을 수 있도록 하였습니다.
- 상명대생들의 기준이 담긴 식당 순위표이므로, 장소를 직접 추가하여 아직 리스트에 존재하지않은 맛집을 추가할 수 있습니다.
- 1~3위의 장소에는 노란색 테두리와 트로피 그림으로 도드라지게 나타내어, 최상위권 식당임을 나타냅니다.
<br>



## 📹 Demo

### PC Page

**Main page**|**Admin sort**
-----|-----
<img src="https://github.com/SMUeat/.github/assets/56509933/aa05c9c6-1dbb-4ae5-8019-c23725888959" width="100%">|<img src="https://github.com/SMUeat/.github/assets/56509933/6f25afae-fbf4-47e4-8b09-326d1b65370b" width="100%">
모든 장소를 순위별로 정렬한 목록 메인 페이지 입니다.|관리자용 정렬 페이지 입니다.

### Mobile Page

**Main page**|**Admin sort**
-----|-----
<img src="https://github.com/SMUeat/.github/assets/56509933/276f6e02-bed9-450b-a836-109463837cc2" width="100%">|<img src="https://github.com/SMUeat/.github/assets/56509933/0b505996-6f0e-48a7-8982-c910802cba5c" width="100%">
모든 장소를 순위별로 정렬한 목록 메인 페이지 입니다.|관리자용 정렬 페이지 입니다.

<br>



## 💻 Architecture
![smueat_architecture drawio](https://github.com/SMUeat/.github/assets/56509933/95cde2c7-7149-4c5a-840e-1e152b8a33e0)
<br><br>



## 💡 Tech Stack
|Frontend|Backend|Other|
|:------:|:------:|:------:|
|<img src="https://img.shields.io/badge/Django Template Engine-092E20?style=flat-square&logo=Django&logoColor=white"/></a><br><img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=HTML5&logoColor=white"/></a><br><img src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=CSS3&logoColor=white"/></a><br><img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a><br><img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=SQLite&logoColor=white"/></a>|<img src="https://img.shields.io/badge/Amazon AWS-232F3E?style=flat-square&logo=Amazon AWS&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Github-111011?style=flat-square&logo=Github&logoColor=white"/></a><br><img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat-square&logo=Visual Studio Code&logoColor=white"/></a>

```
- Frontend : Django Template Engine, HTML, CSS, JavaScript
- Backend : Django, Python
- Database: SQLite
- Deployment: Amazon AWS
- Version control: Github
- Development Environment : Visual studio code
```
<br>



## 🗂️ Database
<img width="1470" alt="DB ERD" src="https://github.com/SMUeat/.github/assets/56509933/accaf8c4-14d7-4b22-8c20-7947136f5fdc">
<br><br>



## 📂 Directory Structure

```bash
├── SMUeat
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-39.pyc
│   │   ├── admin.cpython-39.pyc
│   │   ├── apps.cpython-39.pyc
│   │   ├── forms.cpython-39.pyc
│   │   ├── models.cpython-39.pyc
│   │   ├── tests.cpython-39.pyc
│   │   ├── urls.cpython-39.pyc
│   │   └── views.cpython-39.pyc
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── migrations
│   │   ├── 0001_initial.py
│   │   ├── 0002_alter_review_comment.py
│   │   ├── 0003_review_password.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── 0001_initial.cpython-39.pyc
│   │       ├── 0002_alter_review_comment.cpython-39.pyc
│   │       ├── 0003_review_password.cpython-39.pyc
│   │       └── __init__.cpython-39.pyc
│   ├── models.py
│   ├── static
│   │   └── SMUeat
│   │       └── 상명대마크.png
│   ├── templates
│   │   └── SMUeat
│   │       ├── base.html
│   │       ├── checkpassword.html
│   │       ├── checkpassword_review.html
│   │       ├── create_place.html
│   │       ├── create_place_fail.html
│   │       ├── create_review.html
│   │       ├── delete_place.html
│   │       ├── delete_review.html
│   │       ├── info.html
│   │       ├── notice.html
│   │       ├── place_list.html
│   │       ├── review_list.html
│   │       ├── search_fail.html
│   │       ├── search_success.html
│   │       ├── tmi.html
│   │       └── update_review.html
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
├── projectdjango
│   ├── __init__.py
│   ├── __pycache__
│   │   ├── __init__.cpython-39.pyc
│   │   ├── settings.cpython-39.pyc
│   │   ├── urls.cpython-39.pyc
│   │   └── wsgi.cpython-39.pyc
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── static2
    ├── SMUeat
    │   └── 상명대마크.png
    └── admin
        ├── css
        ├── fonts
        ├── img
        └── js
```
<br>



## 👨‍👩‍👧‍👧 Team (Full Stack)

|                                              [사현진](https://github.com/tkguswls1106)                                              |
| :------------------------------------------------------------------------------------------------------------------------------: |
| <img width = "300" src ="https://github.com/OnlineMemo/.github/assets/56509933/a13439f7-934d-41e1-be52-190e40753707"> |
|                                                   Frontend & Backend Developer                                                    |
