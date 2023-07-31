[웹 개발자 단과반 1교시] HTML, CSS, JS 프론트엔드 속성 실무<br />
Git 개념정리💻
<br /><br />

맥 -> Terminal
<br />
win -> Git Bash 설치

# Termimal / Git Bash 실행
```bash
$ ls -al
$ cd Desktop
$ mkdir test
$ cd test
$ ls -al
$ ...
$ touch README.md
$ cd ..
$ ls -al
$ rm -rf test
```

- `ls -al` : list - al 어떤 폴더를 시작으로 보고있는지 확인
- `cd Desktop` : (cd : change directory) 바탕화면으로 가기
- `mkdir test` : (make directory) 이름이 test인 폴더 만들기
- `cd test` : test 이름의 폴더 보기
- `ls -al` : test 폴더 안에 파일 보기
- `...` : 아무것도 없다는 뜻
- `touch README.md` : README.md(설명글/메모장) 파일 만들기
- `cd ..` : desktop으로 다시 가기(.. : 뒤로가기)
- `ls -al` : 바탕화면 폴더 보기
- `rm -rf test` : test 폴더 삭제하기

# Git 프로젝트 생성
```bash
$ git init
$ git remote 저장소URL
$ git add .
$ git commit -m '커밋 메세지'
$ git push origin master
```

- `git init` : git 선언
- `git remote 저장소URL` : git 저장소와 연결
- `git add .` : 폴더 안에 파일들 업로드 준비
- `git commit -m '커밋 메세지'` : 커밋 메세지 작성
- `git push origin master` : 저장소에 코드를 업로드

# Git 에서 코드 복제
```bash
$ git clone 저장소URL
```

- `git clone 저장소URL` : 저장소에서 코드 복제



  
