![Haxe Logo](images/haxe-logo.png)

A curated list of **haxe** game development resources.

# Contents
* [Game Engines](#game-engines)
* [Physics](#physics)
* [Architecture](#architecture)
* [Game hosts API](#game-hosts-API)
* [Networking](#networking)
* [Serialization and storage](#serialization-and-storage)
* [Games](#games)
* [Miscellaneous](#misc)
* [Articles](#articles)
* [Other haxe lists](#other-haxe-lists)

# Game engines

Those are haxe 4 compatible game engines.

Engine | Target | Doc | Description
-------| -------|:---:| -----------
[Armory (Kha)](https://github.com/armory3d/armory) | Web, Mobile, Desktop, Consoles | Yes | Armory is an open-source 3D game engine with full Blender integration.
[Away3D](https://github.com/openfl/away3d) | Web, Mobile, Desktop | Yes | An open source, real-time 3D engine for OpenFL.
[HaxeFlixel (OpenFL)](https://github.com/HaxeFlixel/flixel) | Web, Mobile, Desktop, Consoles | Yes | Free, cross-platform 2D game engine powered by OpenFL.
[Haxegon (OpenFL)](https://github.com/haxegon/haxegon) | Web, Mobile, Desktop, Consoles | Yes | A programming library for beginners. Powered by OpenFL and Starling.
[Heaps](https://github.com/HeapsIO/heaps) | Web, Mobile, Desktop, Consoles | Yes | High Performance Game Framework.
[hxdefold](https://github.com/hxdefold/hxdefold) | Web, Mobile, Desktop | Yes | Haxe/Lua externs for Defold game engine
[OpenFL](https://github.com/openfl/openfl) | Web, Mobile, Desktop, Consoles | Yes | Interactive game and app development library.
[Starling](https://github.com/openfl/starling) | Web, Mobile, Desktop | Yes | The "Cross-Platform Game Engine", a popular Stage3D framework.
[Stencyl (OpenFL)](https://github.com/Stencyl/stencyl-engine) | Web, Mobile, Desktop | Yes | Create Flash, HTML5, iOS, Android, and desktop games with no code with Stencyl
[unreal.hx](https://github.com/proletariatgames/unreal.hx) | Web, Mobile, Desktop, Consoles | Yes | Unreal.hx: Haxe Integration for Unreal.
*haxe3 or unmaintained* &#x1F648; | _ | _ | [Flambe](https://github.com/aduros/flambe), [HaxePunk](https://github.com/HaxePunk/HaxePunk), [luxe](https://github.com/underscorediscovery/luxe)
**Smaller Engines** | | |
[Clay](https://github.com/clay2d/clay) | Web, Mobile, Desktop, Consoles | No | Clay is a cross-platform, 2d game framework.
[Flurry](https://github.com/Aidan63/Flurry) | Web, Desktop | No | 2D focused, cross-platform game engine with multiple rendering backends.
[gm2d](https://github.com/nmehost/gm2d) | Web, Mobile, Desktop | No | A library for rapid game developement with NME and Waxe.
[hank](https://github.com/NQNStudios/hank) | N/A | Yes | Portable narrative scripting language based on Ink.
[iron (Kha)](https://github.com/armory3d/iron) | Web, Mobile, Desktop, Consoles | No | Iron is a library for building ultra-portable 3D tools.
[xt3d](https://github.com/stuartcaunt/xt3d) | Web, Mobile, Desktop | No | An open-source, cross-platform, 3D graphics and game-development framework using Lime.
*haxe3 or unmaintained* &#x1F648; | _ | _ | [Gecko2D](https://github.com/Nazariglez/Gecko2D), [haxe-phaser3](https://github.com/sebbernery/haxe-phaser3), [Khapunk](https://bitbucket.org/stalei/khapunk)


Low-level Engine | Target | Doc | Description
---------------- | -------|:---:| -----------
[Kha](https://github.com/Kode/Kha) | Web, Mobile, Desktop, Console | Yes | Ultra-portable, high performance, open source multimedia framework.
[Lime](https://github.com/openfl/lime) | Web, Mobile, Desktop | Yes | Lime is a flexible, lightweight layer for haxe cross-platform developers.
[linc_glfw](https://github.com/Sunjammer/linc_glfw) | Desktop | Yes | GLFW binding (multi-platform library for OpenGL, OpenGL ES and Vulkan).
[NME](https://github.com/haxenme/nme) | Web, Mobile, Desktop | No | A cross-platform native backend for Haxe projects.
*haxe3 or unmaintained* &#x1F648; | _ | _ | [snow](https://github.com/snowkit/snow)



# Physics
Library | Doc | Description
------- |:---:| -----------
[echo](https://github.com/AustinEast/echo/) | Yes | Simple Physics Library.
[haxebullet](https://github.com/armory3d/haxebullet) | Yes | Bullet 3D Physics for Haxe.
[nape-haxe4](https://github.com/HaxeFlixel/nape-haxe4) | Yes | Haxe/AS3 Physics Engine (the original haxe3 version of nape can be found [here](https://github.com/deltaluca/nape)).
*haxe3 or unmaintained* &#x1F648; | |[box2d](https://github.com/openfl/box2d/), [LiquidFunx](https://github.com/JohnSword/liquidfunx)


# Architecture
```
IoC == Inversion of Control  
EC == Entity Component  
ECS == Entity-Component-System
FSM == Finite State Machine
MVC == Model View Controller
```

Library | Architecture | Doc | Description
--------| -------------|:---:| -----------
[awe6](https://github.com/hypersurge/awe6) | IoC, EC | yes | The inverted game framework, is a development tool focused on Future Proofing.
[ecs](https://github.com/kevinresol/ecs) | ECS | hum | Experimental macro-powered Entity-Component-System game engine.
[ecx](https://github.com/eliasku/ecx) | ECS | yes | ECX is Entity Component System framework.
[GASM](https://github.com/HacksawStudios/GASM) | ECS | no | Framework agnostic EntityComponent System for Haxe.
[Gluon](https://gitlab.com/d-moreno/gluon) | ECS | no | A tiny library that integrates engine agnostic ECS library Baldrick and Heaps.
[ghost](https://github.com/AustinEast/ghost) | ECS | no | ECS Game Framework built on top of Heaps.
[hexMachina](https://github.com/DoclerLabs/hexCore) | MVC | yes | A powerful multi-modular MVC framework.
[HxFSM](https://github.com/lbergman/HxFSM) | ECS | hum | Simple FSM
[OSIS](https://github.com/Dvergar/OSIS) | ECS | yes | Entity Component System architecture with networking support.
*haxe3 or unmaintained* &#x1F648;| | | [Ash-Haxe](https://github.com/nadako/Ash-HaXe), [IceEntity](https://github.com/NicoM1/IceEntity), [hxE](https://github.com/PDeveloper/hxE), [eskimo](https://github.com/PDeveloper/eskimo), [edge](https://github.com/fponticelli/edge), [ZE2D](https://github.com/zgoh/ZE2D), [echo](https://github.com/deepcake/echo), [baldrick](https://github.com/hamaluik/baldrick)


# Game hosts API
Library | Doc | Description
------- |:---:| -----------
[SteamWrap](https://github.com/larsiusprime/SteamWrap) | Yes | Haxe native extension for the Steam API.
*haxe3 or unmaintained* &#x1F648; | _ |[extension-steamworks](https://github.com/HaxeExtension/extension-steamworks), [kong.hx](https://github.com/djcsdy/kong.hx), [hxGameJolt](https://github.com/Zielak/hxGameJolt), [GameJolt-API-Haxe-bindings](https://github.com/matrefeytontias/GameJolt-API-Haxe-bindings)


# Networking
Library | Doc | Description
------- |:---:| -----------
[Anette](https://github.com/Dvergar/Anette) | Yes | Simple network library (no UDP).
[colyseus-hx](https://github.com/colyseus/colyseus-hx) | yes | Multiplayer Game Client.
[haxe-simple-peer (js)](https://github.com/melonin/haxe-simple-peer) | hum | Haxe externs for simple-peer.
[hxWebSockets](https://github.com/ianharrigan/hxWebSockets) | hum | Websockets for all haxe platforms.
Built-in | Yes | Heaps, OpenFL (HaxeFlixel & co), Kha (Armory).
*haxe3 or unmaintained* &#x1F648; | _ |[hxnet](https://github.com/MattTuttle/hxnet), [linc_enet](https://github.com/snowkit/linc_enet), [peerhx](https://github.com/haxorplatform/peerhx)


# Serialization and storage
Library | Doc | Description
------- |:---:| -----------
[Bits](https://github.com/RealyUniqueName/Bits) | Yes | Binary bit flags with unlimited amount of bits.
[CastleDB](https://github.com/ncannasse/castle) | Yes | CastleDB is a structured static database easing collaboration.
[hxbit](https://github.com/ncannasse/hxbit) | Yes | HxBit is a binary serialization and network synchronization library  .
[PODStream](https://github.com/Dvergar/PODStream) | Yes | POD serializer.
*haxe3 or unmaintained* &#x1F648; | _ |[msgpack-haxe](https://github.com/aaulia/msgpack-haxe), [protohx](https://github.com/nitrobin/protohx), [protoc-gen-haxe](https://github.com/Atry/protoc-gen-haxe), [flatbuffers-haxe](https://github.com/troyedwardsjr/flatbuffers-haxe)



# Games
Game | Platform | Engine | Screenshot
-----|----------|--------|-----------
**RELEASED** | | |
[Dead Cells](https://dead-cells.com/) | Desktop, Consoles | Heaps | ![Screenshot](images/dead-cells.jpg)
[Defender's Quest](http://www.defendersquest.com/) | Desktop, Consoles | HaxeFlixel (OpenFL) | ![Screenshot](images/defenders-quest.jpg)
[Evoland](http://evoland.shirogames.com/) | Desktop, Mobile | Heaps | ![Screenshot](images/evoland.jpg)
[Northgard](http://northgard.net/) | Desktop | Heaps | ![Screenshot](images/northgard.jpg)
[Papers, Please](http://papersplea.se/) | Desktop, iOS, PsVita| OpenFL | ![Screenshot](images/papers-please.jpg)
[Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/) | Desktop | HaxePunk (OpenFL) | ![Screenshot](images/pocket-kingdom.jpg)
[rymdkapsel](https://rymdkapsel.com/) | Desktop, Mobile | OpenFL | ![Screenshot](images/rymdkapsel.jpg)
[The Westport Independent](http://www.doublezeroonezero.com/westport.html) | Desktop, Mobile | Luxe | ![Screenshot](images/westport-independent.jpg)
**IN DEVELOPMENT** | | |
[Darksburg](https://store.steampowered.com/app/939100/Darksburg/) | Desktop, ? | Heaps | ![Screenshot](images/darksburg.jpg)
[Dicey Dungeons](http://diceydungeons.com/) | Desktop, ? | Haxegon (OpenFL) | ![Screenshot](images/dicey-dungeons.jpg)
[Frontier Story](https://frontierstorygame.com/) | Desktop | Heaps | ![Screenshot](images/frontier-story.jpg)

More showcase :
* https://www.openfl.org/showcase/
* https://haxeflixel.com/showcase/
* https://itch.io/games/made-with-haxe
* https://haxepunk.com/games/
* https://github.com/aduros/flambe/wiki/Showcase
* https://github.com/Kode/Kha/wiki/Games-Built-With-Kha

# Misc

Type | Library | Description
-----|---------|------------
Animation | [spine-hx](https://github.com/jeremyfa/spine-hx) | Spine runtime for Haxe automatically converted from the official Java/libgdx runtime. For Heaps: [Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine).
_ | HaxeFlixel | Spine parser via [flixel-addons](https://github.com/HaxeFlixel/flixel-addons/tree/dev/flixel/addons/editors).
_ | [Heaps-Spine](https://github.com/Beeblerox/Heaps-Spine) | Spine player for heaps.
Color manipulation | [nxColor](https://github.com/oscarcs/nxColor) | Color manipulation library.
Collision | [differ](https://github.com/snowkit/differ) | A separation axis theorem collision library.
Editor | [flixel-studio](https://github.com/Dovyski/flixel-studio) | In-game editor for HaxeFlixel.
Procedural generation | [Dungeon builder](https://github.com/julsam/dungeon-builder) | Dungeon Builder is a set of dungeon generation algorithm (works w/ hx4 w/ minor changes).
Localization | [firetongue](https://github.com/larsiusprime/firetongue) | A translation/localization framework written in Haxe.
Map parser | [PyxelEdit Map Importer](https://github.com/Dvergar/PyxelEdit-Map-Importer) | Parser for maps generated by the editor PyxelEdit.
_ | Heaps | Built-in parser for Tiled.
_ | HaxeFlixel | Parser for Tiled & Ogmo via [flixel-addons](https://github.com/HaxeFlixel/flixel-addons/tree/dev/flixel/addons/editors).
Math helpers | [hxmath](https://github.com/tbrosman/hxmath) | A game-oriented math library for the Haxe language.
_ | [haxe-glm](https://github.com/hamaluik/haxe-glm) | A toolset for using 2, 3, and 4 dimensional vectors and matrices, as well as quaternions.
_ | [hx-vector2d](https://github.com/markknol/hx-vector2d) | Worlds most complete Vector2d / Point class. With operator overloading.
Modding | [polymod](https://github.com/larsiusprime/polymod) | An atomic modding framework for Haxe games/apps.
Particles | [Sparkler](https://github.com/RudenkoArts/sparkler) | Modular Particle System.
Monetization | [extension-iap](https://github.com/charmdev/extension-iap) | Provides an access to in-app purchases (iOS) and in-app billing (Android) for OpenFL projects using a common API. Fork of [this](https://github.com/HaxeExtension/extension-iap).
_ | HaxeFlixel | Built-in.
Pathfinding | [pathfinder](https://github.com/hypersurge/pathfinder) | easy A* (A Star / astar) pathfinding (Haxe).
Sprite | [haxe-aseprite](https://github.com/PongoEngine/haxe-aseprite) | Parser for .ase and .aseprite files.
Texture Packer | [hxpk](https://github.com/bendmorris/hxpk) | Port of the libGDX Texture Packer.
Tweening | [actuate](https://github.com/jgranick/actuate) | Actuate is a flexible, fast "tween" library.
_ | [YATL](https://github.com/Yanrishatum/yatl) | Yet Another (Haxe) Tweening Library.
UI | [domkit](https://github.com/ncannasse/domkit) | CSS Components based strictly typed UI framework.
_ | [flixel-ui](https://github.com/HaxeFlixel/flixel-ui) | GUI library for HaxeFlixel

# Articles
* [Flash is dead, long live OpenFL!](http://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
* [Flash is gone, what now?](https://www.linkedin.com/pulse/flash-gone-what-now-matan-uberstein/)
* [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
* [Building 42 games within a year — Insane game development](https://medium.com/@mknol/building-42-games-within-a-year-insane-game-development-5340d506068f)
* [Porting to console via Unity](https://do-games.com/blog/the-adventure-pals-console-tech-part1)

# Other haxe lists
* https://github.com/nadako/awesome-haxe
* https://github.com/anissen/awesome-snowkit
* https://github.com/MatthijsKamstra/awesome-haxe-js

# Relevant things to sort and/or add

* https://github.com/restorer/zame-haxe-particles/ (haxe3)
* https://github.com/proletariatgames/HUGS (haxe3)
* https://github.com/unihx/unihx (haxe3)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
