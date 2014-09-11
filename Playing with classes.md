**How put or remove classes to the html elements?**


1. First, include the libraries...:

```
<script src="anijs-helper-dom-min.js"></script>
<script src="anijs-min.js"></script>
```

2. and the auxiliar stylesheet of your preference:

```
<link rel="stylesheet" href="animate.css">
```

3. Then inside the anijs sentence... 

You can use the words: 

 * $addClass
 * $removeClass
 * $toggleClass

Like the next examples:

```
<input type="hidden" data-anijs="if: mouseover, on: .tab, do: $removeClass active, to: .tab.active;
                             	if: mouseover, on: .tab, do: $addClass active, to: target">
```