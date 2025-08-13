---
title: "Sections"
weight: 6
chapter: false
---

The `section` element represents a generic standalone section of the page.
Similar to the `div`, it is used to group elements, but unlike the `div`, a `section` always has a heading element and additional elements with related content.

We'll add two sections to our page, one for "Anatomy and Physiology" and one for "Behaviour":

{{% notice style="warning" title="Before - Replace this code" %}}
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

{{% notice style="tip" title="After - Updated code" %}}
```html
<main>
  <section>
    <h2>Anatomy and Physiology</h2>
    <h3>Size</h3>
    <p>The largest living species of turtle (and fourth-largest reptile) is the leatherback turtle which can reach over 2.7 m (8 ft 10 in) in length and weigh over 500 kg (1,100 lb).</p>
    <h3>Shell</h3>
    <p>The shell of a turtle is unique among vertebrates and serves to protect the animal and provide shelter from the elements.</p>
  </section>
  <section>
    <h2>Behaviour</h2>
    <h3>Diet and Feeding</h3>
    <p>Most turtle species are opportunistic omnivores; land-dwelling species are more herbivorous and aquatic ones more carnivorous.</p>
    <p>Turtles generally eat their food in a straightforward way, though some species have special feeding techniques.</p>
  </section>
    <img src="https://assets.codepen.io/5804361/turtle_1.jpg"/>
    <img src="https://assets.codepen.io/5804361/turtle_2.jpg"/>
    <img src="https://assets.codepen.io/5804361/turtle_3.jpg"/>
</main>
```
{{% /notice %}}

{{% notice style="warning" title="Test" icon="vial" %}}

The two sections will have a lighter purple background, compared to the main.

{{% /notice %}}

Here's our page so far:

![Screenshot of page with purple background behind sections.](../../images/myrtle_sections.png)
