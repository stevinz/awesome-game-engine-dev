<h1 align="center">
    <img width="1100" src="aged-title.png" alt="Awesome Game Engine Dev Logo"/>
</h1>

# Awesome Game Engine Development [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A list of awesome assets, libraries, and tools geared toward Game Engine Development. Specifically with an eye towards high-level, fully featured game engines (e.g., [Godot](https://godotengine.org) / [Unity](https://unity.com)). This includes things typically not found in a low-level game engine, game framework, or graphics library (e.g., [MonoGame](https://www.monogame.net) / [SDL](https://www.libsdl.org)). Most importantly a visual editor, but also things such as scipting support, physics integration, special effects, etc. This list currently favors programming core engine functionality in the following languages: C/C++, C#, Haxe, or Javascript. Of course, a game engine could be designed in [any language](https://en.wikipedia.org/wiki/List_of_programming_languages)!

<br>

### NOTE: This list is under development, it is still in draft state. Contributions will be welcome when the draft is complete, but are currently not accepted.

<br>

### License Legend
- Open Source Software
    - :star: - [Public Domain License](https://en.wikipedia.org/wiki/Public-domain-equivalent_license) ([CC0](https://creativecommons.org/publicdomain/zero/1.0/), [BOLA](https://blitiri.com.ar/p/bola/), [WTFPL](https://en.wikipedia.org/wiki/WTFPL), [Unlicense](https://en.wikipedia.org/wiki/Unlicense), etc.)
    - :tada: - [Permissive License](https://en.wikipedia.org/wiki/Permissive_software_license) ([MIT](https://en.wikipedia.org/wiki/MIT_License), [BSD](https://en.wikipedia.org/wiki/BSD_licenses), [ZLIB / LIBPNG](https://en.wikipedia.org/wiki/Zlib_License), [ISC](https://en.wikipedia.org/wiki/ISC_license), [Apache](https://en.wikipedia.org/wiki/Apache_License), etc.)
    - :lock: - [Copyleft License](https://en.wikipedia.org/wiki/Copyleft) ([CC](https://en.wikipedia.org/wiki/Creative_Commons_license), [GPL](https://en.wikipedia.org/wiki/GNU_General_Public_License) / [LGPL](https://en.wikipedia.org/wiki/GNU_Lesser_General_Public_License), [MPL](https://en.wikipedia.org/wiki/Mozilla_Public_License), etc.)
- Asset / Service / Tool
    - :free: - Free
    - :moneybag: - Paid
    - :money_with_wings: - Partially Free
- Other
    - :books: - Article
    - :earth_americas: - Website

:octocat: - Any item with an OctoCat has a GitHub repo, click on it to see the source code!

<br>

## Index
- [Game Development](#Game-Development)
    - [Collections](#Collections)
    - [Developer Portals](#Developer-Portals)
- [Game Engines](#Game-Engines)
    - [Popular](#Popular)
    - [AAA](#AAA)
    - [Commercial](#Commercial)
    - [Specialty](#Specialty)
- [Games](#Games)
- [How To](#How-To)
    - [Scripting](#Scripting)
- [Learning](#Learning)
    - [Game Engine Development](#Game-Engine-Development)
    - [Programming](#Programming)
- [Libraries](#Libraries)
    - [C/C++](#C++)
    - [C#](#C#)
    - [Haxe](#Haxe)
    - [Java](#Java)
    - [Javascript](#Javascript)
    - [Python](#Python)
- [Game Programming](#Game-Programming)
    - [AI](#AI)
- [Tools](#Tools)
    - [Image Editing](#Image-Editing)
    - [Modeling](#Modeling)
    - [Textures](#Textures)
- [Website](#Website)
- [Business](#Business)

<br>

## Game Development
_Helpful resources for game development_
- ### Collections
    - :books: [Gamedev](https://github.com/Calinou/awesome-gamedev#readme) : A collection of free software and free culture resources for making amazing games.
    - :books: [Graphics Libraries](https://github.com/jslee02/awesome-graphics-libraries#readme) : Awesome curated list of 3D graphics libraries and resources.
    - :books: [Magictools](https://github.com/ellisonleao/magictools#readme) : A list of Game Development resources to make magic happen.
- ### Developer Portals
    - :earth_americas: [itch.io](https://itch.io) : Platform to host, showcase, promote, buy and sell games and game development resources.

## Game Engines
_Production game engines to tinker with, explore, learn and inspire_
- ### Popular
    - :tada: [Godot](https://godotengine.org) [:octocat:](https://github.com/godotengine/godot#readme) : Feature-packed, open source engine. Excellent! [[Awesome Godot](https://github.com/godotengine/awesome-godot#readme)]
    - :money_with_wings: [Unity](https://unity.com) : Sets the bar for Game Engines. [[Awesome Unity](https://github.com/RyanNielson/awesome-unity)]
    - :money_with_wings: [Unreal Engine](https://www.unrealengine.com) : AAA game capable, photoreal visuals. [[Awesome UE4](https://github.com/insthync/awesome-ue4#readme)]
    - :books: [Wikipedia: List of Game Engines](https://en.wikipedia.org/wiki/List_of_game_engines) : Thorough list of game engines along with their platforms and licenses.
- ### AAA
    - :tada: [Amazon Lumberyard](https://aws.amazon.com/lumberyard/) [:octocat:](https://github.com/aws/lumberyard) : Free, open source AAA game engine deeply integrated with AWS and Twitch.
    - :moneybag: [C4 Engine](http://c4engine.com) : Modern console engine.
    - :money_with_wings: [CRYENGINE](https://www.cryengine.com) [:octocat:](https://github.com/CRYTEK/CRYENGINE) : Powerful real-time game development platform created by Crytek.
    - :money_with_wings: [Flax Engine](https://flaxengine.com) [:octocat:](https://github.com/FlaxEngine/FlaxEngine) : Modern 3D game engine written in C++ and C#. Stunning graphics, powerful scripts.
    - :moneybag: [FROSTBITE](https://www.ea.com/frostbite) : (by Electronic Arts) Cutting-Edge Games and Experiences.
    - :moneybag: [Gamebryo](http://www.gamebryo.com) : Complete toolset, flexible workflow, rapid prototyping.
    - :money_with_wings: [NeoAxis](https://www.neoaxis.com) [:octocat:](https://github.com/NeoAxis/NeoAxisEngine) : Versatile real-time platform for making 2D / 3D games and apps.
    - :tada: [O3DE](https://docs.o3de.org) [:octocat:](https://github.com/o3de/o3de/) : (Successor to Amazon Lumberyard) Multi-platform AAA-capable 3D engine to build cinema-quality 3D worlds, and high-fidelity simulations.
    - :moneybag: [Snowdrop Engine](https://www.massive.se/project/snowdrop-engine/) : (by Massive Entertainment) Enabling relatively small teams to create ambitious AAA games.
    - :money_with_wings: [Unigine](https://unigine.com) : Real-time 3D engine. Photorealistic graphics, large virtual worlds, C++ and C# API.
    - :free: [Wave Engine](https://waveengine.net) : The graphics development engine for business and industry. Build high-quality 3D and 2D solutions and deploy to any platform. [Projects/Samples](https://github.com/WaveEngine/)    
- ### Commercial
    - :moneybag: [AppGameKit Studio](https://www.appgamekit.com/studio) : Easy, quick and powerful programming.
    - :money_with_wings: [Buildbox](https://www.buildbox.com) : Create 3D & 2D video games without coding.
    - :money_with_wings: [Construct](https://www.construct.net/) : Browser based drag and drop game builder. [[Awesome Construct](https://github.com/ConstructCommunity/awesome-construct#readme)]
    - :money_with_wings: [Felgo](https://felgo.com/games) : Build Cross-Platform 2D Games in Days. Based on the Qt framework.
    - :money_with_wings: [GameMaker Studio](https://www.yoyogames.com/en/gamemaker) : (by YoYo Games) 2D Game Development Environment with large following.
    - :money_with_wings: [GameSalad](https://gamesalad.com) : Sophisticated visual programming interface.
    - :money_with_wings: [MANU](https://manu.co) : Unique animation system helps you create games without coding.
    - :money_with_wings: [ShiVa](https://shiva-engine.com) : 3D game and application development suite.
    - :money_with_wings: [Simulation Starter Kit](https://benmorris.itch.io/plugin-based-scene-editor) : Supports the creation of simple interactive 3D applications across a range of platforms and devices. [Developer Website](http://fireflytech.org)
    - :money_with_wings: [Stencyl](http://www.stencyl.com) [:octocat:](https://github.com/Stencyl/stencyl-engine) (Repo for  runtime only) : Quick and easy game making. Visual scripting similar to [Scratch](https://scratch.mit.edu).
- ### Specialty
    - :moneybag: [3dSen](https://geod.itch.io/3dnes) : Unique NES emulator that converts NES games into full 3D experiences and let you play them in realtime. [Developer Website](http://www.geodstudio.net)
    - :money_with_wings: [DopeFish](https://subpixel-studios.itch.io/dopefish) : Full GML Doom/Heretic map loading system for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :tada: [GB Studio](https://www.gbstudio.dev) [:octocat:](https://github.com/chrismaltby/gb-studio) : Retro adventure game creator for Game Boy available for Mac, Linux and Windows.
    - :moneybag: [Platforming Engine](https://robvansaaze.itch.io/platforming-engine) : Everything you need to create your very own platforming game for [GameMaker Studio](https://www.yoyogames.com/en/gamemaker).
    - :moneybag: [RPG Maker](https://www.rpgmakerweb.com) : Lets you create an original role-playing game without any specialized knowledge or training.

## Games
_Open source games to be dissected for knowledge_
- :lock: [VoltAir](http://google.github.io/VoltAir/doc/main/html/index.html) [:octocat:](https://github.com/google/VoltAir) : Made by Google, a full 2D game built on top of [QtQuick](https://doc.qt.io/qt-5/qtquick-index.html) and [Liquidfun](http://google.github.io/liquidfun/).

## How To
_Exploring specific functionality of a game engine_
- ### Geometry
    - ### Mesh
- ### Layout
    - ### Blob Tiles
- ### Lighting
    - ### Lighting 2D
    - ### Lighting 3D / Light Maps
- ### Particles
- ### Portals
- ### Ropes
- ### Scripting
- ### Shaders
    - ### Articles
    - ### Bloom
    - ### Fire
    - ### Noise
    - ### Outlines
    - ### Smoke
- ### Soft Body Physics
- ### Transparency
- ### Water

## Learning
_Info on topics necessary for designing and developing game engines_
- ### Game Engine Development
    - :books: [How to become a game engine developer](https://www.haroldserrano.com/blog/how-to-become-a-game-engine-developer) : Short and simple starting point on Game Engine Development
- ### Programming
    - :books: [Games of Coding](https://github.com/michelpereira/awesome-games-of-coding#readme) : Awesome list of games that teach you a programming language.
    - :books: [Learn to Program](https://github.com/karlhorky/learn-to-program#readme) : Educational resources to learn to program.

## Libraries
_Language specific game engine development libraries / frameworks / code_
- ### C/C++
    - ### - Language: Collections -
        - :books: [Awesome C++](https://github.com/fffaraz/awesome-cpp#readme) : A curated list of awesome C++ (or C) frameworks, libraries, resources, and shiny things. 
        - :books: [Awesome C++ Game Dev](https://github.com/Caerind/AwesomeCppGameDev#readme) : A curated list of awesome C++ (mainly) things for Game Development.
    - ### Game Engine
        - :tada: [Cocos2d-x](https://www.cocos.com/en/cocos2dx) [:octocat:](https://github.com/cocos2d/cocos2d-x) : Provides rendering, GUI, audio, network, physics, user input, etc. Widely used in game development and application construction.
        - :tada: [Defold](https://defold.com) [:octocat:](https://github.com/defold/defold) : Open sourced by King. Free to use game engine for development of desktop, mobile and web games.
        - :tada: [LOVE](https://love2d.org) [:octocat:](https://github.com/love2d/love) : LÖVE is an awesome 2D game framework for writing game code with Lua.
        - :tada: [ORX](http://orx-project.org) [:octocat:](https://github.com/orx/orx) : Orx is a 2.5D data-driven game development engine.
        - :tada: [Panda3D](https://www.panda3d.org) [:octocat:](https://github.com/panda3d/panda3d) : Powerful, mature cross-platform game engine for Python and C++, developed by Disney and CMU.
        - :tada: [Solar2D](https://solar2d.com) [:octocat:](https://github.com/coronalabs/corona) : (Previously known as Corona) Focus on ease of iterations and usage.
    - ### Game Engine w/Editor
        - :tada: [Esenthel](https://esenthel.com/) [:octocat:](https://github.com/Esenthel/EsenthelEngine) : Cross-platform feature-packed open source engine. Easy to use. In development since the year 2000.
        - :tada: [Irrlicht](https://irrlicht.sourceforge.io) [:octocat:](https://sourceforge.net/projects/irrlicht/) : Cross-platform 3D engine written in C++ worked on for nearly 2 decades.
        - :tada: [Polycode](http://polycode.org/features/) [:octocat:](https://github.com/ivansafrin/Polycode) : Cross-platform framework for creative code. Nice editor.
        - :tada: [Torque 3D](https://torque3d.org/torque3d/) [:octocat:](https://github.com/GarageGames/Torque3D) : High performance 3D engine.
        - :lock: [UPBGE](https://upbge.org) [:octocat:](https://github.com/UPBGE/upbge) : Blender game engine. Forked from [Blender](https://www.blender.org).
    - ### Graphics
        - :tada: [Ogre](https://www.ogre3d.org) [:octocat:](https://github.com/OGRECave/ogre) : Scene-oriented, flexible 3D engine.
    - ### Graphics w/Editor
        - :tada: [Horde3D](http://www.horde3d.org) [:octocat:](https://github.com/horde3d/Horde3D) : 3D rendering and animation engine. Horde3D [scene editor docs](http://horde3d.org/wiki/index.php?title=Horde3D_Scene_Editor).
- ### C#
    - ### - Language -
    - ### Game Engine
        - :tada: [MonoGame](https://www.monogame.net) [:octocat:](https://github.com/MonoGame/MonoGame) : Framework for creating powerful cross-platform games in C#.
    - ### Game Engine w/Editor
        - :tada: [Stride](https://stride3d.net) [:octocat:](https://github.com/stride3d/stride) : (formerly Xenko) C# game engine for realistic rendering and VR.
- ### Haxe
    - ### - Language -
        - :tada: [Haxe](https://haxe.org) [:octocat:](https://github.com/HaxeFoundation/haxe) : Official site. Very cool programming language used to produce cross-platform native code.
        - :books: [Haxelibs](https://lib.haxe.org/all) : A list of every library uploaded to Haxe's website.
        - :books: [haxetink](https://github.com/haxetink) : Various add-on libraries for Haxe.
        - :books: [snowkit](http://snowkit.org) [:octocat:](https://github.com/snowkit) : A collective of Haxe developers.
    - ### - Language: Articles -
        - :books: [Flash is dead, long live OpenFL](https://web.archive.org/web/20201112021925/https://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
        - :books: [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
    - ### - Language: Collections -
        - :books: [Awesome Haxe](https://github.com/nadako/awesome-haxe#readme) : Awesome curated list of useful Haxe links.
        - :books: [Awesome Haxe Game Dev](https://github.com/Dvergar/awesome-haxe-gamedev#readme) : Awesome list of game dev resources for Haxe.
    - ### Animation
        - :tada: [Actuate](https://github.com/jgranick/actuate) : Flexible, fast "tween" library.
        - :tada: [openfl/DragonBones](https://github.com/openfl/dragonbones) : Runtime support for [DragonBones](https://www.dragonbones.com) skeletal animation.
        - :tada: [spine-hx](https://github.com/jeremyfa/spine-hx) : [Spine](https://esotericsoftware.com) runtime for Haxe.
    - ### Application
        - :tada: [HashLink](https://hashlink.haxe.org) [:octocat:](https://github.com/HaxeFoundation/hashlink/) : Virtual machine for Haxe.
        - :tada: [hexMachina](http://hexmachina.org) [:octocat:](https://github.com/DoclerLabs/hexCore) : Powerful modular MVC framework written in Haxe.
        - :tada: [Lime](https://lime.software) [:octocat:](https://github.com/haxelime/lime) : A flexible, lightweight layer for Haxe cross-platform developers.
        - :tada: [nme](https://github.com/haxenme/nme) : Cross-platform native backend for Haxe projects.
    - ### Entity Component System
        - :tada: [ecx](https://github.com/eliasku/ecx) : Entity Component System framework for Haxe.
        - :tada: [GASM](https://github.com/HacksawStudios/GASM) : Framework agnostic Entity Component System for Haxe.
    - ### Game Engine
        - :tada: [Citrus](http://citrusengine.com) [:octocat:](https://github.com/DaVikingCode/Citrus-Engine) : 2D and 3D ActionScript 3 based engine.
        - :tada: [Clay](https://github.com/clay2d/clay) : Cross-platform 2d game framework.
        - :tada: [HaxeFlixel](https://haxeflixel.com) [:octocat:](https://github.com/HaxeFlixel/flixel) : Cross-platform 2D game engine powered by Haxe and OpenFL.
        - :tada: [OpenFL](https://www.openfl.org) [:octocat:](https://github.com/openfl/openfl) : For creative expression on the web, desktop, mobile and consoles.
    - ### Game Engine w/Editor
        - :tada: [Armory](https://armory3d.org) [:octocat:](https://github.com/armory3d/armory) : 3D game engine with full Blender integration.
        - :tada: [Away3D](https://www.away3d.com) [:octocat:](https://github.com/openfl/away3d) : Real-time 3D engine for OpenFL.
        - :tada: [flixel-studio](https://github.com/Dovyski/flixel-studio) : Embeddable, in-game editor for [HaxeFlixel](https://haxeflixel.com).
        - :tada: [Hide](https://github.com/heapsio/hide) : Extensible IDE for [Heaps](https://heaps.io).
        - :tada: [LDtk](https://ldtk.io) [:octocat:](https://github.com/deepnight/ldtk) : Very cool modern, lightweight and efficient 2D level editor.
        - :tada: [Starling](https://gamua.com/starling/) [:octocat:](https://github.com/openfl/starling) : Popular Stage3D framework.
    - ### Graphics
        - :tada: [Heaps](https://heaps.io) [:octocat:](https://github.com/HeapsIO/heaps) : High-performance cross-platform graphics engine by the creators of [Haxe](https://haxe.org).
        - :tada: [Kha](https://kha.tech) [:octocat:](https://github.com/Kode/Kha) : Ultra-portable, high performance, open source multimedia framework.
        - :tada: [Sparkler](https://github.com/AndreiRudenko/sparkler) : Modular Macro-powered Particle System.
    - ### Gui
        - :tada: [HaxeUI](http://haxeui.org) [:octocat:](https://github.com/haxeui/haxeui-core) : Cross-platform set of styleable application centric, rich UI components.
    - ### Physics
        - :tada: [haxebullet](https://github.com/armory3d/haxebullet) : Bullet 3D Physics bindings for Haxe.
        - :tada: [HeapsIO/bullet](https://github.com/HeapsIO/bullet) : Bullet 3D Physics for Heaps (Haxe's native low-level game framework).
        - :tada: [jellyPhysics](https://github.com/michaelapfelbeck/jellyPhysics) : Soft body physics engine.
        - :tada: [Nape](https://joecreates.github.io/napephys/) [:octocat:](https://github.com/HaxeFlixel/nape-haxe4) : Very impressive powerful, fast, and friendly 2D Rigid Body physics engine.
    - ### Serialization / Storage
        - :tada: [CastleDB](https://github.com/ncannasse/castle) : Structured database with a local web service to edit it.
        - :tada: [format](https://github.com/HaxeFoundation/format) : Various files formats support for Haxe.
        - :tada: [HxBit](https://github.com/HeapsIO/hxbit) : Binary serialization and network synchronization library.
    - ### Utility
        - :tada: [hxColorToolkit](https://github.com/andyli/hxColorToolkit) : Library for color conversion and color scheme generation.
        - :tada: [HxMath](https://github.com/tbrosman/hxmath) : Game-oriented math library for the Haxe language.
        - :tada: [nxColor](https://github.com/oscarcs/nxColor) : Color manipulation library.
        - :tada: [SteamWrap](https://github.com/larsiusprime/SteamWrap) : Haxe native extension for the Steam API.
    - ### Visual Scripting
        - :tada: [haxe-blockly](https://github.com/nickmain/haxe-blockly) : Haxe wrapper for [Blockly](https://developers.google.com/blockly)
- ### Java
    - ### Game Engine, Low-Level
        - :books: [Awesome libGDX](https://github.com/rafaskb/awesome-libgdx#readme) : Awesome list of resources for libGDX.
        - :tada: [libGDX](https://libgdx.com) [:octocat:](https://github.com/libgdx/libgdx) : Cross-platform Java game development framework.     
- ### Javascript
    - ### Game Engine
        - :tada: [GDevelop](https://gdevelop-app.com) [:octocat:](https://github.com/4ian/GDevelop) : A 2D full-featured, open-source game development software platform.
        - :tada: [Phaser](https://phaser.io) [:octocat:](https://github.com/photonstorm/phaser) : Fast 2D game framework for making HTML5 games for desktop and mobile web browsers, supports Canvas and WebGL.
        - :tada: [Turbulenz](http://biz.turbulenz.com/developers) [:octocat:](https://github.com/turbulenz/turbulenz_engine) : Modular 3D and 2D game framework for making HTML5 powered games for browsers, desktops and mobile devices.
    - ### Game Engine w/Editor
        - :tada: [A-Frame](https://aframe.io) [:octocat:](https://github.com/aframevr/aframe/) : Web framework for building virtual reality (VR) experiences.
        - :tada: [Cocos Creator](https://www.cocos.com/en/creator) [:octocat:](https://github.com/cocos-creator/engine) : A Cross-Platform 2D/3D Game Creation Tool
        - :tada: [Pixelbox.js](https://pixwlk.itch.io/pixelbox) [:octocat:](https://github.com/cstoquer/pixelbox) : Sandbox framework to fast-prototype tile-based games in HTML5 and JavaScript. [Editor](https://pixwlk.itch.io/pixelbox)
        - :money_with_wings: [PlayCanvas](http://playcanvas.com) [:octocat:](https://github.com/playcanvas/engine) : Collaboratively build stunning HTML5 games and visualizations.
    - ### Graphics
        - :tada: [LUME](https://lume.io) [:octocat:](https://github.com/lume/lume) : Toolkit that simplifies the creation of interactive 2D / 3D experiences for any device from mobile to desktop to AR/VR.
    - ### Graphics w/Editor
        - :tada: [babylon.js](https://www.babylonjs.com) [:octocat:](https://github.com/BabylonJS/Babylon.js) : One of the most powerful, beautiful, and simple Web rendering engines in the world.
        - :tada: [CopperLicht](http://ambiera.com/copperlicht/) : Commercial grade open source 3D JavaScript library for WebGL. [CopperCube Editor](http://ambiera.com/coppercube/index.html)
        - :tada: [three.js](https://threejs.org) [:octocat:](https://github.com/mrdoob/three.js/) : Easy to use, lightweight, cross-browser, general purpose 3D library. [Editor](https://threejs.org/editor/) | [Examples](https://threejs.org/examples/)
- ### Python
    - ### Gui
        - :tada: [Kivy](https://kivy.org/) [:octocat:](https://github.com/kivy/kivy) : Open source UI framework written in Python, running on Windows, Linux, macOS, Android and iOS.

## Game Programming
- ### AI

## Tools
- ### Image Editing
- ### Modeling
- ### Textures

## Website

## Business

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
