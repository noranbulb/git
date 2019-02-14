
git law
-

업데이트 방법
```` sh
git add .
git commit -m "first commit"
git push --force origin master
````

다운로드 방법
```` sh
git pull origin master
````

commit 삭제 방법
```` sh
git reset --hard HEAD~3
````
```` sh
git reset --hard HEAD^^^
````




브런치 생성 방법
```` sh
git branch 이름 ( 브런치 생성 )
git checkout 이름 ( 브런치 선택 )

git commit -m "first commit" 을 해야 브런치가 생성된다
git push --force origin master

````


원격 브런치 리스트 보기와 삭제 방법
```` sh
git remote show origin ( 브런치 목록 보기 )
git push origin :브런지 이름 ( 브런치 삭제 )





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
  
