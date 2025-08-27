# basicReact

git config --global user.name
git config -- global user.email

git --global user.name
git --global user.email


//저장소 생성 및 연결
$ git init
$ git remote add origin [원격저장소 주소]
$ git branch -m master main

//파일 업로드
$ git pull (또는 git pull origin main)
$ git add .
$ git commit -m "commit message"
$ git push (또는 git push origin main)

연결상태 확인
$ git remote -v

origin remove
$ git remote rm origin

브랜치 확인
$ git branch

브랜치 초기화 및 연결
$ git config --global init.defaultBranch [브랜치 이름]

깃 상태 확인
$ git status
$ git rm --cached -r .
$ git push -u origin main


