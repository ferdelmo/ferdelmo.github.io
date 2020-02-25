## Polarization Mapping
This is a project derived from my TFG in the Universidad de Zaragoza under the suppervision of Adolfo Muñoz. Our work ends up in an invetigation paper called **Polarization Mapping**, wich was presented in the Spanish Congress of Computer Graphics(CEIG2019). The paper was selected as **best paper of the Spanish Conference on Computer Graphics 2019 (CEIG2019)** and was **published through the Computers & Graphics** track of the Spanish Conference on Computer Graphics 2019 (CEIG2019).

Our work present a method to edit image with polarized light, together with a capture method. The main idea of the work is to modify the polarization of an image as a post-process effect, simlarly to tone mapping with HDR. Our method allow different types of filters. First of all it allows to reproduce any polarizing filter existing in hardware and even create software filters that are hardly reproduce by hardware. We also present two kinds of filters to maximize (or minimize) different image parameters, luminance, saturation and contrast. These filters can be applied with two approach, global filters, that basically select the best linear polarizer to maximize that parameter. And local filters, that apply a different linear polarizer per pixel to maximize the parameter. The local approach generate results that are imposible to reproduce by hardware and allows intersting effects, like minimizing the reflects on any surface in the image.

[Project page](http://giga.cps.unizar.es/~amunoz/projects/CG2019_polarization/)

[DOI](https://doi.org/10.1016/j.cag.2019.06.011)

<div style="-webkit-column-count: 3; -moz-column-count: 3; column-count: 3; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div class="column">
        <h3>Original image</h3>
        <img src="images/cielo/cubo.jpg">
    </div>
    <div class="column">
        <h3>Luminance maximization per pixel</h3>
        <img src="images/cielo/LumLMax.jpg">
    </div>
    <div class="column">
        <h3>Luminance maximization per pixel</h3>
        <img src="images/cielo/LumLMin.jpg">
    </div>
</div>

## Duality

Casual android game published in the play store [link](https://play.google.com/store/apps/details?id=com.Delmogames.Duality) inspired by The Imposible Game and Geometry Dash. This was my first project as an under-graduated and my first project with Unity.

## Chess Thing

**Chess Thing** is a game made for the _2-Buttons Game Jam 2019_ wich has the restriction that the game need to be played and used with only 2 buttons (obiusly). In the game you control a pawn in an infinity chess table who had to advanced avoiding the other pieces that will attack you. It's time turn based  where you have three options, stay in the same position or advance one or two tiles.

The game can be played [here](https://ferdelmo.itch.io/chess-thing)

[Source Code](https://github.com/ferdelmo/ChessThing) (It's a game jam, so expect any kind of hacks there)


## Windmill Engine
This is my personal project of doing a videogame engine from scratch using vulkan as graphics API. For now only small steps on the render engine are done. 

TODO: put images with renders from point lights and directional lights, normal mapping etc.

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ferdelmo/ferdelmo.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
