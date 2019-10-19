# Git Bash로 프로젝트 업로드

## 초기설정
    $ git --version //설치확인
    $ git config --global user.name "seongbong" //이름
    $ git config --global user.email "ha3548@naver.com" //이메일
    $ git config --list //설정확인

## 프로젝트 파일 업로드
    $ cd Desktop/폴더명 //바탕화면에 프로젝트폴더가 있을 때
    $ git init //새로운 git 저장소 생성
    $ git status //파일 상태 확인
    $ git add 파일or폴더 //저장소에 파일or폴더 추가
    $ git add . //모든파일
    $ git commit -m "commit" //"커밋메세지"
    $ git remote add origin https://github.com/레파지토리주소.git
    $ git remote -v //원격저장소 추가 확인
    $ git push origin master //창이 뜨면 github id, pw 입력

## Repository 폴더 삭제/추가
    //github 저장소 내려받기
    $ git clone https://github.com/레파지토리주소.git
    
삭제

    $ git rm -rf 파일or폴더 //원격저장소,로컬저장소에서 모두 삭제
    $ git rm -r --cached 파일or폴더 //원격저장소에서만 삭제, 로컬저장소는 그대로
     
추가

    $ git add 파일or폴더 //저장소에 파일or폴더 추가
    $ git add . //모든파일
    
저장

    $ git commit -m "remove/add directory" //"커밋메세지"
    $git push origin master

