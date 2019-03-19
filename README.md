# PluralSight Login Page Clone
A simple, responsive clone of the **_PluralSight Login Page_** - [View](http://esankole.gq/todolist/)


[![Practice](https://img.shields.io/badge/Practice-CSS-blue.svg)](http://www.esankole.gq/todolist/)

_<p align="center">"Good artists copy. Great artists steal" - Picaso_</p>

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

Also chose to use [Materialize CSS Toasts](https://materializecss.com/toasts.html) instead of crappy window methods (like `alert()` and `confirm()`). Added the ToDo Counter Badge as well.
```javascript
M.init(); // Initializes Materialize JS
M.toast({html:'',displayLength:1200});
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

That being said
_<p align="center">Adieu, I must return to Code mountain to continue my training the Ways of  Ninjustu</p>_