## Projects
-[**Polarization Mapping**](#polarization): a tool to edit images with polarized light. An investigation done with my end-of-degree project suppervisor, Adolfo Muñoz, presented in the Spanish Conference on Computer Graphics 2019 (CEIG2019).

-[**Windmill Engine**](#windmill): a personal project to implement a game engine from scratch using **C++** and **Vulkan**.

-[**Nehan**](#nehan): a game develop as my master final project (still in progress). Working together with a team of students of different areas, programmers, designers, artists, producers and marketing people.

-[**Chess Thing**](#chess-thing): a game for the _2-Buttons Game Jam 2019_ made with Unity.

-[**Duality**](#duality): my first videogame in unity done while I was on my second degree year

### Contact
**Mail:** ferdelmo1996@gmail.com

**Tlf.:** +34 685 272 972

## <a name="polarization"></a>Polarization Mapping
This is a project derived from my end-of-degree project in the Universidad de Zaragoza under the suppervision of Adolfo Muñoz. Our work ended up in an invetigation paper called **Polarization Mapping**, which was presented in the Spanish Congress of Computer Graphics(CEIG2019). The paper was selected as **best paper of the Spanish Conference on Computer Graphics 2019 (CEIG2019)** and was published through Computers & Graphics.

Abstract: Photographers use the hardware of the camera (aperture, exposure time...), lens and filters as tools for artistic expressivity. This expressivity has often been enhanced by software, such as high dynamic range images have been edited in post-process with software tone mappers. In this paper, we propose a similar approach with polarization filters: we design a capture process that enables us to acquire a Stokes image (that encodes all the possible light polarization states) with a single camera, and we then offer a set of software tools that can apply any common polarization filter as a software post-process, delaying the choice of the adequate filter and enabling filters that can be mathematically modeled but are not available as hardware. Then, we devise and provide new algorithms that automatically select the optimal filter for specific goals, such as maximizing (or minimizing) brightness, contrast or saturation. We later show how such optimization filters can not only be applied to the whole image, but can also be at per-pixel level, obtaining new interesting effects. Such optimization can work at real time rates, fact that is illustrated with a brush based user editing interactive tool. The different types of filters are tested in a wide range of results.

[Project page](http://giga.cps.unizar.es/~amunoz/projects/CG2019_polarization/)

[DOI](https://doi.org/10.1016/j.cag.2019.06.011)

A small sample of the results obtainable with our application can be seen below.
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

## <a name="windmill"></a>Windmill Engine
This is my personal project of doing a videogame engine from scratch using vulkan as graphics API. It is still in its first steps, and currently working on the render engine with vulkan. Basic features like render meshes, lighting without shadows, and the separation between the main loop and the render thread are implemented.

[Repository](https://github.com/ferdelmo/WindmillEngine)

## <a name="nehan"></a> Nehan ##
This is my master final project that is being developed together with a team of students from different areas. We are using Unreal Engine 4 as our main development tool. For now we can't show anything of the game until we pass some university milestones.

## <a name="chess-thing"></a>Chess Thing

**Chess Thing** is a game made for the _2-Buttons Game Jam 2019_ which has the restriction that the game need to be played and used with only 2 buttons (obiusly). In the game you control a pawn in an infinity chess table who had to advanced avoiding the other pieces that will attack you. You have a limited time to do a move, that can be: stay still, advance one square or advance two. With this limited movement you have to advance all the square that you can. 

One interesting thing done, taking into account the limited time of development (4 days) is the AI, which have three different difficulties, limiting the number of moves the AI can done, controling how many of the positions the player can go will threat, etc. 

The game can be played [here](https://ferdelmo.itch.io/chess-thing)

[Source Code](https://github.com/ferdelmo/ChessThing) (It's a game jam, so expect any kind of hacks there)

## <a name="duality"></a>Duality

This was my first videogame project as an undergraduate. Is a small android game, inspired by The Impossible Game and Geometry Dash that basically put you in control of two squares instead of one, raising the difficulty. It was my first experience with Unity, which I have been using since 2015/2016 to do some other personal projects that ends up unfinished, a couple of game jams and also in my internship in Padaone Games.

The game is published in Google Play ([link](https://play.google.com/store/apps/details?id=com.Delmogames.Duality)).
