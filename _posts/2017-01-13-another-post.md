---
layout: post
title:  "Tristique senectus"
date:   2017-01-13 11:00:00 -0500
categories: jekyll update
bubblegum: "i am an example"
my_variable: footer-b.html
---

Pellentesque habitant morbi [tristique senectus][jekyll-docs] et netus et malesuada fames ac turpis egestas. In id finibus odio, a porta nisi.

<!--more-->

{{page.bubblegum}}

{{site.imgpath}}

[Pellentesque][test-post-link] habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aliquam finibus a risus ut venenatis. Donec elementum libero ex, vitae fermentum justo bibendum a. Vestibulum sit amet dolor id nunc fermentum condimentum id id odio. Ut quis imperdiet nisl. Pellentesque a bibendum velit. Aenean convallis suscipit commodo.

![i love kittens][kitten-pic]

## Headline 2

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce lobortis lacus sit amet ante aliquet rutrum. Sed aliquet mi eu felis gravida, ut faucibus magna bibendum. Vivamus et tellus rutrum, lacinia risus ut, placerat mauris.

Donec sodales diam vitae lacus facilisis bibendum. Pellentesque quis felis suscipit mi commodo sodales in quis dolor. Nunc massa eros, condimentum eu magna eget, semper venenatis lacus. Ut nec vehicula urna. Phasellus ultricies mi id odio eleifend auctor. Nullam fringilla elit sit amet lorem ultrices, in pellentesque eros dignissim.

### Headline 3

Fusce non lectus eget lectus porttitor gravida. Ut eget mauris condimentum, pulvinar libero id, accumsan velit. Nulla pellentesque in neque eget eleifend.

Aliquam turpis leo, semper ac ornare vestibulum, vulputate in nisl. Donec dignissim augue at leo consequat pellentesque. Cras laoreet gravida arcu vel gravida.

### Headline 3

Vestibulum malesuada tempus gravida. Quisque nec turpis vel enim euismod viverra in eu nisi. Fusce dignissim bibendum dui, sed blandit lacus imperdiet non. Vivamus quis ligula tortor. Praesent in pulvinar sapien. Nullam ac est vehicula, dignissim ante quis, tincidunt leo.

#### Headline 4

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce lobortis lacus sit amet ante aliquet rutrum. Sed aliquet mi eu felis gravida, ut faucibus magna bibendum.

#### Headline 4

Vivamus et tellus rutrum, lacinia risus ut, placerat mauris. Donec sodales diam vitae lacus facilisis bibendum. Pellentesque quis felis suscipit mi commodo sodales in quis dolor.

#### Headline 4

Nunc massa eros, condimentum eu magna eget, semper venenatis lacus. Ut nec vehicula urna. Phasellus ultricies mi id odio eleifend auctor.

##### Headline 5

Nullam [fringilla elit][link] sit amet lorem ultrices, in pellentesque eros dignissim.

{% include footer.html %}

bam

{% include {{page.my_variable}} %}


[link]: {% post_url 2017-01-10-welcome-to-jekyll %}
[test-post-link]: http://www.google.com
[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/


[kitten-pic]: {{site.imgpath}}kitten.jpg
