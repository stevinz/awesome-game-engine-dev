<h1 align="center">
    <img width="1100" src="aged-title.png" alt="Awesome Game Engine Dev Logo"/>
</h1>

# Awesome Game Engine Development [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome assets, libraries, and tools for Game Engine Development. Specifically, this list is geared toward development of high-level, fully featured game engines (e.g., [Godot](https://godotengine.org) / [Unity](https://unity.com)). This would include things typically not found in low-level game engines, game frameworks, or graphics libraries (e.g., [MonoGame](https://www.monogame.net) / [SDL](https://www.libsdl.org)). Most importantly of which would be a visual scene editor, but also capabilities such as scipting support, physics integration, special effects, etc. 

This list currently favors (but is not limited to) programming the core engine in the following languages: C, C++, C#, Haxe, or Javascript.


<br>


### NOTE: This list is under development, it is still in draft state. Contributions will be welcome when the draft is complete, but are currently not accepted.


<br>


### License Legend
- Open Source Software
    - :star: - [Public Domain License](https://en.wikipedia.org/wiki/Public-domain-equivalent_license) ([CC0](https://creativecommons.org/publicdomain/zero/1.0/), [BOLA](https://blitiri.com.ar/p/bola/), [WTFPL](https://en.wikipedia.org/wiki/WTFPL), [Unlicense](https://en.wikipedia.org/wiki/Unlicense), etc.)
    - :tada: - [Permissive License](https://en.wikipedia.org/wiki/Permissive_software_license) ([MIT](https://en.wikipedia.org/wiki/MIT_License), [BSD](https://en.wikipedia.org/wiki/BSD_licenses), [ZLIB / LIBPNG](https://en.wikipedia.org/wiki/Zlib_License), [ISC](https://en.wikipedia.org/wiki/ISC_license), [Apache](https://en.wikipedia.org/wiki/Apache_License), [Boost](https://en.wikipedia.org/wiki/Boost_(C%2B%2B_libraries)#License) etc.)
    - :lock: - [Copyleft License](https://en.wikipedia.org/wiki/Copyleft) ([CC](https://en.wikipedia.org/wiki/Creative_Commons_license), [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) / [LGPL](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License), [MPL](https://en.wikipedia.org/wiki/Mozilla_Public_License), etc.)
- Asset / Service / Tool
    - :free: - Free
    - :moneybag: - Paid
    - :money_with_wings: - Partially Free
- Other
    - :books: - Article, Blog Post, or List
    - :earth_americas: - Website
- :octocat: - Link to Repo, click on it to see the source code!
- :fire: - Hot! Amazing, must-see resource!


<br><br>


## Index
- [Game Engines](#Game-Engines)
    - [Popular](#Popular)
    - [AAA](#AAA)
    - [Commercial](#Commercial)
    - [Specialty](#Specialty)
- [Learning](#Learning)
    - [Computer Graphics](#Computer-Graphics)
        - <sub><sup>[General](#Graphics-General) | [DirectX](#Graphics-DirectX) | [Metal](#Graphics-Metal) | [OpenGL](#Graphics-OpenGL) | [Vulkan](#Graphics-Vulkan) | [WebGL](#Graphics-WebGL) | [WebGPU](#Graphics-WebGPU)</sup></sub>
    - [Engine Development](#Engine-Development)
    - [Game Development](#Game-Development)
        - <sub><sup>[Additional Collections](#Game-Development-Additional-Collections) | [Developer Portals](#Game-Development-Developer-Portals)</sup></sub>
    - [Programming](#Programming)
- [Libraries](#Libraries)
    - [C](#C)
        - <sub><sup>[Audio](#C-Audio) | [ECS](#C-Entity-Component-System) | [File Loading](#C-File-Loading) | [Fonts](#C-Fonts) | [Game Engine](#C-Game-Engine) | [Game Framework](#C-Game-Framework) | [Geometry](#C-Geometry) | [Graphics](#C-Graphics) | [Gui](#C-Gui) | [Input](#C-Input) | [Lighting](#C-Lighting) | [Math](#C-Math) | [Physics](#C-Physics) | [Scripting](#C-Scripting) | [Utility](#C-Utility) | [Vector Graphics](#C-Vector-Graphics) | [Windowing](#C-Windowing)</sup></sub>
    - [C++](#Cpp)
    - [C#](#CSharp)
    - [Haxe](#Haxe)
    - [Java](#Java)
    - [Javascript](#Javascript)
    - [Python](#Python)
    - [Rust](#Rust)
- [Specialty Topics](#Specialty-Topics)
    - [AI / Pathfinding](#Topic-AI)
    - [Animation](#Topic-Animation)
    - [Fluid / Smoke](#Topic-Fluid)
    - [Geometry](#Geometry)
    - [Lighting / Shadows](#Lighting)
    - [Particles](#Particles)
    - [Physics](#Physics)
    - [Scripting](#Scripting)
    - [Shaders](#Topic-Shaders)
    - [Tiling](#Tiling)
- [Tools / Software](#Tools)
    - [Animation](#Tools-Animation)
    - [Color](#Tools-Color)
    - [Drawing](#Tools-Drawing)
    - [Game Dev](#Tools-Game-Dev)
    - [Image Editors](#Tools-Image-Editors)
    - [Materials](#Tools-Materials)
    - [Modeling](#Tools-Modeling)
    - [Particles](#Tools-Particles)
    - [Pixel Art](#Tools-Pixel-Art)
    - [Sound](#Tools-Sound)
    - [Textures](#Tools-Textures)


<br>


## Game Engines
_Production game engines to tinker with, explore, learn and inspire_

- ### Popular
    - :tada: [Godot](https://godotengine.org) [:octocat:](https://github.com/godotengine/godot#readme) : :fire: Feature-packed, open source engine. Excellent! [[Awesome Godot](https://github.com/godotengine/awesome-godot#readme)]
    - :money_with_wings: [Unity](https://unity.com) : Sets the bar for Game Engines. [[Awesome Unity](https://github.com/RyanNielson/awesome-unity)]
    - :money_with_wings: [Unreal Engine](https://www.unrealengine.com) : AAA game capable, photoreal visuals. [[Awesome UE4](https://github.com/insthync/awesome-ue4#readme)]
    - :books: [Wikipedia: List of Game Engines](https://en.wikipedia.org/wiki/List_of_game_engines) : Thorough list of game engines along with their platforms and licenses.

- ### AAA
    - :tada: [Amazon Lumberyard](https://aws.amazon.com/lumberyard/) [:octocat:](https://github.com/aws/lumberyard) : Free, open source AAA game engine deeply integrated with AWS and Twitch.
    - :moneybag: [C4 Engine](http://c4engine.com) : Modern console engine.
    - :money_with_wings: [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK/CRYENGINE) : Powerful real-time game development platform created by Crytek.
    - :free: [Evergine](https://evergine.com) : (previously known as Wave Engine) The graphics development engine for business and industry. Build high-quality 3D and 2D solutions and deploy to any platform. [[Projects/Samples](https://github.com/EvergineTeam/Samples)]
    - :money_with_wings: [Flax Engine](https://flaxengine.com) [:octocat:](https://github.com/FlaxEngine/FlaxEngine) : Modern 3D game engine written in C++ and C#. Stunning graphics, powerful scripts.
    - :moneybag: [FROSTBITE](https://www.ea.com/frostbite) : (by Electronic Arts) Cutting-Edge Games and Experiences.
    - :moneybag: [Gamebryo](http://www.gamebryo.com) : Complete toolset, flexible workflow, rapid prototyping.
    - :tada: [O3DE](https://docs.o3de.org) [:octocat:](https://github.com/o3de/o3de/) : (Successor to Amazon Lumberyard) Multi-platform AAA-capable 3D engine to build cinema-quality 3D worlds, and high-fidelity simulations.
    - :moneybag: [Snowdrop Engine](https://www.massive.se/project/snowdrop-engine/) : (by Massive Entertainment) Enabling relatively small teams to create ambitious AAA games.
    - :money_with_wings: [Unigine](https://unigine.com) : Real-time 3D engine. Photorealistic graphics, large virtual worlds, C++ and C# API.

- ### Commercial
    - :moneybag: [AppGameKit Studio](https://www.appgamekit.com/studio) : Easy, quick and powerful programming.
    - :money_with_wings: [Buildbox](https://www.buildbox.com) : Create 3D & 2D video games without coding.
    - :money_with_wings: [Construct](https://www.construct.net/) : Browser based drag and drop game builder. [[Awesome Construct](https://github.com/ConstructCommunity/awesome-construct#readme)]
    - :money_with_wings: [Felgo](https://felgo.com/games) : Build Cross-Platform 2D Games in Days. Based on the Qt framework.
    - :money_with_wings: [GameMaker Studio](https://www.yoyogames.com/en/gamemaker) : (by YoYo Games) 2D Game Development Environment with large following.
    - :money_with_wings: [GameSalad](https://gamesalad.com) : Sophisticated visual programming interface.
    - :money_with_wings: [MANU](https://manu.co) : Unique animation system helps you create games without coding.
    - :money_with_wings: [NeoAxis](https://www.neoaxis.com) [:octocat:](https://github.com/NeoAxis/NeoAxisEngine) : Versatile real-time platform for making 2D / 3D games and apps.
    - :money_with_wings: [PlayCanvas](https://playcanvas.com) [:octocat:](https://github.com/playcanvas/engine) (Repo for  runtime only) : Popular (Flappy Bird), fast and lightweight JavaScript game engine built on WebGL.
    - :money_with_wings: [ShiVa](https://shiva-engine.com) : 3D game and application development suite.
    - :money_with_wings: [Simulation Starter Kit](https://benmorris.itch.io/plugin-based-scene-editor) : Supports the creation of simple interactive 3D applications across a range of platforms and devices. [[Developer Website](http://fireflytech.org)]
    - :money_with_wings: [Stencyl](http://www.stencyl.com) [:octocat:](https://github.com/Stencyl/stencyl-engine) (Repo for  runtime only) : Quick and easy game making. Visual scripting similar to [Scratch](https://scratch.mit.edu).

- ### Specialty
    - :moneybag: [3dSen](https://geod.itch.io/3dnes) : Unique NES emulator that converts NES games into full 3D experiences and let you play them in realtime. [Developer Website](http://www.geodstudio.net)
    - :money_with_wings: [DopeFish](https://subpixel-studios.itch.io/dopefish) : Full GML Doom/Heretic map loading system for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :tada: [GB Studio](https://www.gbstudio.dev) [:octocat:](https://github.com/chrismaltby/gb-studio) : Retro adventure game creator for Game Boy available for Mac, Linux and Windows.
    - :moneybag: [Platforming Engine](https://robvansaaze.itch.io/platforming-engine) : Everything you need to create your very own platforming game for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :moneybag: [RPG Maker](https://www.rpgmakerweb.com) : Lets you create an original role-playing game without any specialized knowledge or training.


<br>


## Learning
_Info on topics necessary for designing and developing game engines_

- ### Computer Graphics
    - #### General Resources <a name="Graphics-General"></a>
        - :books: [Comparison of Modern Graphics APIs](https://alain.xyz/blog/comparison-of-modern-graphics-apis) : A review of modern graphics APIs and how they compare with older graphics APIs in their design and data structures.
        - :books: [GPU Gems](https://developer.nvidia.com/gpugems/gpugems/contributors) : Programming techniques, tips, and tricks for real-time graphics hosted by [NVIDIA](https://www.nvidia.com/).
        - :books: [GPU Gems 2](https://developer.nvidia.com/gpugems/gpugems2/copyright) : Programming techniques for high-performance graphics and general-purpose computation hosted by [NVIDIA](https://www.nvidia.com/).
        - :books: [GPU Gems 3](https://developer.nvidia.com/gpugems/gpugems3/contributors) : A collection of state-of-the-art GPU programming examples hosted by [NVIDIA](https://www.nvidia.com/).
        - :earth_americas: [Lighthouse3d.com](http://www.lighthouse3d.com/tutorials/) : Great collection of tutorials on OpenGL, GLSL and many other computer graphics topics.
        - :earth_americas: [Scratchapixel](https://www.scratchapixel.com) : Very in depth coverage of topics ranging from mathematics and physics for computer graphics, 3D rendering and many more advanced techniques.
    - #### Graphics API: DirectX <a name="Graphics-DirectX"></a>
        - :earth_americas: [DirectXTutorial.com](http://www.directxtutorial.com/default.aspx) : Older resource with lots of tutorials on DirectX versions 9 & 11.
    - #### Graphics API: Metal <a name="Graphics-Metal"></a>

    - #### Graphics API: OpenGL <a name="Graphics-OpenGL"></a>
        - :earth_americas: [Learn OpenGL](https://learnopengl.com) : :fire: Incredible resource! Teaches you everything you need to do modern graphics programming!
        - :earth_americas: [OpenGL Tutorial](https://www.opengl-tutorial.org) : Excellent collection of OpenGL tutorials with full source covering lots of topics.
    - #### Graphics API: Vulkan <a name="Graphics-Vulkan"></a>

    - #### Graphics API: WebGL <a name="Graphics-WebGL"></a>

    - #### Graphics API: WebGPU <a name="Graphics-WebGPU"></a>

    - #### Shaders <a name="Graphics-Shaders"></a>
        _see [Shaders](#Topic-Shaders)_

- ### Engine Development
    - :earth_americas: [3D Game Engine Programming](https://www.3dgep.com) : Helping you build your dream game engine.
    - :books: [How to become a game engine developer](https://www.haroldserrano.com/blog/how-to-become-a-game-engine-developer) : Short and simple starting point on Game Engine Development

- ### Game Development
    - #### Additional Collections <a name="Game-Development-Additional-Collections"></a>
        - :books: [Awesome Gamedev](https://github.com/Calinou/awesome-gamedev#readme) : A collection of free software and free culture resources for making amazing games.
        - :books: [Awesome Graphics Libraries](https://github.com/jslee02/awesome-graphics-libraries#readme) : Awesome curated list of 3D graphics libraries and resources.
        - :books: [Magictools](https://github.com/ellisonleao/magictools#readme) : A list of Game Development resources to make magic happen.

    - #### Developer Portals <a name="Game-Development-Developer-Portals"></a>
        - :earth_americas: [GameDev.net](https://www.gamedev.net) : Huge resource for game development with forums, tutorials, blogs, projects, portfolios, news, and more.
        - :earth_americas: [GameFromScratch.com](https://gamefromscratch.com) : Game development news, tutorials and so much more.
        - :earth_americas: [itch.io](https://itch.io) : Platform to host, showcase, promote, buy and sell games and game development resources.

- ### Programming
    - :books: [Games of Coding](https://github.com/michelpereira/awesome-games-of-coding#readme) : Awesome list of games that teach you a programming language.
    - :books: [Learn to Program](https://github.com/karlhorky/learn-to-program#readme) : Educational resources to learn to program.


<br>


## Libraries
_Language specific game engine development libraries / frameworks / code_

- ### C
    - #### - Language - <a name="C-Language"></a>
        - :earth_americas: [Learn C Programming](https://www.programiz.com/c-programming) : Excellent C tutorials that will guide you to learn C programming one step at a time.
    - #### - Language: Additional Collections - <a name="C-Language-Additional-Collections"></a>
        - :star: [Cute Headers](https://github.com/RandyGaul/cute_headers) : Collection of cross-platform one-file C/C++ libraries with no dependencies, primarily used for games
        - :star: [Pico Headers](https://github.com/empyreanx/pico_headers) : Single-header, cross-platform libraries for game development, written in C
        - :books: [Single File Libs](https://github.com/nothings/single_file_libs) : Amazing collection of single file C/C++ libraries
        - :star: [stb](https://github.com/nothings/stb) : :fire: The original and amazing stb single-file public domain libraries for C/C++
    - #### Audio <a name="C-Audio"></a>

    - #### Entity Component System <a name="C-Entity-Component-System"></a>

    - #### File Loading <a name="C-File-Loading"></a>

    - #### Fonts <a name="C-Fonts"></a>

    - #### Game Engine w/Editor <a name="C-Game-Engine"></a>

    - #### Game Framework <a name="C-Game-Framework"></a>
        - :tada: [SDL](https://libsdl.org) [:octocat:](https://github.com/libsdl-org/SDL) : :fire: Classic, cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D and Metal.
        - :tada: [Sokol](https://floooh.github.io/sokol-html5/) [:octocat:](https://github.com/floooh/sokol) : :fire: Top notch single file header libraries that include cross platform a phenomenal graphics abstraction api, windowing, file handling, audio and more. Excellent!! [[Learn OpenGL Examples, ported to Sokol](https://www.geertarien.com/learnopengl-examples-html5/)]
    - #### Geometry <a name="C-Geometry"></a>

    - #### Graphics <a name="C-Graphics"></a>
        - :tada: [Sokol Graphics Painter](https://github.com/edubart/sokol_gp) : Minimal modern efficient cross platform 2D graphics painter (api) in C implemented using [Sokol](https://floooh.github.io/sokol-html5/) as the backend.
    - #### Gui <a name="C-Gui"></a>

    - #### Input <a name="C-Input"></a>
        - :tada: [Sokol Gamepad](https://github.com/floooh/sokol/pull/393/commits/26a9da9dafd4adb22a1ace0de0d2569da31ae427) : Branch with add on support for game pads in [Sokol](https://github.com/floooh/sokol).
    - #### Lighting <a name="C-Lighting"></a>
        - :star: [Light Mapper](https://github.com/ands/lightmapper) : Single-file library for lightmap baking by using your existing OpenGL renderer.
    - #### Math <a name="C-Math"></a>

    - #### Physics <a name="C-Physics"></a>

    - #### Scripting <a name="C-Scripting"></a>

    - #### Utility <a name="C-Utility"></a>

    - #### Vector Graphics <a name="C-Vector-Graphics"></a>

    - #### Windowing <a name="C-Windowing"></a>

<br>

- ### C++ <a name="Cpp"></a>
    - #### - Language: Additional Collections - <a name="Cpp-Language-Additional-Collections"></a>
        - :books: [Awesome C++](https://github.com/fffaraz/awesome-cpp#readme) : A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. 
        - :books: [Awesome C++ Game Dev](https://github.com/Caerind/AwesomeCppGameDev#readme) : A curated list of awesome C++ (mainly) things for Game Development.
    - #### Game Engine w/Editor <a name="Cpp-Game-Engine"></a>
        - :tada: [Esenthel](https://esenthel.com/) [:octocat:](https://github.com/Esenthel/EsenthelEngine) : Cross-platform feature-packed open source engine. Easy to use. In development since the year 2000.
        - :tada: [Irrlicht](https://irrlicht.sourceforge.io) [:octocat:](https://sourceforge.net/projects/irrlicht/) : Cross-platform 3D engine written in C++ worked on for nearly 2 decades.
        - :tada: [Polycode](http://polycode.org/features/) [:octocat:](https://github.com/ivansafrin/Polycode) : Cross-platform framework for creative code. Nice editor.
        - :tada: [Torque 3D](https://torque3d.org/torque3d/) [:octocat:](https://github.com/GarageGames/Torque3D) : High performance 3D engine.
        - :lock: [UPBGE](https://upbge.org) [:octocat:](https://github.com/UPBGE/upbge) : Blender game engine. Forked from [Blender](https://www.blender.org).
    - #### Game Framework <a name="Cpp-Game-Framework"></a>
        - :tada: [Cocos2d-x](https://www.cocos.com/en/cocos2dx) [:octocat:](https://github.com/cocos2d/cocos2d-x) : Provides rendering, gui, audio, network, physics, user input, etc. Widely used in game development and application construction.
        - :tada: [Defold](https://defold.com) [:octocat:](https://github.com/defold/defold) : Open sourced by King. Free to use game engine for development of desktop, mobile and web games.
        - :tada: [LOVE](https://love2d.org) [:octocat:](https://github.com/love2d/love) : LÖVE is an awesome 2D game framework for writing game code with Lua.
        - :tada: [ORX](http://orx-project.org) [:octocat:](https://github.com/orx/orx) : Orx is a 2.5D data-driven game development engine.
        - :tada: [Panda3D](https://www.panda3d.org) [:octocat:](https://github.com/panda3d/panda3d) : Powerful, mature cross-platform game engine for Python and C++, developed by Disney and CMU.
        - :tada: [Solar2D](https://solar2d.com) [:octocat:](https://github.com/coronalabs/corona) : (Previously known as Corona) Focus on ease of iterations and usage.
    - #### Geometry <a name="Cpp-Geometry"></a>
        - :tada: [Delabella](https://github.com/msokalski/delabella) : Super stable 2D delaunay triangulation.
        - :tada: [Geometric Tools](https://www.geometrictools.com/index.html) : Collection of source code for computing in the fields of mathematics, geometry, graphics, image analysis and physics written in C++ 14.
        - :lock: [libigl](https://libigl.github.io) [:octocat](https://github.com/libigl/libigl) : A simple C++ geometry processing library.
        - :lock: [trimesh2](https://gfx.cs.princeton.edu/proj/trimesh2/) : A C++ library and set of utilities for input, output, and basic manipulation of 3D triangle meshes.
    - #### Graphics <a name="Cpp-Graphics"></a>
        - :tada: [Bgfx](https://github.com/bkaradzic/bgfx) : Cross-platform, graphics API agnostic, rendering library.
        - :tada: [Horde3D](http://www.horde3d.org) [:octocat:](https://github.com/horde3d/Horde3D) : 3D rendering and animation engine. [[Scene Editor Info](http://horde3d.org/wiki/index.php?title=Horde3D_Scene_Editor)].
        - :tada: [Ogre](https://www.ogre3d.org) [:octocat:](https://github.com/OGRECave/ogre) : Scene-oriented, flexible 3D engine.
    - #### Lighting <a name="Cpp-Lighting"></a>
        - :tada: [Thekla Atlas](https://github.com/Thekla/thekla_atlas) : Atlas generation tool, useful when generating light maps for meshes that do not have artist-supplied uv's.
        - :tada: [UVAtlas](https://github.com/Microsoft/UVAtlas) : DirectX library for creating and packing an isochart texture atlases.

<br>

- ### C# <a name="CSharp"></a>
    - #### - Language - <a name="CSharp-"></a>
    - #### Game Engine w/Editor <a name="CSharp-Game-Engine"></a>
        - :tada: [Stride](https://stride3d.net) [:octocat:](https://github.com/stride3d/stride) : (formerly Xenko) C# game engine for realistic rendering and VR.
    - #### Game Framework <a name="CSharp-Game-Framework"></a>
        - :tada: [MonoGame](https://www.monogame.net) [:octocat:](https://github.com/MonoGame/MonoGame) : Framework for creating powerful cross-platform games in C#.
    - #### Physics <a name="CSharp-Physics"></a>
        - :tada: [Aether Physics](https://github.com/tainicom/Aether.Physics2D) : Greet 2D physics library with continuous collision detection, convex and concave polyons, collision groups, joints and much more.

<br>

- ### Haxe
    - #### - Language - <a name="Haxe-Language"></a>
        - :tada: [Haxe](https://haxe.org) [:octocat:](https://github.com/HaxeFoundation/haxe) : Official site. Very cool programming language used to produce cross-platform native code.
        - :books: [Haxelibs](https://lib.haxe.org/all) : A list of every library uploaded to Haxe's website.
        - :books: [haxetink](https://github.com/haxetink) : Various add-on libraries for Haxe.
        - :earth_americas: [Snowkit](http://snowkit.org) [:octocat:](https://github.com/snowkit) : A collective of Haxe developers.
    - #### - Language: Additional Collections - <a name="Haxe-Language-Additional-Collections"></a>
        - :books: [Awesome Haxe](https://github.com/nadako/awesome-haxe#readme) : Awesome curated list of useful Haxe links.
        - :books: [Awesome Haxe Game Dev](https://github.com/Dvergar/awesome-haxe-gamedev#readme) : Awesome list of game dev resources for Haxe.
    - #### - Language: Articles - <a name="Haxe-Language-Articles"></a>
        - :books: [Flash is dead, long live OpenFL](https://web.archive.org/web/20201112021925/https://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
        - :books: [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
    - #### Animation <a name="Haxe-Animation"></a>
        - :tada: [Actuate](https://github.com/jgranick/actuate) : Flexible, fast "tween" library.
        - :tada: [openfl/DragonBones](https://github.com/openfl/dragonbones) : Runtime support for [DragonBones](https://www.dragonbones.com) skeletal animation.
        - :tada: [spine-hx](https://github.com/jeremyfa/spine-hx) : [Spine](https://esotericsoftware.com) runtime for Haxe.
    - #### Application <a name="Haxe-Application"></a>
        - :tada: [HashLink](https://hashlink.haxe.org) [:octocat:](https://github.com/HaxeFoundation/hashlink/) : Virtual machine for Haxe.
        - :tada: [hexMachina](http://hexmachina.org) [:octocat:](https://github.com/DoclerLabs/hexCore) : Powerful modular MVC framework written in Haxe.
        - :tada: [Lime](https://lime.software) [:octocat:](https://github.com/haxelime/lime) : A flexible, lightweight layer for Haxe cross-platform developers.
        - :tada: [nme](https://github.com/haxenme/nme) : Cross-platform native backend for Haxe projects.
    - #### Entity Component System <a name="Haxe-Entity-Component-System"></a>
        - :tada: [ecx](https://github.com/eliasku/ecx) : Entity Component System framework for Haxe.
        - :tada: [GASM](https://github.com/HacksawStudios/GASM) : Framework agnostic Entity Component System for Haxe.
    - #### Game Engine w/Editor <a name="Haxe-Game-Engine"></a>
        - :tada: [Armory](https://armory3d.org) [:octocat:](https://github.com/armory3d/armory) : 3D game engine with full Blender integration.
        - :tada: [Away3D](https://www.away3d.com) [:octocat:](https://github.com/openfl/away3d) : Real-time 3D engine for OpenFL.
        - :tada: [flixel-studio](https://github.com/Dovyski/flixel-studio) : Embeddable, in-game editor for [HaxeFlixel](https://haxeflixel.com).
        - :tada: [Hide](https://github.com/heapsio/hide) : Extensible IDE for [Heaps](https://heaps.io).
        - :tada: [LDtk](https://ldtk.io) [:octocat:](https://github.com/deepnight/ldtk) : Very cool modern, lightweight and efficient 2D level editor.
        - :tada: [Starling](https://gamua.com/starling/) [:octocat:](https://github.com/openfl/starling) : Popular Stage3D framework.
    - #### Game Framework <a name="Haxe-Game-Framework"></a>
        - :tada: [Citrus](http://citrusengine.com) [:octocat:](https://github.com/DaVikingCode/Citrus-Engine) : 2D and 3D ActionScript 3 based engine.
        - :tada: [Clay](https://github.com/clay2d/clay) : Cross-platform 2d game framework.
        - :tada: [HaxeFlixel](https://haxeflixel.com) [:octocat:](https://github.com/HaxeFlixel/flixel) : Cross-platform 2D game engine powered by Haxe and OpenFL.
        - :tada: [OpenFL](https://www.openfl.org) [:octocat:](https://github.com/openfl/openfl) : For creative expression on the web, desktop, mobile and consoles.
    - #### Graphics <a name="Haxe-Graphics"></a>
        - :tada: [Heaps](https://heaps.io) [:octocat:](https://github.com/HeapsIO/heaps) : High-performance cross-platform graphics engine by the creators of [Haxe](https://haxe.org).
        - :tada: [Kha](https://kha.tech) [:octocat:](https://github.com/Kode/Kha) : Ultra-portable, high performance, open source multimedia framework.
        - :tada: [Sparkler](https://github.com/AndreiRudenko/sparkler) : Modular Macro-powered Particle System.
    - #### Gui <a name="Haxe-Gui"></a>
        - :tada: [HaxeUI](http://haxeui.org) [:octocat:](https://github.com/haxeui/haxeui-core) : Cross-platform set of styleable application centric, rich UI components.
    - #### Physics <a name="Haxe-Physics"></a>
        - :tada: [Haxe Bullet](https://github.com/armory3d/haxebullet) : Bullet 3D Physics bindings for Haxe.
        - :tada: [HeapsIO/bullet](https://github.com/HeapsIO/bullet) : Bullet 3D Physics for Heaps (Haxe's native low-level game framework).
        - :tada: [Jelly Physics](https://github.com/michaelapfelbeck/jellyPhysics) : Soft body 2D physics engine.
        - :tada: [Nape](https://joecreates.github.io/napephys/) [:octocat:](https://github.com/HaxeFlixel/nape-haxe4) : Very impressive powerful, fast, and friendly 2D rigid body physics engine.
    - #### Serialization / Storage <a name="Haxe-Serialization"></a>
        - :tada: [CastleDB](https://github.com/ncannasse/castle) : Structured database with a local web service to edit it.
        - :tada: [Format](https://github.com/HaxeFoundation/format) : Various files formats support for Haxe.
        - :tada: [HxBit](https://github.com/HeapsIO/hxbit) : Binary serialization and network synchronization library.
    - #### Utility <a name="Haxe-Utility"></a>
        - :tada: [hxColorToolkit](https://github.com/andyli/hxColorToolkit) : Library for color conversion and color scheme generation.
        - :tada: [HxMath](https://github.com/tbrosman/hxmath) : Game-oriented math library for the Haxe language.
        - :tada: [nxColor](https://github.com/oscarcs/nxColor) : Color manipulation library.
        - :tada: [SteamWrap](https://github.com/larsiusprime/SteamWrap) : Haxe native extension for the Steam API.
    - #### Visual Scripting <a name="Haxe-Visual-Scripting"></a>
        - :tada: [haxe-blockly](https://github.com/nickmain/haxe-blockly) : Haxe wrapper for [Blockly](https://developers.google.com/blockly)

<br>

- ### Java
     - #### - Language: Tutorials - <a name="Java-Language-Articles"></a>
        - :books: (OpenGL & GLSL Tutorials)[https://github.com/mattdesl/lwjgl-basics/wiki] : OpenGL / GLSL tutorials written for LWJGL and libGDX.
    - #### Game Framework <a name="Java-Game-Framework"></a>
        - :tada: [libGDX](https://libgdx.com) [:octocat:](https://github.com/libgdx/libgdx) : Cross-platform Java game development framework that is built on and adds functionality to [LWJGL](https://www.lwjgl.org). [[Awesome libGDX](https://github.com/rafaskb/awesome-libgdx#readme)]
        - :tada: [LWJGL](https://www.lwjgl.org) [:octocat:](https://github.com/LWJGL/lwjgl3) : Library that enables cross-platform access to popular native APIs useful in the development of graphics, audio, parallel computing and XR applications.

<br>

- ### Javascript
    - #### Game Engine w/Editor <a name="Javascript-Game-Engine"></a>
        - :tada: [A-Frame](https://aframe.io) [:octocat:](https://github.com/aframevr/aframe/) : Web framework for building 3D virtual reality (VR) experiences.
        - :tada: [Cocos Creator](https://www.cocos.com/en/creator) [:octocat:](https://github.com/cocos-creator/engine) : A Cross-Platform 2D / 3D Game Creation Tool
        - :tada: [Pixelbox.js](https://pixwlk.itch.io/pixelbox) [:octocat:](https://github.com/cstoquer/pixelbox) : Sandbox framework to fast-prototype 2D tile-based games in HTML5 and JavaScript. [Editor](https://pixwlk.itch.io/pixelbox)
    - #### Game Framework <a name="Javascript-Game-Framework"></a>
        - :tada: [GDevelop](https://gdevelop-app.com) [:octocat:](https://github.com/4ian/GDevelop) : A 2D full-featured, open source game development software platform.
        - :tada: [Phaser](https://phaser.io) [:octocat:](https://github.com/photonstorm/phaser) : Fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supports Canvas and WebGL.
        - :tada: [Turbulenz](http://biz.turbulenz.com/developers) [:octocat:](https://github.com/turbulenz/turbulenz_engine) : Modular 2D / 3D game framework for making HTML5 powered games for browsers, desktops and mobile devices.
    - #### Graphics <a name="Javascript-Graphics"></a>
        - :tada: [Babylon.js](https://www.babylonjs.com) [:octocat:](https://github.com/BabylonJS/Babylon.js) : One of the most powerful, beautiful, and simple Web rendering engines in the world.
        - :tada: [CopperLicht](http://ambiera.com/copperlicht/) : Commercial grade open source 3D JavaScript library for WebGL. [[CopperCube Editor](http://ambiera.com/coppercube/index.html)]
        - :tada: [LUME](https://lume.io) [:octocat:](https://github.com/lume/lume) : Toolkit that simplifies the creation of interactive 2D / 3D experiences for any device from mobile to desktop to AR/VR.
        - :tada: [Three.js](https://threejs.org) [:octocat:](https://github.com/mrdoob/three.js/) : :fire: Easy to use, lightweight, cross-browser, general purpose 3D library. [[Scene Editor](https://threejs.org/editor/) | [Examples](https://threejs.org/examples/) | [Awesome Three.js](https://github.com/fritx/awesome-threejs)]
        - #### Three.js Reference <a name="Javascript-Three-Reference"></a>
            - :earth_americas: [Discover Three.js](https://discoverthreejs.com) : Everything you need to know to create stunning 3D web applications using [Three.js](https://threejs.org).
            - :earth_americas: [SBcode Three.js Tutorials](https://sbcode.net/threejs/) : Fantastic examples with code and explanations of topics from beginner to advanced.
            - :earth_americas: [Stemkoski Three.js Examples](http://stemkoski.github.io/Three.js/) : Excellent set of instructive examples with well commented source code.
            - :books: [Three.js Bookshelf](https://discourse.threejs.org/t/three-js-bookshelf/2468) : Great collection of resources for [Three.js](https://threejs.org).
            - :books: [Three.js Discourse Examples](https://hofk.de/main/discourse.threejs/) : Yearly collection of all examples with source posted on the [Three.js](https://threejs.org) forum
            - :books: [Three.js Manual](https://threejs.org/manual/#en/fundamentals) : (formerly ThreeJsFundamentals) Great info on [Three.js](https://threejs.org) and 3D engines and how they work in general.

<br>

- ### Python
    - #### Gui <a name="Python-Gui"></a>
        - :tada: [Kivy](https://kivy.org/) [:octocat:](https://github.com/kivy/kivy) : Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS.

<br>

- ### Rust
    - #### Game Framework <a name="Rust-Game-Framework"></a>
        - :tada: [Bevy](https://bevyengine.org) [:octocat:](https://github.com/bevyengine/bevy) : :fire: A refreshingly simple data-driven game engine built in Rust.
    - #### Physics <a name="Rust-Physics"></a>
        - :tada: [Rapier](https://rapier.rs) [:octocat:](https://github.com/dimforge/rapier) : 2D and 3D physics engines focused on performance.


<br>


## Specialty Topics
_Exploring specific game engine / game dev topics and features_

- ### AI / Pathfinding <a name="Topic-AI"></a>
    - :books: [Intro to AI](https://www.raywenderlich.com/2808-introduction-to-ai-programming-for-games) : Introduction to AI Programming for Games at [raywenderlich.com](https://www.raywenderlich.com).
    - :books: [Beginner's Guide to Game AI](https://www.gamedev.net/tutorials/programming/artificial-intelligence/the-total-beginners-guide-to-game-ai-r4942/) : Introduction to a range of concepts used in artificial intelligence for games at [gamedev.net](https://www.gamedev.net).

- ### Animation <a name="Topic-Animation"></a>
    - :books: [Skeletons and Inverse Kinematics](https://venturebeat.com/2017/08/09/character-animation-skeletons-and-inverse-kinematics/) : Basic and intermediate principles for using skeletons with inverse kinematics for character animation.

- ### Fluid / Smoke <a name="Topic-Fluid"></a>
    - :books: [Fluid Simulation on the GPU](https://developer.nvidia.com/gpugems/gpugems/part-vi-beyond-triangles/chapter-38-fast-fluid-dynamics-simulation-gpu) : GPU Gems Chapter 38. A method for fast, stable fluid simulation that runs entirely on the GPU.
    - :lock: [Fluids-2D](http://www.csc.kth.se/~mathar/fluids-2d/) [:octocat:](https://github.com/mharrys/fluids-2d) : Real-time fluid dynamics running on the GPU with the help of WebGL and [Three.js](https://threejs.org).
    - :lock: [GPU Fluid Experiments](http://haxiomic.github.io/GPU-Fluid-Experiments/html5/) [:octocat:](https://github.com/haxiomic/GPU-Fluid-Experiments) : Cross-platform GPU fluid simulation.
    - :tada: [WebGL Fluid Simulation](https://paveldogreat.github.io/WebGL-Fluid-Simulation/) [:octocat:](https://github.com/PavelDoGreat/WebGL-Fluid-Simulation) : Play with fluids in your browser (works even on mobile).

- ### Geometry
    - #### Algorithms
        - :books: [Practical Geometry Algorithms](http://geomalgorithms.com/index.html) : Online book that covers algorithms for fundamental geometric objects, computing bounding containers, convex hulls, polyline simplification and more.
    - #### Meshes
        - :books: [Mesh Transforms](https://ciechanow.ski/mesh-transforms/) [:octocat:](https://github.com/olegtyshcneko/CAMeshTransform) : Interesting info on Apple's private API that allows manipulation of the mesh of any UIView.
    - #### Smoothing
        - :books: [Laplacian Smoothing](http://rodolphe-vaillant.fr/entry/70/laplacian-smoothing-c-code-to-smooth-a-mesh) : Draft notes with c++ code for laplacian smoothing of meshes. 
        - :books: [Subdivision at Matt's Webcorner](http://graphics.stanford.edu/~mdfisher/subdivision.html) : Subdivision is a powerful and easily implemented algorithm used, in its simplest application, to smooth meshes.
        - :books: [Subdivision Surfaces](http://www.holmes3d.net/graphics/subdivision/) : Explanations of different schemes used for subdividing surfaces.

- ### Lighting / Shadows
    - #### Lighting 2D
        - :books: [Gleaner Heights: 2D Lighting](http://gleanerheights.blogspot.com/2017/05/lighting-in-2d-games-shader-glsl.html?m=1) : A simple introduction to 2D lighting in a game with GLSL.
        - :books: [Lighting a 2D Game](http://www.wholehog-games.com/devblog/2013/06/07/lighting-in-a-2d-game/) : Nice summary of techniques used in proper 2D lighting with diffuse lighting, self illumination and normal maps.
    - #### Lighting 3D
        - :books: [Basic Lighting](https://learnopengl.com/Lighting/Basic-Lighting) : Excellent basic 3D lighting article by [Learn OpenGL](https://learnopengl.com). There are many excellent more advanced follow-up articles on this site.
    - #### Shadows 2D
        - :books: [2D Pixel Perfect Shadows](https://github.com/mattdesl/lwjgl-basics/wiki/2D-Pixel-Perfect-Shadows) : An approach to 2D pixel-perfect lights/shadows using shaders.
        - :books: [2D Visibility](https://www.redblobgames.com/articles/visibility/) : Excellent interactive tutorial on 2D visibility. Written in Haxe and transpiled to Java, Javascript and C#.
        - :books: [Fast 2D shadows in Unity](https://www.gamedeveloper.com/programming/fast-2d-shadows-in-unity-using-1d-shadow-mapping) : Article about adapting traditional techniques from 3D rendering to achieve fast 2D shadows for a large number of light sources in the Unity game engine.
        - :earth_americas: [Sight & Light](https://ncase.me/sight-and-light/) [:octocat:](https://github.com/ncase/sight-and-light) : How to create 2D visibility/shadow effects for your game.
        - :books: [Symmetric Shadowcasting](https://www.albertford.com/shadowcasting/) : Tutorial on a common technique for calculating field of view.
    - #### Shadows 3D
        - :books: [Efficient Soft-Edged Shadows](https://developer.nvidia.com/gpugems/gpugems2/part-ii-shading-lighting-and-shadows/chapter-17-efficient-soft-edged-shadows-using) : GPU Gems 2 Chapter 17. Efficient Soft-Edged Shadows Using Pixel Shader Branching.
        - :books: [Screen Space Shadows](https://panoskarabelas.com/posts/screen_space_shadows/) : Great exploration of screen space shadows.
        - :books: [Shadow Mapping](https://en.m.wikipedia.org/wiki/Shadow_mapping) : In depth explantion on [Wikipedia](https://en.m.wikipedia.org) of shadow mapping and the techniques used to acheive it.

- ### Particles
    - :books: [Particles](https://learnopengl.com/In-Practice/2D-Game/Particles) : Excellent particle article by [Learn OpenGL](https://learnopengl.com).
    - :books: [Soft Particles](https://keaukraine.medium.com/implementing-soft-particles-in-webgl-and-opengl-es-b968d61133b0) : Implementing soft particles in WebGL and OpenGL ES.

- ### Physics
    - #### General Resources
        - :books: [Game Physics from Scratch](https://brm.io/game-physics-for-beginners/) : If you're a game developer interested in learning about physics engines, these resources are a good place to start.
        - :books: [Open Source Physics Engines](https://www.tapirgames.com/blog/open-source-physics-engines) : A list of open source physics engines.
    - #### Physics 2D
        - :books: [Basic 2D Platformer Physics](https://gamedevelopment.tutsplus.com/series/basic-2d-platformer-physics--cms-998) : This article covers how to create a simple and robust physics system for a platformer game.
        - :books: [How to create 2D Physics Games](https://www.gamedeveloper.com/design/how-to-create-2d-physics-games-with-box2d-library) : Excellent article on how to use [Box2D](https://box2d.org) for 2D game topics ranging from shapes, water (metaballs), ropes, gravity, lines and vehicles.
        - :books: [Ledge Grabbing](https://gamedevelopment.tutsplus.com/tutorials/basic-2d-platformer-physics-part-4--cms-26046) : Tutorial on ledge grabbing in 2D platformer physics.
    - #### Ropes / Chains
        - :books: [Ropes in Contraption Maker](https://www.gamedeveloper.com/design/ropes-in-contraption-maker) : A short discussion about how to implement the physics of ropes in Contraption Maker.
        - :earth_americas: [Matter.js Chains](https://brm.io/matter-js/demo/#chains) [:octocat:](https://github.com/liabru/matter-js/blob/master/examples/chains.js) : Chains demo using the javascript library [Matter.js](https://brm.io/matter-js/).
    - #### Soft Body
        - :books: [Blob Physics](https://cowboyprogramming.com/2007/01/05/blob-physics/) : Using verlet physics to simulate blobs.
        - :books: [Box2D Soft Body Blobs](https://www.emanueleferonato.com/2012/09/21/step-by-step-creation-of-a-box2d-soft-body-blob/) : Step by step creation of a Box2D soft body blob.
    - #### Verlet Physics
        - :books: [Making a Verlet Physics Engine in JavaScript](https://betterprogramming.pub/making-a-verlet-physics-engine-in-javascript-1dff066d7bc5) : Taking a look under the hood of a 2D physics engine in Javascript.
    - #### Water
        - :books: [2D Water](https://prime31.github.io/water2d-part1/) : Modeling 2D water with springs.

- ### Scripting
    - :books: [Adding Languages to Game Engines](https://www.gamedeveloper.com/programming/adding-languages-to-game-engines) : How a self described "lazy programmer" built the powerful scripting language used in making Jedi Knight: Dark Forces 2.
    - :books: [Implementing A Scripting Engine](https://www.flipcode.com/archives/Implementing_A_Scripting_Engine-Part_1_Overview.shtml) : In depth series of articles about writting a scripting engine from scratch.

- ### Shaders <a name="Topic-Shaders"></a>
    - #### - General Resources -
        - :earth_americas: [3D Game Shaders For Beginners](https://lettier.github.io/3d-game-shaders-for-beginners/index.html) [:octocat:](https://github.com/lettier/3d-game-shaders-for-beginners) : :fire: A collection of shading techniques that will take your game visuals to new heights. Including adding textures, lighting, shadows, normal maps, glowing objects, ambient occlusion, reflections, refractions, and more!
        - :earth_americas: [Book of Shaders](https://thebookofshaders.com) [:octocat:](https://github.com/patriciogonzalezvivo/thebookofshaders) : :fire: This is a gentle step-by-step guide through the abstract and complex universe of [Fragment Shaders](https://www.khronos.org/opengl/wiki/Fragment_Shader).
        - :earth_americas: [Geeks3D Shader Library](https://www.geeks3d.com/shader-library/) : Fantastic collection of amazing shaders including post processing, lighting, utlities and more.
        - :earth_americas: [Shadertoy](https://www.shadertoy.com) : Build and share shaders online.
    - #### Bloom
        - :books: [Learn OpenGL Tutorial](https://learnopengl.com/Advanced-Lighting/Bloom) : Excellent presentation of the techniques used for bloom lighting presented in OpenGL.
        - :earth_americas: [Three.js Example](https://threejs.org/examples/?q=bloom#webgl_postprocessing_unreal_bloom) [:octocat:](https://github.com/mrdoob/three.js/blob/master/examples/webgl_postprocessing_unreal_bloom.html) : WebGL bloom effect postprocessing example in [Three.js](https://threejs.org).
        - :books: [Unity Tutorial](https://catlikecoding.com/unity/tutorials/advanced-rendering/bloom/) : Covers how to add support for a bloom effect to a camera.
    - #### Fire
        - :books: [Fire Shader in GLSL](https://clockworkchilli.com/blog/8_a_fire_shader_in_glsl_for_your_webgl_games) : Great fire intro shader using noise textures and masking.
        - :earth_americas: [Simplex 3D Noise](https://www.shadertoy.com/view/MllfDn) : Simplex noise fire simulation shader at [ShaderToy](https://www.shadertoy.com).
    - #### Noise
        - :books: [Book of Shaders - Noise](https://thebookofshaders.com/11/) : Excellent GLSL noise article by [Book of Shaders](https://thebookofshaders.com).
        - :tada: [Direct Computational Noise](https://weber.itn.liu.se/~stegu/jgt2011/supplement.pdf) [:octocat:](https://github.com/ashima/webgl-noise/) : Research paper responsible for the 2D simplex noise function (MIT Licesnse) many games use in their GLSL code.
        - :tada: [psrdnoise](https://github.com/stegu/psrdnoise/) : Tiling simplex flow noise in 2-D and 3-D compatible with GLSL 1.20 (WebGL 1.0) and above.
        - :books: [Understanding Perlin Noise](http://adrianb.io/2014/08/09/perlinnoise.html) [:octocat:](https://gist.github.com/Flafla2/f0260a861be0ebdeef76) : Presents an easy-to-understand analysis of Ken Perlin's Improved Perlin Noise, written in C#.
        - :tada: [WebGL Noise](https://github.com/stegu/webgl-noise/) : Maintained branch of the original Ashima Arts 2D, 3D and 4D noise functions.
    - #### Outlines
        - :earth_americas: [Fast Solid 2D Outline](https://www.shadertoy.com/view/XdV3Dc) : Quickly drawing an outline on the alpha channel of a 2D image at [ShaderToy](https://www.shadertoy.com).
        - :books: [Let it glow!](http://blogs.love2d.org/content/let-it-glow-dynamically-adding-outlines-characters) : Fantastic article with shader code on dynamically adding outlines to characters.
        - :tada: [Outline Shader](https://www.reddit.com/r/godot/comments/8g067a/the_perfect_outline_shader_atleast_close/) [:octocat:](https://github.com/steincodes/godot-shader-tutorials) : Reddit post and github repo of nice outline shader.
    - #### Pixelation
        - :books: [Pixel Art Shaders](https://alaingalvan.tumblr.com/post/79829067408/glsl-pixel-art-shaders) : Useful GLSL postprocessing shaders for pixel art games.
        - :earth_americas: [Three.js Pixelation Example](https://threejs.org/examples/?q=pixel#webgl_postprocessing_pixel) [:octocat:](https://github.com/mrdoob/three.js/blob/master/examples/webgl_postprocessing_pixel.html) : WebGL pixelation postprocessing example in [Three.js](https://threejs.org).
    - #### Water
        - :books: [2D Water Shader](https://rotatingcanvas.com/fragment-shader-to-simulate-water-surface-in-libgdx/) : GLSL fragment shader to simulate 2D water surface in [libGDX](https://libgdx.com).
    - #### Wireframe
        - :books: [Easy Wireframe Display](https://web.archive.org/web/20190220052115/http://codeflow.org/entries/2012/aug/02/easy-wireframe-display-with-barycentric-coordinates/) : Nice explanation with demo of rendering triangles as wireframe using [Barycentric Coordinates](https://en.wikipedia.org/wiki/Barycentric_coordinate_system).
        - :books: [Flat and Wireframe Shading](https://catlikecoding.com/unity/tutorials/advanced-rendering/flat-and-wireframe-shading/) : This tutorial covers how to add support for flat shading and showing the wireframe of a mesh using [Barycentric Coordinates](https://en.wikipedia.org/wiki/Barycentric_coordinate_system).

- ### Tiling
    - :books: [Auto Tile](https://gamedevelopment.tutsplus.com/tutorials/how-to-use-tile-bitmasking-to-auto-tile-your-level-layouts--cms-25673) : How to use tile bitmasking to auto-tile your level layouts.
    - :books: [Blob Tileset](http://www.cr31.co.uk/stagecast/wang/blob.html) : A great tutorial on 2D edge and corner matched tilesets.


<br>


## Tools / Software <a name="Tools"></a>
_Software to help with game engine / video game development_

- ### Animation <a name="Tools-Animation"></a>

- ### Color <a name="Tools-Color"></a>

- ### Drawing <a name="Tools-Drawing"></a>

- ### Game Dev <a name="Tools-Game-Dev"></a>

- ### Image Editors <a name="Tools-Image-Editors"></a>

- ### Materials <a name="Tools-Materials"></a>

- ### Modeling <a name="Tools-Modeling"></a>

- ### Particles <a name="Tools-Particles"></a>

- ### Pixel Art <a name="Tools-Pixel-Art"></a>

- ### Sound <a name="Tools-Sound"></a>

- ### Textures <a name="Tools-Textures"></a>


<br>


## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
