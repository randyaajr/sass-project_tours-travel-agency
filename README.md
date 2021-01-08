# Tours
---


## Languages Used
- HTML5
- CSS3 

## CSS Tricks
clip-path added to the header. 
```
clip-path: polygon(0 0, 100% 0, 100% 75vh, 0 100%);
```
Animations to title
```
@keyframes moveInLeft {
    0% {
        opacity: 0;
        transform: translateX(-100px);
    }

    80% {
        transform: translateX(10px);
    }

    100% {
        opacity: 1;
        transform: translate(0);
    }
}

@keyframes moveInRight {
    0% {
        opacity: 0;
        transform: translateX(100px);
    }

    80% {
        transform: translateX(-10px);
    }

    100% {
        opacity: 1;
        transform: translate(0);
    }
}
```
Compile SASS (In the terminal to start SCSS compiler)
```
npm run compile:sass
```

### Deployment
[Tours Link](https://randyaajr.github.io/tours/)