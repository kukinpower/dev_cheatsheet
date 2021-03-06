dev_cheatsheet

dev notes and useful links [updates]

# Shell scripts

[My collection of amazing scripts](sh.md)

# Learn

## Damn good videos
* [Web Server Concepts and Examples](https://www.youtube.com/watch?v=9J1nJOivdyw)
* [Pointers](https://www.youtube.com/watch?v=XISnO2YhnsY&t=1380s)
* [Kubernetes concepts](https://youtu.be/Krpb44XR0bk)

## 21 school (Ecole 42) guides

* [Clion](clion_getting_started.md)
* [Should you check what malloc() returns?](c-malloc.md)
* [🧭 Как выжить на бассейне школы 21](https://github.com/kukinpower/21_piscine_guide)

## Useful links
* [A minimal tutorial on make](http://kbroman.org/minimal_make/)
* [Makefile tutorial](http://makefiletutorial.com/)
* [Инструкция: создаём свой vpn-сервер](https://vc.ru/dev/66942-sozdaem-svoy-vpn-server-poshagovaya-instrukciya)

## Soft Skills
* [The Ultimate Cheat Sheet For Reinventing Yourself](https://techcrunch.com/2013/10/19/the-ultimate-cheat-sheet-for-reinventing-yourself/)
* [🎥 Андрей Дороничев – Личный совет директоров. Как сконструировать круг разных полезных людей](https://www.youtube.com/watch?v=y8be-fjXSb4)

## Health and life
* [🎥 How the food you eat affects your gut - Shilpa Ravella](https://youtu.be/1sISguPDlhY)
* [🎥 The surprisingly charming science of your gut | Giulia Enders](https://youtu.be/HNMQ_w7hXTA)

## ▶️ Music playlists for work
* [Keep calm and study](https://music.yandex.ru/users/praktikum.test/playlists/1002)
* [🎸 Заряд для программиста](https://music.yandex.ru/users/praktikum.test/playlists/1000)

# Software

## Git

* 🐙 [GitKracken](https://www.gitkraken.com/invite/eJK4c4B6)

## Testing
* [Browserhost. Free crossbrowser tester](http://browsershots.org/)

# C
## Tips
* To easily locate leaks in program on macOS, use debugger. Set breakpoints, and on every breakpoint use `leaks <your-program-process-name>`.

# Frontend

## <a href="cdd.md">CSS</a>

## React
* [Deploy react app on Surge or Github pagese](https://www.freecodecamp.org/news/surge-vs-github-pages-deploying-a-create-react-app-project-c0ecbf317089/)

## 👨🏻‍💻 Hacks and tips

### Highlight code in browser
Enter `data:text/html;,<body contenteditable>` to the address line of chrome. Copy some code from webstorm or vscode and paste somewhere on the page. You will get generated HTML with syntax highlighting. Nice homepage for a browser.

<img src="img/chrome-contenteditable.png"/>

### Copy objects from chrome console
Run `copy(object)` in chrome console to copy object to your clipboard
<a href="https://twitter.com/addyosmani">
<img src="https://pbs.twimg.com/media/DynjoaBUYAAI12l?format=jpg&name=4096x4096" href="https://twitter.com/addyosmani"/></a>
from [Addy Osmani](https://twitter.com/addyosmani)

## JS
### Atwoord's law
>“Any application that can be written in JavaScript, will eventually be written in JavaScript.”
<div style="float: right;">
Jeff Atwood, co-founder of Stack Overflow
</div>

# Git and Github
The difference between git and github is like porn and pornhub

## Basic team git workflow
Master branch should always contain working version of a project. All new features should be made in different branches and than merged to master.

So you should create new branch, make a feature and merge feature branch to master. Than branch can be deleted. And created a new one for another feature.

Basic pipeline:

Create a new branch and go there
```
git checkout -b new_feature
```
There code a new feature and changes to the branch

When feature is ready checkout to master
```
git checkout master
```
Create merge commit
```
git merge --no-ff new_feature
```
If there are no conflicts after merge, push
```
git push
```
If have conflicts, resolve them (vscode is good for this purpose)

Create new commit and push
```
git add -A
git commit -m "message"
git push
```

* [Понятно о регулярках](https://youtu.be/_pLpx6btq6U)
