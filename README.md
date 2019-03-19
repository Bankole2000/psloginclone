# PluralSight Login Page Clone
A simple, responsive clone of the **_PluralSight Login Page_** - [View](https://bankole2000.github.io/psloginclone/)

[![Practice](https://img.shields.io/badge/Practice-CSS-blue.svg)](https://bankole2000.github.io/psloginclone/)

Here's links to both the original and this clone for quick comparison
[View Original](https://app.pluralsight.com/id?redirectTo=%2Fid%2Fdashboard) || [View This clone](https://bankole2000.github.io/psloginclone/)

_<p align="center">"Good artists copy. __Great__ artists ~~create from nothing using only innate talent and/or God-given magic~~ __steal__" - Picaso_</p>

<div align="center" style="text-align:center; margin:auto;">
<img align="center" src="https://i.imgur.com/EgCvXyK.png" width="150"/>
</div>

## What it is
A simple, learning Project to practice HTML and CSS Fundamentals. Built with:
* HTML
* CSS - FlexBox & Media Queries
* [Google Fonts](https://fonts.google.com/) - Custom Google Fonts
* [LOVE](https://www.wikihow.com/Love-Programming) - Strictly for the love of coding _Mehn!_

## What it does

* Doesn't Do anything Yo! Just a cloning exercise. Looks pretty cool though.

## Learning Points
* FlexBox
* CSS Media Queries
* That Horizontal Line OR thing (you know the one)

## Some notes
This is just ___one___ of ___many___ cloning projects I will be doing to build a collection of clones for referencing purposes.
Login Pages are a staple of just about ___every___ website. And being able to make a cool one is pretty important. 
#### Here's the OR thing
HTML => 
```html
<div class="or">
  <hr class="bar">
  <span>OR</span>
  <hr class="bar">
</div>
```
CSS =>
```css
.or{
  display:flex;
  flex-direction: row;
  margin-bottom: 1.2rem;
  align-items: center;
}
.or .bar{
  flex: auto;
  border:none;
  height: 1px;
  background: #aaa;
}
.or span {
  color: #ccc;
  padding: 0 0.8rem;
}
``` 

Here's the gist of media queries =>
```css
@media(min-width: 1200px;){
  //Larger Screens
}
@media(max-width: 768px;){
  //Tablets and Down
}
```
## Future Development
  Just some ideas in my head for improvements I might come back to this to implement.
* Adding Social Login buttons (because wth not?)
* Using SASS
* A little JS for Event handling

## Contribution
Contributions are highly welcome. Feel free to fork, clone, make pull requests, make comments/observations etc.

## Acknowledgments

* Many thanks to [@bradtraversy](https://github.com/bradtraversy) for his awesome courses - _i will not fail you sensei_
* Thanks to [@torvalds](https://github.com/torvalds) For Making the world a better place
* And To anyone reading this... _You're awesome!_


_<p align="center">"The Master has **failed** more times than the beginner has even **tried**" - Bruce Lee</p>_