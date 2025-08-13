---
title: "Div"
weight: 4
chapter: false
---

Unlike the `header` and `nav` elements, the `div` (divider) element does not inherently represent anything.
Instead, this element is used to group other elements.

Let's wrap our `h1` and `img` elements in a `div` tag:

{{% notice style="warning" title="Before - Replace this code" %}}
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

{{% notice style="tip" title="After - Updated code" %}}
```html
<header>
  <nav>
    <a href="https://en.wikipedia.org/wiki/Turtle">Wikipedia</a>
    <a href="https://www.worldwildlife.org/species/sea-turtle">WWF</a>
    <a href="https://www.britannica.com/animal/turtle-reptile">Britannica</a>
  </nav>
  <div>
    <img src="https://assets.codepen.io/5804361/Myrtle_Game.gif" alt="Gif of computer game with turtle moving around a grid."/>
    <h1>Myrtle the Turtle</h1>
  </div>
</header>
```
{{% /notice %}}

{{% notice style="warning" title="Test" icon="vial" %}}

The image and header text should now be side by side.

{{% /notice %}}

Here's our header so far:

![Screenshot of header with image and h1 side by side.](../../images/myrtle_div.png)
