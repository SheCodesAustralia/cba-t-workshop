---
title: "Nav"
weight: 3
chapter: false
---

The `nav` (aka "navigation") is used to provide links that navigate to other webpages.

Let's wrap our three links in opening and closing `nav` tags:

{{% notice style="warning" title="Before - Replace this code" %}}
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

{{% notice style="tip" title="After - Updated code" %}}
```html
<header>
  <nav>
    <a href="https://en.wikipedia.org/wiki/Turtle">Wikipedia</a>
    <a href="https://www.worldwildlife.org/species/sea-turtle">WWF</a>
    <a href="https://www.britannica.com/animal/turtle-reptile">Britannica</a>
  </nav>
  <img src="https://assets.codepen.io/5804361/Myrtle_Game.gif" alt="Gif of computer game with turtle moving around a grid."/>
  <h1>Myrtle the Turtle</h1>
</header>
```
{{% /notice %}}

{{% notice style="warning" title="Test" icon="vial" %}}

The background of the nav should appear as darker pink.
The links should be on the right, each with a white background.

{{% /notice %}}

Here's our header so far:

![Screenshot of page with white nav buttons.](../../images/myrtle_nav.png)
