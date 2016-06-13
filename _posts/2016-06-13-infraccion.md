---
layout: post
title:  "Infracción"
date:   2015
excerpt: "Revisa si un oficial te puede infraccionar"
project: true
tag:
- jekyll 
- moon
- blog
- about
- theme
comments: true

---

    
<center><b>Infracción</b>.</center>
     
n/Fracción es una app que te permite consultar, evaluar y conocer el proceso de infracción según la información oficial brindada por la Secretaría de Seguridad Pública de la Ciudad de México.

En la Ciudad de México sólo los agentes de tránsito habilitados con un handheld pueden levantar infracciones.

* Si un agente de tránsito te detiene, puedes consultar su nombre o número de placa y saber si tiene la facultad para levantar una infracción.

* Si cometiste una infracción evalúa el proceso que el agente siguió en base al artículo 39 del Reglamento de Tránsito Metropolitano.

* Consulta el monto total y las sanciones que debes pagar por la infracción que cometiste.

Infracción es una aplicación de CityDevs.

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
	http://a1.mzstatic.com/us/r30/Purple1/v4/73/0e/53/730e53f6-381e-2100-21c1-3e6189f9d1de/screen322x572.jpeg
	http://a4.mzstatic.com/us/r30/Purple7/v4/b4/7c/eb/b47ceb9b-9bbb-f799-11de-43e353458c70/screen322x572.jpeg
	http://a1.mzstatic.com/us/r30/Purple5/v4/d5/02/14/d502146b-c136-f12c-1c59-380ca1a71a1d/screen322x572.jpeg
{% endcapture %}
{% include gallery images=images caption="Screenshots of Moon Theme" cols=3 %}

---

  
      
Download  [Infracción](https://itunes.apple.com/ai/app/infraccion/id1029765142?mt=8) from AppStore.      


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
