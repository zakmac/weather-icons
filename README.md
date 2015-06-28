## Weather Icons
*Version 2.0.0*

### A free, open source icon-font of Weather icons

Weather Icons is a font of 189 weather themed icons, ready to be dropped right into [Bootstrap](http://www.getbootstrap.com), [Foundation](http://foundation.zurb.com) or any other project. 

Inspired by [Font Awesome](http://fontawesome.io/), they work in essentially the same way. They are infinitley scalable and any CSS that can be applied to text can be applied to them. All you need to do to insert an icon is add the base class and the specific icon class to an "i" element:

```html
<i class="wi wi-day-lightning"></i>
```

At this time, there are no other effects/mixins to do advanced icon manipulation yet.

![Icon Preview](http://wes.io/WeM5/preview.png)

**[View demo and full icon reference](http://erikflowers.github.io/weather-icons/)**

### Getting Started
Getting started is easy. First, put the fonts in the directory ABOVE your css directory. By default, the fonts are referencing a ../fonts/ folder that is on the same level as /css. This can be changed via the `$wi-font-path` variable in `scss/_variables.scss`

Include in your main .less file `scss/weather-icons.scss` and that is all you need to do. 

It is best to clone [the GitHub repo](http://www.github.com/erikflowers/weather-icons) if you want to keep up to date. Please report any issues or requests to the repository here

### CSS Only Method
The pre-compiled CSS sources are compiled using the Less source. To get started using the CSS files, simply copy them to `css/` in your site's root folder and then include the following line of code in your HTML file's `<head>`:
```html
<link rel="stylesheet" type="text/css" href="css/weather-icons.min.css">
```

### Collaboration
If you feel so inclined to add icon ideas, icon art, or other fixes/changes to how the package works, feel free to help! I'd also love it if someone wanted to make this a component as well for bower, npm, component, etc. No idea how to do that myself (yet).

### Contact
Weather Icons is maintained by
* Erik Flowers 
  * [@Erik_UX](http://www.twitter.com/Erik_UX)
  * [helloerik.com](http://www.helloerik.com)
* Zak MacDonald
  * [github.com/zakmac](http://www.zakmac.com)
  * [zakmac.com](http://www.zakmac.com)

### License and credit
* The icon designs are originally by [Lukas Bischoff](http://www.twitter.com/artill)
* Icon art for v1.1 forward, HTML, original Less, and CSS are by [Erik Flowers](http://www.helloerik.com)
* Less refactor and SASS are by [Zak MacDonald](http://github.com/zakmac)

None of this would be  possible without [Bootstrap](http://www.getbootstrap.com), [Font Awesome](http://fontawesome.io/) and [Lukas Bischoff](http://www.twitter.com/artill). I just put it all together into a neat package. Cheatsheet provided by Michael Woywod.

Weather Icons licensed under [SIL OFL 1.1](http://scripts.sil.org/OFL) &mdash; Code licensed under [MIT License](http://opensource.org/licenses/mit-license.html)  &mdash; Documentation licensed under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0)
