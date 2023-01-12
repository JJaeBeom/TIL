# 첫 Github

## README 생성

- GIT 초기화

- GIT repo 생성



빔?

-m안붙이고 그냥 git commit 들어가면 Insert > 첫째줄에 제목써주고 >esc >  제일밑에 :wq 입력



**내 로컬 폴더와 git repository를 연결하는 작업**

remote repo, 즉 github이나 gitlab과 같은 원격 저장소에 있는 repository와 내 로컬 폴더(내 컴퓨터 내부에 있는 폴더)와 연결시키는 작업을 하는 명령어

- git remote add origin 링크  << origin(원격저장소) 꼭 origin이 아니어도 된다.
  
  ex) git remote add origin https://github.com/JJaeBeom/TIL.git
  - 링크 자리에는 repository의 url을 복사해서 넣으면 됨
  - control + c 를 써서 붙여넣으려고 할 때 에러가 날 수 있으니(원래 종료할 때 쓰는 명령어이기도 해서) shift+insert 키를 써서 복사한 내용을 삽입하는것이 좋다
- git remote -v : 현재 이 폴더가 어떤 원격저장소와 연결되어있는지 확인하는 명령어

그런데 만약 내가 연결시켜야 하는 저장소가 아니라면 해당 폴더의 remote repo정보를 지워줘야 함

- git remote rm origin ( 참고로 origin은 default처럼 사용하는 이름이고 따로 설정할 수도 있긴 하다 )
  - rm은 remove의 의미

git push origin master

 origin 주소에 master가 작업한 결과를 업로드

자격 증명 관리자 <<  windows 자격증명 - 일반자격증명- 



## 새로운 수정 사항


