AniJS allows you to handle [CSS3 animations](http://www.sitepoint.com/build-awesome-apps-with-css3-animations/) easily, you just need to **include** the animation styles definition, and after that you can play with **data-anijs** tag. 

```xml
<head>
    <!-- Include the styles definition -->
    <link rel="stylesheet" href="assets/styles/custom-animations.css">
</head>
```

```xml
<button data-anijs="if:click, on: span, do: pulseAnimation, to: .navbar"></button>
```

We **strongly recomend** you to use the amazing [Animate.css library](http://daneden.github.io/animate.css/) as starting point, this library provides beautiful animations.

##Using Animate.css library

```xml
<head>
    <!-- Animate.css library -->
    <link rel="stylesheet" href="http://cdn.jsdelivr.net/animatecss/3.1.0/animate.css">
</head>
```

```xml
<button data-anijs="if:click, on: span, do: bounce animated, to: .navbar"></button>
```

**Note:** Remember to add the **animated** css class  when you are using the  Animated.css library.

##Tips an Tricks

If you want to run the animation only once just add **holdAnimClass** to the **after** definition.

```xml
<button data-anijs="if:click, on: span, do: pulse animated, to: .navbar, after: holdAnimClass"></button>
```
