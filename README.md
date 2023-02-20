# To Do
- [x] Lijst met benodigdheden maken
- [x] Headers naar nederlands aanpassen
- [ ] Readme schrijven
- [x] Stap voor stap foto's toevoegen, e.g. in slider vorm
- [x] Ingredienten tussen haakjes grayed out
- [ ] Kleurenthema aanpassen
- [ ] Links toevoegen aan over mij
- [ ] Foto slider toevoegen aan over mij 
- [ ] Sportvoedingsblog 
- [ ] Sportvoedings recepten: voeg voedingswaarden toe
- [x] indentation ingredientenlijst
- [ ] voetnoten bij ingredientenlijst (en ook bereidingswijze) voor extra toelichting onderaan het recept. Of i-tje
- [x] tabel opmaak voor voedingswaarden. 
- [ ] voedingswaarden een plek geven in de opmaak. 
- [ ] https://lukasmurdock.com/recipe-site-with-jekyll/
- [ ] ander logo
- [ ] logo positie links bovenin 


# Slider/carousel pictures
Pure CSS carousel from https://jekyllcodex.org/without-plugin/slider/. 

### Usage
Add sliders to layout: 
```html
{% include carousel.html height="50" unit="%" number="1" %}

{% include carousel.html height="50" unit="%" number="2" %}
```
You can add `duration=10` if you want to auto rotate to the next image in 10 seconds. 


create YML array called `carousels` in the front matter of the post with this content: 
```yml
carousels:
  - images: 
    - image: /uploads/slider/image1.jpg
    - image: /uploads/slider/image2.jpg
    - image: /uploads/slider/image3.jpg
    - image: /uploads/slider/image4.jpg
  - images: 
    - image: /uploads/slider/image5.jpg
    - image: /uploads/slider/image6.jpg
    - image: /uploads/slider/image7.jpg
    - image: /uploads/slider/image8.jpg
```


# Jekyll template

This website is made with Jekyll, and inspired by the food/baking blog template made by [CloudCannon](http://cloudcannon.com/), see [here](https://github.com/CloudCannon/treat-jekyll-template) for more information.