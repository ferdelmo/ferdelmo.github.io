## Projects
-[**Polarization Mapping**](#polarization): a tool to edit images with polarized light. An investigation done with my end-of-degree project supervisor, Adolfo Muñoz, presented at the Spanish Conference on Computer Graphics 2019 (CEIG2019).

-[**Windmill Engine**](#windmill): a personal project to implement a game engine from scratch using **C++** and **Vulkan**.

-[**Nehan**](#nehan): a game develop as my master's final project.

-[**Chess Thing**](#chess-thing): a game for the _2-Buttons Game Jam 2019_ made with Unity.

### Contact
**Mail:** ferdelmo1996@gmail.com

**Tlf.:** +34 685 272 972

## <a name="polarization"></a>Polarization Mapping
This is a project derived from my end-of-degree project in the Universidad de Zaragoza under the supervision of Adolfo Muñoz. Our work ended up in an investigation paper called **Polarization Mapping**, which was presented at the Spanish Congress of Computer Graphics(CEIG2019). The paper was selected as **best paper of the Spanish Conference on Computer Graphics 2019 (CEIG2019)** and was published through Computers & Graphics.

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
        <figcaption>Image edited with our brush-based tool</figcaption>
    </div>
</div>

In these examples, we are able to minimize or maximize the reflections on different surfaces at the same time independently of their direction. This is only attainable with our software and cannot be captured with a standard camera plus a polarizer.

## <a name="windmill"></a>Windmill Engine
This is my personal project of doing a videogame engine from scratch using Vulkan as graphics API. During it, I learned the basics of graphics API and I build a basic engine able to render 3d meshes with shadows and basic shading, using technics like normal mapping or shadow mapping. On top of that, I build some basic game engine architecture, using gameobject-component architecture. Also, basic collision detection was added with sphere and box colliders.

[Repository](https://github.com/ferdelmo/WindmillEngine)

## <a name="nehan"></a> Nehan ##
This is my master's degree final project that was developed together with a team of students from different areas, and it was built with Unreal Engine 4. During this project, it was my first chance to work in a multidisciplinary team, working with people from art, marketing, other programmers, ... The game is a third-person platformer, in which you have different abilities to control time
I had the opportunity to work on multiple features of the game, highlighting the custom movement system of the player character, building the path finder and path following algorithms of different enemies, the camera system, including the third-person camera and the camera transition system to build cinematics, and the different abilities from the character, that can slow time and reverse it.

[Trailer of the game](https://github.com/ferdelmo/WindmillEngine)
The game was presented to the Playstation Talent program.

## <a name="chess-thing"></a>Chess Thing

**Chess Thing** is a game made for the _2-Buttons Game Jam 2019_ which has the restriction that the game needs to be played and used with only 2 buttons (obviously). In the game, you control a pawn in an infinity chess board who had to advance avoiding the other pieces that will attack you. You have a limited time to do a move, which can be: stay still, advance one square, or advance two. With this limited movement, you have to advance all the squares that you can without being captured

One interesting thing built, taking into account the limited time of development (4 days) is the AI, which has three different difficulties, limiting the number of moves the AI can do, controlling how many of the positions that the player can go will be a threat, etc. 

The game can be played [here](https://ferdelmo.itch.io/chess-thing)

[Source Code](https://github.com/ferdelmo/ChessThing) (It's a game jam, so expect any kind of hacks and ugly solutions there)
