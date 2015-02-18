## Getting started
### 1. **Include the anijs library:**

```html
    <script src="anijs-min.js"></script>
```

### 2. **Include the stylesheet with the animations: **

For example in our case:

```html
    <link rel="stylesheet" href="animate.css">
```

### 3. Play with data-anijs tag:
```html
    <p data-anijs="if: click, on:h1, do: pulse animated, to:h2"></p>
```
Also check this [example](http://codepen.io/darielnoel/pen/trnzk?editors=100)

### Lets take a closer look...

First, you must decide: **What I want my page to Do?** and for that you may begin deciding:

 * Which ***Event*** you want to capture, interact or response on.

 * Which ***Html Elements*** you need to modify or animate.

 * Which ***Actions or Animations*** you want happening over those elements.


Good!, now, using those elements... **How write the anijs setence?**

You can try by completing with those previous elements the next fragment:

>**If:** *Event(click, scroll, mouseover and more)*, **On:** *Html element (css selector)*, **Do:** *Actions or Animations (Rotate animation)*, **To:** *Html element to modify (css selector)*

and finally copy the sentence into some html element like the next example:

```html
    <p data-anijs="if: click, on:h1, do: pulse animated, to:h2"></p>
```

That's all!

Nevertheless, you can play with anijs sentence a lot of more, keep looking around this site, you'll find more details, examples and versatility. You'll have a lot of fun!
