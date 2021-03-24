<h1 align="center">Jervi - portfolio</h1>

<div align="center">
  <h3>
    <span> | </span>
    <a href="https://jervi.netlify.app/">
      Demo
    </a>
    <span> | </span>
  </h3>
</div>

<img src="./img/screenshot.png">


### in process

- [X] Reveal
- [X] Animate Jeriv
- [ ] about me modal
- [ ] my skills modal
- [X] turn moto pic into gif
- [ ] Responsive
- [ ] make form mailing system


- [X] Logo
- [x] Jervi pic
- [x] moto pic
- [x] font modern
- [x] sliding band (marquee)
- [x] 2KingsWebsites logo
- [x] Contanct me modal

## Resources 
[Reveal Content Animation](https://codepen.io/tobiasglaus/pen/oZJdZY) <br>
[Cyberpunk Button](https://codepen.io/jh3y/pen/PoGbxLp) <br>
[Parallax](https://www.youtube.com/watch?v=dc4zyX6DuOc) <br>
[news tape marquee](https://www.google.com/search?q=marquee+html) <br>
[background split](https://www.w3schools.com/cssref/func_linear-gradient.asp)
## Socials

[youtube](https://www.youtube.com/channel/UCD-YOxxLv5yGhcerkZLGZgg) <br>
[facebook](https://www.youtube.com/channel/UCD-YOxxLv5yGhcerkZLGZgg) <br>
[instagram](https://www.instagram.com/gacem_humen/)


## Tips 

#### To frame animate pictures do :

```html
<ul id="scene">
        <img src="/img/jervi6.png" id="jervi">
</ul>
```

```javascript
var jervi = document.getElementById("jervi");

jervi.classList.add("jervi-frames");

setTimeout(() => {
    setTimeout(() => {
        jervi.src = "/img/jervi5.png";
        setTimeout(() => {
            jervi.src = "/img/jervi4.png";
        }, 166);
    }, 166);
}, 0);


```

```css
#jervi.jervi-frames {
    animation-name: jerviAnimation;
    animation-duration: 1s;
    transition: 1s;
}
@keyframes jerviAnimation {
    16.66% {
        background-image: url(/img/jervi6.png);
    }
    33.33% {
        background-image: url(/img/jervi5.png);
    }
    50% {
        background-image: url(/img/jervi4.png);
    }
    66.66% {
        background-image: url(/img/jervi3.png);
    }
    83.33% {
        background-image: url(/img/jervi2.png);
    }
    100% {
        background-image: url(/img/jervi1.png);
    }
}
```


#### to get element by tag
```js
var menu = document.getElementsByClassName("menu")[0];
```








