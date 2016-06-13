---
layout: post
title:  "Ligue Político"
date:   2015
excerpt: "Ligue Político"
project: true
tag:
- jekyll 
- moon
- blog
- about
- theme
comments: true
---

    
<center><b>Ligue Político</b>.</center>
     
Conoce a los candidatos de tu ciudad, provincia y país, y descubre si les importas.

Con Ligue Político podrás conocer quiénes son tus candidatos a puestos de elección popular, de acuerdo a tu ubicación geográfica, para exigirles que se comprometan con la transparencia y la rendición de cuentas. 

Ligue Político es una iniciativa ciudadana, abierta, colaborativa y regional, promovida y apoyada por: Factual, Hivos, Chequeado, Yo Quiero Saber, y Fáctico.

Si un candidato te atrae, desliza a la derecha. ¡Pero cuidado! Si no ha presentado su declaración patrimonial o jurada, ¡exígela!

<iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Moon&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
## Installation
* Fork the [Moon repo](https://github.com/TaylanTatli/Moon/fork)
* Edit `_config.yml` file.
* Remove sample posts from `_posts` folder and add yours.
* Edit `index.md` file in `about` folder.
* Change repo name to `YourUserName.github.io`    
     
That's all.

## Preview

{% capture images %}
	http://a2.mzstatic.com/us/r30/Purple3/v4/d0/69/77/d06977bc-7fca-54ad-5687-66bd40f79b96/screen322x572.jpeg
	http://a4.mzstatic.com/us/r30/Purple3/v4/1d/16/ec/1d16ecbf-aef5-2ad5-dcc1-85db65710ad7/screen322x572.jpeg
	http://a1.mzstatic.com/us/r30/Purple3/v4/c7/0e/b9/c70eb912-6547-2a56-ea70-801dbdfa856b/screen322x572.jpeg
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=3 %}

---

  
      
Download  [Ligue Político](https://itunes.apple.com/mx/app/ligue-politico/id1036339757?mt=8) from AppStore.      


---

### Navigation Links

To set what links appear in the top navigation edit `_data/navigation.yml`. Use the following format to set the URL and title for as many links as you'd like. *External links will open in a new window.*

{% highlight yaml %}
- title: Home
  url: /

- title: Blog
  url: /blog/

- title: Projects
  url: /projects/

- title: About
  url: /about/

- title: Moon
  url: http://taylantatli.me/Moon
{% endhighlight %}

---

## Layouts and Content

Moon Theme use [Jekyll Compress](https://github.com/penibelst/jekyll-compress-html) to compress html output. But it can cause errors if you use "linenos" (line numbers). I suggest don't use line numbers for codes, because it won't look good with this theme, also i didn't give a proper style for them. If you insist to use line numbers, just remove `layout: compress` string from layouts. It will disable compressing.

### Feature Image

You can set feature image per post. Just add `feature: some link` to your post's front matter.

```
feature: /assets/img/some-image.png
or
feaure: http://example.com/some-image.png
```    
 This also will be used for twitter card:

![Moon Twitter Card](https://cloud.githubusercontent.com/assets/754514/14509719/61c5751c-01d6-11e6-8c29-ce8ccad149bf.png)

### Comments
To show disqus comments for your post add `comments: true` to your post's front matter.

---

## Questions?

Found a bug or aren't quite sure how something works? By all means [file a GitHub Issue](https://github.com/TaylanTatli/Moon/issues/new). And if you make something cool with this theme feel free to let me know.

---

## License

This theme is free and open source software, distributed under the MIT License. So feel free to use this Jekyll theme on your site without linking back to me or including a disclaimer.
