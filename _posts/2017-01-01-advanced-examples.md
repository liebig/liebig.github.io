---
title: Advanced examples
layout: post
date: 2017-01-01
categories:
  - deploy
published: true
mathjax: true
excerpt: >-
  ![Swiss
  Alps](https://user-images.githubusercontent.com/4943215/55412536-edbba180-5567-11e9-9c70-6d33bca3f8ed.jpg)


  ## MathJax


  You can enable MathJax by setting `mathjax: true` on a page or globally in the
  `_config.yml`. Some examples:


  [Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the
  complex exponential function to the trigonometric functions.


  $$ e^{i\\theta}=\\cos(\\theta)+i\\sin(\\theta) $$
---
![Swiss Alps](https://user-images.githubusercontent.com/4943215/55412536-edbba180-5567-11e9-9c70-6d33bca3f8ed.jpg)

## MathJax

You can enable MathJax by setting `mathjax: true` on a page or globally in the `_config.yml`. Some examples:

[Euler's formula](https://en.wikipedia.org/wiki/Euler%27s_formula) relates the complex exponential function to the trigonometric functions.

$$ e^{i\\theta}=\\cos(\\theta)+i\\sin(\\theta) $$

New Test

$$ c = \\pm\\sqrt{a^2 + b^2} $$

NEW NEW

Find $${ x, y, z } \\in \\N$$ where: $$x^2 + y^2 = z^2$$

$$\\color{MediumPurple}{This~is~purple} ~and~that~too!? ~\\color{MediumSeaGreen}{But~not~that!}$$

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict\* args, void\* vAdmin, String\* txid, struct Allocator\* requestAlloc) { struct Admin\* admin = Identity\_check((struct Admin\*) vAdmin); int64\_t enabled = admin->asyncEnabled; Dict d = Dict\_CONST(String\_CONST("asyncEnabled"), Int\_OBJ(enabled), NULL); Admin\_sendMessage(&d, txid, admin); }

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

{% gist 5555251 %}

## Images

Upload an image to the _assets_ folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Big tables

| sadsadsad | asdsad | asd | asdsad | asdsadsad | asdsadsad | asdsadsad | asdsadsad | asdsadsad | asdsadsad |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 21  | 213 | Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 213 | 999999999 | 999999999 | 213 | 999999999 | 999999999 |
| Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 2121 | 21  | Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 213 | 999999999 | 999999999 | 213 | 999999999 | 999999999 |
| Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 12  | 213 | Cookie oat cake cheesecake topping cupcake croissant. Candy danish dessert gummies jelly-o dessert pastry. Dragée chupa chups jelly beans sweet sesame snaps. Lemon drops pastry halvah chocolate apple pie cookie donut. Icing brownie jujubes toffee gingerbread pudding gummi bears. Apple pie caramels chupa chups dragée candy canes bonbon cookie soufflé. Donut tart lollipop toffee brownie dessert pastry. Brownie apple pie jelly oat cake cheesecake powder croissant. Cheesecake gummies jelly gummies croissant. Croissant sweet marshmallow chupa chups halvah sesame snaps candy carrot cake. Pudding cupcake candy canes sweet roll lemon drops jujubes danish cookie. Gummi bears lemon drops apple pie gummies dessert bonbon apple pie wafer tiramisu. Marshmallow candy canes dessert pudding candy jujubes jelly. Sweet pastry jujubes jelly-o oat cake pudding. | 213 | 999999999 | 999999999 | 213 | 999999999 | 999999999 |

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="[https://www.youtube.com/embed/\_C0A5zX-iqM](https://www.youtube.com/embed/_C0A5zX-iqM)" %}