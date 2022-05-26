python -m venv venv

source venv/Scripts/activate

pip install -r requirements.txt 

python manage.py migrate

python manage.py loaddata genre_data.json

python manage.py loaddata movie_data.json 

python manage.py runserver



python -m pip install --upgrade pip

<hr>

git switch -c 브랜치이름

브랜치만들고 이동 작업 add commit => 브랜치에서 push

GitHub에서  push한 내용 pull request 하기 

pull request 확인 후 merge => 깃허브 반영

 @로컬로 돌아와서 브랜치 master로 변경 후  pull !!!!

git switch master

git pull origin master

끝나고 꼭 삭제  git branch -D 앱이름





<hr>



- Fix : 잘못된 동작을 고칠 때   > Fix typo in Home.vue 
- Add : 새로운 것을 추가할 때   > Add Detail.vue 
- Remove : 삭제가 있을 때   > Remove Detail.vue 
- Update : 정상적으로 동작하는 파일을 보완하는 경우   > Update login logic to accounts.js

<hr>
admin 계정 !!
ID: admin
PW: templix



<hr>

<body class="" style="background: linear-gradient(to bottom, #434343 1% , #141414); background-repeat: no-repeat;  background-attachment: fixed; height: 100%; margin: 0;">

 <nav class="navbar navbar-expand-lg navbar-dark sticky-top bg-dark">

<hr>


  File "C:\Users\minjae\Desktop\finalll\templix\movies\urls.py", line 2, in <module>
    from . import views
  File "C:\Users\minjae\Desktop\finalll\templix\movies\views.py", line 7, in <module>
    from dotenv import load_dotenv
ModuleNotFoundError: No module named 'dotenv'



<hr>



- 현재 가능 : 인덱스 페이지 / 이미지 추천 / 태그라인 추천 / 검색 결과 / 영화별 리뷰, 별점 작성 / 전체 리뷰 페이지 / 리뷰 생성, 수정, 삭제

- 불가능 : 마이페이지 / 리뷰페이지 댓글 / 장르 출력 / 리뷰 좋아요

  

  
  
  
  
  장르 추천(디테일), 유투브api, 카카오api, 비동기요청,테그라인있는것만 데이터만들기?  
  
  
  
  >>>>>>>>>>>>>>> 정렬,리뷰댓글 
