# Aerthas Unity Shaders
 Bunch of the shaders I make for Unity

## Arc System Works Shader - DISCLAIMER BELOW
## [If you are unfamiliar with GitHub, click here to download](https://github.com/Aerthas/Aerthas-Unity-Shaders/releases)
![Example of a render using the shader!](https://i.imgur.com/eRlrYKg.png)<br/>
(Yes this is a render using my shader)<br/>
![Example of a render using the shader!](https://i.imgur.com/zRXvGlV.jpg)<br/><br/>
Emulates the look of the FABULOUS Arc System Works games.<br/><br/>
Confirmed games this shader will work with:
* Dragon Ball: FighterZ
* GUILTY GEAR Xrd REV 2
* GUILTY GEAR Xrd -SIGN-
* Granblue Fantasy Versus

Unconfirmed games that there is a 99.999% chance it will work with:
* Every other Arc System Works game that I just don't have
## DISCLAIMER:
So this shader is made with ZERO teachings, and everything I know about shaders is self taught over the last year and half. I know some colors might be off, such as the highlight fresnel color, but I am actively trying to figure out how the game does it. If you have ANY information about how a specific thing should be differently to make it look better please do not hesitate to [join my discord specifically for this shader.](https://discord.gg/EkCSZg8)<br/><br/>
Secondary note: Yes, if you are animating something (or using VRChat), the colors will look right under normal light but might not look right if you are trying to do something such as having a point light in your hand to emulate a kamehameha. Arc System Games do not actually light in "real time" per se, but every single option of the shader is MANUALLY edited frame by frame by the art team as they make animations. If you want something to look PERFECT during an animation, you need to put in just as much work as the original art team did. I'll keep trying to make it easy to work with, but there MUST be a lot of variables.

## [Comic Book Shader](https://github.com/Aerthas/Aerthas-Unity-Shaders/blob/master/Misc/Comic%20Book%20Dot%20Shadows.shader)
![](https://i.imgur.com/krJmn8f.png)<br/><br/>
[See it in motion!](https://i.imgur.com/UnYRWuZ.mp4)<br/><br/>
Give yourself the style of a comic book. Dot size and shadow intensity completely customizable. [This one DOES require this Comic Book Dot.tga file](https://github.com/Aerthas/Aerthas-Unity-Shaders/blob/master/Misc/Comic%20Dot.tga)<br/><br/>
*Shader will utilize the world lighting if there is a world light, or will switch to its own internal shading automatically if there isn't one.*

## [Runescape Shader](https://github.com/Aerthas/Aerthas-Unity-Shaders/blob/master/Misc/Runescape.shader)
![](https://i.imgur.com/WussxtK.png)<br/><br/>
[See it in motion!](https://i.imgur.com/f33WrHN.mp4)<br/><br/>
Nice dinky shader to emulate the look of Runescape. Dithered shadows to make it look closer to the game, and the verticies will round the location to the nearest world position to give it that jittering look.<br/><br/>
*Shader will utilize the world lighting if there is a world light, or will switch to its own internal shading automatically if there isn't one.*
