---
title: "Header"
weight: 2
chapter: false
---

The `header` element is used for introductory content.
This is usually the main heading for the page and the navigation bar.

Let's wrap our `h1` and `image` in the header:

{{% notice style="warning" title="Before - Replace this code" %}}
```html

  <a href="https://en.wikipedia.org/wiki/Turtle">Wikipedia</a>
  <a href="https://www.worldwildlife.org/species/sea-turtle">WWF</a>
  <a href="https://www.britannica.com/animal/turtle-reptile">Britannica</a>
  <img src="https://assets.codepen.io/5804361/Myrtle_Game.gif" alt="Gif of computer game with turtle moving around a grid."/>
  <h1>Myrtle the Turtle</h1>
  
```
{{% /notice %}}

{{% notice style="tip" title="After - Updated code" %}}
```html
<header>
  <a href="https://en.wikipedia.org/wiki/Turtle">Wikipedia</a>
  <a href="https://www.worldwildlife.org/species/sea-turtle">WWF</a>
  <a href="https://www.britannica.com/animal/turtle-reptile">Britannica</a>
  <img src="https://assets.codepen.io/5804361/Myrtle_Game.gif" alt="Gif of computer game with turtle moving around a grid."/>
  <h1>Myrtle the Turtle</h1>
</header>
```
{{% /notice %}}

{{% notice style="warning" title="Test" icon="vial" %}}

The background of the header should appear pink.

{{% /notice %}}

Here's our header so far:

![Screenshot of page with pink header.](../../images/myrtle_header.png)
