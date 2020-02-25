## Polarization Mapping
This is a project derived from my TFG in the Universidad de Zaragoza under the suppervision of Adolfo Muñoz. Our work ends up in an invetigation paper called **Polarization Mapping**, wich was presented in the Spanish Congress of Computer Graphics(CEIG2019). The paper was selected as **best paper of the Spanish Conference on Computer Graphics 2019 (CEIG2019)** and was **published through the Computers & Graphics** track of the Spanish Conference on Computer Graphics 2019 (CEIG2019).

Our work present a method to edit image with polarized light, together with a capture method. The main idea of the work is to modify the polarization of an image as a post-process effect, simlarly to tone mapping with HDR. Our method allow different types of filters. First of all it allows to reproduce any polarizing filter existing in hardware and even create software filters that are hardly reproduce by hardware. We also present two kinds of filters to maximize (or minimize) different image parameters, luminance, saturation and contrast. These filters can be applied with two approach, global filters, that basically select the best linear polarizer to maximize that parameter. And local filters, that apply a different linear polarizer per pixel to maximize the parameter. The local approach generate results that are imposible to reproduce by hardware and allows intersting effects, like minimizing the reflects on any surface in the image.

[Project page](http://giga.cps.unizar.es/~amunoz/projects/CG2019_polarization/)

[DOI](https://doi.org/10.1016/j.cag.2019.06.011)

<div style="-webkit-column-count: 3; -moz-column-count: 3; column-count: 3; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div class="column">
        <img src="images/cielo/cubo.jpg">
        <figcaption>Original image</figcaption>
    </div>
    <div class="column">
        <img src="images/cielo/LumLMax.jpg">
        <figcaption>Luminance maximization per pixel</figcaption>
    </div>
    <div class="column">
        <img src="images/cielo/LumLMin.jpg">
        <figcaption>Luminance minimization per pixel</figcaption>
    </div>
</div>

<div style="-webkit-column-count: 4; -moz-column-count: 4; column-count: 4; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
    <div class="column">
        <img src="images/coche1/I.jpg">
        <figcaption>Original image</figcaption>
    </div>
    <div class="column">
        <img src="images/coche1/LumLMax.jpg">
        <figcaption>Luminance maximization per pixel</figcaption>
    </div>
    <div class="column">
        <img src="images/coche1/LumLMin.jpg">
        <figcaption>Luminance minimization per pixel</figcaption>
    </div>
    <div class="column">
        <img src="images/coche1/minLateralMaxFront.jpg">
        <figcaption>Image edited with our brush based tool</figcaption>
    </div>
</div>

## Windmill Engine
This is my personal project of doing a videogame engine from scratch using vulkan as graphics API. For now only small steps on the render engine are done. 

TODO: put images with renders from point lights and directional lights, normal mapping etc.

## Chess Thing

**Chess Thing** is a game made for the _2-Buttons Game Jam 2019_ wich has the restriction that the game need to be played and used with only 2 buttons (obiusly). In the game you control a pawn in an infinity chess table who had to advanced avoiding the other pieces that will attack you. It's time turn based  where you have three options, stay in the same position or advance one or two tiles.

The game can be played [here](https://ferdelmo.itch.io/chess-thing)

[Source Code](https://github.com/ferdelmo/ChessThing) (It's a game jam, so expect any kind of hacks there)

## Duality

Casual android game published in the play store [link](https://play.google.com/store/apps/details?id=com.Delmogames.Duality) inspired by The Imposible Game and Geometry Dash. This was my first project as an under-graduated and my first project with Unity.



## Contact
**Mail:** ferdelmo1996@gmail.com

**Tlf.:** +34 685 272 972
