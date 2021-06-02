<h1 align = "center">🚀GIT 사용법🛰</h1>

<p align = "center"><img src = "https://git-scm.com/images/logo@2x.png"/></p>

## Contents
- [GIT을 사용하기 위한 준비💾](https://github.com/sustainable-git/GIT/blob/main/contents/01_preparation.md)
  - `git --version`
#
- [GIT 설정하기🛠](https://github.com/sustainable-git/GIT/blob/main/contents/02_setting.md)
  - `git config --global user.name "이름"`
  - `git config --global user.email "이메일"`
  - `git config --global --edit"`
    - `git config --global core.autocrlf input`(Mac)
    - `git config --global core.autocrlf true`(Window)
    - `git config --global core.editor "xed --wait"`(Xcode)
    - `git config --global core.editor "code --wait"`(Visual Studio Code)
#
- [GIT 생성하고 삭제하기🗑](https://github.com/sustainable-git/GIT/blob/main/contents/03_init.md)
  -  `git init`
  -  `rm -rf .git`
#
- [Staging Area에서 파일 Track 또는 Untrack 하기👀✨](https://github.com/sustainable-git/GIT/blob/main/contents/04_add.md)
  -  `git add 파일명`
     -  `git add .`
  -  `git rm --cached 파일명`
  -  `echo 파일명 > .gitignore`
     - `echo *.log > .gitignore`
  -  `git status`
     -  `git status -s`
