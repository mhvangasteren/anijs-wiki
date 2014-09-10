# How use it?

#### 1. **Include the anijs library**

 ```html
 <script src="anijs-min.js"></script>
 ```

#### 2. **Include an auxiliar stylesheet with the animations you will need**

For example in our case:

```html
<link rel="stylesheet" href="animate.css">
```

#### 3. Play with data-anijs tag:
```html
<p data-anijs="if: click, on:h1, do: pulse animated, to:h2"></p>
```

If you do not understand that we are talking about, don't worry continue reading, My first time was hard.

#### 3. Decide:

 * Which ***Event*** do you want to capture, interact or response on.

 * Which ***Html Elements*** do you want to modify or animate.

 * Which ***Actions or Animations*** do over those elements.

#### 4. Write the sentence inside any html element:

 Using the previous decided elements, complete the sentence:  

 **If:** *some event(click, scroll, mouseover and more)*, **On:** *any element (css selector)*, **Do:** *some behavior(Rotate animation)*, **To:** *(any element)*

...and write it inside any html element (*code, span, p, div*...) like the next example:

```html
<p data-anijs="if: click, on:h1, do: pulse animated, to:h2"></p>
```