
## git law
-

#### 1.이미 깃에 연결 되었지만 포멧후 깃에 업데이트 안될때 로그인
```` sh
git remote add origin https://github.com/noranbulb/jxslider.git //프로젝트 주소
git config --global user.email "you@example.com" //깃에 사용했던 이메일 입력
git config --global user.name "Your Name" // 이름 입력

````

#### 2.폴더별로 깃 연결 ( --global 삭제 )
```` sh
git config user.email "you@example.com" //깃에 사용했던 이메일 입력
git config user.name "Your Name" // 이름 입력

````

#### 3.수정파일 업데이트 방법
```` sh
git add . //모든 파일 선택
git commit -m "first commit" //수정내용 표시
git push origin master //일반 업로드
git push --force origin master //강제 업로드 : 로컬과 깃에 파일이 달라서 업데이트 안되면 강제 푸시를 하여 업데이트 할수가 있지만 형상관리가 없어지기 때문에 깃에 파일이 최신이라면 git pull로 로컬에 가져온후에 작업을 생각해봐야한다
````

#### 4.서버에서 로컬로 복사
```` sh
git clone https://github.com/noranbulb/jxslider.git //폴더 그대로 복사
git remote add upstream https://github.com/freevuehub/new-ui-todo.git //상대방 리모트를 upstream이라는 명으로 추가
git pull upstream master //상대방 주소인 upstream에 master의 파일 받아오기
git pull origin master //origin이 마이 주소였고 master 브런치에 파일 받아오기

````

#### 5.리모트 관리 ( clone 후에 필수 연결해야함 )
```` sh
git remote add upstream https://github.com/freevuehub/new-ui-todo.git //상대방 리모트 추가
git remote //리모트 목록
git remote remove uptest  //리모트 삭제

````

#### 6.상대방 깃 가져오고 형상관리
```` sh

fork 를 먼저 하고
git clone https://github.com/noranbulb/new-ui-todo.git ( 폴더 그대로 복사 )
git remote add upstream https://github.com/freevuehub/new-ui-todo.git // 상대방 리모트 추가
git pull upstream master // 파일 받아오고

git push 내 깃 허브에 업데이트

````

![screensh](./resources/img/pull_request_1.jpg)
![screensh](./resources/img/pull_request_2.jpg)
![screensh](./resources/img/pull_request_3.jpg)
![screensh](./resources/img/pull_request_4.jpg)


#### 7.브런치 생성 방법
```` sh
git branch dev (dev 브런치 생성 )
git checkout dev (dev 브런치 선택 )

git push --force origin dev
````
![screensh](./resources/img/branch_pull_request_1.jpg)
![screensh](./resources/img/branch_pull_request_2.jpg)
![screensh](./resources/img/branch_pull_request_3.jpg)
![screensh](./resources/img/branch_pull_request_4.jpg)
![screensh](./resources/img/branch_pull_request_5.jpg)


#### 8.원격 브런치 리스트 보기와 삭제 방법
```` sh
git remote show origin ( 브런치 목록 보기 )
git push origin :브런지 이름 ( 브런치 삭제 )

````


#### commit 삭제 방법
```` sh
git reset --hard HEAD~3
````
```` sh
git reset --hard HEAD^^^
````



#### top title
```` sh
  project name
  -------    (ex: -가 한개여도 상관없다 )
````

#### sub title
```` sh
  #### sub title
  -------
````

#### html expression
```` sh
  ```` html    내용작성      ````
````

#### javascript xpression
```` sh
  ```` javascript    내용작성      ````
````


#### table expression
```` sh
  Option | Type | Default | Description
  ------ | ---- | ------- | -----------
````


  td 1 | td 2 | td 3 | td 3
  -- | -- | -- | --
--- | 2 | 3 | 4

