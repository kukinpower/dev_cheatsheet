dev_cheatsheet

dev notes and useful links [updates]

# Learn

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


# Frontend

## CSS
### Flexbox
* [🥕 Grid Garden](https://codepip.com/games/grid-garden/)
* [🐸 Flexbox Froggy](https://flexboxfroggy.com/)
* [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
* [🎥 What The FlexBox?!](https://www.youtube.com/watch?v=Vj7NZ6FiQvo&list=PLu8EoSxDXHP7xj_y6NIAhy0wuCd4uVdid&index=1&ab_channel=WesBos)

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

### How to center an object

#### #1 way
```css
.container {
	position: absolute;
	left: 50%;
	top: 50%;
	transform: translate(-50%, -50%);
}
```