# Awesome Game Engine Development [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> An awesome list that curates the best Game Engine Development articles, libraries, tools, tutorials, and more. Favors C/C++ and Javascript.

<br>

### NOTE - Oct 1, 2021: This is a draft, this list is still being built out...

Contributions will be welcome when draft is complete, but are currently not accepted.
<br><br>

### License Legend

:star: - Public Domain License (CC0, BOLA, WTFPL, Unlicense, etc.)\
:tada: - Permissive License (MIT, BSD, ZLIB / LIBPNG, ISC, Apache, BSL, etc.)\
:lock: - Restrictive License (Copyleft, ShareAlike, GPL / LGPL, MPL, etc.)\
:question: - License Unknown
:free: - Closed Source, Free\
:moneybag: - Closed Source, Paid\
:money_with_wings: - Closed Source, Partially Free\
:books: - Article / Website

:octocat: - Any item with an OctoCat has a GitHub repo, click on it to see the source code!

<br>

### Definitions
- <b>Game Engine, High-Level</b> : Full featured game creation software with scene editor.
- <b>Game Engine, Low-Level</b> : Game creation library that handles rendering, possibly more.

<br>

## Index
- [GameDevEssentials](#GameDevEssentials)
- [GameEngineDesign](#GameEngineDesign)
- [Coding](#Coding)
- [C++](#C++)
- [C#](#C#)
- [Haxe](#Haxe)
- [Java](#Java)
- [Javascript](#Javascript)
- [Python](#Python)
- [Scripting](#Scripting)
- [GameDesign](#GameDesign)
- [GameProgramming](#GameProgramming)
    - [AI](#AI)
- [Tools](#Tools)
    - [ImageEditing](#ImageEditing)
    - [Modeling](#Modeling)
    - [Textures](#Textures)
- [Website](#Website)

<br>

## GameDevEssentials
Helpful resources for any game developer / game engine developer.
- :money_with_wings: [itch.io](https://itch.io) : Platform to host, showcase, promote, buy / sell games and resources.
- :books: [Wikipedia: List of Game Engines](https://en.wikipedia.org/wiki/List_of_game_engines) : Thorough list of game engines, their platforms and their licenses.

## GameEngineDesign
Info on design and development of a game engine.
- :books: [How to become a game engine developer](https://www.haroldserrano.com/blog/how-to-become-a-game-engine-developer) : Short and simple starting point on Game Engine Development

## Coding
Learn to code.
- :books: [Games of Coding](https://github.com/michelpereira/awesome-games-of-coding#readme) : Awesome list of games that teach you a programming language.
- :books: [Learn to Program](https://github.com/karlhorky/learn-to-program#readme) : Educational resources to learn to program.

## C++
Game Engine Development tools and libaries for C++.
- ### Basic Info
    - :books: [Awesome C++](https://github.com/fffaraz/awesome-cpp#readme) : Awesome list of C++ frameworks, libraries, and resources.
    - :books: [Awesome C++ Game Dev](https://github.com/Caerind/AwesomeCppGameDev#readme) : Awesome list of C++ things for Game Development.
- ### Game Engines, High-Level
    - :tada: [Godot](https://godotengine.org) [:octocat:](https://github.com/godotengine/godot) : Feature-packed, open source engine.
    - :money_with_wings: [Unity](https://unity.com) : The standard in game development.
    - :money_with_wings: [Unreal Engine](https://www.unrealengine.com) : AAA game capable, photoreal visuals.

## C#
Game Engine Development tools and libaries for C#.

## Haxe
Game Engine Development tools and libaries for Haxe.
- ### Basic Info
    - :books: [Awesome Haxe Game Dev](https://github.com/Dvergar/awesome-haxe-gamedev#readme) : Awesome list of game dev resources for Haxe.
    - :tada: [Haxe](https://haxe.org) [:octocat:](https://github.com/HaxeFoundation/haxe) : Very cool programming language used to produce cross-platform native code.
- ### Animation
    - :tada: [openfl/DragonBones](https://github.com/openfl/dragonbones) : Runtime support for [DragonBones](https://www.dragonbones.com) skeletal animation.
- ### Architecture
    - :tada: [hexMachina](http://hexmachina.org) [:octocat:](https://github.com/DoclerLabs/hexCore) : Powerful modular MVC framework written in Haxe.
- ### Entity Component System
    - :tada: [ecx](https://github.com/eliasku/ecx) : Entity Component System framework for Haxe.
    - :tada: [GASM](https://github.com/HacksawStudios/GASM) : Framework agnostic Entity Component System for Haxe.
- ### Game Engines, High-Level
    - :tada: [Armory](https://armory3d.org) [:octocat:](https://github.com/armory3d/armory) : 3D game engine with full Blender integration.
    - :tada: [Away3D](https://www.away3d.com) [:octocat:](https://github.com/openfl/away3d) : Real-time 3D engine for OpenFL.
    - :tada: [Hide](https://github.com/heapsio/hide) : Extensible IDE for [Heaps](https://heaps.io).
    - :tada: [flixel-studio](https://github.com/Dovyski/flixel-studio) : Embeddable, in-game editor for [HaxeFlixel](https://haxeflixel.com).
    - :tada: [Starling](https://gamua.com/starling/) [:octocat:](https://github.com/openfl/starling) : Popular Stage3D framework.
    - :money_with_wings: [Stencyl](http://www.stencyl.com) [:octocat:](https://github.com/Stencyl/stencyl-engine) : (Built with Haxe) Quick and easy game making.
- ### Game Engines, Low-Level
    - :tada: [HaxeFlixel](https://haxeflixel.com) [:octocat:](https://github.com/HaxeFlixel/flixel) : Cross-platform 2D game engine powered by Haxe and OpenFL.
    - :tada: [Heaps](https://heaps.io) [:octocat:](https://github.com/HeapsIO/heaps) : High performance game framework by the creators of Haxe.
    - :tada: [Kha](https://kha.tech) [:octocat:](https://github.com/Kode/Kha) : Ultra-portable, high performance, open source multimedia framework.
    - :tada: [OpenFL](https://www.openfl.org) [:octocat:](https://github.com/openfl/openfl) : For creative expression on the web, desktop, mobile and consoles.
    - :tada: [Lime](https://lime.software) [:octocat:](https://github.com/haxelime/lime) : A flexible, lightweight layer for Haxe cross-platform developers.
- ### Physics
    - :tada: [haxebullet](https://github.com/armory3d/haxebullet) : Bullet 3D Physics bindings for Haxe.
    - :tada: [HeapsIO/bullet](https://github.com/HeapsIO/bullet) : Bullet 3D Physics for Heaps (Haxe's native low-level game framework).
    - :tada: [jellyPhysics](https://github.com/michaelapfelbeck/jellyPhysics) : Soft body physics engine.
    - :tada: [Nape](https://joecreates.github.io/napephys/) [:octocat:](https://github.com/HaxeFlixel/nape-haxe4) : Very impressive powerful, fast, and friendly 2D Rigid Body physics engine.
- ### Serialization / Storage
    - :tada: [CastleDB](https://github.com/ncannasse/castle) : A structured database with a local web service to edit it.
    - :tada: [HxBit](https://github.com/HeapsIO/hxbit) : Haxe Binary serialization and network synchronization library.
    - :tada: [HxBit](https://github.com/HeapsIO/hxbit) : Haxe Binary serialization and network synchronization library.
    - :question: [PODStream](https://github.com/Dvergar/PODStream) : Plain Old Data serializer.
- ### Visual Scripting
    - :tada: [haxe-blockly](https://github.com/nickmain/haxe-blockly) : Haxe wrapper for [Blockly](https://developers.google.com/blockly)

## Java
Game Engine Development tools and libaries for Java.
- ### Game Engines, Low-Level
    - :books: [Awesome libGDX](https://github.com/rafaskb/awesome-libgdx#readme) : Awesome list of resources for libGDX.
    - :tada: [libGDX](https://libgdx.com) [:octocat:](https://github.com/libgdx/libgdx) : Cross platform Java game development framework.
    
## Javascript
Game Engine Development tools and libaries for Javascript.
- ### Game Engines, High-Level
    - :money_with_wings: [Construct](https://www.construct.net/) : Drag and drop browser based game building.

## Python
Game Engine Development tools and libaries for Python.

## Scripting
Scripting and Visual Scripting support.

## GameDesign

## GameProgramming
- ### AI

## Tools
- ### ImageEditing
- ### Modeling
- ### Textures

## Website

## License
[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
