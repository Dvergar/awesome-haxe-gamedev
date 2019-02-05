![Haxe Logo](haxe-logo.png)

# Table of contents
* [Game Engines](#game-engines)
* [Physics](#physics)
* [Architecture](#architecture)
* [Game hosts API](#game-hosts-API)
* [Networking](#networking)
* [Serialization](#serialization)
* [Games](#games)
* [Miscellaneous](#misc)
* [Articles](#articles)
* [Other haxe lists](#other-haxe-lists)

# Game engines

Those are haxe 4 compatible game engines.

Engine | Target | Doc | Description
-------| -------|:---:| -----------
[Armory (Kha)](https://github.com/armory3d/armory) | Web, Mobile, Desktop, Consoles | Yes | Armory is an open-source 3D game engine with full Blender integration
[Away3d](https://github.com/openfl/away3d) | Web, Mobile, Desktop | Yes | An open source, real-time 3D engine for OpenFL
[HaxeFlixel (OpenFl)](https://github.com/HaxeFlixel/flixel) | Web, Mobile, Desktop | Yes | Free, cross-platform 2D game engine powered by Haxe and OpenFL
[Haxegon (OpenFl)](https://github.com/HaxeFlixel/flixel) | Web, Mobile, Desktop | Yes | A haxe programming library for beginners. Powered by OpenFL and Starling.
[Heaps](https://github.com/HeapsIO/heaps) | Web, Mobile, Desktop, Consoles | Yes | High Performance Game Framework
[OpenFl](https://github.com/openfl/openfl) | Web, Mobile, Desktop | Yes | Interactive game and app development library
[Starling](https://github.com/openfl/starling) | Web, Mobile, Desktop | Yes | The "Cross-Platform Game Engine", a popular Stage3D framework
[unreal.hx](https://github.com/proletariatgames/unreal.hx) | Web, Mobile, Desktop, Consoles | Yes | Unreal.hx: Haxe Integration for Unreal
**Smaller Engines** | | |
[Clay](https://github.com/clay2d/clay) | Web, Mobile, Desktop, Consoles | No | Clay is a cross-platform, 2d game framework.
[gm2d](https://github.com/nmehost/gm2d) | Web, Mobile, Desktop | No | A library for rapid game developement with Haxe, NME and Waxe.
[hank](https://github.com/NQNStudios/hank) | N/A | Yes | Portable narrative scripting language based on Ink.
[iron (Kha)](https://github.com/armory3d/iron) | Web, Mobile, Desktop, Consoles | No | Iron is a library for building ultra-portable 3D tools
*haxe3 or unmaintained* &#x1F648; | _ | _ | [Gecko2D](https://github.com/Nazariglez/Gecko2D), [Flambe](https://github.com/aduros/flambe), [haxe-phaser3](https://github.com/sebbernery/haxe-phaser3), [HaxePunk](https://github.com/HaxePunk/HaxePunk), [Khapunk](https://bitbucket.org/stalei/khapunk), [luxe](https://github.com/underscorediscovery/luxe),


Low-level Engine | Target | Doc | Description
---------------- | -------|:---:| -----------
[Kha](https://github.com/Kode/Kha) | Web, Mobile, Desktop, Console | Yes | Ultra-portable, high performance, open source multimedia framework.
[Lime](https://github.com/openfl/lime) | Web, Mobile, Desktop | Yes | Lime is a flexible, lightweight layer for Haxe cross-platform developers
[NME](https://github.com/haxenme/nme) | Web, Mobile, Desktop | No | A cross-platform native backend for Haxe projects
*haxe3 or unmaintained* &#x1F648; | _ | _ | [snow](https://github.com/snowkit/snow),



# Physics
Library | Doc | Description
------- |:---:| -----------
[nape](https://github.com/XenizoGames/nape_haxe_4) | Yes | Haxe/AS3 Physics Engine (Haxe 4 port of [nape](https://github.com/deltaluca/nape))
[haxebullet](https://github.com/armory3d/haxebullet) | Yes | Bullet 3D Physics for Haxe
*haxe3 or unmaintained* &#x1F648; | |[box2d](https://github.com/openfl/box2d/)


# Architecture
IoC == Inversion of Control  
EC == Entity Component  
ECS == Entity-Component-System

Library | Architecture | Doc | Description
--------| -------------|:---:| -----------
[awe6](https://github.com/hypersurge/awe6) | IoC, EC | yes | The inverted game framework, is a development tool focused on Future Proofing.
[ecx](https://github.com/eliasku/ecx) | ECS | yes | ECX is Entity Component System framework for Haxe
[ghost](https://github.com/AustinEast/ghost) | ECS | no | ECS Game Framework built on top of Heaps
[OSIS](https://github.com/Dvergar/OSIS) | ECS | yes | Entity Component System architecture with networking support
*haxe3 or unmaintained* &#x1F648;| | | [Ash-Haxe](https://github.com/nadako/Ash-HaXe), [IceEntity](https://github.com/NicoM1/IceEntity), [hxE](https://github.com/PDeveloper/hxE), [eskimo](https://github.com/PDeveloper/eskimo), [edge](https://github.com/fponticelli/edge), [ZE2D](https://github.com/zgoh/ZE2D)


# Game hosts API
Library | Doc | Description
------- |:---:| -----------
[SteamWrap](https://github.com/larsiusprime/SteamWrap) | Yes | Haxe native extension for the Steam API
*haxe3 or unmaintained* &#x1F648; | _ |[extension-steamworks](https://github.com/HaxeExtension/extension-steamworks), [kong.hx](https://github.com/djcsdy/kong.hx), [hxGameJolt](https://github.com/Zielak/hxGameJolt), [GameJolt-API-Haxe-bindings](https://github.com/matrefeytontias/GameJolt-API-Haxe-bindings)


# Networking
Library | Doc | Description
------- |:---:| -----------
[Anette](https://github.com/Dvergar/Anette) | Yes | Simple haxe network library (no UDP)
[hxWebSockets](https://github.com/ianharrigan/hxWebSockets) | hum | Websockets for all haxe platforms
Built-in | Yes | Heaps, OpenFL (Haxeflixel & co), Kha (Armory)
*haxe3 or unmaintained* &#x1F648; | _ |[hxnet](https://github.com/MattTuttle/hxnet), [linc_enet](https://github.com/snowkit/linc_enet)


# Serialization
Library | Doc | Description
------- |:---:| -----------
[hxbit](https://github.com/ncannasse/hxbit) | Yes | HxBit is a binary serialization and network synchronization library for Haxe.  
[PODStream](https://github.com/Dvergar/PODStream) | Yes | PODStream will serialize and deserialize your fields from/to BytesInput / BytesOutput.
*haxe3 or unmaintained* &#x1F648; | _ |[msgpack-haxe](https://github.com/aaulia/msgpack-haxe), [protohx](https://github.com/nitrobin/protohx), [protoc-gen-haxe](https://github.com/Atry/protoc-gen-haxe)



# Games
Game | Platform | Engine | Screenshot
-----|----------|--------|-----------
**RELEASED** | | |
[Dead Cells](https://dead-cells.com/) | Desktop, Consoles | Heaps | |
[Defender's Quest](http://www.defendersquest.com/) | Desktop | OpenFl | |
[Evoland](http://evoland.shirogames.com/) | Desktop, Mobile | Heaps | |
[Northgard](http://northgard.net/) | Desktop | Heaps | |
[Papers, please](http://papersplea.se/) | Desktop, iOS, PsVita| | |
[Pocket Kingdom](https://store.steampowered.com/app/462620/Pocket_Kingdom/) | Desktop | HaxePunk (OpenFl) | |
[rymdkapsel](https://rymdkapsel.com/) | Desktop, Mobile | OpenFl | |
[The Westport Independent](http://www.doublezeroonezero.com/westport.html) | Desktop, Mobile | Luxe | |
**IN DEVELOPMENT** | | |
[Darksburg](https://store.steampowered.com/app/939100/Darksburg/) | Desktop, ? | Heaps
[Dicey Dungeons](http://diceydungeons.com/) | Desktop, ? | Haxegon (OpenFl)
[Frontier Story](https://frontierstorygame.com/) | Desktop | Heaps

More showcase :
* https://www.openfl.org/showcase/
* https://haxeflixel.com/showcase/
* https://haxepunk.com/games/
* https://github.com/aduros/flambe/wiki/Showcase
* https://github.com/Kode/Kha/wiki/Games-Built-With-Kha

# Misc

Type | Library | Description
-----|---------|------------
Color manipulation | [nxColor](https://github.com/oscarcs/nxColor) | Haxe color manipulation library.
Localization | [firetongue](https://github.com/larsiusprime/firetongue) | A translation/localization framework written in Haxe
Map parser | [PyxelEdit Map Importer](https://github.com/Dvergar/PyxelEdit-Map-Importer) | Parser for maps generated by the editor PyxelEdit
_ | Heaps | Built-in parser for Tiled
Math helpers | [hxmath](https://github.com/tbrosman/hxmath) | A game-oriented math library for the Haxe language
Pathfinding | [pathfinder](https://github.com/hypersurge/pathfinder) | easy A* (A Star / astar) pathfinding (Haxe)
Tweening | [actuate](https://github.com/jgranick/actuate) | Actuate is a flexible, fast "tween" library
UI | [domkit](https://github.com/ncannasse/domkit) | CSS Components based strictly typed UI framework for Haxe
_ | [flixel-ui](https://github.com/HaxeFlixel/flixel-ui) | GUI library for HaxeFlixel

# Articles
* [Flash is dead, long live OpenFL!](http://gamasutra.com/blogs/LarsDoucet/20140318/213407/Flash_is_dead_long_live_OpenFL.php)
* [Flash is gone, what now?](https://www.linkedin.com/pulse/flash-gone-what-now-matan-uberstein/)
* [How I wrote my own 3D game engine and shipped a game with it in 20 months](https://kircode.com/post/how-i-wrote-my-own-3d-game-engine-and-shipped-a-game-with-it-in-20-months)
* [Building 42 games within a year — Insane game development](https://medium.com/@mknol/building-42-games-within-a-year-insane-game-development-5340d506068f)

# Other haxe lists
* https://github.com/nadako/awesome-haxe
* https://github.com/anissen/awesome-snowkit
* https://github.com/MatthijsKamstra/awesome-haxe-js

# Relevant things to sort and/or add

* Particle emitters
* https://github.com/proletariatgames/HUGS (haxe3)
* https://github.com/unihx/unihx (haxe3)