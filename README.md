<h1 align="center">
    <img width="1100" src="aged-title.png" alt="Awesome Game Engine Dev Logo"/>
</h1>

# Awesome Game Engine Development [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> Awesome list of assets, libraries, and tools for Game Engine Development. Specifically, this list is geared toward development of high-level, fully featured game engines (e.g., [Godot](https://godotengine.org) / [Unity](https://unity.com)). This would include things typically not found in low-level game engines / app or game frameworks / graphics libraries (e.g., [MonoGame](https://www.monogame.net) / [SDL](https://www.libsdl.org)). Most importantly of which would be a visual scene editor, but also capabilities such as scipting support, physics integration, asset management, special effects, etc. 

This list currently favors (but is not limited to) programming the core engine in the following languages: C, C++, C#, Haxe, or Javascript.


<br><br>


### License Legend
- Open Source Software
    - :star: - [Public Domain License](https://en.wikipedia.org/wiki/Public-domain-equivalent_license) ([CC0](https://creativecommons.org/publicdomain/zero/1.0/), [BOLA](https://blitiri.com.ar/p/bola/), [WTFPL](https://en.wikipedia.org/wiki/WTFPL), [Unlicense](https://en.wikipedia.org/wiki/Unlicense), etc.)
    - :tada: - [Permissive License](https://en.wikipedia.org/wiki/Permissive_software_license) ([MIT / Expat](https://en.wikipedia.org/wiki/MIT_License), [BSD](https://en.wikipedia.org/wiki/BSD_licenses), [ZLIB / LIBPNG](https://en.wikipedia.org/wiki/Zlib_License), [ISC](https://en.wikipedia.org/wiki/ISC_license), [Apache](https://en.wikipedia.org/wiki/Apache_License), [Boost](https://en.wikipedia.org/wiki/Boost_(C%2B%2B_libraries)#License) etc.)
    - :lock: - [Copyleft License](https://en.wikipedia.org/wiki/Copyleft) ([CC](https://en.wikipedia.org/wiki/Creative_Commons_license), [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) / [LGPL](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License), [MPL](https://en.wikipedia.org/wiki/Mozilla_Public_License), etc.)
- Asset / Service / Tool
    - :free: - Free
    - :moneybag: - Paid
    - :money_with_wings: - Partially Free
- Other
    - :books: - Article, Blog, Collection, List, Tutorial(s)
    - :earth_americas: - Website
- :octocat: - Link to Repository. Click on it to see Source Code!
- :fire: - Hot, Amazing Resource!


<br><br>


## Index
- [Game Engines](#Game-Engines)
    - [Popular](#Popular)
    - [AAA](#AAA)
    - [Commercial](#Commercial)
    - [Specialty](#Specialty)
- [Learning](#Learning)
    - [Computer Graphics](#Computer-Graphics)
        - <sub><sup>[DirectX](#Graphics-DirectX) | [Metal](#Graphics-Metal) | [OpenGL](#Graphics-OpenGL) | [Vulkan](#Graphics-Vulkan) | [WebGL](#Graphics-WebGL) | [WebGPU](#Graphics-WebGPU) | [XNA](#Graphics-XNA) </sup></sub>
    - [Engine Development](#Engine-Development)
    - [Game Development](#Game-Development)
    - [Programming](#Programming)
- [Libraries](#Libraries)
    - [C](#C)
    - [C++](#Cpp)
    - [C#](#CSharp)
    - [Dart](#Dart)
    - [Haxe](#Haxe)
    - [Java](#Java)
    - [Javascript](#Javascript)
    - [Python](#Python)
    - [Rust](#Rust)
- [Specialty Topics](#Specialty-Topics)
    - [AI / Pathfinding](#Topic-AI)
    - [Animation](#Topic-Animation)
    - [Entity Component System](#Topic-ECS")
    - [Fluid / Smoke](#Topic-Fluid)
    - [Geometry](#Geometry)
        - <sub><sup>[Algorithms](#Algorithms) | [Meshes](#Meshes) | [Smoothing](#Smoothing)</sup></sub>
    - [Lighting / Shadows](#Lighting)
        - <sub><sup>[Lighting](#Lighting-2D) | [Shadows](#Shadows-2D)</sup></sub>
    - [Particles](#Particles)
    - [Physics](#Physics)
        - <sub><sup>[Platformer](#Platformer) | [Ropes / Chains](#Topics-Physics-Ropes) | [Soft Body](#Soft-Body) | [Verlet](#Verlet-Physics) | [Water](#Topics-Physics-Water)</sup></sub>
    - [Scripting](#Scripting)
    - [Shaders](#Topic-Shaders)
         - <sub><sup>[Bloom](#Bloom) | [Fire](#Fire) | [Noise](#Noise) | [Outlines](#Outlines) | [Pixelation](#Pixelation) | [Water](#Topics-Shaders-Water) | [Wireframe](#Wireframe)</sup></sub>
    - [Tiling](#Tiling)
- [Tools / Software](#Tools)
    - [Animation](#Tools-Animation)
    - [Audio](#Tools-Audio)
        - <sub><sup>[Music](#Tools-Audio-Music) | [Sound Effects](#Tools-Audio-Sound-Effects)</sup></sub>
    - [Color](#Tools-Color)
    - [Drawing](#Tools-Drawing)
    - [Game Dev](#Tools-Game-Dev)
    - [Image Editors](#Tools-Image)
    - [Materials](#Tools-Materials)
    - [Modeling](#Tools-Modeling)
    - [Particles](#Tools-Particles)
    - [Pixel Art](#Tools-Pixel-Art)
    - [Sound](#Tools-Sound)
    - [Textures](#Tools-Textures)
    - [Voxel](#Voxel)
- [Video Game Assets](#Video-Game-Assets)
    - [Graphics](#Assets-Graphics)
    - [Materials](#Assets-Materials)
    - [Models](#Assets-Models)
    - [Music](#Assets-Music)
    - [Sound Effects](#Assets-Sound-Effects)


<br><br>


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
    - :money_with_wings: [PlayCanvas](https://playcanvas.com) [:octocat:](https://github.com/playcanvas/engine) (Repo for  runtime only) : Popular (Flappy Bird), fast and lightweight JavaScript game engine built on WebGL. [[Awesome PlayCanvas](https://github.com/playcanvas/awesome-playcanvas#readme)]
    - :money_with_wings: [ShiVa](https://shiva-engine.com) : 3D game and application development suite.
    - :money_with_wings: [Simulation Starter Kit](https://benmorris.itch.io/plugin-based-scene-editor) : Supports the creation of simple interactive 3D applications across a range of platforms and devices. [[Developer Website](http://fireflytech.org)]
    - :money_with_wings: [Stencyl](http://www.stencyl.com) [:octocat:](https://github.com/Stencyl/stencyl-engine) (Repo for  runtime only) : Quick and easy game making. Visual scripting similar to [Scratch](https://scratch.mit.edu).

- ### Specialty
    - :moneybag: [3dSen](https://geod.itch.io/3dnes) : Unique NES emulator that converts NES games into full 3D experiences and let you play them in realtime. [Developer Website](http://www.geodstudio.net)
    - :money_with_wings: [DopeFish](https://subpixel-studios.itch.io/dopefish) : Full GML Doom/Heretic map loading system for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :tada: [GB Studio](https://www.gbstudio.dev) [:octocat:](https://github.com/chrismaltby/gb-studio) : Retro adventure game creator for Game Boy available for Mac, Linux and Windows.
    - :moneybag: [Platforming Engine](https://robvansaaze.itch.io/platforming-engine) : Everything you need to create your very own platforming game for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :moneybag: [RPG Maker](https://www.rpgmakerweb.com) : Lets you create an original role-playing game without any specialized knowledge or training.
    - :lock: [Twine](https://twinery.org) [:octocat:](https://github.com/klembot/twinejs) : Tool for telling interactive, nonlinear stories.


<br><br>


## Learning
_Info on topics necessary for designing and developing game engines_

- ### Computer Graphics
    - #### Awesome Collections <a name="Graphics-Awesome"></a>
        - :books: [Awesome Graphics Libraries](https://github.com/jslee02/awesome-graphics-libraries#readme) : Awesome curated list of 3D graphics libraries and resources.
    - #### Blog Articles <a name="Graphics-Blog-Articles"></a>
        - :books: [Comparison of Modern Graphics APIs](https://alain.xyz/blog/comparison-of-modern-graphics-apis) : Review of modern graphics APIs and how they compare with older graphics APIs in their design and data structures.
    - #### Books <a name="Graphics-Books"></a>
        - :books: [GPU Gems](https://developer.nvidia.com/gpugems/gpugems/contributors) : Programming techniques, tips, and tricks for real-time graphics hosted by [NVIDIA](https://www.nvidia.com/).
        - :books: [GPU Gems 2](https://developer.nvidia.com/gpugems/gpugems2/copyright) : Programming techniques for high-performance graphics and general-purpose computation hosted by [NVIDIA](https://www.nvidia.com/).
        - :books: [GPU Gems 3](https://developer.nvidia.com/gpugems/gpugems3/contributors) : Collection of state-of-the-art GPU programming examples hosted by [NVIDIA](https://www.nvidia.com/).
    - #### Education Portals <a name="Graphics-Education"></a>
        - :books: [Lighthouse3d.com](http://www.lighthouse3d.com/tutorials/) : Great collection of tutorials on OpenGL, GLSL and many other computer graphics topics.
        - :books: [Scratchapixel](https://www.scratchapixel.com) : Very in depth coverage of topics ranging from mathematics and physics for computer graphics, 3D rendering and many more advanced techniques.
    - #### Graphics API: DirectX <a name="Graphics-DirectX"></a>
        - :earth_americas: [DirectX](https://docs.microsoft.com/en-us/windows/win32/directx) : Microsoft DirectX provides a set of APIs that you can use to create 2D / 3D games and other high-performance multimedia apps. [[Sample Code](https://github.com/microsoft/DirectX-Graphics-Samples) | [Blog](https://devblogs.microsoft.com/directx/)]
        - :books: [DirectXTutorial.com](http://www.directxtutorial.com/default.aspx) : Older resource with lots of tutorials on DirectX versions 9 & 11.
    - #### Graphics API: Metal <a name="Graphics-Metal"></a>
        - :earth_americas: [Metal](https://developer.apple.com/metal/) : Metal provides a platform-optimized, low-overhead API for developing the latest 3D applications and amazing games on Apple platforms. [[Sample Code](https://developer.apple.com/metal/sample-code/)]
        - :books: [Metal Tutorial](https://www.raywenderlich.com/7475-metal-tutorial-getting-started) : Learn how to get started with Apple’s 3D graphics API at [raywenderlich.com](https://www.raywenderlich.com).
    - #### Graphics API: OpenGL <a name="Graphics-OpenGL"></a>
        - :books: [LearnOpenGL](https://learnopengl.com) : :fire: Incredible resource! Teaches you everything you need to do modern graphics programming!
        - :earth_americas: [OpenGL](https://www.opengl.org/) : The industry's foundation for high performance graphics.
        - :books: [OpenGL Tutorial](https://www.opengl-tutorial.org) : Excellent collection of OpenGL tutorials with full source covering lots of topics.
    - #### Graphics API: Vulkan <a name="Graphics-Vulkan"></a>
        - :earth_americas: [Vulkan](https://www.vulkan.org) - Vulkan is a cross-platform industry standard enabling developers to target a wide range of devices with the same graphics API. [[Sample Code](https://github.com/khronosGroup/Vulkan-samples)]
        - :books: [Vulkan Tutorial](https://vulkan-tutorial.com) : This tutorial will teach you the basics of using the Vulkan graphics and compute API.
    - #### Graphics API: WebGL <a name="Graphics-WebGL"></a>
        - :earth_americas: [WebGL](https://www.khronos.org/webgl/) [:octocat:](https://github.com/KhronosGroup/WebGL) : Cross-platform open web standard for a low-level 3D graphics API based on OpenGL ES, exposed to ECMAScript (Javascript) via the HTML5 Canvas element.
        - :books: [WebGL Fundamentals](https://webglfundamentals.org) : :fire: Set of articles that teach WebGL from basic principles, bringing you to a full understanding of what WebGL really is and how it really works.
        - :books: [WebGL 2 Fundamentals](https://webgl2fundamentals.org) : WebGL Fundamentals tutorials updated to use / take advantage of / explain WebGL2.
        - :books: [WebGL Tutorial](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/Tutorial) : This Mozilla tutorial describes how to use the canvas element to draw WebGL graphics, starting with the basics.
    - #### Graphics API: WebGPU <a name="Graphics-WebGPU"></a>
        - :earth_americas: [Dawn](https://dawn.googlesource.com/dawn) : Google's open-source and cross-platform implementation of the work-in-progress WebGPU standard.
        - :earth_americas: [WebGPU](https://github.com/gpuweb/gpuweb/wiki/Implementation-Status) [:octocat:](https://github.com/gpuweb/gpuweb) : Next generation web API that exposes modern computer graphics capabilities, specifically Direct3D 12, Metal, and Vulkan, for performing rendering and computation operations on the GPU.
        - :earth_americas: [WebGPU Demos](https://webkit.org/demos/webgpu/) : Apple's a collection of simple WebGPU examples. They should work in the latest WebKit builds and Safari Technology Preview release.
    - #### Platform: XNA <a name="Graphics-XNA"></a>
        - :books: [RB Whitaker's Wiki](http://rbwhitaker.wikidot.com/) : Great C# learning resource, amazing [XNA Tutorials](http://rbwhitaker.wikidot.com/xna-tutorials), [MonoGame Tutorials](http://rbwhitaker.wikidot.com/monogame-tutorials), and more.
        - :books: [XNA Game Studio Archive](https://github.com/SimonDarksideJ/XNAGameStudio) : :fire: Required visit for [MonoGame](https://www.monogame.net) / [FNA](https://fna-xna.github.io) developers. Amazing [XNA](https://en.wikipedia.org/wiki/Microsoft_XNA) resource. Contains the XNA Educational Library, Shawn Hargreave's blog, the Ziggyware tutorials and the excellent Riemer's tutorial series.
    - #### Shaders <a name="Graphics-Shaders"></a>
        _see [Shaders](#Topic-Shaders)_

- ### Engine Development
    - #### Blog Articles <a name="Engine-Blog-Articles"></a>
        - :books: [3D Game Engine Programming](https://www.3dgep.com) : Helping you build your dream game engine.
        - :books: [How to Become a Game Engine Developer](https://www.haroldserrano.com/blog/how-to-become-a-game-engine-developer) : Short and simple starting point on game engine development. 
    - #### Books <a name="Engine-Books"></a>
        - :books: [Game Engine Architecture](https://www.gameenginebook.com) : Covers both the theory and practice of game engine software development, bringing together complete coverage of a wide range of topics.
    
- ### Game Development
    - #### Awesome Collections <a name="Game-Development-Awesome"></a>
        - :books: [Awesome Gamedev](https://github.com/Calinou/awesome-gamedev#readme) : Collection of free software and free culture resources for making amazing games.
        - :books: [GameDev-Resources](https://github.com/Kavex/GameDev-Resources) : Wonderful list of Game Development resources.
        - :books: [Magictools](https://github.com/ellisonleao/magictools#readme) : List of Game Development resources to make magic happen.
        - :earth_americas: [Open Source Libraries](https://opensourcelibs.com) : Massive collection of the world's best open source software.
    - #### Books <a name="Game-Development-Books"></a>
        - :books: [Game Programming Patterns](https://gameprogrammingpatterns.com) : Book that features a collection of patterns found in games that make code cleaner, easier to understand, and faster.
    - #### Developer Portals <a name="Game-Development-Portals"></a>
        - :earth_americas: [GameDev.net](https://www.gamedev.net) : Huge resource for game development with forums, tutorials, blogs, projects, portfolios, news, and more.
        - :earth_americas: [GameFromScratch.com](https://gamefromscratch.com) : Game development news, tutorials and so much more.
        - :earth_americas: [itch.io](https://itch.io) : Platform to host, showcase, promote, buy and sell games and game development resources.

- ### Programming
    - :books: [Big-O Cheat Sheet](https://www.bigocheatsheet.com) : This webpage covers the space and time Big-O complexities of common algorithms used in Computer Science.
    - :earth_americas: [Deadlock Empire](https://deadlockempire.github.io/#menu) : Interactive tutorial to master threads and concurrency.
    - :books: [Every Programmer Should Know](https://github.com/mtdvio/every-programmer-should-know) : Collection of (mostly) technical things every software developer should know.
    - :books: [Games of Coding](https://github.com/michelpereira/awesome-games-of-coding#readme) : Awesome list of games that teach you a programming language.
    - :earth_americas: [Geeks for Geeks](https://www.geeksforgeeks.org) : Free tutorials, articles, online and classroom courses, coding competitions, job opportunities and more.
    - :books: [Learn to Program](https://github.com/karlhorky/learn-to-program#readme) : Educational resources to learn to program.
    - :books: [TIOBE Index](https://www.tiobe.com/tiobe-index/) : Indicator of the popularity of programming languages. The index is updated once a month.

- ### Topics
    _see [Specialty Topics](#Specialty-Topics)_        


<br><br>


## Libraries
_Language specific game engine development libraries / frameworks / code_

- ### Basic
    - #### - Language - <a name="Basic-Language"></a>
        - :tada: [Basics Page](http://basic.mindteq.com/index.php?i=popular) : Comprehensive list of BASIC languages.
    - #### App Framework <a name="Basic-App-Framework"></a>
        - :moneybag: [Basic for Qt](https://www.q7basic.org/index.html) : (formerly Q7Basic) Multi-platform BASIC programming language and environment, built on top of [Qt](https://www.qt.io).
        - :tada: [QB64](https://qb64.org) [:octocat:](https://github.com/QB64Team/qb64) : Modern extended BASIC + OpenGL language that retains QB4.5 / QBasic compatibility and compiles native binaries for Windows, Linux and macOS.
        - :books: [Visual Basic](https://docs.microsoft.com/en-us/dotnet/visual-basic/) : Object-oriented programming language developed by Microsoft. Using Visual Basic makes it fast and easy to create type-safe .NET apps.
    - #### Game Framework <a name="Basic-Game-Framework"></a>
        - :tada: [Dark Basic](https://www.thegamecreators.com/product/dark-basic-pro-open-source) [:octocat:](https://github.com/TheGameCreators/Dark-Basic-Pro) : Open source BASIC programming language for creating Windows applications and games.

<br>

- ### C
    - #### - Language - <a name="C-Language"></a>
        - :books: [Learn C Programming](https://www.programiz.com/c-programming) : Excellent C tutorials that will guide you to learn C programming one step at a time.
    - #### - Language: Awesome Collections - <a name="C-Language-Awesome"></a>
        - :star: [Cute Headers](https://github.com/RandyGaul/cute_headers) : Collection of cross-platform one-file C/C++ libraries with no dependencies, primarily used for games by [Randy Gaul](https://github.com/RandyGaul). 
        - :star: [libs](https://github.com/mattiasgustavsson/libs) : Single-file public domain libraries for C/C++ by [Mattias Gustavsson](https://github.com/mattiasgustavsson).
        - :star: [Pico Headers](https://github.com/empyreanx/pico_headers) : Single-header, cross-platform libraries for game development, written in C by [Empyreanx](https://github.com/empyreanx).
        - :books: [Single File Libs](https://github.com/nothings/single_file_libs) : Amazing collection of single file C/C++ libraries compiled from many authors.
        - :star: [stb](https://github.com/nothings/stb) : :fire: The original and amazing stb single-file public domain libraries for C/C++ by [Sean Barrett](https://github.com/nothings).
    - #### App Framework <a name="C-App-Framework"></a>
        - :tada: [entrypoint](https://github.com/jimon/entrypoint) : Lightweight entry point for games.
        - :tada: [glfw](https://www.glfw.org) [:octocat:](https://github.com/glfw/glfw) : Cross-platform, simple API for creating windows, OpenGL / Vulkan contexts and surfaces, receiving input and events.
        - :tada: [raylib](https://www.raylib.com) [:octocat:](https://github.com/raysan5/raylib) : Simple and easy-to-use library to enjoy 2D / 3D videogame programming.
        - :tada: [SDL](https://libsdl.org) [:octocat:](https://github.com/libsdl-org/SDL) : :fire: Classic, cross-platform development library designed to provide low level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL, Direct3D and Metal.
        - :tada: [Sokol](https://floooh.github.io/sokol-html5/) [:octocat:](https://github.com/floooh/sokol) : :fire: Top notch cross-platform, single file header libraries that include a phenomenal graphics abstraction api, windowing, file handling, audio and more. Excellent!!        
    - #### Audio <a name="C-Audio"></a>
        - :star: [miniaudio](https://miniaud.io) [:octocat:](https://github.com/mackron/miniaudio) : Single file audio playback and capture library written in C.
        - :tada: [SDL_mixer](https://libsdl.org/projects/SDL_mixer/) [:octocat:](https://github.com/libsdl-org/SDL_mixer) : Audio mixer that supports various file formats for [SDL](https://libsdl.org).
        - :tada: [SoLoud](http://sol.gfxile.net/soloud/) [:octocat:](https://github.com/jarikomppa/soloud)
    - #### Entity Component System <a name="C-Entity-Component-System"></a>
        - :tada: [flecs](https://github.com/SanderMertens/flecs) : Fast and lightweight Entity Component System that lets you build games and simulations with millions of entities written in C99.
    - #### File Formats <a name="C-File-Formats"></a>
        - :tada: [assimp](https://www.assimp.org) [:octocat:](https://github.com/assimp/assimp) : The Open Asset Importer Library. Loads 40+ 3D file formats into one unified and clean data structure.
        - :tada: [cgltf](https://github.com/jkuhlmann/cgltf) : Single-file glTF 2.0 loader and writer written in C99.
        - :star: [dr_libs](https://github.com/mackron/dr_libs) : Single file audio decoding libraries for C/C++.
        - :tada: [libspng](https://github.com/randy408/libspng) : Simple, modern libpng alternative.
        - :tada: [miniz](https://github.com/richgel999/miniz) : Single C source file drop-in replacement for zlib's most used API's (libpng and libzip).
        - :tada: [OBJ GL Loader v2](https://github.com/karolek471/objgl) : Quite fast wavefront OBJ loader for OpenGL.
        - :tada: [PL_MPEG](https://github.com/phoboslab/pl_mpeg) : Single file C library for decoding MPEG1 Video and MP2 Audio.
        - :star: [stb_vorbis](https://github.com/nothings/stb/blob/master/stb_vorbis.c) : Ogg Vorbis audio decoder.
    - #### File System <a name="C-File-System"></a>
        - :tada: [hexembed](https://github.com/codeplea/hexembed) : Small utility to help embed files in C/C++ programs in an easy, cross-platform way.
        - :star: [incbin](https://github.com/graphitemaster/incbin) : Include binary and text files in your C/C++ applications with ease.
        - :tada: [PhysicsFS](http://icculus.org/physfs/) [:octocat:](https://github.com/icculus/physfs) : A portable, flexible file i/o abstraction, provides abstract access to various archives.
        - :star: [Where Am I](https://github.com/gpakosz/whereami) : Drop-in, multi platform, two file library to locate the current executable and the current module on the file system.
    - #### Fonts <a name="C-Fonts"></a>
        - :tada: [Font Stash](https://github.com/memononen/fontstash) : Light-weight library that uses [stb_truetype](https://github.com/nothings/stb/blob/master/stb_truetype.h) to render fonts on demand to a texture atlas.
        - :tada: [IconFontCppHeaders](https://github.com/juliettef/IconFontCppHeaders) - C, C++ headers and C# classes for icon fonts Font Awesome, Fork Awesome, Google Material Design icons, Kenney game icons and Fontaudio.
        - :tada: [msdf-c](https://github.com/eg-z/msdf-c) : Pure C multi-channel signed distance field generator.
        - :star: [stb_truetype](https://github.com/nothings/stb/blob/master/stb_truetype.h) : Single header file library that processes TrueType font files.
        - :tada: [vertext](https://github.com/kevinmkchin/vertext) : Single-header C library for generating vertices for rendering text, requires [stb_truetype](https://github.com/nothings/stb/blob/master/stb_truetype.h).
    - #### Game Engine w/Editor <a name="C-Game-Engine"></a>
        - :star: [AVA](https://github.com/r-lyeh/AVA) : Tiny, minimalistic 3D game engine in C.
    - #### Game Framework <a name="C-Game-Framework"></a>
        - :star: [FWK](https://raw.githack.com/r-lyeh/FWK/master/art/docs/docs.html) [:octocat:](https://github.com/r-lyeh/FWK) : 3D game framework in C.        
    - #### Geometry <a name="C-Geometry"></a>
        - :tada: [blob](https://github.com/BlockoS/blob) : Single header implementation of a contour tracing algorithm
        - :tada: [Marching Squares](https://prideout.net/marching-squares) [:octocat:](https://github.com/prideout/par/blob/master/par_msquares.h) : Converts grayscale images, or 8-bit color images, into triangles.
        - :tada: [Octasphere](https://prideout.net/blog/octasphere/) [:octocat:](https://github.com/prideout/par/blob/master/par_octasphere.h) : Tiny malloc-free library that generates triangle meshes for spheres, rounded boxes, and capsules.
        - :tada: [par_shapes](https://prideout.net/shapes) [:octocat:](https://github.com/prideout/par/blob/master/par_shapes.h) : Simple C library for creation and manipulation of triangle meshes including platonic solids, spheres and more.
        - :tada: [par_streamlines](https://prideout.net/blog/par_streamlines/) [:octocat:](https://github.com/prideout/par/blob/master/par_streamlines.h) : Library for triangulating wide/thick lines, Béziers, and streamlines. [[Demo](https://github.com/prideout/streamlines_demo)]
    - #### Graphics: 2D <a name="C-Graphics-2D"></a>
        - :tada: [NanoVG](https://github.com/memononen/nanovg) : Antialiased 2D vector drawing library on top of OpenGL for UI and visualizations.
    - #### Graphics: 3D <a name="C-Graphics-3D"></a>
        - :tada: [Sokol Gfx](https://github.com/floooh/sokol/blob/master/sokol_gfx.h) [:octocat:](https://github.com/floooh/sokol) : Cross-platform, single header file graphics abstraction api, part of the larger, amazing [Sokol](https://floooh.github.io/sokol-html5/) library. [[Examples](https://floooh.github.io/sokol-html5) | [LearnOpenGL Examples, ported to Sokol](https://www.geertarien.com/learnopengl-examples-html5/)]
        - :tada: [Sokol Graphics Painter](https://github.com/edubart/sokol_gp) : Minimal modern efficient cross-platform 2D graphics painter (api) in C implemented using [Sokol](https://floooh.github.io/sokol-html5/) as the backend.
    - #### Gui <a name="C-Gui"></a>
        - :tada: [cimgui](https://github.com/cimgui/cimgui) : Thin c-api wrapper programmatically generated for the excellent C++ immediate mode gui [Dear ImGui](https://github.com/ocornut/imgui).
        - :tada: [NAppGUI](https://nappgui.com/en/home/web/home.html) [:octocat:](https://github.com/frang75/nappgui_src) : Professional, well documented SDK to build cross-platform desktop applications using C.
        - :tada: [Native File Dialog](https://github.com/mlabbe/nativefiledialog) : Tiny, neat library that portably invokes cross-platform native file open and save dialogs.
        - :tada: [Nuklear](https://immediate-mode-ui.github.io/Nuklear/doc/index.html) [:octocat:](https://github.com/Immediate-Mode-UI/Nuklear) : Single-header ANSI C immediate mode cross-platform GUI library.
    - #### Input <a name="C-Input"></a>
        - :tada: [libgamepad](https://github.com/mtwilliams/libgamepad) : Cross-platform library for gamepad input.
        - :tada: [Sokol Gamepad](https://github.com/floooh/sokol/pull/393/commits/26a9da9dafd4adb22a1ace0de0d2569da31ae427) : Branch with add on support for game pads in [Sokol](https://github.com/floooh/sokol).
    - #### Lighting <a name="C-Lighting"></a>
        - :star: [Light Mapper](https://github.com/ands/lightmapper) : Single-file library for lightmap baking by using your existing OpenGL renderer.
    - #### Math <a name="C-Math"></a>
        - :tada: [cglm](https://github.com/recp/cglm) : Highly optimized OpenGL math for C.
        - :star: [Handmade Math](https://github.com/HandmadeMath/Handmade-Math) : Simple math library for games and computer graphics.
        - :tada: [Kazmath](https://github.com/Kazade/kazmathv) : Math library targeted at games.
        - :tada: [raymath](https://github.com/raysan5/raylib/blob/master/src/raymath.h) : Math library included in the [raylib](https://www.raylib.com) game framework.
    - #### Physics <a name="C-Physics"></a>
        - :tada: [Chipmunk](https://chipmunk-physics.net) [:octocat:](https://github.com/slembcke/Chipmunk2D) : Fast and lightweight 2D game physics library. [[Docs](http://chipmunk-physics.net/release/ChipmunkLatest-Docs/)]
    - #### Scripting <a name="C-Scripting"></a>
        - :tada: [Duktape](https://github.com/svaarala/duktapev) : Embeddable Javascript engine with a focus on portability and compact footprint.
        - :tada: [JerryScript](https://jerryscript.net) [:octocat:](https://github.com/jerryscript-project/jerryscript) : Ultra-lightweight JavaScript engine for the Internet of Things.
        - :tada: [Lua](https://www.lua.org) [:octocat:](https://github.com/lua/lua) : Powerful, efficient, lightweight, embeddable scripting language.
        - :tada: [QuickJS](https://bellard.org/quickjs/) [:octocat:](https://github.com/bellard/quickjs) : Small and embeddable Javascript engine.
    
<br>

- ### C++ <a name="Cpp"></a>
    - #### - Language - <a name="Cpp-Language"></a>
        - :earth_americas: [C++ Papyrus](https://caiorss.github.io/C-Cpp-Notes/index.html) : Exploring C++ basic and advanced concepts and also modern C++ features with both small and reproducible C++ sample programs and interactive examples.
        - :earth_americas: [cppreference.com](https://en.cppreference.com/w/cpp) : Provide programmers with a complete online reference for the C and C++ languages and standard libraries.
        - :books: [Learn C++](https://www.learncpp.com) : :fire: Whether you’ve had any prior programming experience or not, the tutorials on this site will walk you through all the steps to write, compile, and debug your C++ programs, all with plenty of examples.
        - :books: [Modern Cpp Features](https://github.com/AnthonyCalandra/modern-cpp-features) : Cheatsheet of modern C++ language and library features.
    - #### - Language: Awesome Collections - <a name="Cpp-Language-Awesome"></a>
        - :books: [Awesome C++](https://github.com/fffaraz/awesome-cpp#readme) : Curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. 
        - :books: [Awesome C++ Game Dev](https://github.com/Caerind/AwesomeCppGameDev#readme) : Curated list of awesome C++ (mainly) things for Game Development.
        - :tada: [Boost Libraries](https://www.boost.org) [:octocat:](https://github.com/boostorg) : Free peer-reviewed portable C++ source libraries, that work well with the C++ Standard Library. Basically an extension of the STL, many Boost libaries go on to become part of the STL.
        - :books: [Gamedev Libraries](https://github.com/raizam/gamedev_libraries) : Collection of open source C/C++ libraries for game development.
        - :books: [Inqlude](https://inqlude.org) : Comprehensive listing of all existing libraries for developers of applications using the [Qt](https://www.qt.io) toolkit.
        - :books: [List of Open Source C++ Libraries](https://en.cppreference.com/w/cpp/links/libs) : Comprehensive list of open source C++ libraries from [cppreference.com](https://en.cppreference.com/w/).
        - :books: [NVIDIA GameWorks](https://github.com/NVIDIAGameWorks) : NVIDIA Technologies for game and application developers.
    - #### - Language: Cross-Platform - <a name="Cpp-Language-Cross-Platform"></a>
        - :earth_americas: [emscripten](https://emscripten.org) [:octocat:](https://github.com/emscripten-core/emscripten) : The C/C++ to Javascript (WebAssembly) compiler.
    - #### App Framework <a name="Cpp-App-Framework"></a>
        - :tada: [SFML](https://www.sfml-dev.org/index.php) [:octocat:](https://github.com/SFML/SFML) : Simple, fast, cross-platform and object-oriented multimedia API. It provides access to windowing, graphics, audio and network.
    - #### Animation <a name="Cpp-Animation"><a/>
        - :tada: [ozz-animation](http://guillaumeblanc.github.io/ozz-animation/) [:octocat:](https://github.com/guillaumeblanc/ozz-animation) : Open source skeletal animation library and toolset.
        - :tada: [Tweeny](https://mobius3.github.io/tweeny/) [:octocat:](https://github.com/mobius3/tweeny) : Inbetweening library designed for the creation of complex animations for games and other beautiful interactive software.
    - #### Audio <a name="Cpp-Audio"><a/>
        - :moneybag: [irrKlang](https://www.ambiera.com/irrklang/) : High level 2D and 3D cross-platform (Windows, macOS, Linux) sound engine and audio library.
        - :moneybag: [Juce](https://juce.com) : The leading framework for multi-platform audio applications.
        - :lock: [OpenAL Soft](https://github.com/kcat/openal-soft) : Software implementation of the OpenAL 3D audio API.
        - :tada: [PortAudio](http://www.portaudio.com) [:octocat:](https://github.com/PortAudio/portaudio) : Free, cross-platform, open-source, audio I/O library.
    - #### Entity Component System <a name="Cpp-Entity-Component-System"></a>
        - :tada: [EntityX](https://github.com/alecthomas/entityx) : Fast, type-safe C++ Entity-Component system.
        - :tada: [Entt](https://github.com/skypjack/entt) : Gaming meets modern C++, a fast and reliable entity component system.
    - #### Fonts <a name="Cpp-Fonts"></a>
        - :tada: [HarfBuzz](https://harfbuzz.github.io) [:octocat:](https://github.com/harfbuzz/harfbuzz) : Text shaping library, allows programs to convert a sequence of Unicode input into properly formatted and positioned glyph output—for any writing system and language.
        - :moneybag: [Slug](http://sluglibrary.com) : For rendering high-quality, resolution-independent text and vector graphics in 3D applications on the GPU.
    - #### File Formats <a name="Cpp-File-Formats"></a>
        - :star: [jpeg-compressor](https://github.com/richgel999/jpeg-compressor) : Small (~1000 lines), easy to use public domain single library that writes baseline JPEG compressed images.
        - :tada: [tinydng](https://github.com/syoyo/tinydng) : Header only DNG / TIFF loader and writer.
        - :tada: [tinyexr](https://github.com/syoyo/tinyexr) : Tiny OpenEXR image loader/saver library.
        - :tada: [tinygltf](https://github.com/syoyo/tinygltf) : Header only C++11 tiny glTF 2.0 library.
        - :tada: [tinyobjloader](https://github.com/tinyobjloader/tinyobjloader) : Tiny but powerful single file wavefront obj loader.
    - #### Game Engine w/Editor <a name="Cpp-Game-Engine"></a>
        - :tada: [Ethereal Engine](https://github.com/volcoma/EtherealEngine) : Cross-platform C++ game engine and editor.
        - :tada: [Esenthel](https://esenthel.com/) [:octocat:](https://github.com/Esenthel/EsenthelEngine) : Cross-platform feature-packed open source engine. Easy to use. In development since the year 2000.
        - :tada: [ezEngine](http://ezengine.net/index.html) [:octocat:](https://github.com/ezEngine/ezEngine) : Open source game engine in active development. [[Editor Info](http://ezengine.net/pages/getting-started/editor-overview.html)]
        - :tada: [Irrlicht](https://irrlicht.sourceforge.io) [:octocat:](https://sourceforge.net/projects/irrlicht/) : Cross-platform 3D engine written in C++ worked on for nearly 2 decades.
        - :tada: [Lumix Engine](https://github.com/nem0/LumixEngine) : Yet another C++ open source 3D game engine with an [Dear ImGui](https://github.com/ocornut/imgui) based editor.
        - :lock: [neoGFX](https://neogfx.org) [:octocat:](https://github.com/i42output/neogfx) : Cross-platform GPU-oriented C++ application / game framework.
        - :tada: [Polycode](http://polycode.org/features/) [:octocat:](https://github.com/ivansafrin/Polycode) : Cross-platform framework for creative code. Nice editor.
        - :tada: [Torque 3D](https://torque3d.org/torque3d/) [:octocat:](https://github.com/GarageGames/Torque3D) : High performance 3D engine built on [Forge](https://github.com/ConfettiFX/The-Forge).
        - :lock: [UPBGE](https://upbge.org) [:octocat:](https://github.com/UPBGE/upbge) : Blender game engine. Forked from [Blender](https://www.blender.org).
    - #### Game Framework <a name="Cpp-Game-Framework"></a>
        - :tada: [Acid](https://github.com/EQMG/Acid) : Open-source, cross-platform game engine written in modern C++17 and structured to be fast, simple, and extremely modular.
        - :tada: [Cocos2d-x](https://www.cocos.com/en/cocos2dx) [:octocat:](https://github.com/cocos2d/cocos2d-x) : Provides rendering, gui, audio, network, physics, user input, etc. Widely used in game development and application construction.
        - :tada: [Defold](https://defold.com) [:octocat:](https://github.com/defold/defold) : Open sourced by King. Free to use game engine for development of desktop, mobile and web games.
        - :lock: [Fireworks Engine](https://github.com/Pikachuxxxx/Fireworks-Engine) : Lightweight sandbox game engine using OpenGL for additional customisation and quick prototyping.
        - :tada: [Halley](https://github.com/amzeratul/halley) : Lightweight game engine written in C++17. It has been used to ship Wargroove, a turn-based strategy game, on desktop and consoles.
        - :tada: [LOVE](https://love2d.org) [:octocat:](https://github.com/love2d/love) : LÖVE is an awesome 2D game framework for writing game code with Lua.
        - :tada: [ORX](http://orx-project.org) [:octocat:](https://github.com/orx/orx) : Orx is a 2.5D data-driven game development engine.
        - :tada: [Oryol](http://floooh.github.io/oryol/) [:octocat:](https://github.com/floooh/oryol) : Small, portable and extensible C++ 3D coding framework.
        - :star: [Ouzel](https://github.com/elnormous/ouzel) : Public domain C++ game engine mainly targeted for development of 2D games.
        - :tada: [Panda3D](https://www.panda3d.org) [:octocat:](https://github.com/panda3d/panda3d) : Powerful, mature cross-platform game engine for Python and C++, developed by Disney and CMU.
        - :tada: [Solar2D](https://solar2d.com) [:octocat:](https://github.com/coronalabs/corona) : (Previously known as Corona) Focus on ease of iterations and usage.
        - :tada: [two](https://github.com/hugoam/two) : C++ toolkit for rapid development of live graphical apps and games.
        - :tada: [Urho3D](https://urho3d.io) [:octocat:](https://github.com/urho3d/Urho3D) : Free lightweight, cross-platform 2D and 3D game engine.
        - :money_with_wings: [Valve Source SDK](https://developer.valvesoftware.com/wiki/Source_SDK_2013) [:octocat:](https://github.com/ValveSoftware/source-sdk-2013) : The 2013 edition of the Source SDK by [Valve Software](https://www.valvesoftware.com/). [[Info](https://en.wikipedia.org/wiki/Source_(game_engine))]
    - #### Geometry <a name="Cpp-Geometry"></a>
        - :tada: [CinoLib](https://github.com/mlivesu/cinolib) : Header only C++ library for processing polygonal and polyhedral meshes.
        - :tada: [Delabella](https://github.com/msokalski/delabella) : Super stable 2D delaunay triangulation.
        - :tada: [delaunator-cpp](https://github.com/soerendd/delaunator-cpp) : Really fast C++ library for Delaunay triangulation of 2D points.
        - :lock: [Easy3D](https://github.com/LiangliangNan/Easy3D) : Easy-to-use and efficient library for 3D modeling, geometry processing, and rendering.
        - :tada: [Extrude](https://github.com/stevinz/extrude) : Converts 2D images into 3D extruded meshes.
        - :tada: [Geometric Tools](https://www.geometrictools.com/index.html) : Collection of source code for computing in the fields of mathematics, geometry, graphics, image analysis and physics written in C++ 14.
        - :tada: [GeometronLib](https://github.com/LukasBanana/GeometronLib) : Generates meshes for basic 3D geometric shapes (cube / sphere / cylinder / capsule and more) and handles ray / geometry intersection.
        - :lock: [libigl](https://libigl.github.io) [:octocat:](https://github.com/libigl/libigl) : Simple C++ geometry processing library.
        - :tada: [meshoptimizer](https://github.com/zeux/meshoptimizer) : Mesh optimization library that makes meshes smaller and faster to render.
        - :tada: [Polygon Mesh Processing Library](http://www.pmp-library.org) [:octocat:](https://github.com/pmp-library/pmp-library) : Modern C++ open-source library for processing and visualizing polygon surface meshes.
        - :tada: [PolyPartition](https://github.com/ivanfratric/polypartition) : Lightweight C++ library for 2D polygon partition and triangulation.
        - :star: [RamerDouglasPeucker](https://gist.github.com/TimSC/0813573d77734bcb6f2cd2cf6cc7aa51) - 2D implementation of the Ramer-Douglas-Peucker algorithm (reduces number of points in a line).
        - :tada: [Recast & Detour](https://github.com/recastnavigation/recastnavigation) : Navigation-mesh toolset for games.
        - :tada: [Seam-aware Decimater](https://github.com/songrun/SeamAwareDecimater) : Simplifies a mesh while preserving its UV's boundary, based on this paper, [Seamless](https://cragl.cs.gmu.edu/seamless/).
        - :tada: [Spheres](https://github.com/caosdoar/spheres) : Four methods to create a sphere mesh.
        - :lock: [trimesh2](https://gfx.cs.princeton.edu/proj/trimesh2/) : Library and set of utilities for input, output, and basic manipulation of 3D triangle meshes.
        - :tada: [V-HACD](https://github.com/kmammou/v-hacd) : Decomposes a 3D surface into a set of "near" convex parts.
    - #### Graphics: 2D <a name="Cpp-Graphics-2D"></a>
        - :tada: [Blend2D](https://blend2d.com) [:octocat:](https://github.com/blend2d/blend2d) : High performance 2D vector graphics engine written in C++.
        - :tada: [C++ Bitmap Library](http://www.partow.net/programming/bitmap/index.html) [:octocat:](https://github.com/ArashPartow/bitmap) : Incredible bitmap loading and manipulation library.
        - :tada: [QNanoPainter](https://github.com/QUItCoding/qnanopainter) : OpenGL accelerated C++ vector drawing library for Qt, powered by [NanoVG](https://github.com/memononen/nanovg).
        - :tada: [Skia](https://skia.org) [:octocat:](https://github.com/google/skia) : Complete 2D graphic library for drawing Text, Geometries, and Images by [Google](https://www.google.com).
        - :tada: [vg-renderer](https://github.com/jdryg/vg-renderer) : Vector graphics renderer for [Bgfx](https://github.com/bkaradzic/bgfx), based on ideas from [NanoVG](https://github.com/memononen/nanovg) and ImDrawList ([Dear ImGui](https://github.com/ocornut/imgui)).
    - #### Graphics: 3D <a name="Cpp-Graphics-3D"></a>
        - :tada: [Bgfx](https://github.com/bkaradzic/bgfx) : Cross-platform, graphics API agnostic, rendering library.
        - :tada: [Diligent Engine](http://diligentgraphics.com/diligent-engine/) [:octocat:](https://github.com/DiligentGraphics/DiligentEngine) : Modern, lightweight cross-platform graphics API abstraction library.
        - :tada: [Ember](https://github.com/strah19/Ember) : Open source graphics framework for C++ using SDL2 and OpenGL.
        - :tada: [Filament](https://google.github.io/filament/) [:octocat:](https://github.com/google/filament) : Real-time physically-based renderer by [Google](www.google.com). It is mobile-first, but also multi-platform.
        - :tada: [Forge](https://github.com/ConfettiFX/The-Forge) : :fire: Cross-platform rendering framework supporting all major platforms and consoles.
        - :tada: [Horde3D](http://www.horde3d.org) [:octocat:](https://github.com/horde3d/Horde3D) : 3D rendering and animation engine. [[Scene Editor Info](http://horde3d.org/wiki/index.php?title=Horde3D_Scene_Editor)].
        - :tada: [LLGL](https://github.com/LukasBanana/LLGL) : Thin abstraction layer for the modern graphics APIs OpenGL, Direct3D, Vulkan, and Metal.
        - :tada: [magnum engine](https://magnum.graphics) [:octocat:](https://github.com/mosra/magnum) : Lightweight and modular C++11 graphics middleware for games and data visualization.
        - :tada: [Ogre](https://www.ogre3d.org) [:octocat:](https://github.com/OGRECave/ogre) : Scene-oriented, flexible 3D engine.
        - :tada: [Tungsten](https://github.com/tunabrain/tungsten) : High performance physically based renderer in C++11.
        - :tada: [Wicked Engine](https://wickedengine.net) [:octocat:](https://github.com/turanszkij/WickedEngine) : Open-source C++ engine focusing on modern rendering techniques and performance.
    - #### Gui <a name="Cpp-Gui"></a>
        - :tada: [Crazy Eddie's GUI](http://cegui.org.uk) [:octocat:](https://github.com/cegui/cegui) : Versatile, multi-platform library for creating graphical user interfaces for games and rendering applications.
        - :tada: [Dear ImGui](https://github.com/ocornut/imgui) : :fire: Bloat-free graphical user interface for C++ with minimal dependencies, compatible with nearly any 3D rednering library.
        - :lock: [FLTK](https://www.fltk.org) [:octocat:](https://github.com/fltk/fltk) : Cross-platform C++ GUI toolkit for Linux, Windows, and macOS. Provides modern GUI functionality without the bloat and supports 3D graphics via OpenGL.
        - :lock: [GTK](https://www.gtk.org) : The [GIMP](https://www.gimp.org) Toolkit, a multi-platform toolkit for creating graphical user interfaces. [[Repo](https://gitlab.gnome.org/GNOME/gtk/)] 
        - :books: [List of C++ UI Libraries](https://philippegroarke.com/posts/2018/c++_ui_solutions/) : Excellent list of C++ gui libraries, with pictures and descriptions.
        - :tada: [litehtml](http://www.litehtml.com) [:octocat:](https://github.com/litehtml/litehtml) : Lightweight HTML/CSS rendering engine.
        - :tada: [Nana](http://nanapro.org/en-us/) [:octocat:](https://github.com/cnjinhao/nana) : Cross-platform library for GUI programming in modern C++ style.
        - :star: [Portable File Dialogs](https://github.com/samhocevar/portable-file-dialogs) : Portable GUI dialogs library, C++11, single-header. Works on Windows, macOS or Linux.
        - :lock: [Qt](https://www.qt.io) : The industry standard. Most popular c++ cross-platform gui library there is. Open source and paid commercial licensing available.
        - :star: [RmlUi](https://github.com/mikke89/RmlUi) : Takes your HTML/CSS-like source files and turns them into vertices, indices and draw commands, and then you bring your own renderer to draw them. [[Docs](https://mikke89.github.io/RmlUiDoc/)]
        - :star: [Turbo Badger](https://github.com/fruxo/turbobadger) : Small footprint UI library for hardware accelerated games & applications. [[Oryol Example](https://floooh.github.io/oryol-samples/wasm/TurboBadgerDemo.html)]
        - :lock: [Wt](https://www.webtoolkit.eu/wt/) [:octocat:](https://github.com/emweb/wt) : Web GUI library in modern C++. Quickly develop highly interactive web UIs with widgets, without having to write a single line of JavaScript.
        - :lock: [wxWidgets](https://wxwidgets.org) [:octocat:](https://github.com/wxWidgets/wxWidgets) : Cross-platform C++ framework for writing advanced GUI applications using native controls.
    - #### Input <a name="Cpp-Input"></a>
        - :tada: [Gainput](http://gainput.johanneskuhlmann.de) [:octocat:](https://github.com/jkuhlmann/gainput) : Awesome C++ input library for your game. It's easy to use, open source and cross-platform.
        - :tada: [OIS](https://github.com/wgois/OIS) : Object oriented input system. Compatiable with many systems and operating systems.
        - :tada: [Oryol Input](https://github.com/floooh/oryol/tree/043683dcb3181beb64ae1c85ea76e4a4eb71c124/code/Modules/Input) : Input module from the [Oryol](http://floooh.github.io/oryol/) game framework.
    - #### Lighting <a name="Cpp-Lighting"></a>
        - :tada: [Thekla Atlas](https://github.com/Thekla/thekla_atlas) : Atlas generation tool, useful when generating light maps for meshes that do not have artist-supplied uv's.
        - :tada: [UVAtlas](https://github.com/Microsoft/UVAtlas) : DirectX library for creating and packing an isochart texture atlases.
    - #### Math <a name="Cpp-Math"></a>
        - :tada: [OpenGL Mathematics](https://glm.g-truc.net/0.9.9/index.html) [:octocat:](https://github.com/g-truc/glm) : Header only C++ mathematics library for graphics software.
    - #### Physics <a name="Cpp-Physics"></a>
        - :tada: [Box2D](https://box2d.org) [:octocat:](https://github.com/erincatto/box2d) : The original, classic, battle tested 2D physics engine for games. [[Docs](https://box2d.org/documentation/) | [Tutorials](http://www.iforce2d.net/b2dtut/introduction) | [Fixed Time-Step Implementation](https://www.unagames.com/blog/daniele/2010/06/fixed-time-step-implementation-box2d)]
        - :tada: [Bullet Physics](https://pybullet.org/wordpress/) [:octocat:](https://github.com/bulletphysics/bullet3) : 3D Physics simulation for games, visual effects, robotics and reinforcement learning.
        - :tada: [Liquid Fun](https://google.github.io/liquidfun/) [:octocat:](https://github.com/google/liquidfun) : An extension of [Box2D](https://box2d.org), it adds a particle based fluid and soft body simulation to the rigid body functionality of [Box2D](https://box2d.org).
        - :tada: [ReactPhysics3D](https://www.reactphysics3d.com) [:octocat:](https://github.com/DanielChappuis/reactphysics3d) : Physics engine library that can be used in 3D simulations and games.
        - :tada: [qu3e](https://github.com/RandyGaul/qu3e) : Compact, light-weight and fast 3D physics engine in C++. It is has been specifically created to be used in games.
    - #### Reflection <a name="Cpp-Reflection"></a>
        - :tada: [Boost.PFR](https://www.boost.org/doc/libs/master/doc/html/boost_pfr.html) [:octocat:](https://github.com/boostorg/pfr) : Very basic reflection C++14 library. Part of the [Boost Libraries](https://www.boost.org).
        - :tada: [Magic Enum](https://github.com/Neargye/magic_enum) : Header-only C++17 library provides static reflection for enums, work with any enum type without any macro or boilerplate code.
        - :tada: [Meta](https://github.com/skypjack/meta) : Header-only, non-intrusive and macro-free runtime reflection system in C++17.
        - :tada: [Nameof](https://github.com/Neargye/nameof) : Header-only C++17 library provides nameof macros and functions to simply obtain the name of a variable, type, function, macro, and enum.
        - :tada: [Ponder](https://billyquith.github.io/ponder/) [:octocat:](https://github.com/billyquith/ponder) : Expose C++17 classes and objects so they can used as data. Serialisation and Lua scripting supported.
        - :tada: [Reflect](https://github.com/stevinz/reflect) : Small, flexible, single header library for runtime reflection and meta data in C++11.
        - :tada: [RTTR](https://www.rttr.org) [:octocat:](https://github.com/rttrorg/rttr) : An open source library, which adds reflection to C++11.
    - #### Scripting <a name="Cpp-Scripting"></a>
        - :tada: [AngelScript](http://www.angelcode.com/angelscript/) : Cross-platform scripting library, follows the widely known syntax of C/C++, and uses common C/C++ datatypes for more efficient communication with the host application.
        - :lock: [ArkScript](https://arkscript-lang.dev) [:octocat:](https://github.com/ArkScript-lang/Ark) : Small, fast, functional and scripting language for C++ projects.
        - :tada: [ChaiScript](http://chaiscript.com) [:octocat:](https://github.com/ChaiScript/ChaiScript) : Embedded scripting language designed from to directly target C++17.
        - :tada: [GameMonkey Script](http://www.gmscript.com) [:octocat:](https://github.com/publicrepo/gmscript) : Embedded scripting language for C++ apps, tools and games.
        - :tada: [v8](https://v8.dev) [:octocat:](https://github.com/v8/v8) : Google’s open source high-performance JavaScript and WebAssembly engine, written in C++.
    - #### Serialization <a name="Cpp-Serialization"></a>
        - :tada: [Cap'n Proto](https://capnproto.org/capnp-tool.html) [:octocat:](https://github.com/capnproto/capnproto) : Insanely fast data interchange format and capability-based RPC (remote procedure call) system.
        - :tada: [cereal](https://github.com/USCiLab/cereal) : Header-only C++11 serialization library. Takes arbitrary data types and reversibly turns them into different representations, such as compact binary encodings, XML, or JSON.
        - :tada: [Cista++](https://cista.rocks) [:octocat:](https://github.com/felixguendling/cista) : Simple, high-performance, zero-copy C++ serialization & reflection library.
        - :tada: [FlatBuffers](https://google.github.io/flatbuffers/) [:octocat:]() : Efficient cross-platform serialization library for C, C++, C#, Go, Java, Kotlin, JavaScript, Lua, PHP, Python, Rust, Swift and more. It was originally created at Google for game development and other performance-critical applications.
        - :tada: [JSON for Modern C++](https://json.nlohmann.me) [:octocat:](https://github.com/nlohmann/json) : JSON for Modern C++.
        - :tada: [Protobuf](https://developers.google.com/protocol-buffers/) [:octocat:](https://github.com/protocolbuffers/protobuf) : Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data.
        - :tada: [RapidJSON](http://rapidjson.org) [:octocat:](https://github.com/Tencent/rapidjson/) : A fast JSON parser/generator for C++ with both SAX/DOM style API.
    - #### Terrain <a name="Cpp-Terrain"></a>
        - :tada: [Terra Forge 3D](https://jaysmito101.github.io/TerraForge3D/) [:octocat:](https://github.com/Jaysmito101/TerraForge3D) : Procedural 3D terrain generation and texturing tool.
    - #### Utility <a name="C-Utility"></a>
        - :tada: [any-lite](https://github.com/martinmoene/any-lite) : A C++17-like any, a type-safe container for single values of any type for C++98, C++11 and later in a single-file header-only library.
        - :tada: [EASTL](https://github.com/electronicarts/EASTL/) : Electronic Arts Standard Template Library. It is an extensive and robust implementation that has an emphasis on high performance.
        - :tada: [Parallel Hashmap](https://github.com/greg7mdp/parallel-hashmap) : Family of header-only, very fast and memory-friendly hashmap and btree containers.
        - :tada: [spdlog](https://github.com/gabime/spdlog) : Fast C++ logging library.
        - :tada: [tiny-process-library](https://gitlab.com/eidheim/tiny-process-library) [:octocat:](https://github.com/eidheim/tiny-process-library) : Small, platform independent library making it simple to create and stop new processes in C++.
        - :tada: [TinyXML-2](https://github.com/leethomason/tinyxml2) : Simple, small, efficient, C++ XML parser that can be easily integrated into other programs.
    - #### Visual Scripting <a name="Cpp-Visual-Scripting"></a>
        - :tada: [NodeEditor](https://github.com/paceholder/nodeeditor) : General-purpose [Qt](https://www.qt.io)-based node editor library aimed at graph-controlled data processing.
        - :tada: [QuickQanava](http://cneben.github.io/QuickQanava/index.html) [:octocat:](https://github.com/cneben/QuickQanava) : Library written in C++ 14 designed to display graphs and relational content in a [QtQuick](https://www.qt.io) application.

<br>

- ### C# <a name="CSharp"></a>
    - #### - Language - <a name="CSharp-Language"></a>
        - :books: [Dot Net Perls](https://www.dotnetperls.com) : Amazing reference for the C# language.
    - #### - Language: Cross-Platform - <a name="CSharp-Language-Cross-Platform"></a>
        - :earth_americas: [Blazor](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor) [:octocat:](https://github.com/dotnet/aspnetcore/blob/main/src/Components/README.md) : Microsoft's C# to Javascript (WebAssembly) technology.
        - :tada: [Mono](https://www.mono-project.com) [:octocat:](https://github.com/mono/mono) : Open source implementation of Microsoft's .NET Framework based on the ECMA standards for C# and the Common Language Runtime.
    - #### Audio <a name="CSharp-Audio"><a/>
        - :tada: [NAudio](https://github.com/naudio/NAudio) : Audio and MIDI library for .NET.
    - #### Entity Component System <a name="CSharp-Entity-Component-System"></a>
        - :tada: [LeoECS](https://github.com/Leopotam/ecs) : Fast ECS Framework powered by C# with optional integration to Unity.
    - #### Game Engine w/Editor <a name="CSharp-Game-Engine"></a>
        - :tada: [Duality](https://www.duality2d.net) [:octocat:](https://github.com/AdamsLair/duality) : Modular 2D game engine that provides its own visual editor. Built on C# and [OpenTK](https://opentk.net).
        - :tada: [Flat Red Ball](https://flatredball.com) [:octocat:](https://github.com/vchelaru/FlatRedBall) : 2D game engine built on [MonoGame](https://www.monogame.net). Various tools to help with game design. [[Gui Editor](http://vchelaru.github.io/Gum/)]
        - :tada: [Stride](https://stride3d.net) [:octocat:](https://github.com/stride3d/stride) : (formerly Xenko) C# game engine for realistic rendering and VR.
        - :money_with_wings: [Unity](https://unity.com) : Industry standard for game engines, uses C# for scripting.
    - #### Game Framework <a name="CSharp-Game-Framework"></a>
        - :tada: [FNA](https://fna-xna.github.io) [:octocat:](https://github.com/FNA-XNA/FNA) : Accuracy-focused reimplementation of the Microsoft XNA Game Studio 4.0 libraries.
        - :tada: [Monofoxe](https://github.com/Martenfur/Monofoxe) : Game engine designed to simplify working with, and built on [MonoGame](https://www.monogame.net).
        - :tada: [MonoGame](https://www.monogame.net) [:octocat:](https://github.com/MonoGame/MonoGame) : Framework for creating powerful cross-platform games in C#. The spiritual successor to XNA with thousands of titles shipped across desktop, mobile, and console platforms.
        - :tada: [Nez](https://github.com/prime31/Nez) : Feature-rich 2D framework that sits on top of [MonoGame](https://www.monogame.net). Provides a solid base for you to build a 2D game on.
        - :tada: [Protogame](https://github.com/RedpointGames/Protogame) : Cross-platform 2D / 3D game engine for C#, built on top of MonoGame.
    - #### Graphics: 3D <a name="CSharp-Graphics-3D"></a>
        - :tada: [OpenTK](https://opentk.net) [:octocat:](https://github.com/opentk/opentk) : Fast, portable, low-level C# bindings for OpenGL, OpenGL ES, OpenAL, and OpenCL. Runs on all major platforms and powers hundreds of apps, games, and scientific research programs. [[LearnOpenGL Examples, ported to OpenTK](https://github.com/opentk/LearnOpenTK)]
        - :tada: [Veldrid](https://veldrid.dev) [:octocat:](https://github.com/mellinoe/veldrid) : Cross-platform, graphics API-agnostic rendering and compute library for .NET.
    - #### Gui <a name="CSharp-Gui"></a>
        - :tada: [GeonBit.UI](https://github.com/RonenNess/GeonBit.UI) : UI system for [MonoGame](https://www.monogame.net) projects.
        - :tada: [MonoGame.Forms](https://github.com/BlizzCrafter/MonoGame.Forms) : The easiest way of integrating a MonoGame render window into your Windows Forms project.
        - :tada: [Myra](https://github.com/rds1983/Myra) : UI Library for [MonoGame](https://www.monogame.net), [FNA](https://fna-xna.github.io) and [Stride](https://stride3d.net).
    - #### Physics <a name="CSharp-Physics"></a>
        - :tada: [Aether Physics](https://github.com/tainicom/Aether.Physics2D) : Great 2D physics library with continuous collision detection, convex and concave polyons, collision groups, joints and much more.
        - :tada: [Velcro Physics](https://github.com/Genbox/VelcroPhysics) : (formerly Farseer Physics, original C# port of Box2D) High performance 2D collision detection system with realistic physics responses.
    - #### Utility <a name="CSharp-Utility"></a>
        - :tada: [Facepunch.Steamworks](https://github.com/Facepunch/Facepunch.Steamworks) : C# Steamworks implementation.

<br>

- ### Dart
    - #### - Language - <a name="Dart-Language"></a>
        - :tada: [Dart](https://dart.dev) [:octocat:](https://github.com/dart-lang/) : Official site. Client-optimized language for fast apps on any platform.
    - #### - Language: Awesome Collections - <a name="Dart-Language-Awesome"></a>
        - :books: [Awesome Dart](https://github.com/yissachar/awesome-dart) : Curated list of awesome Dart frameworks, libraries, and software.
    - #### App Framework <a name="Dart-App-Framework"></a>
        - :tada: [Flutter](https://flutter.dev) [:octocat:](https://github.com/flutter) : Open source framework by Google for building beautiful, natively compiled, multi-platform applications from a single codebase. [[Awesome Flutter](https://github.com/Solido/awesome-flutter)]
    - #### File Formats <a name="Dart-File-Formats"></a>
        - :tada: [image](https://github.com/brendan-duncan/image) : Library for decoding / encoding image formats, and image processing.
    - #### Game Framework <a name="Dart-Game-Framework"></a>
        - :tada: [Flame](https://flame-engine.org) [:octocat:](https://github.com/flame-engine/flame) : Minimalist Flutter based 2D game engine. [[Awesome Flame](https://github.com/flame-engine/awesome-flame#readme) | [Examples](https://examples.flame-engine.org/#/) | [Tutorials](https://tutorials.flame-engine.org/#/)]

<br>

- ### Haxe
    - #### - Language - <a name="Haxe-Language"></a>
        - :tada: [Haxe](https://haxe.org) [:octocat:](https://github.com/HaxeFoundation/haxe) : Official site. Very cool programming language used to produce cross-platform native code.
    - #### - Language: Awesome Collections - <a name="Haxe-Language-Awesome"></a>
        - :books: [Awesome Haxe](https://github.com/nadako/awesome-haxe#readme) : Awesome curated list of useful Haxe links.
        - :books: [Awesome Haxe Game Dev](https://github.com/Dvergar/awesome-haxe-gamedev#readme) : Awesome list of game dev resources for Haxe.
        - :books: [Haxelibs](https://lib.haxe.org/all) : List of every library uploaded to Haxe's website.
        - :books: [haxetink](https://github.com/haxetink) : Various add-on libraries for Haxe.
        - :earth_americas: [Snowkit](http://snowkit.org) [:octocat:](https://github.com/snowkit) : Collective of Haxe developers.
    - #### - Language: Blog Articles - <a name="Haxe-Language-Blog-Articles"></a>
        - :books: [Flash is dead, long live OpenFL](https://web.archive.org/web/20201112021925/https://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
        - :books: [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
    - #### - Language: Cross-Platform - <a name="Haxe-Language-Cross-Platform"></a>
        - :tada: [HashLink](https://hashlink.haxe.org) [:octocat:](https://github.com/HaxeFoundation/hashlink/) : Virtual machine for Haxe.
    - #### Animation <a name="Haxe-Animation"></a>
        - :tada: [Actuate](https://github.com/jgranick/actuate) : Flexible, fast "tween" library.
        - :tada: [DragonBones](https://github.com/openfl/dragonbones) : Runtime support for [DragonBones](https://www.dragonbones.com) skeletal animation.
        - :tada: [spine-hx](https://github.com/jeremyfa/spine-hx) : [Spine](https://esotericsoftware.com) runtime for Haxe.
    - #### App Framework <a name="Haxe-App-Framework"></a>
        - :tada: [Lime](https://lime.software) [:octocat:](https://github.com/haxelime/lime) : Flexible, lightweight layer for Haxe cross-platform developers.
        - :tada: [nme](https://github.com/haxenme/nme) : Cross-platform native backend for Haxe projects.
    - #### Entity Component System <a name="Haxe-Entity-Component-System"></a>
        - :tada: [ecx](https://github.com/eliasku/ecx) : Entity Component System framework for Haxe.
        - :tada: [GASM](https://github.com/HacksawStudios/GASM) : Framework agnostic Entity Component System for Haxe.
    - #### Game Engine w/Editor <a name="Haxe-Game-Engine"></a>
        - :tada: [Armory](https://armory3d.org) [:octocat:](https://github.com/armory3d/armory) : 3D game engine with full Blender integration.
        - :tada: [Away3D](https://www.away3d.com) [:octocat:](https://github.com/openfl/away3d) : Real-time 3D engine for OpenFL.
        - :tada: [flixel-studio](https://github.com/Dovyski/flixel-studio) : Embeddable, in-game editor for [HaxeFlixel](https://haxeflixel.com).
        - :tada: [Hide](https://github.com/heapsio/hide) : Extensible IDE for [Heaps](https://heaps.io).
        - :tada: [LDtk](https://ldtk.io) [:octocat:](https://github.com/deepnight/ldtk) : :fire: Very cool modern, lightweight and efficient 2D level editor.
        - :tada: [Starling](https://gamua.com/starling/) [:octocat:](https://github.com/openfl/starling) : Popular (Angry Birds) 2D game engine built on OpenFL. [[Editor](http://starlingbuilder.github.io)]
    - #### Game Framework <a name="Haxe-Game-Framework"></a>
        - :tada: [Citrus](http://citrusengine.com) [:octocat:](https://github.com/DaVikingCode/Citrus-Engine) : 2D and 3D ActionScript 3 based engine.
        - :tada: [Clay](https://github.com/clay2d/clay) : Cross-platform 2d game framework.
        - :tada: [HaxeFlixel](https://haxeflixel.com) [:octocat:](https://github.com/HaxeFlixel/flixel) : Cross-platform 2D game engine powered by Haxe and OpenFL.
        - :tada: [OpenFL](https://www.openfl.org) [:octocat:](https://github.com/openfl/openfl) : For creative expression on the web, desktop, mobile and consoles.
    - #### Graphics <a name="Haxe-Graphics"></a>
        - :tada: [Heaps](https://heaps.io) [:octocat:](https://github.com/HeapsIO/heaps) : :fire: High-performance cross-platform graphics engine by the creators of [Haxe](https://haxe.org).
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
        - :tada: [hexMachina](http://hexmachina.org) [:octocat:](https://github.com/DoclerLabs/hexCore) : Powerful modular MVC framework written in Haxe.
        - :tada: [hxColorToolkit](https://github.com/andyli/hxColorToolkit) : Library for color conversion and color scheme generation.
        - :tada: [HxMath](https://github.com/tbrosman/hxmath) : Game-oriented math library for the Haxe language.
        - :tada: [SteamWrap](https://github.com/larsiusprime/SteamWrap) : Haxe native extension for the Steam API.
    - #### Visual Scripting <a name="Haxe-Visual-Scripting"></a>
        - :tada: [haxe-blockly](https://github.com/nickmain/haxe-blockly) : Haxe wrapper for [Blockly](https://developers.google.com/blockly)

<br>

- ### Java
    - #### - Language - <a name="Java-Language"></a>
        - :earth_americas: [Java](https://dev.java) [:octocat:](https://github.com/openjdk) : Official site. General-purpose programming language typically compiled to bytecode that can run on any [Java virtual machine](https://en.wikipedia.org/wiki/Java_virtual_machine).
    - #### - Language: Awesome Collections - <a name="Java-Language-Awesome"></a>
        - :books: [Awesome Java](https://github.com/akullpp/awesome-java) : Curated list of awesome frameworks, libraries and software for the Java programming language.
    - #### - Language: Tutorials - <a name="Java-Language-Tutorials"></a>
        - :books: [Learn Java](https://dev.java/learn/) : Official docs and tutorials.
        - :books: [OpenGL & GLSL Tutorials](https://github.com/mattdesl/lwjgl-basics/wiki) : OpenGL / GLSL tutorials written for LWJGL and libGDX.
    - #### Game Framework <a name="Java-Game-Framework"></a>
        - :tada: [libGDX](https://libgdx.com) [:octocat:](https://github.com/libgdx/libgdx) : Cross-platform Java game development framework that is built on and adds functionality to [LWJGL](https://www.lwjgl.org). [[Awesome libGDX](https://github.com/rafaskb/awesome-libgdx#readme)]
        - :tada: [LWJGL](https://www.lwjgl.org) [:octocat:](https://github.com/LWJGL/lwjgl3) : Library that enables cross-platform access to popular native APIs useful in the development of graphics, audio, parallel computing and XR applications.

<br>

- ### Javascript
    - #### - Language - <a name="Javascript-Language"></a>
        - :books: [Eloquent JavaScript](https://eloquentjavascript.net) : Well written online book about modern Javascript programming, with examples.
    - #### - Language: Cross-Platform - <a name="Javascript-Language-Cross-Platform"></a>
        - :tada: [Electron](https://www.electronjs.org) [:octocat:](https://github.com/electron/electron) : Build cross-platform desktop apps with Javascript, HTML, and CSS.
        - :tada: [NW.js](https://nwjs.io) [:octocat:](https://github.com/nwjs/nw.js) : (previously known as node-webkit) Build cross-platform desktop apps with Javascript, HTML, and CSS. Lets you call all Node.js modules directly from DOM.
        - :tada: [React Native](https://reactnative.dev) [:octocat:](https://github.com/facebook/react-native) : Framework for building native applications using [React](https://reactjs.org).
        - :money_with_wings: [Ultralight](https://ultralig.ht/) : Based on WebKit — supports most modern HTML5, CSS, and JavaScript features while still remaining light and configurable. Currently available for Windows, macOS, Linux, and Xbox.
        - :tada: [WebView2](https://developer.microsoft.com/en-us/microsoft-edge/webview2/) : Microsoft Edge WebView2 control allows you to embed web technologies (HTML, CSS, and JavaScript) in your native apps. [[Docs](https://docs.microsoft.com/en-us/microsoft-edge/webview2/)]
        - :tada: [Window.js](https://windowjs.org) [:octocat:](https://github.com/windowjs/windowjs) : Open-source Javascript runtime for desktop graphics programming.
    - #### Game Engine w/Editor <a name="Javascript-Game-Engine"></a>
        - :tada: [A-Frame](https://aframe.io) [:octocat:](https://github.com/aframevr/aframe/) : Web framework for building 3D virtual reality (VR) experiences.
        - :tada: [Cocos Creator](https://www.cocos.com/en/creator) [:octocat:](https://github.com/cocos-creator/engine) : Cross-Platform 2D / 3D Game Creation Tool
        - :tada: [Pixelbox.js](https://pixwlk.itch.io/pixelbox) [:octocat:](https://github.com/cstoquer/pixelbox) : Sandbox framework to fast-prototype 2D tile-based games in HTML5 and JavaScript. [[Editor](https://pixwlk.itch.io/pixelbox)]
    - #### Game Framework <a name="Javascript-Game-Framework"></a>
        - :tada: [GDevelop](https://gdevelop-app.com) [:octocat:](https://github.com/4ian/GDevelop) : Full-featured, open source 2D game development software platform.
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
    - #### - Language - <a name="Python-Language"></a>
        - :earth_americas: [Python.org](https://www.python.org) : Programming language that lets you work quickly and integrate systems more effectively. [[Docs](https://www.python.org/doc/)]
    - #### - Language: Awesome Collections - <a name="Python-Language-Awesome"></a>
        - :books: [Awesome Python](https://github.com/vinta/awesome-python) : Curated list of awesome Python frameworks, libraries, software and resources.
    - #### - Language: Cross-Platform - <a name="Python-Language-Cross-Platform"></a>
        - :money_with_wings: [Anvil](https://anvil.works) : Full stack web apps with nothing but Python.
    - #### Game Framework <a name="Python-Game-Framework"></a>
        - :tada: [Arcade](https://api.arcade.academy/en/latest/) [:octocat:](https://github.com/pythonarcade/arcade) : Easy to use Python library for creating 2D arcade games.
        - :tada: [Panda3D](https://www.panda3d.org) [:octocat:](https://github.com/panda3d/panda3d) : Powerful, mature cross-platform game engine for Python and C++, developed by Disney and CMU.
        - :lock: [Pygame](https://www.pygame.org) [:octocat:](https://github.com/pygame/pygame) : Library for making multimedia applications (like games) using Python, built on top of the excellent [SDL](https://libsdl.org) library.
        - :tada: [Pygcurse](http://inventwithpython.com/pygcurse/) [:octocat:](https://github.com/asweigart/pygcurse) : [Curses-like](https://en.wikipedia.org/wiki/Curses_%28programming_library%29) module that can display a grid of text characters in a [Pygame](https://www.pygame.org) Surface Object. Provides an easy way to create text adventures, roguelikes, and console-style applications in Python.
    - #### Gui <a name="Python-Gui"></a>
        - :tada: [Kivy](https://kivy.org/) [:octocat:](https://github.com/kivy/kivy) : Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS.

<br>

- ### Rust
    - #### - Language - <a name="Rust-Language"></a>
        - :earth_americas: [Rust](https://www.rust-lang.org) [:octocat:](https://github.com/rust-lang) : Language empowering everyone to build reliable and efficient software. [[Docs](https://www.rust-lang.org/learn)]
    - #### - Language: Awesome Collections - <a name="Rust-Language-Awesome"></a>
        - :books: [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) : Curated list of Rust code and resources.
    - #### App Framework <a name="Rust-App-Framework"></a>
        - :tada: [Makepad](https://makepad.dev) [:octocat:](https://github.com/makepad/makepad) : Cross-platform, creative software development platform and native-rendering UI framework for Rust.
    - #### Game Framework <a name="Rust-Game-Framework"></a>
        - :tada: [Amethyst](https://amethyst.rs) [:octocat:](https://github.com/amethyst/amethyst) : Data-driven and data-oriented 2D / 3D game engine aiming to be fast and as configurable as possible.
        - :tada: [Bevy](https://bevyengine.org) [:octocat:](https://github.com/bevyengine/bevy) : :fire: Refreshingly simple data-driven 2D / 3D game engine built in Rust.
        - :tada: [macroquad](https://github.com/not-fl3/macroquad) : Simple and easy to use game library for Rust programming language, heavily inspired by [raylib](https://www.raylib.com).
    - #### Graphics: 3D <a name="Rust-Graphics-3D"></a>
        - :tada: [Kiss3D](http://kiss3d.org) [:octocat:](https://github.com/sebcrozet/kiss3d) : Keep it simple, stupid 3d graphics engine for Rust.
    - #### Physics <a name="Rust-Physics"></a>
        - :tada: [Rapier](https://rapier.rs) [:octocat:](https://github.com/dimforge/rapier) : 2D and 3D physics engines focused on performance.


<br><br>


## Specialty Topics
_Exploring specialty application / game engine / game development topics and features_

- ### AI / Pathfinding <a name="Topic-AI"></a>
    - :books: [Intro to AI](https://www.raywenderlich.com/2808-introduction-to-ai-programming-for-games) : Introduction to AI Programming for Games at [raywenderlich.com](https://www.raywenderlich.com).
    - :books: [Beginner's Guide to Game AI](https://www.gamedev.net/tutorials/programming/artificial-intelligence/the-total-beginners-guide-to-game-ai-r4942/) : Introduction to a range of concepts used in artificial intelligence for games at [gamedev.net](https://www.gamedev.net).

- ### Animation <a name="Topic-Animation"></a>
    - :books: [Skeletons and Inverse Kinematics](https://venturebeat.com/2017/08/09/character-animation-skeletons-and-inverse-kinematics/) : Basic and intermediate principles for using skeletons with inverse kinematics for character animation.

- ### Entity Component System <a name="Topic-ECS"></a>
    - :books: [A Simple Entity Component System](https://austinmorlan.com/posts/entity_component_system/) : Article that provides a basis for an eneity component system in C++.
    - :books: [Evolve Your Hierarchy](https://cowboyprogramming.com/2007/01/05/evolve-your-heirachy/) : Article that provides a solid overview of EC systems and why you should use them at [Cowboy Programming](https://cowboyprogramming.com).
    - :books: [Introduction to Component Based Architecture in Games](https://www.raywenderlich.com/2806-introduction-to-component-based-architecture-in-games) : Nice blog post about component based architecture at at [raywenderlich.com](https://www.raywenderlich.com).
    - :books: [Nomad Game Engine](https://savas.ca/nomad) [:octocat:](https://github.com/taurheim/NomadECS) : Series of articles building a basic entity component system from the ground up in C++.
    - :books: [What's an Entity System](http://entity-systems.wikidot.com) : Overview of component / entity systems and how they are used in game development.

- ### Fluid / Smoke <a name="Topic-Fluid"></a>
    - :books: [Fluid Simulation on the GPU](https://developer.nvidia.com/gpugems/gpugems/part-vi-beyond-triangles/chapter-38-fast-fluid-dynamics-simulation-gpu) : GPU Gems Chapter 38 - Method for fast, stable fluid simulation that runs entirely on the GPU.
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
        - :books: [Gleaner Heights: 2D Lighting](http://gleanerheights.blogspot.com/2017/05/lighting-in-2d-games-shader-glsl.html?m=1) : Simple introduction to 2D lighting in a game with GLSL.
        - :books: [Lighting a 2D Game](http://www.wholehog-games.com/devblog/2013/06/07/lighting-in-a-2d-game/) : Nice summary of techniques used in proper 2D lighting with diffuse lighting, self illumination and normal maps.
    - #### Lighting 3D
        - :books: [Basic Lighting](https://learnopengl.com/Lighting/Basic-Lighting) : Excellent basic 3D lighting article by [LearnOpenGL](https://learnopengl.com). There are many excellent more advanced follow-up articles on this site.
    - #### Shadows 2D
        - :books: [2D Pixel Perfect Shadows](https://github.com/mattdesl/lwjgl-basics/wiki/2D-Pixel-Perfect-Shadows) : An approach to 2D pixel-perfect lights/shadows using shaders.
        - :books: [2D Visibility](https://www.redblobgames.com/articles/visibility/) : Excellent interactive tutorial on 2D visibility. Written in Haxe and transpiled to Java, Javascript and C#.
        - :books: [Fast 2D shadows in Unity](https://www.gamedeveloper.com/programming/fast-2d-shadows-in-unity-using-1d-shadow-mapping) : Article about adapting traditional techniques from 3D rendering to achieve fast 2D shadows for a large number of light sources in the Unity game engine.
        - :books: [Sight & Light](https://ncase.me/sight-and-light/) [:octocat:](https://github.com/ncase/sight-and-light) : How to create 2D visibility/shadow effects for your game.
        - :books: [Symmetric Shadowcasting](https://www.albertford.com/shadowcasting/) : Tutorial on a common technique for calculating field of view.
    - #### Shadows 3D
        - :books: [Efficient Soft-Edged Shadows](https://developer.nvidia.com/gpugems/gpugems2/part-ii-shading-lighting-and-shadows/chapter-17-efficient-soft-edged-shadows-using) : GPU Gems 2 Chapter 17 - Efficient Soft-Edged Shadows Using Pixel Shader Branching.
        - :books: [Screen Space Shadows](https://panoskarabelas.com/posts/screen_space_shadows/) : Great exploration of screen space shadows.
        - :books: [Shadow Mapping](https://en.m.wikipedia.org/wiki/Shadow_mapping) : In depth explantion on [Wikipedia](https://en.m.wikipedia.org) of shadow mapping and the techniques used to acheive it.

- ### Particles
    - :books: [Particles](https://learnopengl.com/In-Practice/2D-Game/Particles) : Excellent particle article by [LearnOpenGL](https://learnopengl.com).
    - :books: [Soft Particles](https://keaukraine.medium.com/implementing-soft-particles-in-webgl-and-opengl-es-b968d61133b0) : Implementing soft particles in WebGL and OpenGL ES.

- ### Physics
    - #### General Resources
        - :books: [Fix Your Timestep!](https://gafferongames.com/post/fix_your_timestep/) - Article about the technique needed to keep stable the numerical integration performed by the physics simulation while running your video game with a variable frame-rate.
        - :books: [Game Physics from Scratch](https://brm.io/game-physics-for-beginners/) : If you're a game developer interested in learning about physics engines, these resources are a good place to start.
        - :books: [Intro to Physics](https://www.toptal.com/game/video-game-physics-part-i-an-introduction-to-rigid-body-dynamics) : Video Game Physics Tutorial - Part I: An Introduction to Rigid Body Dynamics.
        - :books: [Open Source Physics Engines](https://www.tapirgames.com/blog/open-source-physics-engines) : List of open source physics engines.
    - #### Platformer
        - :books: [Basic 2D Platformer Physics](https://gamedevelopment.tutsplus.com/series/basic-2d-platformer-physics--cms-998) : This article covers how to create a simple and robust physics system for a platformer game.
        - :books: [How to create 2D Physics Games](https://www.gamedeveloper.com/design/how-to-create-2d-physics-games-with-box2d-library) : Excellent article on how to use [Box2D](https://box2d.org) for 2D game topics ranging from shapes, water (metaballs), ropes, gravity, lines and vehicles.
        - :books: [Ledge Grabbing](https://gamedevelopment.tutsplus.com/tutorials/basic-2d-platformer-physics-part-4--cms-26046) : Tutorial on ledge grabbing in 2D platformer physics.
    - #### Ropes / Chains <a name="Topics-Physics-Ropes"></a>
        - :books: [Ropes in Contraption Maker](https://www.gamedeveloper.com/design/ropes-in-contraption-maker) : Short discussion about how to implement the physics of ropes in Contraption Maker.
        - :earth_americas: [Matter.js Chains](https://brm.io/matter-js/demo/#chains) [:octocat:](https://github.com/liabru/matter-js/blob/master/examples/chains.js) : Chains demo using the javascript library [Matter.js](https://brm.io/matter-js/).
    - #### Soft Body
        - :books: [Blob Physics](https://cowboyprogramming.com/2007/01/05/blob-physics/) : Using verlet physics to simulate blobs.
        - :books: [Box2D Soft Body Blobs](https://www.emanueleferonato.com/2012/09/21/step-by-step-creation-of-a-box2d-soft-body-blob/) : Step by step creation of a Box2D soft body blob.
    - #### Verlet Physics
        - :books: [Making a Verlet Physics Engine in JavaScript](https://betterprogramming.pub/making-a-verlet-physics-engine-in-javascript-1dff066d7bc5) : Taking a look under the hood of a 2D physics engine in Javascript.
    - #### Water <a name="Topics-Physics-Water"></a>
        - :books: [2D Water](https://prime31.github.io/water2d-part1/) : Modeling 2D water with springs.

- ### Scripting
    - :books: [Adding Languages to Game Engines](https://www.gamedeveloper.com/programming/adding-languages-to-game-engines) : How a self described "lazy programmer" built the powerful scripting language used in making Jedi Knight: Dark Forces 2.
    - :books: [Implementing a Scripting Engine](https://www.flipcode.com/archives/Implementing_A_Scripting_Engine-Part_1_Overview.shtml) : In depth series of articles about writting a scripting engine from scratch.
    - :books: [Embedded Scripting Languages](https://caiorss.github.io/C-Cpp-Notes/index.html) : Selection of embedded scripting languages and engines available as libraries.
    - :books: [List of Embedded Scripting Languages](https://github.com/dbohdan/embedded-scripting-languages) : List of reasonably mature open source embedded scripting languages to use in your application.
    - :books: [Scriptorium](https://github.com/r-lyeh-archived/scriptorium) : Game scripting languages benchmarked.

- ### Shaders <a name="Topic-Shaders"></a>
    - #### - General Resources -
        - :books: [3D Game Shaders For Beginners](https://lettier.github.io/3d-game-shaders-for-beginners/index.html) [:octocat:](https://github.com/lettier/3d-game-shaders-for-beginners) : :fire: Collection of shading techniques that will take your game visuals to new heights. Including adding textures, lighting, shadows, normal maps, glowing objects, ambient occlusion, reflections, refractions, and more!
        - :books: [Book of Shaders](https://thebookofshaders.com) [:octocat:](https://github.com/patriciogonzalezvivo/thebookofshaders) : :fire: This is a gentle step-by-step guide through the abstract and complex universe of [Fragment Shaders](https://www.khronos.org/opengl/wiki/Fragment_Shader).
        - :earth_americas: [Geeks3D Shader Library](https://www.geeks3d.com/shader-library/) : Fantastic collection of amazing shaders including post processing, lighting, utlities and more.
        - :earth_americas: [Shadertoy](https://www.shadertoy.com) : Build and share shaders online.
    - #### Bloom
        - :books: [LearnOpenGL Tutorial](https://learnopengl.com/Advanced-Lighting/Bloom) : Excellent presentation of the techniques used for bloom lighting presented in OpenGL.
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
    - #### Water <a name="Topics-Shaders-Water"></a>
        - :books: [2D Water Shader](https://rotatingcanvas.com/fragment-shader-to-simulate-water-surface-in-libgdx/) : GLSL fragment shader to simulate 2D water surface in [libGDX](https://libgdx.com).
    - #### Wireframe
        - :books: [Easy Wireframe Display](https://web.archive.org/web/20190220052115/http://codeflow.org/entries/2012/aug/02/easy-wireframe-display-with-barycentric-coordinates/) : Nice explanation with demo of rendering triangles as wireframe using [Barycentric Coordinates](https://en.wikipedia.org/wiki/Barycentric_coordinate_system).
        - :books: [Flat and Wireframe Shading](https://catlikecoding.com/unity/tutorials/advanced-rendering/flat-and-wireframe-shading/) : This tutorial covers how to add support for flat shading and showing the wireframe of a mesh using [Barycentric Coordinates](https://en.wikipedia.org/wiki/Barycentric_coordinate_system).

- ### Tiling
    - :books: [Auto Tile](https://gamedevelopment.tutsplus.com/tutorials/how-to-use-tile-bitmasking-to-auto-tile-your-level-layouts--cms-25673) : How to use tile bitmasking to auto-tile your level layouts.
    - :books: [Blob Tileset](http://www.cr31.co.uk/stagecast/wang/blob.html) : Great tutorial on 2D edge and corner matched tilesets.


<br><br>


## Tools / Software <a name="Tools"></a>
_Software to help with game engine / video game development_

- ### Animation <a name="Tools-Animation"></a>

- ### Audio Creation <a name="Tools-Audio"></a>
    - #### Music <a name="Tools-Audio-Music"></a>

    - #### Sound Effects <a name="Tools-Audio-Sound-Effects"></a>
        - :free: [Bfxr](https://www.bfxr.net) [:octocat:](https://github.com/increpare/bfxr) : The classic program of choice for many people looking to make sound effects for computer games.
        - :free: [ChipTone](https://sfbgames.itch.io/chiptone) : Excellent tool for generating sound effects.

- ### Color <a name="Tools-Color"></a>
    - :earth_americas: [Colormind](http://colormind.io) : Color scheme generator that can learn color styles from photographs, movies and popluar art.
    - :earth_americas: [COLOURlovers](https://www.colourlovers.com) : Creative community where people from around the world create and share colors, palettes and patterns.
    - :earth_americas: [Coolors](https://coolors.co) : Super fast color palette generator.
    - :earth_americas: [paletton](https://paletton.com) : Explore complementary colors on the color wheel.

- ### Drawing / Vector Editors <a name="Tools-Drawing"></a>

- ### Game Dev <a name="Tools-Game-Dev"></a>

- ### Image / Photo Editors <a name="Tools-Image"></a>

- ### Materials <a name="Tools-Materials"></a>

- ### Modeling <a name="Tools-Modeling"></a>

- ### Particles <a name="Tools-Particles"></a>

- ### Pixel Art <a name="Tools-Pixel-Art"></a>

- ### Sound <a name="Tools-Sound"></a>

- ### Textures <a name="Tools-Textures"></a>

- ### Voxel <a name="Tools-Voxel"></a>


<br><br>


## Video Game Assets
_Resources to help bring video games and game engines alive_

- ### Graphics <a name="Assets-Graphics"></a>
    - :money_with_wings: [Flaticon](https://www.flaticon.com) : Nice vector icons and stickers.
    - :money_with_wings: [Freepik](https://www.freepik.com) : High quality illustrations, photos, icons and presentation templates.
    - :free: [Kenny](https://www.kenney.nl/assets) : Amazing 2D and 3D CC0 1.0 game graphics and other assets.
    - :money_with_wings: [Mobile Game Graphics](https://mobilegamegraphics.com) : Nice collection of a mix of free and paid original 2D game graphics.
    - :free: [Open Game Art](https://opengameart.org) : Leading portal for free / public domain game art online.
    - :moneybag: [Shutterstock](https://www.shutterstock.com) : Millions of images, videos and music tracks.
    - :free: [Top Free Game Assets](https://itch.io/game-assets/free) : Top free game assets listed on [itch.io](https://itch.io).

- ### Materials <a name="Assets-Materials"></a>
    - :free: [ambientCG](https://ambientcg.com) : Public domain materials for physically based rendering.
    - :free: [pmndrs materials](https://market.pmnd.rs/materials) : Nice collection of public domain materials.

- ### Models <a name="Assets-Models"></a>
    - :free: [3D Models CC0](https://www.3dmodelscc0.com) : Free 3D models, all the 3D assets on this site are licensed as public domain.
    - :free: [pmndrs market](https://market.pmnd.rs) : Nice collection of public domain models.
    - :free: [Poly Pizza](https://poly.pizza) : Build something beautiful with thousands of free low poly models.
    - :books: [Retro3DGraphicsCollection](https://github.com/Miziziziz/Retro3DGraphicsCollection) : Compilation of game-ready retro style 3d graphic assets (think PS1) that are commercially usable with no attribution, share-alike, or such required.
    - :money_with_wings: [Sketchfab](https://sketchfab.com) : Huge library of 3D assets.

- ### Music <a name="Assets-Music"></a>
    - :money_with_wings: [Bensound](https://www.bensound.com/royalty-free-music) : Wonderful, original music tracks, free to use with attribution. Perfect for use in games.
    - :money_with_wings: [Incompetech](https://incompetech.com/wordpress/) : Nice collection of tracks. Use music for free with attribution or buy once and use forever.
    - :money_with_wings: [Melody Loops](https://www.melodyloops.com/music/free/) : Great mix of free and affordable music loops.
    - :money_with_wings: [Royalty Free Music Clips](https://www.royaltyfreemusicclips.com/pir/free_music_loops.shtml) : Huge collection of free and paid royalty free music tracks.
    - :money_with_wings: [Soundimage](https://soundimage.org/looping-music/) : Looping music tracks intended for videogame developers. All are free to use with attribution.

- ### Sound Effects <a name="Assets-Sound-Effects"></a>
    - :free: [freesound](https://freesound.org/browse/) : Community based archive of free sound effects.
    - :money_with_wings: [Free Sound Effects](https://www.freesoundeffects.com) : Large collection of sound effects.
    - :moneybag: [Soundsnap](https://www.soundsnap.com) : Professional sound effects library with hundreds of thousands of sounds, subscription based.

<br><br>

## Contributing

<br>

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
