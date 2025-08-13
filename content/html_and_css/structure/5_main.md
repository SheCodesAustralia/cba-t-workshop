---
title: "Main"
weight: 5
chapter: false
---

The `main` element represents the dominant content in the `body` of the page.

As per the others, let's wrap our `h2` and `h3` headings, paragraphs and images with a `main` opening and closing tag:

{{% notice style="warning" title="Before - Replace this code" %}}
```html

  <h2>Anatomy and Physiology</h2>
  <h3>Size</h3>
  <p>The largest living species of turtle (and fourth-largest reptile) is the leatherback turtle which can reach over 2.7 m (8 ft 10 in) in length and weigh over 500 kg (1,100 lb).</p>
  <h3>Shell</h3>
  <p>The shell of a turtle is unique among vertebrates and serves to protect the animal and provide shelter from the elements.</p>

  <h2>Behaviour</h2>
  <h3>Diet and Feeding</h3>
  <p>Most turtle species are opportunistic omnivores; land-dwelling species are more herbivorous and aquatic ones more carnivorous.</p>
  <p>Turtles generally eat their food in a straightforward way, though some species have special feeding techniques.</p>

  <img src="https://assets.codepen.io/5804361/turtle_1.jpg"/>
  <img src="https://assets.codepen.io/5804361/turtle_2.jpg"/>
  <img src="https://assets.codepen.io/5804361/turtle_3.jpg"/>

```
{{% /notice %}}

{{% notice style="tip" title="After - Updated code" %}}
```html
<main>

  <h2>Anatomy and Physiology</h2>
  <h3>Size</h3>
  <p>The largest living species of turtle (and fourth-largest reptile) is the leatherback turtle which can reach over 2.7 m (8 ft 10 in) in length and weigh over 500 kg (1,100 lb).</p>
  <h3>Shell</h3>
  <p>The shell of a turtle is unique among vertebrates and serves to protect the animal and provide shelter from the elements.</p>

  <h2>Behaviour</h2>
  <h3>Diet and Feeding</h3>
  <p>Most turtle species are opportunistic omnivores; land-dwelling species are more herbivorous and aquatic ones more carnivorous.</p>
  <p>Turtles generally eat their food in a straightforward way, though some species have special feeding techniques.</p>

  <img src="https://assets.codepen.io/5804361/turtle_1.jpg"/>
  <img src="https://assets.codepen.io/5804361/turtle_2.jpg"/>
  <img src="https://assets.codepen.io/5804361/turtle_3.jpg"/>

</main>
```
{{% /notice %}}

{{% notice style="warning" title="Test" icon="vial" %}}

The content in the main should have a purple background.

{{% /notice %}}


Here's our page so far:

![Screenshot of page with purple background.](../../images/myrtle_main.png)
