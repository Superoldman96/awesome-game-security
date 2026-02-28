
# [`awesome-game-security`](https://gs.awesome.rip)[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![image](https://github.com/gmh5225/awesome-game-security/assets/13917777/a39c6322-40ed-45b5-afcb-93e8d5477a0b)
[![image](awesome-image.webp)](https://opensea.io/assets/ethereum/0x1c5ffb607ef75158b435bd21a898d848620b4b13/1)
```
If you find that some links are not working, you can simply replace the username with gmh5225. 
Or you can send an issue for me.
```
> Show respect to all the projects below, perfect works of art :saluting_face:

## How to contribute?
- https://github.com/HyunCafe/contribute-practice
- https://docs.github.com/en/get-started/quickstart/contributing-to-projects

## Skills for AI Agents
This repository provides skills that can be used with AI agents and coding assistants such as [Cursor](https://www.cursor.com/), [OpenClaw](https://docs.openclaw.ai/), [Claude Code](https://docs.anthropic.com/en/docs/claude-code), [Codex CLI](https://github.com/openai/codex), and other compatible tools. Install skills to get specialized knowledge about game security topics.

**[View on learn-skills.dev](https://learn-skills.dev/skills/gmh5225/awesome-game-security)**

**Installation:**
```bash
npx skills add https://github.com/gmh5225/awesome-game-security --skill <skill-name>
```

**Available Skills:**
| Skill | Description |
|-------|-------------|
| `anti-cheat-systems` | Anti-cheat development and bypass techniques |
| `dma-attack-techniques` | DMA/PCIe-based attack methods |
| `game-engine-resources` | Game engine internals and modding |
| `game-hacking-techniques` | General game hacking methods |
| `graphics-api-hooking` | DirectX/OpenGL/Vulkan hooking |
| `mobile-security` | Android/iOS game security |
| `awesome-game-security-overview` | Overview of this repository |
| `reverse-engineering-tools` | RE tools and techniques |
| `windows-kernel-security` | Windows kernel exploitation |

**Example:**
```bash
# Install anti-cheat systems skill
npx skills add https://github.com/gmh5225/awesome-game-security --skill anti-cheat-systems

# Install multiple skills
npx skills add https://github.com/gmh5225/awesome-game-security --skill windows-kernel-security
npx skills add https://github.com/gmh5225/awesome-game-security --skill reverse-engineering-tools
```

## Contents
- [Game Engine](#game-engine)
- [Mathematics](#mathematics)
- [Renderer](#renderer)
- [3D Graphics](#3d-graphics)
- [AI](#ai)
- [Image Codec](#image-codec)
- [Wavefront Obj](#wavefront-obj)
- [Task Scheduler](#task-scheduler)
- [Game Network](#game-network)
- [PhysX SDK](#physx-sdk)
- [Game Develop](#game-develop)
- [Game Assets](#game-assets)
- [Game Hot Patch](#game-hot-patch)
- [Game Testing](#game-testing)
- [Game Tools](#game-tools)
- [Game Manager](#game-manager)
- [Game CI](#game-ci)
- [DirectX](#directx)
- [OpenGL](#opengl)
- [Vulkan](#vulkan)
- [Cheat](#cheat)
- [Anti Cheat](#anti-cheat)
- [Some Tricks](#some-tricks)
- [Windows Security Features](#windows-security-features)
- [WSL](#wsl)
- [WSA](#wsa)
- [Windows Emulator](#windows-emulator)
- [Linux Emulator](#linux-emulator)
- [Android Emulator](#android-emulator)
- [IOS Emulator](#ios-emulator)
- [Game Boy](#game-boy)
- [Nintendo Switch](#nintendo-switch)
- [Xbox](#Xbox)

## Game Engine
> Guide
- https://github.com/QianMo/Game-Programmer-Study-Notes
- https://github.com/raysan5/custom_game_engines [A comprehensive list of custom game engines]
- https://github.com/stevinz/awesome-game-engine-dev [Awesome Game Engine Development]
- https://github.com/Gforcex/OpenGraphic [Graphic Engine & Game Engine lists]
- https://github.com/bobeff/open-source-engines [A list of open source game engines]
- https://github.com/ThisisGame/cpp-game-engine-book
- https://github.com/netwarm007/GameEngineFromScratch
- https://forums.unrealengine.com [Unreal]
- https://docs.unrealengine.com [Unreal]
- https://www.unrealengine.com/resources [Unreal]
- https://github.com/donaldwuid/unreal_source_explained [Unreal]
- https://github.com/mikeroyal/Unreal-Engine-Guide [Unreal]
- https://github.com/Allar/ue5-style-guide [Unreal]
- https://github.com/revan1611/UE-Interview-Cheat-Sheet [Unreal]
- https://github.com/tomlooman/ue4-tutorials [Unreal]
- https://github.com/JaredP94/Unreal-Development-Guides-and-Tips [Unreal]
- https://github.com/lettier/3d-game-shaders-for-beginners [Shader]
- https://github.com/PardCode/OpenGL-3D-Game-Tutorial-Series [OpenGL]
- https://github.com/PardCode/CPP-3D-Game-Tutorial-Series [DirectX]
- https://github.com/ssloy/tinyrenderer [Render]
- https://github.com/crazyshader/GameDev [Unity]
- https://github.com/RyanNielson/awesome-unity [Unity]
- https://github.com/shadirvan/Unity-Cheat-Sheet [Unity]
- https://github.com/QianMo/Unity-Design-Pattern [Unity Design]
- https://github.com/whx-prog/The-Seed-Link-Future [Unity VR]
- https://github.com/twohyjr/Metal-Game-Engine-Tutorial [Apple's Metal Api]

> Source
- https://github.com/EpicGames/UnrealEngine
- https://github.com/Unity-Technologies/UnityCsReference [C# reference]
- https://github.com/cocos2d/cocos2d-x
- https://github.com/cocos/cocos-engine
- https://github.com/cocos/cocos4
- https://github.com/gmh5225/GameEngine-CRYENGINE
- https://github.com/panda3d/panda3d
- https://github.com/ValveSoftware/source-sdk-2013
- https://github.com/gmh5225/source-sdk-orangebox
- https://github.com/UTINKA/source-engine.2003
- https://github.com/gmh5225/SourceEngine2007
- https://github.com/nillerusr/source-engine
- https://github.com/gmh5225/GoldSourceRebuild [GoldSource engine rebuild]
- https://github.com/adriengivry/Overload
- https://github.com/gmh5225/GameEngine-MapleEngine
- https://github.com/inanevin/LinaEngine
- https://github.com/storm-devs/storm-engine
- https://github.com/minetest/minetest
- https://github.com/godotengine/godot
- https://github.com/gmh5225/reGS
- https://github.com/nem0/LumixEngine
- https://github.com/urho3d/Urho3D
- https://github.com/KorokEngine/Korok [Golang]
- https://github.com/BoomingTech/Pilot
- https://github.com/Sirkles/JoshoEngine-Native
- https://github.com/ExplosionEngine/Explosion
- https://github.com/danhuynh0803/Campfire
- https://github.com/lowenware/dotrix [Rust]
- https://github.com/bevyengine/bevy [Rust]
- https://github.com/FyroxEngine/Fyrox [Rust]
- https://github.com/AmbientRun/Ambient [Rust]
- https://github.com/not-fl3/macroquad [Rust 2D]
- https://github.com/AbyssEngine/AbyssEngine [ARPG]
- https://github.com/skylicht-lab/skylicht-engine
- https://github.com/ValveSoftware/halflife [Half-Life 1]
- https://github.com/SamVanheer/halflife-unified-sdk [Half-Life SDK]
- https://github.com/alliedmodders/hl2sdk [Half-Life SDK]
- https://github.com/ezhangle/hlmaster [Half-Life Master Server]
- https://github.com/MonoGame/MonoGame [.NET]
- https://github.com/vchelaru/FlatRedBall [.NET 2D]
- https://github.com/nCine/nCine [2D]
- https://github.com/gameplay3d/gameplay [2D/3D]
- https://github.com/NoelFB/blah [C++ 2D]
- https://github.com/Squalr/Squally [C++ 2D]
- https://github.com/u3d-community/U3D [C++ 2D/3D]
- https://github.com/turbulenz/turbulenz_engine [HTML5]
- https://github.com/melonjs/melonJS [HTML5]
- https://github.com/egret-labs/egret-core [HTML5]
- https://github.com/pixijs/pixijs [HTML5]
- https://github.com/playcanvas/engine [HTML5 3D]
- https://github.com/TorqueGameEngines/Torque2D [2D]
- https://github.com/TorqueGameEngines/Torque3D [3D]
- https://github.com/gmh5225/GameEngine-CX3D [3D]
- https://github.com/solenum/exengine [C99 3D]
- https://github.com/TheCherno/Hazel
- https://github.com/duddel/yourgamelib
- https://github.com/Serious-Engine/Base
- https://github.com/benanil/Castle-Engine [DX11]
- https://github.com/OpenArena/engine [quake3]
- https://github.com/rbfx/rbfx [C# support and WYSIWYG editor]
- https://github.com/BobbyAnguelov/Esoterica
- https://github.com/ZDoom/gzdoom [Doom]
- https://github.com/UZDoom/UZDoom [Doom source port, GZDoom continuation]
- https://github.com/L-Spiro/L.-Spiro-Engine-2022
- https://github.com/MohitSethi99/ArcEngine
- https://github.com/gscept/nebula
- https://github.com/irisengine/iris [cross-platform C++]
- https://github.com/WistfulHopes/NightSkyEngine [A fighting game engine written in Unreal Engine 5]
- https://github.com/ObEngine/ObEngine [2D+Lua]
- https://github.com/harukumo/HorizonEngine [3D rendering engine]
- https://github.com/benjinx/Toon [C++]
- https://github.com/chrismaltby/gb-studio [GameBoy]
- https://github.com/orx/orx [C++]
- https://github.com/gmh5225/EtherealEngine [C++]
- https://github.com/clibequilibrium/EquilibriumEngine [C++] 
- https://github.com/turanszkij/WickedEngine [C++ 3D]
- https://github.com/AustinBrunkhorst/Ursine3D [C++ 3D]
- https://github.com/RavEngine/RavEngine [C++ 3D]
- https://github.com/asc-community/MxEngine [C++ 3D]
- https://github.com/jmorton06/Lumos [C++ 2D/3D]
- https://github.com/fredakilla/GPlayEngine [C++ 2D/3D]
- https://github.com/crownengine/crown [C++ 2D/3D]
- https://github.com/FlaxEngine/FlaxEngine [C++/C# 3D]
- https://github.com/stride3d/stride [C# 3D]
- https://github.com/Net5F/AmalgamEngine
- https://github.com/rxi/kit [pixels]
- https://github.com/isadorasophia/murder [pixel]
- https://github.com/nitaigao/engine-showcase [Old engine]
- https://github.com/PanosK92/SpartanEngine [Research-focused game engine designed for real-time solutions]
- https://github.com/OpenXRay/xray-16 [Improved version of the X-Ray Engine]
- https://github.com/love2d/love [2D game framework for Lua]
- https://github.com/PixelGuys/Cubyz [3D voxel sandbox game written by Zig language]


> Game Engine Plugins:Unreal
- [Plugin for UE4 to user Rider for Unreal Engine as code editor](https://github.com/JetBrains/RiderSourceCodeAccess)
- [Design-agnostic node system for scripting game’s flow in Unreal Engine](https://github.com/MothCocoon/FlowGraph)
- [Sample Unreal Engine 5.0.1 C++ Project That Incorporates Dear ImGui](https://github.com/stungeye/UE5-With-Dear-ImGui)
- [A set of tools and utilities for use with Unreal Engine projects using ImGui](https://github.com/nakdeyes/UnrealImGuiTools)
- [A simple Unreal Engine subsystem to provide a more accurate server world time to clients](https://github.com/Erlite/NetworkTimeSync)
- [UE4 UI Texture Validator Plugin](https://github.com/benui-dev/UE-BUIValidator)
- [Unreal Engine .NET 6 integration](https://github.com/nxrighthere/UnrealCLR)
- [Houdini Engine Plugin for Unreal Engine](https://github.com/sideeffects/HoudiniEngineForUnreal)
- [A small tutorial repository on capturing images with semantic annotation from UnrealEngine to disk](https://github.com/TimmHess/UnrealImageCapture)
- [UE4 plugin for live2d model](https://github.com/Arisego/UnrealLive2D)
- [An Unreal Engine code plugin that adds a custom asset type and editor to the engine](https://github.com/JanKXSKI/AssetTutorialPlugin)
- [Unreal Engine 4 Plugin for Lua APIs implementation](https://github.com/rdeioris/LuaMachine)
- [Debug Menu for UnrealEngine4](https://github.com/000-aki-000/GameDebugMenu)
- ['Dear Imgui' remote access library and application](https://github.com/sammyfreg/netImgui)
- [Customizable performance metric charts and STAT commands control panel](https://github.com/DarknessFX/DFoundryFX)
- [Unreal Engine plugin providing a set of Hermes endpoints](https://github.com/cdpred/RedTalaria)
- [Unreal Engine 4 Plugin for Lua APIs implementation](https://github.com/rdeioris/LuaMachine)
- [Copies the argument string to the clipboard and outputs the characters copied to the clipboard](https://github.com/aoharudesu/Clipboard_Tools-UE4)
- [Generic graph data structure plugin for ue4](https://github.com/jinyuliao/GenericGraph)
- [A quick implementation of modular game features for the 'BTS' test](https://github.com/gmh5225/BT_ModularGameFeatures)

> Game Engine Plugins:Unity
- [A markdown viewer for unity](https://github.com/gwaredd/UnityMarkdownViewer)
- [An integrated solution for authoring / importing / simulating / rendering strand-based hair in Unity](https://github.com/Unity-Technologies/com.unity.demoteam.hair)
- [A maintained collection of useful & free unity scripts / library's / plugins and extensions](https://github.com/michidk/Unity-Script-Collection)
- [ChatGPT integration with Unity Editor](https://github.com/keijiro/AICommand)
- [Code editor integration for supporting Cursor as code editor for unity](https://github.com/boxqkrtm/com.unity.ide.cursor)

> Game Engine Plugins:Godot
- https://github.com/libriscv/godot-sandbox [Sandboxing that enables safe modding for Godot games]
- https://github.com/gtibo/Godot-Plush-Character [3D Plush Character for Godot 4.x]

> Game Engine Plugins:Lumix
- https://github.com/nem0/lumixengine_maps [Map downloader]


> Game Engine Detector
- https://github.com/walzer/game-engine-detector [Mobile Game]


## Mathematics
- https://github.com/nfrechette/rtm
- https://github.com/Groovounet/glm
- https://github.com/microsoft/DirectXMath
- https://github.com/Kazade/kazmath
- https://github.com/milakov/int_fastdiv
- https://github.com/freemint/fdlibm
- https://github.com/Jaysmito101/cgl

## Renderer
- https://github.com/bkaradzic/bgfx [Rendering library]
- https://github.com/DiligentGraphics/DiligentEngine [Rendering library]
- https://github.com/kanition/pbrtbook [Physically Based Rendering: From Theory To Implementation]
- https://github.com/keith2018/SoftGLRender
- https://github.com/DQLin/VolumetricReSTIRRelease
- https://github.com/HackerPoet/NonEuclidean
- [A graphics engine designed to run on a single thread on CPU](https://github.com/FHowington/CPUEngine) 
- https://github.com/paroj/gltut [OpenGL Render]
- https://github.com/ashawkey/raytracing [RayTracer]
- https://github.com/sultim-t/xash-rt [Xash3D FWGS with a real-time path tracing]
- https://github.com/crosire/reshade [A generic post-processing injector for games and video software]
- https://github.com/harukumo/HorizonEngine [3D rendering engine]
- https://github.com/Patryk27/strolle [Real-time rendering engine]
- https://github.com/ssloy/tinyraytracer [A brief computer graphics / rendering course]
- https://github.com/freetype/freetype [Render fonts]
- https://github.com/MethanePowered/MethaneKit [DirectX 12, Metal & Vulkan]
- https://github.com/EmbarkStudios/kajiya [Experimental real-time global illumination renderer]

## 3D Graphics
- https://github.com/gmh5225/mesa
- https://github.com/MethanePowered/MethaneKit [DirectX 12, Metal & Vulkan]
- https://github.com/mrdoob/three.js [JavaScript 3D Library]

## AI
- https://github.com/ls361664056/GameAI-paper-list [zh]

## Image Codec
- https://github.com/nothings/stb
- https://github.com/libjpeg-turbo/libjpeg-turbo
- https://github.com/erkkah/tigr
- https://github.com/tsoding/olive.c

## Wavefront Obj
- https://github.com/tinyobjloader/tinyobjloader
- https://github.com/Twinklebear/tobj [Rust]

## Task Scheduler
- https://github.com/SergeyMakeev/TaskScheduler

## Game Network
> Guide
- https://github.com/MFatihMAR/Game-Networking-Resources
- https://partner.steamgames.com/doc/api/ISteamNetworkingMessages#functions_sendrecv [Steam]
- https://github.com/mcxiaoke/mqtt [mqtt]

> Source
- https://github.com/cloudwu/skynet
- https://github.com/ketoo/NoahGameFrame [Server Engine]
- https://github.com/chronoxor/CppServer
- https://github.com/Qihoo360/evpp
- https://github.com/ValveSoftware/GameNetworkingSockets [Steam]
- https://github.com/skywind3000/kcp [KCP]
- https://github.com/Unit-X/kcp-cpp [KCP]
- https://github.com/TLeonardUK/ds3os [Dark Souls 3]
- https://github.com/TLeonardUK/ds2os [Dark Souls 2]
- https://github.com/rathena/rathena [MMORPG]
- https://github.com/TrinityCore/TrinityCore [Server for WOW]
- https://github.com/uNetworking/uWebSockets [WebSockets]
- https://github.com/socketio/socket.io [Nodejs]
- https://github.com/mqttjs/MQTT.js [mqtt nodejs]
- https://github.com/eclipse/paho.mqtt.cpp [mqtt cpp]
- https://github.com/topfreegames/pitaya [Server framework]
- https://github.com/azerothcore/azerothcore-wotlk [Server for WOW]
- https://github.com/arlyon/azerust [Rust Server for WOW]
- https://github.com/arlyon/awesome-wow-rust [Rust Server for WOW]
- https://github.com/2601677867/One-Click-Run_Source_Server [Server for Source Engine]

## PhysX SDK
- https://github.com/NVIDIAGameWorks/PhysX
- https://github.com/NVIDIAGameWorks/PhysX-3.4
- https://github.com/bulletphysics/bullet3


## Game Develop
> Guide
- https://github.com/Calinou/awesome-gamedev
- https://github.com/notpresident35/learn-awesome-gamedev
- https://github.com/yrgo/awesome-educational-games
- https://github.com/bobeff/open-source-games [A list of open source games]
- https://github.com/michelpereira/awesome-open-source-games [Collection of Games]
- https://github.com/raizam/gamedev_libraries [A collection of open source c/c++ libraries for gamedev]
- https://github.com/gheja/game-design-documents [Game design documents]
- https://github.com/Kavex/GameDev-Resources [Game Development resources]
- https://github.com/crazyshader/GameDev [Unity]
- https://github.com/RyanNielson/awesome-unity [Unity]
- https://github.com/QianMo/Unity-Design-Pattern [Unity Design]
- https://github.com/michal-z/zig-gamedev [Building game development ecosystem for ziglang]
- https://github.com/OTFCG/Awesome-Game-Analysis [Video game tech analysis resources]
- https://github.com/killop/anything_about_game [Game Development resources]
- https://github.com/TastSong/GameProgrammerStudyNotes [Game Development notes]
- https://github.com/gmh5225/gtav-sourcecode-build-guide [GTA V Source Code Build Tutorial]

> Source
- https://github.com/PiMoNFeeD/csgo-src [Leaked CSGO]
- https://github.com/perilouswithadollarsign/cstrike15_src [Leaked CSGO With CI]
- https://github.com/gmh5225/Far-Cry-1-Source-Full [Leaked Far Cry 1]
- https://github.com/gmh5225/FarCry [Leaked Far Cry 1]
- https://github.com/SwagSoftware/Kisak-Strike [Open Source CSGO]
- https://github.com/SwagSoftware/KisakCOD [COD4 Open Source Reimplementation]
- https://github.com/gmh5225/csso-src [CSGO Mod]
- https://github.com/thomaseichhorn/cs16-client [Rewrote CS1.6]
- https://github.com/s1lentq/ReGameDLL_CS [Reversed CS1.6]
- https://github.com/Velaron/cs16-client [Reversed CS1.6]
- https://github.com/Source2ZE/CS2Fixes [CS2 mod]
- https://github.com/gmh5225/Game-GTA-re3 [Reversed GTA III, Vice City]
- https://github.com/gmh5225/reGTA [Reverse Engineered GTA III and GTA VC]
- https://github.com/gta-reversed/gta-reversed-modern [Reimplementation of GTA:SA 1.0 US]
- https://github.com/gmh5225/Grand-Theft-Auto-Modding-Source [Code snippets for Vice City]
- https://github.com/SmileyAG/ReCZDS [Reversed CZeror]
- https://github.com/Harrison1/unrealcpp [UE4 C++ examples]
- https://github.com/QianMo/UE4-FPS-Game [UE4 FPS Game]
- https://github.com/KitchenGun/UE4_FPS [UE4 FPS Demo]
- https://github.com/tomlooman/SimpleFPSTemplate [UE4 FPS Demo]
- https://github.com/tomlooman/EpicSurvivalGame [UE4 FPS Game]
- https://github.com/QianMo/UE4-Tank-Game [UE4 Game]
- https://github.com/UE-DEMO/UE-UE5-FPS-wlaster [UE5 FPS Game]
- https://github.com/gmh5225/UE5-FPS-CryptRaider [UE5 FPS Game]
- https://github.com/LeroyTechnologies/ProjectM [UE5 FPS Game]
- https://github.com/invi1998/MultiplayerBlasterGame [UE5 FPS Game]
- https://github.com/DruidMech/MultiplayerCourseBlasterGame [UE5 FPS Game]
- https://github.com/gmh5225/UE5MultiplayerProject [UE5 horror game with anti-cheat]
- https://github.com/perfect-hand/ue5-cardgame [UE5 Card Game]
- https://github.com/stackOverflower92/FightingGame-UE5 [UE5 Fighting Game]
- https://github.com/gmh5225/UnrealEngine5-UltimateStreetFighters [UE5 StreetFighters Game]
- https://github.com/EvelynSchwab/ComponentFuseMechanic [UE5 constraining system]
- https://github.com/CobraCodeDev/TP_2DSideScrollerBP [UE5 2D template]
- https://github.com/gmh5225/ue5-roll-a-ball-game [UE5 Roll a Ball Game]
- https://github.com/tomlooman/ActionRoguelike [UE Roguelike Game]
- https://github.com/Unity-Technologies/FPSSample [Unity Game]
- https://github.com/OguzKaira/FPS-Movement [Unity FPS]
- https://github.com/OguzKaira/SQLite-Unity3D [Unity SQLite]
- https://github.com/swordjoinmagic/MoBaDemo [Unity MoBa]
- https://github.com/gmh5225/U3D_MiniDNF [Unity mini DNF]
- https://github.com/gmh5225/unity-vrchat-template [Unity VRChat Template]
- https://github.com/Saukiya/Arknights [Unity Arknights]
- https://github.com/ZehMatt/SnakeRoyal [Mini Game With Server]
- https://github.com/MKXJun/Super-Fighter [DX11 Mini Game]
- https://github.com/MKXJun/Rubik-Cube [DX9/11 Mini Game]
- https://github.com/Suprcode/mir2 [MIR2]
- https://github.com/Suprcode/mir3-zircon [MIR3]
- https://github.com/WolfireGames/overgrowth [Overgrowth]
- https://github.com/solidi/hl-mods [Modification For Half-Life]
- https://github.com/codingben/maple-fighters [A small online game similar to MapleStory]
- https://github.com/gmh5225/WinAPI_MapleStory [WinAPI MapleStory]
- https://github.com/ZeromaXHe/MapleStoryCopy [Godot MapleStory]
- https://github.com/loqix/Fortnite [Fortnite]
- https://github.com/bradharding/doomretro [DOOM]
- https://github.com/Daivuk/PureDOOM [DOOM]
- https://github.com/NSG650/NtDOOM [Doom running in the NT kernel]
- https://github.com/Luxon98/Super-Mario-Bros-game [Remake of Super Mario]
- https://github.com/plibither8/2048.cpp [2048]
- [An open source re-implementation of RollerCoaster Tycoon 2](https://github.com/OpenRCT2/OpenRCT2)
- [This is the old Paradise SPRX BO2 soruce code](https://github.com/gopro2027/ParadiseBO2)
- https://github.com/dreamstalker/rehlds [Reverse-engineered HLDS]
- https://github.com/AndroidModLoader/AndroidModLoader [Android Mod Loader]
- https://github.com/marblexu/PythonPlantsVsZombies [PlantsVsZombies]
- https://github.com/mhyousefi/ZombiesVsPlants [PlantsVsZombies]
- https://github.com/Fewnity/Counter-Strike-DS-Unity-Project [Unity CS]
- https://github.com/Fewnity/Counter-Strike-Nintendo-DS [Nintendo CS]
- https://github.com/ppy/osu [osu]
- https://github.com/ppy/osu-framework [osu]
- https://github.com/dufernst/LegionCore-7.3.5 [wow]
- https://github.com/RageProject/5.4.7-Wow-source [wow]
- https://github.com/SkyFire/MopCore547 [wow]
- https://github.com/Arctium/WoW-Launcher [wow launcher]
- https://github.com/skMetinek/Non-Newtonian-New-York [Spider-Man Remastered Mod]
- https://github.com/playgameservices/cpp-android-basic-samples [Sample games using the Google Play Games C++ SDK]
- https://github.com/pafuhana1213/KawaiiPhysics [Simple fake Physics for UnrealEngine4 & 5]
- https://github.com/pafuhana1213/VTuberWithUE4 [UE4 VTuber]
- https://github.com/Bratah123/GojoTheSpire [Slay The Spire Remastered Mod]
- https://github.com/snesrev/zelda3 [A reimplementation of Zelda 3]
- https://github.com/kantam5/DeadByDaylight [Dead By Daylight Copy]
- https://github.com/Phobos-developers/Phobos [Red Alert 2: Yuri's Revenge engine extension]
- https://github.com/praydog/AutomataMP [NieR]
- https://github.com/xinyu-evolutruster/3D-Racing-Game [A racing game based on OpenGL]
- https://github.com/ProjectBorealis/PBCharacterMovement [HL2-style, classic FPS movement for UE4 implemented in C++]
- https://github.com/Merisho/tx-holdem [Texas Holdem Poker made by JS]
- https://github.com/raysan5/raylib [A simple and easy-to-use library to enjoy videogames programming]
- https://github.com/NotYetGames/WarriOrb [a Dark-Souls like action platformer using UE4]
- https://github.com/pjasicek/OpenClaw [Reimplementation of Captain Claw (1997) platformer]
- https://github.com/galaxyhaxz/devilution [Reversed Devilution]
- https://github.com/assaultcube/AC [FPS Game]
- https://github.com/fishfolk/jumpy [Pixels style]
- https://github.com/jynew/jynew [JinYongLegend]
- https://github.com/johndpope/pianogame [Piano Game]
- https://github.com/gmh5225/QQTang [QQTang]
- https://github.com/kvnxiao/storytime [Remake of MapleStory]
- https://github.com/deathkiller/jazz2-native [Remake of Jazz Jackrabbit 2]
- https://github.com/electronicarts/CnC_Red_Alert [Command and Conquer: Red Alert]
- https://github.com/huangkaoya/redalert2 [Red Alert 2 on Web]

> MCP server
- https://github.com/TensorBlock/awesome-mcp-servers [Awesome MCP]
- https://github.com/ahujasid/blender-mcp [Blender Model Context Protocol Integration]
- https://github.com/chongdashu/unreal-mcp [MCP for Unreal Engine]
- https://github.com/kvick-games/UnrealMCP [MCP for Unreal Engine]
- https://github.com/VedantRGosavi/UE5-MCP [MCP for Unreal Engine 5]
- https://github.com/justinpbarnett/unity-mcp [MCP for unity]
- https://github.com/wondeks/unity-mcp [MCP for unity]
- https://github.com/gmh5225/mcpup [MCP for unity]
- https://github.com/gmh5225/vibe-blocks-mcp [MCP for Roblox Studio]
- https://github.com/LaurieWired/GhidraMCP [MCP for Ghidra]
- https://github.com/gmh5225/GhidrAssistMCP [MCP for Ghidra]
- https://github.com/mrexodia/ida-pro-mcp [MCP for IDA pro]
- https://github.com/cnitlrt/headless-ida-mcp-server [MCP for IDA pro(headless)]
- https://github.com/MxIris-Reverse-Engineering/ida-mcp-server [MCP for IDA pro]
- https://github.com/taida957789/ida-mcp-server-plugin [MCP for IDA pro]
- https://github.com/fdrechsler/mcp-server-idapro [MCP for IDA pro]
- https://github.com/rand-tech/pcm [MCP for IDA pro]
- https://github.com/Iamgublin/ida-codex-mcp [IDA Codex MCP]
- https://github.com/axelmierczuk/tenrec [A headless, extendable, multi-session, IDA Pro MCP framework]
- https://github.com/blacktop/ida-mcp-rs [Headless IDA Pro MCP server]
- https://github.com/fosdickio/binary_ninja_mcp [MCP for Binary_Ninja]
- https://github.com/Invoke-RE/binja-lattice-mcp [MCP for Binary_Ninja]
- https://github.com/dnakov/radare2-mcp [Radare2 MCP Server]
- https://github.com/GLips/Figma-Context-MCP [Cursor Talk To Figma MCP server]
- https://github.com/gmh5225/hex2dec-mcp [MCP server that provides conversion between hexadecimal and decimal numbers]
- https://github.com/signal-slot/mcp-gdb [MCP for GDB]
- https://github.com/svnscha/mcp-windbg [MCP for WinDBG]
- https://github.com/AgentSmithers/x64DbgMCPServer [MCP for x64Dbg]
- https://github.com/bromoket/x64dbg_mcp [MCP for x64Dbg with extensive tooling]
- https://github.com/IChooseYou/Reclass [MCP for Reclass]
- https://github.com/ant4g0nist/lisa.py [MCP for LLDB]
- https://github.com/droidrun/droidrun [MCP for Android]
- https://github.com/un4ckn0wl3z/MemMCP [Cheat Engine-like but MCP]
- https://github.com/Eruditi/CE-MCP-Plugin [MCP for Cheat Engine]
- https://github.com/miscusi-peek/cheatengine-mcp-bridge [MCP for Cheat Engine]
- https://github.com/beamstar/cheatengine-mcp-bridge [MCP for Cheat Engine]
- https://github.com/illegal-instruction-co/processhacker-mcp [MCP for runtime analysis and process hacking; ProcessHacker for AI agents, extensible with DLL plugins]
- https://github.com/zinja-coder/apktool-mcp-server [A MCP Server for APK Tool (Part of Android Reverse Engineering MCP Suites)]
- https://github.com/regenrek/deepwiki-mcp [MCP for deepwiki]
- https://github.com/gmh5225/zig-mcp-server [A high-performance implementation of the MCP protocol in Zig]
- https://github.com/noopstudios/interactive-feedback-mcp [Interactive User Feedback MCP]
- https://github.com/gmh5225/interactive-feedback-macos-mcp [A native macOS MCP server for collecting interactive user feedback with AppleScript dialogs and image support]
- https://github.com/datalayer/jupyter-mcp-server [MCP for Jupyter]
- https://github.com/PortSwigger/mcp-server [MCP for Burp Suite]
- https://github.com/cycraft-corp/BinaryAnalysisMCPs [Binary analysis MCPs collections]

> MCP server security
- https://github.com/johnhalloran321/mcpSafetyScanner [MCPSafetyScanner - Automated MCP safety auditing and remediation using Agents]
- https://github.com/appsecco/vulnerable-mcp-servers-lab [A collection of servers which are deliberately vulnerable to learn Pentesting MCP Servers]

> AI Agents
- https://github.com/0xeb/windbg-copilot [WinDbg Copilot - Agentic Debugging extension]


## Game Assets
- https://github.com/Miziziziz/Retro3DGraphicsCollection
- https://github.com/HitmanHimself/GOWTool [God of War 2018]
- https://github.com/KhronosGroup/glTF [Runtime 3D Asset Delivery]
- https://github.com/syoyo/tinygltf [Header only C++11 tiny glTF 2.0 library]
- https://github.com/atenfyr/UAssetGUI [Viewing and modifying UE4 game assets]
- https://github.com/UETools/UETools [Accessing, reading and deserializing UE4 assets]
- https://github.com/atenfyr/UAssetAPI [A low-level .NET library for reading and writing Unreal Engine game assets]

## Game Hot Patch
- https://github.com/Tencent/xLua
- https://github.com/Tencent/InjectFix
- https://github.com/focus-creative-games/hybridclr


## Game Testing
- https://github.com/UnityTech/GamesTestAutomationExample [The collecting ideas on how to do Test Automation in Games]
- https://github.com/nowsprinting/UnityAutomatedQAExamples [Unity Automated QA Guidebook]
- https://github.com/AirtestProject/Airtest [UI Automation Framework]
- https://github.com/dendibakh/perf-ninja [Performance Analysis]
- https://github.com/CookiePLMonster/UptimeFaker [Detecting High PC Uptime]
- https://github.com/GameTechDev/PresentMon [Graphics Performance]
- https://github.com/gatling/gatling [Server Testing]
- https://github.com/aristocratos/btop [Performance Monitor]
- https://github.com/Celtoys/Remotery [A realtime CPU/GPU profiler]
- https://github.com/Volkanite/Push [Monitor GPU/CPU/RAM performance]
- https://github.com/google/orbit [C/C++ Performance Profiler]
- https://github.com/wolfpld/tracy [C++ frame profiler]
- https://github.com/bombomby/optick [C++ Profiler For Games]
- https://github.com/RomanceTheHeart/Automation_Examples [Automating certain tasks in the Unreal editor]
- https://github.com/DaedalicEntertainment/ue4-test-automation [Facilitates setting up integration test suits with Unreal Engine 4 Gauntlet]
- https://github.com/DenuvoSoftwareSolutions/Onlooker [Tool to collect and visualize memory usage of a process tree]
- https://github.com/milostosic/rprof [CPU scope based profiling library]
- https://github.com/DarknessFX/DFoundryFX [UE Performance]

## Game Tools
- [Play your favorite games in a borderless window; no more time consuming alt-tabs](https://github.com/Codeusa/Borderless-Gaming)
- https://github.com/bad-antics/rce-shield [RCE hardening toolkit for PC gamers]
- https://github.com/Genymobile/scrcpy [Display and control your Android device]
- https://github.com/ryanjon2040/Unreal-Binary-Builder [Build UE Source]
- https://github.com/ryanjon2040/UnrealNetworkProfiler [Network Profiler for UE]
- [Command line tool for getting the download URL for the latest or specific version of Unity](https://github.com/neogeek/get-unity)
- https://github.com/recastnavigation/recastnavigation [Navigation-mesh Toolset for Games]
- https://github.com/TensorWorks/UE-Clang-Format [UE Clang-Format configuration]
- https://github.com/inflation/goldberg_emulator [Steam emulator]
- https://github.com/PixiEditor/PixiEditor [PixiEditor is a Universal Editor for all your 2D needs]

## Game Manager
- https://github.com/JosefNemec/Playnite

## Game CI
- https://github.com/game-ci
- https://github.com/nikaera/Unity-GameCI-Sample [Unity]

## DirectX
> Guide
- https://github.com/planetchili/hw3d [C++ 3D DirectX Tutorial]
- https://github.com/jpvanoosten/LearningDirectX12 [DX12]
- https://github.com/PAMinerva/LearnDirectX [DX12]
- https://github.com/MKXJun/DirectX11-With-Windows-SDK [DX11 zh]
- https://github.com/d3dcoder/d3d12book [DX12]
- https://github.com/pkurth/D3D12Renderer [DX12]

> Hook
- https://github.com/rdbo/DX11-BaseHook [DX11 Imgui]
- https://github.com/DrNseven/D3D12-Hook-ImGui [DX12 Imgui]
- https://github.com/niemand-sec/DirectX11Hook [DX11 Imgui]
- https://github.com/guided-hacking/GH_D3D11_Hook [DX11]
- https://github.com/gogo9211/Discord-Overlay-Hook [DX11]
- https://github.com/ocornut/imgui/commit/923bd2fd217c1dc1e75fa92b0284d3817904988b [DX11/12 ResizeBuffers]
- https://github.com/marlkiller/d3dhook_imgui [d3d opengl hook imgui x86/x64]
- [Universal graphical hook for a D3D9-D3D12, OpenGL and Vulkan based games](https://github.com/Rebzzel/kiero)
- https://github.com/jmpews/Dobby [a lightweight, multi-platform, multi-architecture hook framework]
- https://github.com/Sh0ckFR/Universal-Dear-ImGui-Hook [An universal Dear ImGui Hook]
- https://github.com/bruhmoment21/UniversalHookX [DX/OpenGL/Vulkan]

> Tools
- https://github.com/visotw/3d9 [Fixing broken stereoscopic effects in DX11 games]

> Emulation 
- https://github.com/code-tom-code/Software_D3D9 [DX9]

> Compatibility
- https://github.com/CnCNet/cnc-ddraw [Old Game]
- https://github.com/microsoft/D3D9On12 [The Direct3D9-On-12 mapping layer]
- https://github.com/Daniel-Lobo/WineHooks [Compatibility and enhancement framework for classic PC games]
- https://github.com/samuelgr/Xidi [DirectInput interface for XInput controllers]

> Overlay
- https://github.com/SeanPesce/Direct3D9-Overlay

## OpenGL
> Guide
- https://github.com/JoeyDeVries/LearnOpenGL

> Source
- https://github.com/brackeen/glfm [Write OpenGL ES code in C/C++]

> Hook
- https://github.com/bruhmoment21/UniversalHookX

## Vulkan
> Guide
- https://github.com/googlesamples/android-vulkan-tutorials

> API
- https://github.com/liblava/liblava [Modern and easy-to-use library for Vulkan]
- https://github.com/corporateshark/lightweightvk

> Hook
- https://github.com/Rebzzel/kiero [X86/64 Windows]
- https://github.com/bruhmoment21/UniversalHookX [X86/64 Windows]
- https://github.com/gmh5225/Vulkan-Hook [X86/64 Windows]
- https://github.com/Sh0ckFR/Universal-Dear-ImGui-Hook
- https://github.com/Halen84/ImGuiRDR2Hook

## Cheat
> Guide
- https://github.com/dsasmblr/game-hacking
- https://github.com/dsasmblr/hacking-online-games
- https://github.com/jbro129/android-modding [A collection of repositories related to Android game modding]
- https://github.com/kovidomi/game-reversing
- https://github.com/TheZong/Game-Hacking
- https://github.com/mytechnotalent/Reverse-Engineering
- https://github.com/wtsxDev/reverse-engineering
- https://github.com/mytechnotalent/Hacking-Windows
- https://github.com/kotae4/intro-to-gamehacking
- https://blog.can.ac/author/can1357
- https://github.com/SinaKarvandi/Hypervisor-From-Scratch [Hypervisor]
- https://secret.club
- https://back.engineering
- https://vollragm.github.io
- https://www.triplefault.io
- https://advancedvectorextensions.github.io
- https://bright.engineer
- https://reversing.info
- https://www.unknowncheats.me
- https://forum.ragezone.com
- https://guidedhacking.com
- https://github.com/guided-hacking
- https://gamehacking.academy
- https://github.com/GameHackingAcademy
- https://areweanticheatyet.com [A list of games using anti-cheats]
- https://github.com/aclist/aclist.github.io [Anti-cheat compatibility list]
- https://github.com/imadr/Unity-game-hacking [Unity]
- https://vollragm.github.io/posts/unity-reversing [Unity]
- https://wiki.cheatengine.org/index.php?title=Mono [CE Mono]
- https://github.com/krampus-nuggets/ce-tutorial [CE]
- https://il2cppdumper.com [IL2CPP]
- https://www.unknowncheats.me/forum/unity/465283-il2cppruntimedumper.html [IL2CPP]
- https://github.com/shalzuth/NativeNetSharp [Injecting C# code]
- https://github.com/januwA/game-reversed-study [CE Guide zh]
- https://github.com/csgohacks/master-guide [CSGO Guide]
- [different-ways-hooking](https://www.unknowncheats.me/forum/general-programming-and-reversing/154643-different-ways-hooking.html) [Hook Guide]
- http://pwnadventure.com [Hackable Game]
- https://github.com/GameCrashProject/UE4-Hacking-Guideline [Unreal]
- https://github.com/TimMisiak/WinDbgCookbook [WinDbg]
- https://github.com/anhkgg/awesome-windbg-extensions [WinDbg]
- [Undetected Cheat Engine](https://www.unknowncheats.me/forum/anti-cheat-bypass/504191-undetected-cheat-engine-driver-2022-bypass-anticheats-eac.html)
- [Guide about remote Windows kernel debugging](https://github.com/konstantin89/windows-kernel-debugging-guide)
- https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Games.md [Game Hacking]
- https://github.com/cragson/osmium [C++ Framework for external cheats]
- https://github.com/WangXuan95/Xilinx-FPGA-PCIe-XDMA-Tutorial [DMA Tutorial]
- https://github.com/NetKingJ/awesome-android-security [Android (Samsung) Security Research References]
- https://github.com/gregkh/kernel-development [Linux kernel development]
- https://github.com/MatheuZSecurity/Rootkit [Collection of codes focused on Linux rootkits]
- https://github.com/ARandomPerson7/Appsealing-Reversal [A Reversal and bypass for Appsealing]
- https://klecko.github.io/posts/selinux-bypasses [Bypass selinux]
- https://github.com/Solaree/pairipcore [Public researchings of the Google's Android apps protection]
- https://github.com/enjoy-digital/litepcie [Small footprint and configurable PCIe core]
- https://lolc2.github.io [collection of C2 frameworks that leverage legitimate services to evade detection]

> Debugging
- https://github.com/stars/gmh5225/lists/debugger [List]
- https://github.com/cheat-engine/cheat-engine
- https://github.com/SinaKarvandi/Hypervisor-From-Scratch [Hypervisor]
- https://github.com/JasonGoemaat/CheatEngineMonoHelper [CE Mono Helper]
- https://github.com/gmh5225/frida-ceserver [CE Server For IOS]
- https://github.com/gmh5225/ceserver-ios [Porting ceserver to iOS.Dynamic analysis]
- https://github.com/gmh5225/ceserver-ios [An iOS port of Cheat Engine's ceserver]
- https://github.com/gmh5225/cheat-engine-ceserver-pcileech [CE Server For Pcileech]
- https://github.com/gmh5225/veh [CE Plugin For Manualmap VEH Dll]
- https://github.com/gmh5225/x64dbg [A debugger for Windows x86/64]
- https://github.com/gmh5225/syser [A debugger for Windows x86/64]
- https://github.com/gmh5225/koidbg [A debugger for Windows ARM64]
- https://github.com/DoranekoSystems/DynaDbg [A debugger for Android/IOS]
- https://github.com/gmh5225/fastDbg [x86_64 native/qemu kernel debugger]
- https://github.com/gmh5225/GDB-Windows-Binaries [GDB]
- https://github.com/ajkhoury/ReClassEx
- https://github.com/gmh5225/ReClass.NET
- https://github.com/gmh5225/ReClass.NET-DriverReader [ReClass DriverReader]
- https://github.com/gmh5225/KReClassEx [Kernel ReClassEx]
- https://github.com/gmh5225/ReClass-DMA [ReClass DMA]
- https://github.com/IChooseYou/Reclass [Reclass MCP refactored]
- https://github.com/gmh5225/CheatEngine-DMA [CheatEngine DMA]
- https://github.com/gmh5225/Cheat-Engine-DMA-Plugin [CheatEngine DMA]
- https://github.com/gmh5225/DotX64Dbg
- https://github.com/gmh5225/xdv
- https://github.com/gmh5225/edb-debugger [For Linux]
- https://github.com/gmh5225/PINCE [For Linux]
- https://github.com/gmh5225/kLLDB [LLDB based debugger for Linux Kernel]
- https://github.com/gmh5225/TitanHide
- https://github.com/gmh5225/HyperHide 
- https://github.com/gmh5225/HyperDbg
- https://github.com/gmh5225/vt-debuger
- https://github.com/gmh5225/execution-trace-viewer
- https://github.com/changeofpace/Force-Page-Protection [Bypass Remap Memory]
- https://github.com/gmh5225/ILSpy [For Unity]
- https://github.com/gmh5225/dnSpy [For Unity]
- https://github.com/gmh5225/dnSpy.Extension.HoLLy [For Unity]
- https://github.com/gmh5225/dncil [For Unity]
- https://github.com/gmh5225/CFB [Monitor IRP]
- https://github.com/gmh5225/IOCTLDump [Monitor IRP]
- https://ioninja.com/downloads.html [Protocol Analyzer]
- https://github.com/gmh5225/SteamAntiAntiDebug [Steam]
- https://github.com/gmh5225/H5GG [IOS cheat engine]
- https://github.com/gmh5225/pwatch [HWBP on linux/android]
- https://github.com/enenH/pwatch-c [HWBP on linux/android]
- https://github.com/gmh5225/hardware-breakpoint [HWBP on linux/android]
- https://github.com/gmh5225/JDBG [Java Runtime Reverse Engineering and Debugging Tool]
- https://github.com/gmh5225/eDBG [eBPF-based lightweight debugger for Android]
- https://github.com/gmh5225/eHook [eBPF hook]
- https://github.com/gmh5225/stackplz [eBPF-based debugger for Android]
- https://github.com/gmh5225/edbgserver [eBPF-powered debugger server for Linux and Android]
- https://github.com/gmh5225/qbdi-tracer-android [Android assembly instruction tracing tool]
- https://github.com/un4ckn0wl3z/MemMCP [Cheat Engine-like but MCP]
- https://github.com/gmh5225/eBPFDexDumper [DexDumper based eBPF on Android Platform]

> Packet Sniffer&Filter
- https://github.com/gmh5225/win-shaper
- https://github.com/gmh5225/ndisapi
- https://github.com/gmh5225/Akebi-PacketSniffer
- https://github.com/gmh5225/Divert [Packet Divert]
- https://github.com/gmh5225/inject
- https://github.com/gmh5225/Packet-Sniffer [Packet Logger/Decryptor]

> Packet Capture&Parse
- https://github.com/gmh5225/PcapPlusPlus [Pcap]
- https://github.com/gmh5225/npcap

> SpeedHack
- https://github.com/gmh5225/Speedhack
- https://github.com/gmh5225/Speed-Hack
- https://github.com/gmh5225/ce_speed_hack

> RE Tools
- https://dogbolt.org
- https://github.com/gmh5225/cve-maker [Tool to find CVEs and Exploits]
- https://github.com/gmh5225/retoolkit [Reverse Engineer's Toolkit]
- https://github.com/gmh5225/RETools
- https://github.com/gmh5225/ACEPatcher [.NET Patcher]
- https://github.com/gmh5225/KACE [Emulate Drivers in RING3 with self context mapping or unicorn]
- https://github.com/gmh5225/KACE [Emulate Drivers in RING3 with self context mapping or unicorn]
- https://github.com/VollRagm/PTView [Browse Page Tables on Windows]
- https://github.com/gmh5225/Apktool [Apk]
- https://github.com/gmh5225/Obfu-DE-Scate [Apk]
- https://github.com/gmh5225/APKToolGUI [GUI for apktool, signapk, zipalign and baksmali utilities]
- https://github.com/Genymobile/scrcpy  [Display and control your Android device]
- https://github.com/gmh5225/QtScrcpy [Display and control your Android device]
- https://github.com/gmh5225/GH-Offset-Dumper [Scans for signatures and netvars and dumps their relative offsets]
- https://github.com/gmh5225/GH-Entity-List-Finder [Scans game processes for most likely entity list addresses]
- https://github.com/gmh5225/APKiD [PEiD for Android]
- https://github.com/gmh5225/Recaf [Java]
- https://github.com/gmh5225/SE-tools [Nintendo Switch]
- https://github.com/gmh5225/XCI-Explorer [XCI Explorer]
- https://github.com/gmh5225/JitDumper [A CIL method body dumper]
- https://github.com/gmh5225/Android_boot_image_editor [A tool for reverse engineering Android ROM images]
- https://github.com/gmh5225/pe-bear [PE Viewer]
- https://github.com/gmh5225/TotalPE2 [PE Viewer]
- https://github.com/gmh5225/APKLab [Android Reverse-Engineering Workbench for VS Code]
- https://github.com/gmh5225/unflutter [Static analyzer for Flutter/Dart AOT snapshots]
- https://github.com/gmh5225/MemProcFS-Analyzer [Windows Forensic Analysis]
- https://github.com/gmh5225/kavanoz [Statically unpacking common android banker malware]
- https://github.com/gmh5225/PipeViewer [Shows detailed information about named pipes in Windows]
- https://github.com/gmh5225/regenny [Reconstruct structures and generate header files]
- https://github.com/gmh5225/EtwExplorer [View ETW Provider manifest]
- https://github.com/gmh5225/ceserver-ios [Porting ceserver to iOS.Dynamic analysis]
- https://github.com/gmh5225/ioctlpus [Be used to make DeviceIoControl requests with arbitrary inputs]
- https://github.com/gmh5225/Nauz-File-Detector [Linker/Compiler/Tool detector]
- https://github.com/gmh5225/HexWalk [Hex Viewer/Editor/Analyzer]
- https://github.com/gmh5225/ioctl_helper [GUI tool for sending IOCTL to windows drivers]
- https://github.com/gmh5225/dwex [DWARF Explorer]
- https://github.com/gmh5225/RisohEditor [Win32 resource editor]
- https://github.com/gmh5225/de4py [Toolkit for python reverse engineering]
- https://github.com/gmh5225/minidump [Python library to parse and read Microsoft minidump file format]
- https://github.com/gmh5225/QuickAsm [x86/x86 assembler and emulator]
- https://github.com/gmh5225/chasm [Chasm Runtime Assembler]
- https://github.com/gmh5225/jadx [Dex to Java decompiler]
- https://github.com/gmh5225/Deobfuscator [A deobfuscator for java]
- https://github.com/gmh5225/android-classyshark [Android and Java bytecode viewer]
- https://github.com/gmh5225/vmlinux-to-elf [vmlinux to elf]
- https://github.com/gmh5225/DbgViewEx [A tool to log ETW Events and system debug logs]
- https://github.com/gmh5225/binaryinternals [View Internals of Binary File]
- https://github.com/gmh5225/ImHex [A Hex Editor for Reverse Engineers]
- https://github.com/gmh5225/pdblister [Faster version of `symchk /om` for generating PDB manifests]
- https://github.com/gmh5225/vermagic [Change vermagic and CRCs of a Linux Kernel Module]
- https://github.com/gmh5225/pesign [Linux tools for signed PE-COFF binaries]
- https://github.com/gmh5225/UnSign [Remove all digital signatures from PE/COFF executable]
- https://github.com/gmh5225/PECleaner [Strips all RICH header information from x86/x64 binaries]
- https://github.com/gmh5225/AntiHook [Enum and Remove Hook in Windows]
- https://github.com/gmh5225/ApkSigner [Android Apk Sign Tool]
- https://github.com/gmh5225/VirtualKD-Redux [A revival and modernization of VirtualKD]
- https://github.com/gmh5225/apk.sh [A Bash script that makes reverse engineering Android apps easier]
- https://github.com/gmh5225/payload_dumper [Android OTA payload dumper]
- https://github.com/gmh5225/payload-dumper-go [Android OTA payload dumper]
- https://github.com/gmh5225/Xiaomi-HyperOS-BootLoader-Bypass [Xiaomi HyperOS BootLoader Bypass]
- https://github.com/gmh5225/btrace [Android App Dynamic Behavior Tracking Tool using eBPF]
- https://github.com/gmh5225/SignToolGUI [signtool GUI]
- https://disasm.pro/ [A realtime assembler/disassembler]
- https://github.com/gmh5225/abyss [Android system call hook]
- https://github.com/gmh5225/RPGMakerDecrypter [Tool for extracting RPG Maker XP, VX and VX Ace encrypted archives]
- https://github.com/gmh5225/compiler-binary-richprint [Print compiler information stored in Rich Header of PE executable]
- https://github.com/gmh5225/GoReSym [Go symbol recovery tool]
- https://github.com/gmh5225/shredos.x86_64 [Disk Eraser]
- https://github.com/gmh5225/hidden_syscall_monitoring [monitors hidden syscalls called from call of duty anticheat]
- https://github.com/gmh5225/pdbr [pdb + Rich library]
- https://github.com/gmh5225/pdb-rs [Tools and documents for working with Microsoft PDB files, in Rust]
- https://github.com/gmh5225/JDBG [Java Runtime Reverse Engineering and Debugging Tool]
- https://github.com/gmh5225/vulkan [A PE dumper for processes protected by user mode anti-tamper solutions (hyperion, theia, etc.)]
- https://github.com/gmh5225/fiano [Go-based tools for modifying UEFI firmware]
- https://github.com/gmh5225/PESignAnalyzer [A Simple PE File Signature information Extracting Tool]
- https://github.com/gmh5225/SDCM [Surface Dev Center Manager tool to automate WHQL/Attestation submissions]
- https://github.com/gmh5225/RuntimeViewer [Objective-C Runtime Viewer for macOS and iOS]
- https://github.com/gmh5225/raung [Assembler/disassembler for java bytecode]
- https://github.com/gmh5225/dayu [Open/HarmonyOS abc file parser and decompiler]
- https://github.com/gmh5225/arkdecompiler [HarmonyOS NEXT decompilation tool]
- https://github.com/gmh5225/dalvikus [Android reverse-engineering tool / smali editor]
- https://github.com/gmh5225/VMDragonSlayer [Advanced Virtual Machine Detection and Analysis Framework]
- https://github.com/gmh5225/XenonDumper [Dumps files & data required to use the Xenon Xbox 360 Low Level Emulator]
- https://github.com/gmh5225/DelphiReSym [A Delphi symbol name recovery tool for reverse engineers]
- https://github.com/gmh5225/Ouroboros [A Symbolic-Execution Decompiler written in Rust]
- https://github.com/gmh5225/re-architect [RE-Architect is an advanced automated reverse engineering platform that utilizes binary analysis techniques and machine learning to understand binary files and extract meaningful information]
- https://github.com/gmh5225/js-debugger-bypass-script [JS Debugger Bypass UserScript]
- https://github.com/gmh5225/DiaSymbolView [PDB file inspection tool]
- https://github.com/gmh5225/Nodejs-Tracer [Simple Node.jstracer that logs calls to analyze heavily obfuscated Node.js malware]
- https://github.com/gmh5225/ntoskrnlwalker [Resolve offsets, gadgets and symbols from NTKernel]

> Mixed boolean-arithmetic
- https://github.com/Colton1skees/mba-resources [List of mixed boolean-arithmetic resources]

> Fix VMP
- https://github.com/gmh5225/VMProtect
- https://github.com/gmh5225/NoVmpy
- https://github.com/gmh5225/VMP-Vmp3_64bit_disasm-prerelease-
- https://github.com/gmh5225/Vmp3_utils
- https://github.com/gmh5225/titan
- https://github.com/gmh5225/Mergen
- https://github.com/gmh5225/VmpHelper
- https://github.com/gmh5225/vmdevirt-vtil
- https://github.com/gmh5225/VMPUnpacker/tree/master [Unpacker]
- https://github.com/gmh5225/VMDragonSlayer [Advanced Virtual Machine Detection and Analysis Framework]

> Fix Themida
- https://github.com/gmh5225/TDE
- https://github.com/gmh5225/themida-unmutate
- https://github.com/gmh5225/Themida-Research [Themida 3.x research]

> Fix OLLVM
- https://bbs.pediy.com/thread-272414.htm
- https://github.com/gmh5225/obpo-plugin
- https://github.com/gmh5225/AntiOllvm [AntiOllvm Fla with Fake Runtime]
- https://github.com/gmh5225/DeObfBR [libtprt.so]
- https://github.com/gmh5225/deobf [libtprt.so]
- https://github.com/gmh5225/ollvm-unflattener [unflattener]
- https://github.com/gmh5225/ollvm-unflattener [unflattener]

> Dynamic Binary Instrumentation
- https://github.com/gmh5225/unicorn_pe
- https://github.com/momo5502/sogen [Windows User Space Emulator]
- https://github.com/gmh5225/emulator [Windows User Space Emulator]
- https://github.com/gmh5225/KUBERA [A x86 environment emulator for Windows user and kernel binaries]
- https://github.com/gmh5225/zyemu [x86-64 user mode emulation using Zydis]
- https://github.com/gmh5225/PeVisor [PE]
- https://github.com/gmh5225/TinyInst
- https://github.com/gmh5225/cpp-veh-dbi
- https://github.com/gmh5225/CovCane
- https://github.com/gmh5225/river
- https://github.com/gmh5225/mambo [ARM]
- https://github.com/gmh5225/drmemory
- https://github.com/gmh5225/dynre-x86
- https://github.com/gmh5225/adbi [For Android]
- https://github.com/gmh5225/adbi [For Android]
- https://github.com/gmh5225/pyda [Write dynamic binary analysis tools in Python]
- https://github.com/gmh5225/w1tn3ss [dynamic binary instrumentation, analysis, and patching framework]
- https://github.com/gmh5225/qbdi-tracer-android [Android assembly instruction tracing tool]
- https://github.com/gmh5225/CUTracer [A dynamic binary instrumentation tool for tracing and analyzing CUDA kernel instructions]

> Launcher Abuser
- https://github.com/gmh5225/launcher-abuser

> PatchGuard-related
- https://github.com/armasm/EasyAntiPatchGuard
- https://github.com/gmh5225/Shark
- https://github.com/gmh5225/Patchguard-2023 [Shark]
- https://github.com/gmh5225/UPGDSED [File]
- https://github.com/gmh5225/EfiGuard [EFI]
- https://github.com/gmh5225/PG1903 [Demo NX]
- https://gist.github.com/gmh5225/0a0c8e3a2d718e2d6f9b6a07d5e0f80a [PG CTX]
- https://github.com/gmh5225/QuickPGTrigger [Stress Testing]
- https://github.com/gmh5225/Sushi [Monitoring PG]
- https://github.com/gmh5225/Disabling-Hyper-V [Disable Hyper-V]
- https://github.com/gmh5225/PatchGuardBypass
- https://github.com/gmh5225/Demystifying-PatchGuard
- https://github.com/gmh5225/dse_pg_bypass [DSE & PG bypass via BYOVD attack]
- https://github.com/gmh5225/VulnerablePatchGuardExploit [A Vulnerable PatchGuard Exploit that can be used to disable PatchGuard on Runtime]
- https://github.com/gmh5225/tableflipper [partially disable patchguard up to win11 21H2]
- https://github.com/gmh5225/PatchGuardEncryptorDriver [Self-implemented PatchGuard]
- https://r0keb.github.io/posts/PatchGuard-Internals [PatchGuard Internals]
- https://github.com/gmh5225/kurasagi [Windows 11 24H2 Runtime PatchGuard Bypass]

> Driver Signature enforcement
- https://github.com/gmh5225/dse_hook
- https://github.com/gmh5225/Dse-Patcher-2
- https://github.com/gmh5225/DisableDSE

> Windows Kernel Explorer
- https://github.com/gmh5225/WinKernel-Resources [Guide]
- https://github.com/supermanc88/Document/tree/master/Windows%20Driver%20Development [Guide]
- https://windiff.vercel.app [Diff]
- https://github.com/gmh5225/ntoskrnl_file_collection [Various versions of ntoskrnl files]
- https://github.com/gmh5225/win32k_file_collection [Various versions of win32k files]
- https://github.com/gmh5225/win32k_file_collection2 [Various versions of win32k files]
- https://github.com/jiubanlo/WinNT5_src_20201004 [Leaked Windows XP Source]
- https://github.com/BlackINT3/OpenArk [Tool]
- https://github.com/BeneficialCode/WinArk [Tool]
- https://github.com/hfiref0x/KDU [Kernel Driver Utility Tool]
- https://github.com/jthuraisamy/TelemetrySourcerer [Enumerate and disable callbacks/ETW]
- https://github.com/preludeorg/ThreatIntelligenceConsumer [Consuming from the Threat-Intelligence ETW provider without a driver or PPL privilege]
- https://github.com/progmboy/openprocmon [open source process monitor]
- https://github.com/winsiderss/systeminformer [The original name is "Process Hacker"]
- https://github.com/0xcpu/ExecutiveCallbackObjects [Callback]
- https://github.com/0xcpu/WinAltSyscallHandler [AltSystemCallHandlers]
- https://github.com/DownWithUp/CallMon [AltSystemCallHandlers]
- https://github.com/everdox/InfinityHook [ETW Hook]
- https://github.com/AyinSama/Anti-AntiDebuggerDriver [ETW Hook]
- https://github.com/gmh5225/AcDrv [ETW Hook]
- https://github.com/FiYHer/InfinityHookPro [ETW Hook Ex]
- https://github.com/gmh5225/ETWHOOK-InfinityHookClass [ETW Hook Ex]
- https://github.com/DearXiaoGui/InfinityHookPro-main [ETW Hook WIN11]
- https://github.com/ThomasonZhao/InfinityHookProMax [ETW Hook WIN11]
- https://github.com/Oxygen1a1/InfinityHook_latest [ETW Hook WIN11]
- https://github.com/gmh5225/PDF-PMC-X86 [A Study on PMI in x86-Architecture]
- https://github.com/KelvinMsft/ThreadSpy [PMI Callback]
- https://github.com/KelvinMsft/PerfMon [PMI Callback]
- https://github.com/gmh5225/PMI-hpc [PMI]
- https://github.com/marcusbotacin/BranchMonitoringProject [PMI]
- https://github.com/gmh5225/NMI-EnumNmiCallback [Enumerate NMI]
- https://github.com/gmh5225/Disable-nmi-callbacks [Disable NMI]
- https://github.com/gmh5225/NMICallbackBlocker2 [Disable NMI]
- https://github.com/gmh5225/NMI-nmi_callback [Triggering NMI]
- https://github.com/gmh5225/Kernel_Anti-Cheat [NMI]
- https://github.com/jlgreathouse/AMD_IBS_Toolkit [AMD Sampling]
- https://github.com/intelpt/WindowsIntelPT [Intel PT]
- https://github.com/CristiNacu/ingsoc [Intel PT]
- https://github.com/DProvinciani/pt-detector [Intel PT]
- https://github.com/googleprojectzero/winafl [Intel PT Fuzzer]
- https://github.com/intelpt/winipt [ipt.sys]
- https://github.com/australeo/libipt-rs [ipt.sys]
- https://github.com/intelpt/processor-trace [Intel PT Decoder]
- https://github.com/gmh5225/Driver-intel-PEBs-LoopHPCs [Intel PEBs]
- https://github.com/libiht/libiht [Intel Hardware Trace Library]
- https://github.com/gmh5225/Ark [Tool]
- https://github.com/gmh5225/ntoskrnl_file_collection [Ntoskrnl Version]
- https://github.com/gmh5225/win32k_file_collection [Win32k Version]
- https://github.com/gmh5225/win32k_file_collection2 [Win32k Version]
- https://github.com/gmh5225/MSSymbolsCollection [Kernel Symbols]
- https://github.com/am0nsec/wkpe [Enumerate VAD]
- https://github.com/armvirus/DriverDllFInder [Find Driver Useless Memory]
- https://github.com/MahmoudZohdy/APICallProxy [Windows API Call Obfuscation]
- https://github.com/Spuckwaffel/Simple-MmcopyMemory-Hook [Hook MmcopyMemory]
- https://github.com/VollRagm/PTView [Browse Page Tables on Windows]
- https://github.com/misc0110/PTEditor [PT Editor]
- https://github.com/IcEy-999/Ntoskrnl_Viewer [Ntoskrnl Viewer]
- https://github.com/ekknod/Nmi [Blocking NMI interrupts]
- https://github.com/EquiFox/KsDumper [Dumping processes using the power of kernel space]
- https://github.com/mastercodeon314/KsDumper-11 [Classic and legendary KsDumper]
- https://github.com/not-matthias/Nemesis [Dumping processes using the power of kernel space]
- https://github.com/allogic/KDBG [Tool]
- https://github.com/backengineering/Voyager [A Hyper-V Hacking Framework For Windows 10 x64 (AMD & Intel)]
- https://github.com/gmh5225/Voyager [A Hyper-V Hacking Framework For Windows 10 x64 (AMD & Intel)]
- https://github.com/noahware/hyper-reV [memory introspection and reverse engineering hypervisor powered by leveraging Hyper-V]
- https://github.com/LabGuy94/Diskjacker [Runtime Hyper-V Hijacking with DDMA]
- https://github.com/zer0condition/BusterCall [HVCI bypass via PFN swapping to call arbitrary kernel functions from user-mode]
- https://github.com/NurdAlert/modded-voyager
- https://github.com/gmh5225/Fortnite-VoyagerTF [Voyager for Fortnite]
- https://github.com/repnz/apc-research [APC Internals Research Code]
- https://github.com/intel/pcm [Processor Counter Monitor]
- https://github.com/ChengChengCC/Ark-tools [Some kernel research]
- https://github.com/alal4465/KernelMon [Monitoring Windows Kernel Drivers]
- https://github.com/gmh5225/Practical-Reverse-Engineering-Solutions [DPC+APC]
- https://github.com/br-sn/CheekyBlinder [Enumerating and removing kernel callbacks using signed vulnerable drivers]
- https://github.com/GetRektBoy724/DCMB [Removing kernel callbacks]
- https://github.com/V-i-x-x/kernel-callback-removal [Removing kernel callbacks]
- https://github.com/Air14/KDBGDecryptor [A simple example how to decrypt kernel debugger data block]
- https://github.com/FaEryICE/MemScanner [Memory scanner]
- https://github.com/Oliver-1-1/RwxScanner [RWX Memory scanner]
- https://github.com/irql/nokd [Kernel debugger protocol]
- https://github.com/DejavuSecure/DetectNtoskrnlIntegrity [Windows Kernel Security: Memory Integrity Verification with Disk Verification of ntoskrnl.exe]
- https://github.com/brew02/BudgetEPT [Create stealthy, inline, EPT-like hooks using SMAP and SMEP]
- https://github.com/synacktiv/windows_kernel_shadow_stack [Shadow Stack]
- https://github.com/noahware/apic [C++ library for sending processor interrupts via x2apic & xapic]
- https://github.com/zer0condition/NTMemory [Usermode NT Explorer - Query kernel addresses, translate virtual to physical addresses, inspect the PFN database, and more.]

> Linux Kernel Explorer
- https://github.com/MatheuZSecurity/Rootkit [Collection of codes focused on Linux rootkits]
- https://github.com/MatheuZSecurity/ksentinel [Kernel integrity monitor for detecting syscall hooking]
- https://github.com/gmh5225/kLLDB [LLDB based debugger for Linux Kernel]
- https://github.com/sad0p/venom [Linux Kernel Rookit Hooking Mechanism]

> Magisk
- https://github.com/PShocker/Zygisk-MagiskHide
- https://github.com/longpoxin/hideroot
- https://github.com/canyie/Riru-MomoHider
- https://github.com/newbit1/rootAVD [root AVD]
- https://github.com/Fox2Code/FoxMagiskModuleManager [A module manager for Magisk]
- https://github.com/Dr-TSNG/ZygiskOnKernelSU [Run Zygisk on KernelSU]
- https://github.com/svoboda18/magiskboot [Boot Image Modification Tool]
- https://github.com/xiaoxindada/magiskboot_ndk_on_linux [Boot Image Modification Tool]
- https://github.com/ookiineko/magiskboot_build [Boot Image Modification Tool]
- https://github.com/gmh5225/magiskboot-linux [Use GitHub Actions to build magiskboot]
- https://github.com/the-dise/EasyPixel [Magisk module that disguises a device under Google Pixel]
- https://github.com/gmh5225/MagiskHide [Portable MagiskHide]
- https://github.com/lico-n/ZygiskFrida [Injects frida gadget using zygisk]
- https://github.com/Admirepowered/Zygisk_mod [Standalone implementation of Zygisk]
- https://github.com/anasfanani/Magisk-Tailscaled [Magisk module for running Tailscale]
- https://github.com/j-hc/FlagSecurePatcher [Disable flag secure and screenshot listeners]
- https://github.com/hackcatml/zygisk-memdump [A zygisk module that dumps so file from process memory]
- https://github.com/PerformanC/ReZygisk [Transparent implementation of Zygisk]
- https://github.com/jiqiu2022/Zygisk-MyInjector [Zygisk Injector]
- https://github.com/Exo1i/MagiskHluda [Run a more undetectable frida server on boot using magisk]
- https://github.com/MhmRdd/NoHello [A Zygisk module to hide root]
- https://github.com/ys1231/MoveCertificate [A Magisk/KernelSU/APatch module for moving user certificates to system certificates. Supports Android 7-15]
- https://github.com/ri-char/zygisk-dump-dex [A zygisk module that hooks `libdexfile.so` to dump dex]

> Xposed
- https://github.com/NPC2000/AppPealing-new [An Xposed module that disables Inka AppSealing, a popular anti-cheat and anti-root solution]

> Frida
- https://github.com/hackcatml/frida-watchpoint-tutorial [Frida's setHardwareWatchpoint tutorial]
- https://github.com/ChiChou/grapefruit [Runtime mobile instrumentation toolkit for iOS/Android, web UI]
- https://github.com/ChiChou/vscode-frida [Unofficial Frida extension for VSCode]
- https://github.com/CrackerCat/strongR-frida-android
- https://github.com/gmh5225/frida-ue4dump [UE4]
- https://github.com/jcalabres/hook-updater [Update Frida hooks automatically]
- https://github.com/gmh5225/frida-boot [A binary instrumentation workshop, with Frida, for beginners]
- https://github.com/smartdone/Frida-Scripts [Some scripts]
- https://github.com/0xdea/frida-scripts [Some scripts]
- https://github.com/SeeFlowerX/frida-smali-trace [Smali trace]
- https://github.com/Ylarod/Florida [anti-detection version of frida-server]
- https://github.com/noobpk/frida-android-hook [Trace classes/functions/and modify the return values]
- https://github.com/apkunpacker/AntiFrida_Bypass [Bypass Some AntiFrida Checks]
- https://github.com/Abbbbbi/Frida-Seccomp [Frida-Seccomp]
- https://github.com/rednaga/frida-stack [Getting better stacks and backtraces in Frida]
- https://github.com/DoranekoSystems/frida-FindoutWhatAccess [Find out what accesses this address]
- https://github.com/piotrbania/frida_usb_dump [Frida script that allows to sniff & dump USB traffic on macOS]
- https://github.com/hackcatml/frida-findJNINativeMethods [Find JNI native methods while the app is running]
- https://github.com/miticollo/xpc-tracer [A tracer based on frida for XPC messages in iOS and macOS]
- https://github.com/0xCD4/SSL-bypass [Root Detection & SSL Bypass Script]
- https://github.com/aimardcr/FridaDetectionBypass [Debugger Detection Bypass]
- https://github.com/gmh5225/FridaScript [Low level scripting app for iOS]
- https://github.com/AsenOsen/frida-stealth [Stealth patch for Frida, stealth knowledge collection]
- https://github.com/Exo1i/MagiskHluda [Run a more undetectable frida server on boot using magisk]
- https://github.com/suifei/fridare [Powerful Frida repackaging tool for iOS and Android. Easily modify Frida servers to enhance stealth and bypass detection]

> Hook ART(android)
- https://github.com/PAGalaxyLab/YAHFA
- https://github.com/canyie/pine

> Hook syscall(android)
- https://github.com/gmh5225/abyss [Android system call hook]

> Android Terminal Emulator
- https://github.com/termux/termux-app
- https://github.com/gmh5225/neotty
- https://github.com/jackpal/Android-Terminal-Emulator
- https://github.com/NeoTerrm/NeoTerm

> Android File Explorer
- https://github.com/nzcv/note [Guide-zh]
- https://github.com/gmh5225/Apktool [A tool for reverse engineering Android apk files]
- https://github.com/gmh5225/APKToolGUI [GUI for apktool, signapk, zipalign and baksmali utilities]
- https://github.com/pxb1988/dex2jar
- https://github.com/gmh5225/jadx [Dex to Java decompiler]
- https://github.com/LuckyPray/DexKit-Android [dex deobfuscator]
- https://github.com/LSPosed/DexBuilder [Generate dex file by c++]
- https://github.com/gmh5225/APKiD [PEiD for Android]
- https://github.com/gmh5225/APKLab [Android Reverse-Engineering Workbench for VS Code]
- https://github.com/pgp/XFiles [File explorer for (rooted) Android]
- https://github.com/gmh5225/AdbFileManager [File manager using ADB protocol]
- https://github.com/MuntashirAkon/AppManager [A full-featured package manager and viewer]
- https://github.com/pgp/XFiles [A general-purpose file explorer for (rooted) Android]
- https://github.com/Raival-e/File-Explorer [An Android file explorer]
- https://github.com/obfusk/apksigcopier [apksigcopier - copy/extract/patch android apk signatures & compare apks]
- https://github.com/gmh5225/dalvikus [Android reverse-engineering tool / smali editor]

> Android Memory Explorer
- https://github.com/misc0110/PTEditor [PT Editor]
- https://github.com/joaomlneto/procmap
- https://github.com/kp7742/MemDumper [Dump]
- https://github.com/gmh5225/eBPFDexDumper [DexDumper based eBPF on Android Platform]
- https://github.com/mrcang09/Android-Mem-Edit
- https://github.com/ExploitTheLoop/writemem
- https://github.com/abcz316/rwProcMem33 [Linux read & write process memory module]
- https://github.com/ri-char/rwMem [The fork version of rwProcMem33]
- https://github.com/IAIK/armageddon [Cache attacks on ARM]
- https://github.com/tamirzb/CVE-2021-1961 [CVE RW]
- https://github.com/MJx0/KittyMemory [Runtime code patching]
- https://github.com/gmh5225/KittyMemory-IOS [Runtime code patching for IOS]
- https://github.com/vrolife/mypower [Memory scanner]
- https://github.com/gmh5225/memory_server [Memory scanner & analyzer with REST API]
- https://github.com/KuhakuPixel/AceTheGame [Game Hacking Tools]
- https://github.com/gmh5225/Android-MemoryTool [RPM]
- https://github.com/Anonym0usWork1221/C-Android-Memory-Tool [RPM]
- https://github.com/Poko-Apps/MemKernel [RPM]
- https://github.com/DeNA/mempatch [Memory tampering tool]
- https://github.com/hackcatml/zygisk-memdump [A zygisk module that dumps so file from process memory]
- https://github.com/mrexodia/lldbext-dump [Extension to create a full memory dump using LLDB on Android]
- https://github.com/block/stoic [Run code within any debuggable Android process, without modifying its APK]
- https://github.com/gmh5225/qbdi-tracer-android [Android assembly instruction tracing tool]

> Android Application CVE
- https://github.com/nahid0x1/CVE-2024-0044 [a vulnerability affecting Android version 12 & 13]

> Android Kernel CVE
- https://github.com/ScottyBauer/Android_Kernel_CVE_POCs [List]
- https://github.com/tangsilian/android-vuln [List]
- https://github.com/jiayy/android_vuln_poc-exp [List]
- https://github.com/jsirichai/CVE-2019-2215 [Root for Pixel 2/XL]
- https://github.com/bluefrostsecurity/CVE-2020-0041 [Root for Pixel 3]
- https://github.com/j4nn/CVE-2020-0041 [Root for Pixel 3]
- https://github.com/polygraphene/DirtyPipe-Android [Root for Pixel 6]
- https://github.com/tiann/DirtyPipeRoot [Root for Pixel 6]
- https://github.com/Markakd/bad_io_uring [Root for Pixel 6]
- https://github.com/0x36/Pixel_GPU_Exploit [Root for Pixel7/8 Pro with Android 14]
- https://soez.github.io/posts/CVE-2022-22265-Samsung-npu-driver [Root for Samsung]
- https://github.com/0xbinder/android-kernel-exploitation-lab [CVE-2019-2215]
- https://github.com/zhuowei/cheese [CVE-2025-21479]
- https://github.com/farazsth98/poc-CVE-2025-38352 [CVE-2025-38352]

> Android Bootloader Bypass
- https://github.com/gmh5225/Xiaomi-HyperOS-BootLoader-Bypass [Xiaomi HyperOS BootLoader Bypass]

> Android ROM
- https://xdaforums.com [Guide]
- https://github.com/Akipe/awesome-android-aosp [Guide]
- https://github.com/musabcel/android_rom_list [List]
- https://github.com/gmh5225/payload_dumper [Android OTA payload dumper]
- https://developer.android.com/studio/run/win-usb [Google USB Driver]
- http://www.miui.com/unlock/download.html [Unlocker for xiaomi]
- https://miuiver.com/miflash [MiFlash]
- https://xiaomifirmwareupdater.com [Xiaomi Firmware Updater]
- https://sourceforge.net/projects/recovery-for-xiaomi-devices/files [TWRP for xiaomi]
- https://github.com/gmh5225/Android_boot_image_editor [Android ROM tool]
- https://github.com/badabing2005/PixelFlasher [Android ROM tool for Pixel]
- https://github.com/Ctapchuk/android_bootable_recovery-OFRP [OrangeFox Recovery]

> Android Device Trees
- https://github.com/MiCode/kernel_devicetree [xiaomi device trees]
- https://github.com/cupid-development/ [xiaomi device trees]
- https://github.com/PixelOS-AOSP/official_devices [PixelOS device trees]
- https://github.com/ymdzq/OFRP-device_xiaomi_mondrian [OFRP for Redmi K60 (mondrian)]
- https://github.com/flakeforever/device_xiaomi_mondrian [Pixel Experience Plus for for Redmi K6/POCO F5 Pro]

> Android Kernel Source
- https://source.android.com/docs/setup/build/building-kernels [Docs]
- https://android.googlesource.com/kernel/manifest/+refs [manifest]
- https://android.googlesource.com/kernel/manifest [manifest]
- https://android.googlesource.com/kernel/common [GKI]
- https://github.com/aosp-mirror/kernel_common [GKI]
- https://github.com/PixelOS-AOSP/manifest [An AOSP based ROM aiming to provide the best of Pixel]
- https://www.android-x86.org [X86]
- https://blissos.org [X86]
- https://github.com/MiCode/Xiaomi_Kernel_OpenSource [xiaomi kernel]
- https://github.com/xiaomi-sm8450-kernel [xiaomi kernel]
- https://github.com/Danda420/kernel_xiaomi_sm8250 [xiaomi kernel for POCO F3/F4]
- https://github.com/LowTension/android_kernel_xiaomi_sm8475 [Pixel Experience Plus for for Redmi K6/POCO F5 Pro]
- https://github.com/GrapheneOS-Archive/kernel_msm-coral [Pixel 4/4XL/4a]
- https://github.com/msnx/KernelSU-Pixel4XL [KernelSU for Google Pixel4XL]
- https://github.com/universal5433/android_kernel_samsung_universal5433 [samsung 15433]
- https://github.com/SM7325-AE/android_kernel_motorola_dubai [Moto Edge 30]
- https://github.com/mylove90/pc_ginkgo [Redmi Note 8/8T with KernelSU]
- https://github.com/fiqri19102002/android_kernel_xiaomi_sweet [Redmi Note 10 Pro]
- https://github.com/ExWhyZed9/android_kernel_gki_common_5.10 [Redmi Note 11T Pro(+) / POCO X4 GT]
- https://github.com/psavarmattas/android_kernel_oneplus_sm7250-WKSU [KernelSU for Oneplus]
- https://github.com/huawei-mediatek-devs/android_kernel_huawei_mt6761 [huawei mt6761]
- https://github.com/pascua28/android_kernel_samsung_sm7150 [samsung sm7150]
- https://github.com/gmh5225/A146B-KSU [KernelSU for SAMSUNG A14 5G (a14x)]
- https://github.com/utziacre/android_kernel_xiaomi_pipa [Xiaomi Pad 6 kernel]
- https://github.com/utziacre/android_kernel_oneplus_sm8250 [OnePlus 8/8T/8Pro/(9R?) kernel]

> Android Root
- https://github.com/fynks/awesome-android-root [Awesome Android Root]
- https://github.com/topjohnwu/Magisk
- https://github.com/tiann/KernelSU
- https://github.com/gmh5225/KernelSU-4.4 [Adapted for Linux Kernel 4.4 + Google GCC 4.9]
- https://github.com/bmax121/APatch
- https://github.com/lzghzr/APatch_kpm [APatch modules]
- https://github.com/abcz316/SKRoot-linuxKernelRoot
- https://github.com/0x36/Pixel_GPU_Exploit
- https://github.com/0xCD4/SSL-bypass [Root Detection & SSL Bypass Script]

> Android Kernel driver development
- https://github.com/gmh5225/AndroidDriveSignity [Bypass driver signature verification in Android kernel(ARMv8.3)]
- https://github.com/gmh5225/android-kernel-driver-template [A GKI Android kernel driver(AArch64) template]
- https://github.com/dabao1955/kernel_build_action [a action to build kernel automatically]
- https://github.com/TheWildJames/kernel_build_scripts [kernel build scripts]
- https://github.com/fuqiuluo/android-wuwa [Android aarch64 rootkit]
- https://github.com/fuqiuluo/ovo [Android aarch64 kernel driver module providing efficient memory operations, touch simulation and IPC. Features include fast memory remapping]

> Android Kernel Explorer
- https://docs.kernel.org [Linux Kernel documentation]
- https://armv8-ref.codingbelief.com/en [ARM Architecture Reference Manual for ARMv8-A]
- https://github.com/yhnu/op7t [DIY Kernel]
- https://github.com/yabinc/simpleperf_demo [Perf]
- https://github.com/gmh5225/android_ebpf [EBPF]
- https://github.com/PShocker/Android_bpf_sys [EBPF]
- https://github.com/gmh5225/stackplz [EBPF]
- https://github.com/gmh5225/eDBG [eBPF-based lightweight debugger for Android]
- https://github.com/cloudfuzz/android-kernel-exploitation [Android Kernel Exploitation]
- https://github.com/Snoopy-Sec/Localroot-ALL-CVE [Root CVE]
- https://github.com/xmmword/dpatch [Syscall Dispatcher Patching PoC]
- https://github.com/aquasecurity/tracee [Linux Runtime Security and Forensics using eBPF]
- https://github.com/AndroidReverser-Test/Kernel-Trace [A kpm kernel module based on uprobe, capable of simultaneously hooking a large number of user address space functions]
- https://github.com/fuqiuluo/android-wuwa [Android aarch64 rootkit]
- https://github.com/fuqiuluo/rnidbg [An Android-ARM64 kernel emulator written in Rust. (Rewrite from unidbg)]

> Android Kernel Driver
- https://github.com/rogxo/kernel_hack
- https://github.com/Jiang-Night/Kernel_driver_hack
- https://github.com/WeiJiLab/kernel-hook-framework [Kernel inline hook framework]
- https://github.com/Poko-Apps/MemKernel [RPM]

> Android Network Explorer
- https://github.com/emanuele-f/PCAPdroid

> Android memory loading
- https://github.com/icculus/mojoelf
- https://github.com/lockedbyte/so_loader

> IOS jailbreak
- https://github.com/KpwnZ/Def1nit3lyN0tAJa1lbr3akTool [iOS 15.7 and iOS 16.5]
- https://github.com/opa334/Dopamine [iOS 15 and 16]
- https://github.com/roothide/Dopamine2-roothide [iOS 15 and 16]
- https://github.com/felix-pb/kfd [iOS 15 and 16]
- https://github.com/0x36/weightBufs [ANE kernel r/w exploit for iOS 15 and macOS 12]
- https://github.com/jjolano/shadow
- https://github.com/gmh5225/IOS-jailbreak--Fugu15
- https://github.com/Kc57/iHide
- https://github.com/palera1n/palera1n
- https://github.com/checkra1n
- https://github.com/opa334/TrollStore [jailed app]
- https://github.com/paradiseduo/IPAPatch [Patch iOS Apps without Jailbreak]
- https://github.com/34306/mdc0 [CVE-2025-24203]
- https://github.com/jailbreakdotparty/dirtyZero [CVE-2025-24203]
- https://github.com/staturnzz/oob_entry [iOS 3.0-10.3.4 tfp0 kernel exploit]

> IOS Memory Explorer
- https://github.com/hackcatml/kfd-explorer [iOS kernel memory explorer]
- https://github.com/DerekSelander/dynadump [A runtime ObjC class-dump]
- https://github.com/jsherman212/xnuspy [an iOS kernel function hooking framework for checkra1n'able devices]
- https://gist.github.com/gmh5225/95151b245267a27b3cdbea949632c680 [DirtyZero Exp]
- https://github.com/gmh5225/RuntimeViewer [Objective-C Runtime Viewer for macOS and iOS]

> IOS File Explorer
- https://github.com/DerekSelander/dynadump [A runtime ObjC class-dump]
- https://github.com/LaurieWired/Malimite [Malimite is an iOS and macOS decompiler designed to help researchers analyze and decode IPA files and Application Bundles]

> IOS App Packaging
- https://github.com/addrianyy/ios_packager [Package and sign iOS applications]

> Virtual Environments
- https://github.com/FBlackBox/BlackBox [Android]
- https://github.com/ServenScorpion/VirtualApp [Android]
- https://github.com/mandiant/flare-vm
- https://github.com/hzqst/VmwareHardenedLoader
- https://github.com/d4rksystem/VMwareCloak
- https://github.com/utmapp/UTM [Run virtual machines on iOS]

> Decompiler
- IDA Pro
- Binary Ninja
- https://github.com/radareorg
- https://github.com/gmh5225/ghidra
- https://github.com/gmh5225/retdec
- https://github.com/gmh5225/Recaf [Java]
- https://github.com/gmh5225/bytecode-viewer [Java]
- https://github.com/gmh5225/deobfuscator [Java]
- https://github.com/gmh5225/binsync [Sync]
- https://github.com/gmh5225/ethersplay [EVM dissassembler]
- https://github.com/gmh5225/Ouroboros [A Symbolic-Execution Decompiler written in Rust]

> IDA themes
- https://github.com/gmh5225/dp701 [Dark theme for IDA Pro]
- https://github.com/gmh5225/ida-dark-plus [Dark+ Theme]
- https://github.com/gmh5225/long_night
- https://github.com/gmh5225/IdaThemer

> IDA Plugins
- https://github.com/gmh5225/ida-plugins [List of IDA Plugins]
- https://github.com/gmh5225/idaplugins-list [List of IDA Plugins]
- https://github.com/gmh5225/idawilli [IDA Pro resources, scripts, and configurations]
- https://github.com/gmh5225/idasdk-collection/tree/master [IDA SDK]
- https://github.com/gmh5225/ida-sdk [IDA SDK]
- https://github.com/gmh5225/IDASkins [Skins]
- https://github.com/gmh5225/ida-nord-theme [Skins]
- https://github.com/giladreich/ida_migrator [Migrate Database]
- https://github.com/gmh5225/NtRays [Windows Kernel Enhance]
- https://github.com/gmh5225/ida_bitfields [Windows Kernel Enhance]
- https://github.com/gmh5225/DriverBuddyReloaded [Windows Kernel Analysis]
- https://github.com/gmh5225/IDA2Obj [COFF Relink]
- https://github.com/synacktiv/dotNIET [Import .NET Symbol]
- https://github.com/aliyunav/Finger [Recognizing Function By Cloud]
- https://github.com/gmh5225/FindFunc [Recognizing Function By Pattern]
- https://github.com/gmh5225/sigmakerex [Signature Maker]
- https://github.com/gmh5225/IDA-Pro-SigMaker [Signature Maker]
- https://github.com/gmh5225/ida-sigmaker [Signature Maker]
- https://github.com/gmh5225/FakePDB [PDB Generation From IDA]
- https://github.com/gmh5225/Ponce [Symbolic Execution]
- https://github.com/gmh5225/ttddbg [Time Travel Debugging]
- https://github.com/gmh5225/LazyIDA [LazyIDA]
- https://github.com/gmh5225/HappyIDA [Hex-Rays decompiler utilities: parameter labeling, SEH, Rust strings]
- https://github.com/gmh5225/ida-function-string-associate [IDA 9.X: auto-generate function comments from string literals]
- https://github.com/gmh5225/qsynthesis [Greybox Synthesizer geared for deobfuscation of assembly instructions]
- https://github.com/gmh5225/ida_medigate [RTTI]
- https://github.com/gmh5225/findyara-ida [Yara]
- https://github.com/gmh5225/ida_vmware_windows_gdb [IDA+VMWARE+GDB]
- https://github.com/gmh5225/ida_bochs_windows [IDA+BOCHS]
- [An integration for IDA and VS Code which connects both to easily execute and debug IDAPython scripts](https://github.com/gmh5225/idacode)
- https://github.com/gmh5225/efiXplorer [UEFI firmware]
- https://github.com/Accenture/protobuf-finder [Protobuf]
- https://github.com/gmh5225/golang_loader_assist [GO Reversed]
- https://github.com/gmh5225/GhidraDec [Ghidra Decompiler]
- https://github.com/gmh5225/EasyRe [Trace Execution]
- https://github.com/gmh5225/ida_ps5_elf_plugin [PS5 elf loader]
- https://github.com/gmh5225/tenet [Execution Traces]
- https://github.com/gmh5225/Tenet-IDA9.0 [Execution Traces]
- https://github.com/gmh5225/frinet [Frida-based tracer]
- https://github.com/gmh5225/findcrypt-yara [Find crypto constants]
- https://github.com/gmh5225/VMAttack [VMAttack PlugIn for IDA Pro]
- https://github.com/gmh5225/sk3wldbg [Unicorn]
- https://github.com/gmh5225/Classy [Manage classes]
- https://github.com/gmh5225/ida_names [Renames pseudocode windows with the current function name]
- https://github.com/helpsystems/turbodiff [diff]
- https://github.com/joxeankoret/diaphora [diff]
- [An IDAPython module for way more convienent way to Reverse Engineering iOS kernelcaches](https://github.com/cellebrite-labs/ida_kcpp)
- https://gitlab.com/eshard/d810 [Deobfuscate code at decompilation time by modifying IDA Pro microcode]
- https://github.com/CKCat/d810 [Deobfuscate code at decompilation time by modifying IDA Pro microcode]
- https://github.com/w00tzenheimer/d810-ng [D-810ng (Next Generation) is an evolution of d810 to deobfuscate code at decompilation time]
- https://github.com/airbus-seclab/AutoResolv [Resolves functions imported from external libraries]
- https://github.com/snare/ida-efiutils [EFI binaries]
- https://github.com/JusticeRage/Gepetto [ChatGPT]
- https://github.com/MayerDaniel/ida_gpt [ChatGPT]
- https://github.com/mahaloz/DAILA [ChatGPT]
- https://github.com/ke0z/VulChatGPT [ChatGPT]
- https://github.com/WPeace-HcH/WPeChatGPT [ChatGPT]
- https://github.com/lzyddf/IDA_Plugin_PCodeGPT [ChatGPT]
- https://github.com/deadeert/EWS [Emulation]
- https://github.com/patois/genmc [Display Hex-Rays Microcode]
- https://github.com/RolfRolles/HexRaysDeob [Hex-Rays Microcode]
- https://github.com/HexRaysSA/goomba [Simplify MBA]
- https://github.com/es3n1n/ida-wakatime-py [WakaTime integration for IDA Pro]
- https://github.com/senator715/IDA-Fusion [Fast Signature scanner & creator]
- https://github.com/cellebrite-labs/PPLorer [Resolves PPL calls to the actual underlying PPL function]
- https://github.com/kweatherman/ida_missinglink [Fills in missing indirect CALL & JMP target information]
- https://github.com/yubie-re/ida-jm-xorstr-decrypt-plugin [Attempts to decrypt JM Xorstr in some x64 binaries]
- https://github.com/timetravelthree/IDARustDemangler [Rust Demangler & Normalizer]
- https://github.com/gmh5225/ida-find-.data-ptr [.data ptr lookup script]
- https://github.com/repnz/ida-plugins [Register Cross References]
- https://github.com/lstaroth/AntiXorstr [Anti Xorstr]
- https://github.com/SentineLabs/AlphaGolang [Analyzing Golang Binaries]
- https://github.com/tmr232/Sark [IDAPython Made Easy]
- https://github.com/govcert-ch/ConfuserEx_IDAPython [Deobfuscation script for ConfuserEx]
- https://github.com/sonyps5201314/pdb [PDB plugin with enhance and bugfix]
- https://github.com/Coldzer0/IDA-For-Delphi [IDA-For-Delphi]
- https://github.com/AntonKukoba1/BetterCallStack [Improve call stack]
- https://github.com/za233/IDADeflat [deflat]
- https://github.com/RomanRybachek/Copy_RVA [Copy RVA]
- https://github.com/RevEngAI/reai-ida [RevEng.AI]
- https://github.com/gaasedelen/microavx [AVX Lifter]
- https://github.com/thalium/ida_kmdf [IDA kmdf]
- https://github.com/zengfr/XrefsExt [XrefsExt plugin]
- https://github.com/sterrasec/genpatch [Python script for patching binary]
- https://github.com/AzzOnFire/yarka [YARA signature creation]
- https://github.com/VirusTotal/vt-ida-plugin [VirusTotal plugin]
- https://github.com/crifan/AutoRename [Auto rename symbol]
- https://github.com/LAC-Japan/IDA_Plugin_AntiDebugSeeker [Extract anti-debugging]
- https://github.com/cseagle/blc [Integrate Ghidra's decompiler]
- https://github.com/Goatman13/ps2_ida_vu_micro [Find and disassembly vu microcode in ps2 executables]
- https://github.com/arizvisa/ida-minsc [Functional DWIM interface]
- https://github.com/wINfOG/IDA_Easy_Life [Deobfuscation]
- https://github.com/senko37/yarascan-ida [Scan file with Yara rules]
- https://github.com/SamuelTulach/ida-unity-pdb-downloader [Unity PDB Downloader]
- https://github.com/TrungNguyen1909/aarch64-sysreg-ida [A IDA plugin to show ARM MSRs nicely]
- https://github.com/danielplohmann/gui-plugin-template [A template for cross-compatible GUI plugins]
- https://github.com/gmh5225/IDA-MapSymbolParser [IDA Map File Symbol Renamer]
- https://github.com/gmh5225/IDA-KallsymsSymbolRenamer [IDA kallsyms Renamer]
- https://github.com/XMCVE/import-kallsyms [IDA Pro Plugin to import /proc/kallsyms for Linux Kernel]
- https://github.com/tomrus88/OpenLumina [Allows connecting to third party Lumina servers]
- https://github.com/stuxnet147/IDA-Assistant [Claude-3 models assistant]
- https://github.com/goseungduk/CE_Tracer-IDA [CheatEngine Value Tracer of IDA]
- https://github.com/binarly-io/idapcode [Displaying the P-Code for the current function]
- https://github.com/ElvisBlue/emotet-deobfuscator [IDA plugin to deobfuscate emotet CFF]
- https://github.com/threatlabz/pikabot-deobfuscator [Deobfuscating Pikabot's strings using RC4 and AES]
- https://github.com/Pycatchown/ClassMaker [IDA plugin to make classes automatically]
- https://github.com/airbus-cert/comida [An IDA Plugin that help analyzing module that use COM]
- https://github.com/Sandspeare/ida2llvm [Lifting IDA Microcode into LLVM IR]
- https://github.com/crtdll/ida-gameguard-str-dec [GameGuard String Decryption]
- https://github.com/kkent030315/IDARustCargo [Displaying potentially installed Cargo dependencies]
- https://github.com/dNop90/dOffset [IDA Pro and Cheat Engine to get the offset of the current module]
- https://github.com/sneakyevil/ida_functioncolor [IDA Plugin to colorize function definition in pseudocode]
- https://github.com/apkunpacker/IDA-Gepetto [IDA plugin which queries Local language models]
- https://github.com/Jackiemin233/Gemini-Genius [IDA python 3 plugin and binary file similarity comparison]
- https://github.com/lj94093/IDAAndroidBreakpoint [IDA plugin aid to set android so breakpoint]
- https://github.com/jonpalmisc/ida_screenshot [High-resolution screenshot capture plugin for IDA Pro]
- https://github.com/JANlittle/IDARustHelper [Small rust binary analysis helper for IDA]
- https://github.com/mefistotelis/ida-pro-loadmap [Plugin for IDA Pro disassembler which allows loading .map files]
- https://github.com/OALabs/hashdb-ida [HashDB API hash lookup plugin for IDA Pro]
- https://github.com/Vu1nT0tal/firmeye [IoT]
- https://github.com/sean2077/big5-decode-ida [IDA Plugin for decoding bytes as big5]
- https://github.com/Vis-Wing/Binoculars [Binoculars is an IDA PRO plugin with an integrated AI interface]
- https://github.com/Reodus/CBS [IDA Plugin to set custom breakpoints on mnemonics]
- https://github.com/matteyeux/IDArling [IDArling is a collaborative reverse engineering plugin for IDA Pro and Hex-Rays]
- https://github.com/richor1042/IDAFuncOutline [optimize the readability of decompiled code for iOS ARM64 binaries]
- https://github.com/Dump-GUY/IDA_PHNT_TYPES [Converted phnt to IDA TIL, IDC (Hex-Rays)]
- https://github.com/gmh5225/DeObfBR [libtprt.so]
- https://github.com/janisslsm/ida-ps4-helper [A helper plugin for PS4 module loader]
- https://github.com/Antelcat/ida_copilot [ChatGPT Agent analyses your IDA pseudocode]
- https://github.com/crytic/ida-evm [IDA Processor Module for the Ethereum Virtual Machine (EVM)]
- https://github.com/NoneShell/IDAComments [a IDA plugin helps you to manage your IDA Comments]
- https://github.com/emoose/idaxex [Xbox360/Xenon loader plugin for IDA 9]
- https://github.com/junron/auto-enum [automatically identify and set enums for standard functions]
- https://github.com/ViRb3/swift-ida [IDA plugin to aid with Swift reverse engineering]
- https://github.com/Krietz7/IDA-DataExportPlus [a IDA Pro plugin to export data better]
- https://github.com/harlamism/IdaClu [For grouping similar functions]
- https://github.com/eset/DelphiHelper [help the analysis of x86/x86_64 binaries written in Delphi]
- https://github.com/milankovo/YaraVM [IDA processor for loading and disassembling compiled yara rules]
- https://github.com/cellebrite-labs/LabSync [An IDA plugin that can be used to partially synchronize IDBs between different users reversing the same binaries]
- https://github.com/cellebrite-labs/FunctionInliner [An IDA plugin that eases reversing of binaries that have been code-size-optimized with function outlining]
- https://github.com/herosi/PyClassInformer [RTTI Parsing IDA plugin]
- https://github.com/0xGotcha/XrefXpert [An advanced cross-reference navigation tool for IDA Pro]
- https://github.com/TKazer/ScyllaHide-For-IDA9.0RC [ScyllaHide-For-IDA9]
- https://github.com/mrexodia/ida-pro-mcp [MCP for IDA pro]
- https://github.com/MxIris-Reverse-Engineering/ida-mcp-server [MCP for IDA pro]
- https://github.com/taida957789/ida-mcp-server-plugin [MCP for IDA pro]
- https://github.com/fdrechsler/mcp-server-idapro [MCP for IDA pro]
- https://github.com/rand-tech/pcm [MCP for IDA pro]
- https://github.com/gmh5225/ida_export_functions [Export IDA Pro Function List to a Specified Path (Markdown Format)]
- https://github.com/L4ys/IDA-WPP-Remover [Remove WPP calls from hexrays decompiled code]
- https://github.com/0xdea/augur [Augur is a blazing fast IDA Pro headless plugin that extracts strings and related pseudo-code from a binary file]
- https://github.com/DennyDai/headless-ida [Run IDA scripts headlessly]
- https://github.com/gilboz/ida_kernelcache_ng [An IDA Plugin for analyzing iOS kernelcaches]
- https://github.com/mahmoudimus/ida-taskr [IDA Taskr is a pure Python library for IDA Pro related parallel computing]
- https://github.com/sigwl/AiDA [An AI-powered assistant for IDA 9.0+ to accelerate reverse engineering of C++ games]
- https://github.com/alexhude/FRIEND [FRIEND is an IDA plugin created to improve disassembly and bring register/instruction documentation right into IDA View]
- https://github.com/cycraft-corp/BinaryAnalysisMCPs [Binary analysis MCPs collections]
- https://github.com/SamuelTulach/unxorer [Yet another IDA Pro/Home plugin for deobfuscating stack strings]
- https://github.com/loyaltypollution/ida2llvm [IDA2LLVM - Dynamic Binary Lifting IDA code to LLVM IR]
- https://github.com/GAMMACASE/PltPatcher [Patches PLT sections when IDA fails to do so]
- https://github.com/yoavst/ida-ios-helper [Plugin to ease reversing iOS projects]
- https://github.com/gmh5225/VMDragonSlayer [Advanced Virtual Machine Detection and Analysis Framework]
- https://github.com/milankovo/ida_enums_helper [IDA Enums Helper Plugin]
- https://github.com/axelmierczuk/tenrec [A headless, extendable, multi-session, IDA Pro MCP framework]
- https://github.com/blacktop/ida-mcp-rs [Headless IDA Pro MCP server]
- https://github.com/kweatherman/yara4ida [Unofficial YARA IDA Pro plugin]
- https://github.com/Berk000x/BinaryLens [An IDA plugin that uses LLM to speed up binary analysis]
- https://github.com/CyberSecurityUP/DriverVuln-Analyzer-IDA-Plugin [Driver Vuln Analyzer]
- https://github.com/ssmugabi/IDAPlugins [Integrate essential IDA Pro plugins for enhanced functionality, including deobfuscation, binary diffing, and custom cryptography support]
- https://github.com/momo5502/patch-finder [IDA plugin to find patched memory]
- https://github.com/HexRaysSA/ida-cyberchef [A Qt-based CyberChef interface designed for malware analysis workflows, particularly in IDA Pro]
- https://github.com/idkhidden/DrawIDA [Lightweight whiteboard plugin for IDA that allows reverse engineers to sketch and brainstorm directly inside IDA]
- https://github.com/rem0obb/rtti-parser [IDA script to parse RTTI information in executable support for IDA 9.2]
- https://github.com/19h/ida-semray [High-performance, AI-driven semantic analysis for the IDA Pro decompiler]
- https://github.com/K4ryuu/IDA-VTableExplorer [C++ virtual table detection and annotation tool for IDA Pro 9.x]
- https://github.com/19h/chernobog [A Hex-Rays IDA Pro plugin for deobfuscating binaries protected with the Hikari LLVM obfuscator]
- https://github.com/danielplohmann/mcrit-plugin [A plugin to use MCRIT from IDA Pro]
- https://github.com/dyussekeyev/ida-spotlight [Workflow-centric function triage and prioritization plugin for IDA Pro]
- https://github.com/s3rg0x/AIMachDec [AIMachDec is an IDA plugin for Apple AARCH64/ARM64 binaries that utilizes LLMs to translate assembly functions into readable pseudo-code in C, Objective-C, or Swift]
- https://github.com/not1cyyy/Kiroshi [An IDA Pro Plugin to detect common Anti-Cheat Artifacts]
- https://github.com/HexRaysSA/ida-claude-code-plugins [IDA Claude Code Plugins]
- https://github.com/stolevchristian/LUDA [Lua scripting plugin for IDA Pro]
- https://github.com/allthingsida/idasql [Interface with IDA in SQL via live virtual tables]
- https://github.com/a1ext/auto_re [IDA PRO auto-renaming plugin with tagging support]
- https://github.com/SymbioticSec/ida-security-scanner [A security-focused code scanner for IDA Pro]
- https://github.com/cristeigabriela/IDAFind [Ctrl+F search support for Pseudocode windows]
- https://github.com/thalium/symless [IDA Pro plugin that helps reconstruct structures]

> IDA Signature Database
- https://github.com/push0ebp/sig-database
- https://github.com/cpkt9762/solana-sbpf-rlib [Solana sBPF rlib files for IDA Pro / Ghidra / Binary Ninja signature generation]

> Binary Ninja Plugins
- https://github.com/Vector35/official-plugins
- https://github.com/Vector35/community-plugins
- https://github.com/FuzzySecurity/BinaryNinja-Themes [Theme]
- https://github.com/EliseZeroTwo/SEH-Helper [SEH Helper]
- https://github.com/Vector35/tanto [Slices Functions]
- https://github.com/ergrelet/triton-bn [Triton]
- https://github.com/google/binexport [BinDiff]
- https://github.com/Pusty/BinaryNinjaPlugins
- https://github.com/gmh5225/seninja [Symbolic Execution]
- https://github.com/gmh5225/opaque-predicates-detective
- https://github.com/gmh5225/fuzzable [Fuzzer]
- https://github.com/gmh5225/binja-division-deoptimization [Division and Modulo Deoptimizer]
- https://github.com/gmh5225/OpaquePredicatePatcher [Opaque Predicate Patcher]
- https://github.com/gmh5225/binja-division-deoptimization [Division and Modulo Deoptimizer]
- https://github.com/gmh5225/obfuscation_detection [Collection of scripts to pinpoint obfuscated code]
- [Package Binary Code as a Python class using Binary Ninja and Unicorn Engine](https://github.com/gmh5225/ripr)
- https://github.com/gmh5225/ariadne [Graph Analysis]
- https://github.com/gmh5225/binja_kc [Plugin for loading MachO kernelcache and dSYM files]
- https://github.com/gmh5225/workflow_objc [Objective-C]
- https://github.com/gmh5225/binja_sigmaker [Create and find signatures]
- https://github.com/gmh5225/AMD-SP-Loader [AMD-SP or PSP firmware]
- https://github.com/gmh5225/binaryninja-openai [Integrates OpenAI]
- https://github.com/gmh5225/frinja [Frida plugin for Binary Ninja]
- https://github.com/danielplohmann/gui-plugin-template [A template for cross-compatible GUI plugins]
- https://github.com/gmh5225/themida-spotter-bn [Detect Themida/WinLicense and Code Virtualizer's obfuscated code locations]
- https://github.com/gmh5225/binaryninja-ollama [Binary Ninja Ollama]
- https://github.com/gmh5225/Shellcoder [BinaryNinja Shellcoder Plugin]
- https://github.com/pd0wm/binaryninja-pcode [This plugin serves as a bridge between Binary Ninja and Ghidra's disassembler]
- https://github.com/gmh5225/deobf [libtprt.so]
- https://github.com/junron/auto-enum [automatically identify and set enums for standard functions]
- https://github.com/gmh5225/bn-ebpf-solana [Binary Ninja plugin for Solana eBPF]
- https://github.com/fosdickio/binary_ninja_mcp [MCP for Binary_Ninja]
- https://github.com/Invoke-RE/binja-lattice-mcp [MCP for Binary_Ninja]
- https://github.com/gmh5225/obfuscation_analysis [Binary Ninja plugin to analyze and simplify obfuscated code]
- https://github.com/gmh5225/native-predicate-solver [Binary Ninja plugin for removing opaque predicates]

> Ghidra Plugins
- https://github.com/gmh5225/awesome-ghidra [List]
- https://github.com/gmh5225/ghidra-frida-hook-gen
- https://github.com/gmh5225/GhidraBoy [Sharp SM83 / Game Boy extension for Ghidra]
- https://github.com/gmh5225/ghidra-openai [ChatGPT]
- https://github.com/gmh5225/ThreatResearch [ChatGPT]
- https://github.com/gmh5225/GptHidra [ChatGPT]
- https://github.com/gmh5225/gpt-wpre [ChatGPT]
- https://github.com/gmh5225/gba-ghidra-loader [GameBoy]
- https://github.com/gmh5225/Ghidra_COFFParser [COFF]
- https://github.com/gmh5225/ghidra_scripts [Scripts]
- https://github.com/gmh5225/ghidra_scripts [Scripts]
- https://github.com/gmh5225/GFred [Command Palette]
- https://github.com/gmh5225/AngryGhidra [Use angr in Ghidra]
- https://github.com/gmh5225/ghidra_bridge [Python 3 bridge to Ghidra's Python scripting]
- https://github.com/gmh5225/GhidraOrbis [Orbis OS specific software and file formats]
- https://github.com/gmh5225/Ghidra-Cpp-Class-Analyzer [C++ Class and Run Time Type Information Analyzer]
- https://github.com/gmh5225/GhidRust [Rust decompiler]
- https://github.com/gmh5225/gdbghidra [GDB session]
- https://github.com/gmh5225/Hyara [Yara]
- https://github.com/gmh5225/Ghidra-Obfuscation-Detection [Detect obfuscated/complex code]
- https://github.com/gmh5225/GhidraScripts [Some scripts]
- https://github.com/gmh5225/BetterStringAnalyzer [A better string analyzer for Ghidra]
- https://github.com/gmh5225/ghidriff [Python Command-Line Ghidra Binary Diffing Engine]
- https://github.com/gmh5225/ghidra-struct-importer [Struct Importer]
- https://github.com/danielplohmann/gui-plugin-template [A template for cross-compatible GUI plugins]
- https://github.com/gmh5225/GhidraGradlePlugin [Gradle]
- https://github.com/gmh5225/GhidrAssist [An LLM extension for Ghidra to enable AI assistance in RE]
- https://github.com/gmh5225/efiSeek [Ghidra analyzer for UEFI firmware]
- https://github.com/LaurieWired/GhidraMCP [MCP for Ghidra]
- https://github.com/gmh5225/ghidra-minidump-loader [Windows Minidump loader for Ghidra]
- https://github.com/gmh5225/GhidrAssistMCP [An MCP extension for Ghidra]
- https://github.com/gmh5225/VMDragonSlayer [Advanced Virtual Machine Detection and Analysis Framework]

> Radare Plugins
- https://github.com/radareorg/r2a [local language model for radare2]
- https://github.com/gmh5225/radius2 [Fast binary emulation and symbolic execution framework using radare2]
- https://github.com/seifreed/r2morph [A metamorphic binary transformation engine based on r2pipe and radare2]

> Windbg Plugins
- https://github.com/comaeio/SwishDbgExt
- https://github.com/gmh5225/comon [Trace COM]
- https://github.com/gmh5225/TWindbg [PEDA-like debugger UI for WinDbg]
- https://github.com/gmh5225/cfgdump [Analyze Control Flow Guard map]
- https://github.com/gmh5225/WinDbg_Scripts [WinDbg scripts]
- https://github.com/gmh5225/dk [Refactored version of tokenext]
- https://github.com/gmh5225/WinDbg-Extensions [Callback Extension]
- https://github.com/gmh5225/WinDbg-JS-Scripts [JS Scripts]
- https://github.com/gmh5225/WinDbg_Copilot [WinDbg Copilot]
- https://github.com/gmh5225/drvtrace [Trace driver module transitions]

> X64DBG Plugins
- https://github.com/gmh5225/x64dbg/wiki/Plugins
- https://github.com/gmh5225/x64dbg-Plugin-Manager
- https://github.com/gmh5225/Multiline-Ultimate-Assembler
- https://github.com/x64dbg/Classroom
- https://github.com/gmh5225/Themidie
- https://github.com/gmh5225/x64dbgScript
- https://github.com/gmh5225/xMalHunter [Detect malicious materials]
- https://github.com/gmh5225/xFindOut
- https://github.com/gmh5225/chaiScriptPlugin
- https://github.com/gmh5225/X64DBG-ViewDllNotification
- https://github.com/gmh5225/AutoAttach
- https://github.com/gmh5225/idenLib [Generate signatures]
- https://github.com/gmh5225/GhidraDec [Ghidra Decompiler]
- https://github.com/gmh5225/x64dbgbinja [Binary Ninja]
- https://github.com/DNLINYJ/Anti_miHoYo_Jcc_Obfuscate
- https://github.com/gmh5225/DisableParallelLoader [Disable parallel loading of dependencies]
- https://github.com/gmh5225/x64dbgpython [Running python3 script]
- https://github.com/gmh5225/idenLibX [Library Function Identification]
- https://github.com/gmh5225/SlothBP [Collaborative Breakpoint Manager]
- https://github.com/gmh5225/ApiBreakpoint [Api Breakpoint]
- https://github.com/gmh5225/yummyPaste [paste string formatted byte data block into x64dbg easy]
- https://github.com/gmh5225/x64dbg-Plugin-Manager [Plugin manager for x64dbg]
- https://github.com/gmh5225/x64dbgPlaytime [Lua script]
- https://github.com/gmh5225/ExpoMon [Exports monitoring]
- https://github.com/gmh5225/x64dbg-xfg-marker [Marks XFG call signatures as data]
- https://github.com/gmh5225/x64dbgCallFinder [Call Finder]
- https://github.com/gmh5225/X64DBG-MapLdr [Loads the map file generated by IDA Pro]
- https://github.com/gmh5225/x64dbgTraceReader [Trace Reader]
- https://github.com/gmh5225/CodeCleaner [Cleaning Themida Mutation Assembly codes]
- https://github.com/gmh5225/ManyTypes [x64dbg typeparsing plugin with Windows types]
- https://github.com/cycraft-corp/BinaryAnalysisMCPs [Binary analysis MCPs collections]

> Cheat Engine Plugins
- https://github.com/gmh5225/CE-Extensions [Lua Extensions]
- https://github.com/gmh5225/CE-lua-extensions [Lua Extensions]
- https://github.com/gmh5225/Mydev-Cheat-Engine-Tables [CT]
- https://github.com/gmh5225/Elden-Ring-CT-TGA [Elden Ring]
- https://github.com/gmh5225/CE-remap-plugin [Remap]
- https://github.com/gmh5225/overwatch-iat-fixer [Overwatch IAT Fixer]
- https://github.com/gmh5225/CE-Examples [Some Examples]
- [Porting ce's monodatacollector to android/ios](https://github.com/gmh5225/frida-il2cpp-datacollector)
- https://github.com/gmh5225/wasm-ceserver [Analyzing WebAssembly]
- https://github.com/Eruditi/CE-MCP-Plugin [MCP for Cheat Engine]

> Injection:Windows
- https://github.com/gmh5225/awesome-injection [awesome injection]
- https://github.com/gmh5225/smap [Scatter Manual Map]
- https://github.com/gmh5225/modmap [Extend Manual Map]
- https://github.com/gmh5225/memmap [Extend Manual Map]
- https://github.com/gmh5225/ModExMap [Extend Manual Map]
- https://github.com/gmh5225/Kernelmode-manual-mapping-through-IAT [IAT Manual Map]
- https://github.com/gmh5225/Stealthy-Kernelmode-Injector [PTE/VAD Manipulation Manual Map]
- https://github.com/gmh5225/injdrv [APC]
- https://github.com/gmh5225/Kernel-dll-injector [APC]
- https://github.com/w1u0u1/kinject [Map + APC]
- https://github.com/gmh5225/RemoteCall [APC Remote Call]
- https://github.com/gmh5225/Simple-Manual-Map-Injector [Manual Map]
- https://github.com/gmh5225/manual_mapping_dll_injector [Manual Map]
- https://github.com/gmh5225/MemJect [Manual Map]
- https://github.com/can1357/ThePerfectInjector [PTE.User]
- https://github.com/gmh5225/fumo_loader [PTE.User]
- https://github.com/gmh5225/executor [PTE.User]
- https://github.com/gmh5225/PresentInjector [PTE.User]
- https://github.com/gmh5225/kernel-eac-be-injector [PTE.User]
- https://github.com/Cr4sh/KernelForge [Hijack ROP]
- https://github.com/gmh5225/be-injector [Attack COW]
- https://github.com/gmh5225/dll-hot-reload [Hot Reload]
- https://github.com/gmh5225/KeUserModeCallBack [KeUserModeCallBack]
- [KeUserModeCallBack Win10](https://github.com/gmh5225/eft/blob/834064aacaab7353173e36acc15933a3cf9289b3/eft/usercallback.h#L50)
- https://github.com/gmh5225/Kernelmode-DLL-Injector [Manual Map]
- [windows kernelmode driver to inject dll into each and every process and perform systemwide function hooking](https://github.com/gmh5225/kptnhook)
- https://github.com/Broihon/GH-Injector-Library [inject library and tool]
- https://github.com/gmh5225/nightshade [inject tool]
- https://github.com/gmh5225/Dirty-Vanity [RtlCreateProcessReflection]
- https://github.com/gmh5225/ntqueueapcthreadex-ntdll-gadget-injection [NtQueueApcThreadEx + gadget]
- https://github.com/gmh5225/FrankensteinAPCInjection [NtQueueApcThreadEx2 + existing handles & natural RWX]
- https://github.com/gmh5225/ProcessInjection [Various process injection techniques]
- https://github.com/gmh5225/lsass-extend-mapper [Manual mapper from LSASS]
- https://github.com/gmh5225/revert-mapper [Map x64 DLLs in WoW64]
- https://github.com/gmh5225/MMInject [Using NX Bit Swapping and VAD hide]
- https://github.com/gmh5225/code_injection [Several code injection techniques]
- https://github.com/gmh5225/Kernel-VAD-Injector [Hide VAD]
- https://github.com/gmh5225/Tartarus-TpAllocInject [TpAllocInject]
- https://github.com/gmh5225/PoolParty [ThreadPool]
- https://github.com/gmh5225/thread_namecalling [SetThreadDescription]
- https://github.com/gmh5225/earlycascade-injection [Early Cascade Injection]
- https://github.com/gmh5225/KMDllInjector [kernel-mode DLL Injector]
- https://github.com/gmh5225/StealthAPCDispatcher [Thread scheduling stealth method using APC with encrypted shellcode]
- https://github.com/gmh5225/Page-Table-Injector [Page Table Injector (PT-Injector)]
- https://github.com/gmh5225/Mini-Launcher [Application launcher with DLL Injection and Lua Scripting]

> Injection:Linux
- https://github.com/gmh5225/awesome-injection [awesome injection]
- https://github.com/gmh5225/mandibule

> Injection:Android
- https://github.com/gmh5225/Android-ModGamesByInjectZygote
- https://github.com/gmh5225/Android-DLL-Injector
- https://github.com/gmh5225/Android-Ptrace-Injector
- https://github.com/gmh5225/Android-LD-Preload-Injector
- https://github.com/gmh5225/yaui
- https://github.com/gmh5225/AndroidSuperInject [Injecting into SELinux-protected system service processes]
- https://github.com/gmh5225/linjector-rs [Code injection on Android without ptrace]
- https://github.com/gmh5225/InjectARM64 [Non-root injection]
- https://github.com/gmh5225/Android-Virtual-Inject [Inject through Virtual Space without root permissions]

> Injection:IOS
- https://github.com/gmh5225/opainject [iOS runtime dylib injection tool]

> Injection:PlayStation
- https://github.com/gmh5225/NineS [A PlayStation 5 ELF injector]


> DLL Hijack
- https://github.com/gmh5225/DLLirant [Hijacking researches]
- https://github.com/gmh5225/DLLirant [Hijacking researches Tool]
- https://github.com/gmh5225/ImpulsiveDLLHijack [Hijacking researches]
- https://github.com/gmh5225/HijackLibs [Project for tracking publicly disclosed DLL Hijacking opportunities]
- https://github.com/gmh5225/DLL-Hijack-ExportDumper [Dump the export table of PE files]
- https://github.com/gmh5225/DLLSpy [DLL Hijacking Detection Tool]
- [Project for identifying executables and DLLs vulnerable to relative path DLL hijacking](https://github.com/gmh5225/windows-dll-hijacking)
- https://github.com/gmh5225/SuperDllHijack [A general DLL hijack technology]
- https://github.com/gmh5225/DLLHSC [DLL Hijack SCanner]

> Hook
- https://github.com/stars/gmh5225/lists/hook [Lists]
- https://github.com/gmh5225/Detours
- https://github.com/gmh5225/DetoursNT
- https://github.com/gmh5225/ntminhook [A modified version of MinHook that only uses the Windows Native API]
- https://github.com/gmh5225/PolyHook
- https://github.com/gmh5225/PolyHook_2_0
- https://github.com/gmh5225/RenHook
- https://github.com/gmh5225/KernelPatch [Hooking the Linux kernel]
- https://github.com/gmh5225/subhook
- https://github.com/axhlzy/PyAsmPatch
- https://github.com/gmh5225/Driver-KDtour [Easy Kernel Detour]
- https://github.com/gmh5225/PGHooker [Page Guard]
- https://github.com/gmh5225/SkipHook [Skip Hook]
- https://github.com/gmh5225/edgegdi_hook [gdi32 .data swap]
- https://github.com/noobpk/frida-android-hook [frida hook for android]
- https://github.com/gmh5225/LightHook [cross-platform hook library]
- https://github.com/3intermute/arm64_silent_syscall_hook [ARM64 Patching exception handler]
- https://github.com/gmh5225/plthook [PLT(Procedure Linkage Table) hook]
- https://github.com/WeiJiLab/kernel-hook-framework [linux kernel inline hook framework]
- https://github.com/gmh5225/And64InlineHook [Android ARMv8 inline hook framework]
- https://github.com/gmh5225/Android_Inline_Hook_ARM64 [Android ARMv8 inline hook framework]
- https://github.com/gmh5225/BWSR [Arm64 inline hooking for iOS, Android, OSX, and Linux]
- https://github.com/regomne/ilhook-rs [Rust x86]
- https://github.com/gmh5225/abyss [Android system call hook]
- https://github.com/jsherman212/xnuspy [an iOS kernel function hooking framework for checkra1n'able devices]

> ROP Finder
- https://github.com/0vercl0k/rp [rp++ is a fast C++ ROP gadget finder for PE/ELF/Mach-O x86/x64/ARM/ARM64 binaries]
- https://github.com/gmh5225/ROPgadget [This tool lets you search your gadgets on your binaries to facilitate your ROP exploitation]
- https://github.com/gmh5225/Agafi [A gadget finder and a ROP-Chainer tool for x86 platforms]
- https://github.com/gmh5225/ropgadget-rs [Another (bad) ROP gadget finder, but this time in Rust]
- https://github.com/gmh5225/ropium [ROPium is a tool that helps you building ROP exploits by finding and chaining gadgets together]
- https://github.com/gmh5225/angrop [angrop is a rop gadget finder and chain builder]

> ROP Generation
- https://github.com/gmh5225/exrop

> Anti Signature Scanning
- https://github.com/gmh5225/avdebugger

> RPM
- https://github.com/gmh5225/access
- https://github.com/gmh5225/intraceptor [access]
- https://github.com/gmh5225/access_updated [Updated fork of btbd/access with Zydis-based dynamic pattern finding for Windows 10/11 compatibility]
- https://github.com/gmh5225/readwrite-kernel-stable
- https://github.com/gmh5225/Blackbone
- https://github.com/gmh5225/Kernel-Bridge
- https://github.com/gmh5225/EUPMAccess
- https://github.com/gmh5225/UMPMLib
- https://github.com/gmh5225/Remap [Clone process]
- https://github.com/gmh5225/EFI_Driver_Access [EFI RPM]
- https://github.com/SamuelTulach/efi-memory [EFI RPM]
- https://github.com/gmh5225/SubGetVariable [EFI RPM]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/489305-read-write-process-attach.html
- https://www.unknowncheats.me/forum/anti-cheat-bypass/444289-read-process-physical-memory-attach.html
- https://github.com/gmh5225/mempeek [Linux]
- https://github.com/gmh5225/meme-rw [kdmapper]
- https://github.com/gmh5225/Driver-RPM-DirectPageManipulation [read physical memory]
- https://github.com/gmh5225/ddma [Disk based DMA for ATA and SCSI]
- https://github.com/gmh5225/DDMA-1 [Disk based DMA for ATA and SCSI]
- https://github.com/gmh5225/vm [Minimal memory library for Windows/Linux]
- https://github.com/gmh5225/TaxiDriver [W/RPM Driver and usermode for Linux]
- https://github.com/gmh5225/Android-MemoryTool [RPM for Android]
- https://github.com/Poko-Apps/MemKernel [RPM for Android]
- https://github.com/Anonym0usWork1221/C-Android-Memory-Tool [RPM for Android]
- https://github.com/0xenia/remem [RPM for Windows]
- https://github.com/gmh5225/DMAInvoker [DMA RPM for Windows]
- https://github.com/gmh5225/Driver-physical-rw [Kernel-mode W/RPM for Windows]
- https://github.com/nbqofficial/norsefire [Kernel-mode W/RPM/mouse_event for Windows]
- https://github.com/gmh5225/Shirakumo [RPM for Windows]
- https://github.com/gmh5225/Usugumo [Kernel-mode W/RPM/mouse_event for Windows]
- https://github.com/gmh5225/WaryasSWHE [Usermode exploit to bypass any AC using a 0day shatter attack]

> DMA
- https://github.com/gmh5225/DMA-FW-Guide-2.0 [Guide]
- https://github.com/gmh5225/DMA [Guide]
- https://github.com/gmh5225/Learn-FPGA-Programming [Guide]
- https://github.com/enjoy-digital/litepcie [Small footprint and configurable PCIe core]
- https://github.com/gmh5225/pciem [A Linux framework for synthetic PCIe device emulation entirely in userspace]
- https://github.com/gmh5225/pcileech
- https://github.com/gmh5225/pcileech-wifi [pcileech-fpga with wireless card emulation]
- https://github.com/gmh5225/pico_dma
- https://github.com/gmh5225/dma-cheat-base [Cheat base]
- https://github.com/gmh5225/DMALib [DMA library]
- https://github.com/gmh5225/DMALibrary [DMA library]
- https://github.com/gmh5225/vm [Minimal memory library for Windows/Linux]
- https://github.com/gmh5225/ReClass-DMA [ReClass DMA]
- https://github.com/gmh5225/CheatEngine-DMA [CheatEngine DMA]
- https://github.com/gmh5225/Cheat-Engine-DMA-Plugin [CheatEngine DMA]
- https://github.com/un4ckn0wl3z/DMACheatEngineLoader [CheatEngine DMA, not open-source]
- https://github.com/gmh5225/MemTools [Windows/Linux DMA testing tools]
- https://github.com/gmh5225/physpatch [Scanning and patching of the entire Windows Kernel using DMA]
- https://github.com/gmh5225/DMA-PCIE-BOARD-75T [DMA-PCIE-BOARD-75T]
- https://github.com/gmh5225/DMA-E3100-CFW-BYPASS [DMA-BYPASS-Killer]
- https://github.com/gmh5225/pcileech-wifi-v2 [pcileech-fpga with wireless card emulation]
- https://github.com/gmh5225/DMA_PE_Dumper [DMA PE (Portable Executable) Dumper with DTB patching capabilities]
- https://github.com/gmh5225/PCILeech-FPGA-DMA_VMD [PCILeech FPGA DMA VMD Controller Simulation Project]
- https://github.com/Herooyyy/Free-DMA-Firmware-pcileech [Free DMA Firmware.Bypass VGK/FAC and MSI-X interrupt]
- https://github.com/gmh5225/Pcileech-AMDPCI [Using no interrupt bypass faceit/vgk]
- https://github.com/Herooyyy/Pcileech-Intel-I226-V-FullEmu [Intel-I226-V]
- https://github.com/Herooyyy/Pcileech-ISABridge [Use specific PID/VID to bypass faceit]
- https://github.com/d1skq/vgk-dma-bypass [VGK DMA bypass]
- https://github.com/Ptolemaios9/Pcileech-DMA-NVMe-VMD [Firmware real camouflage through motherboard VMD function.（Pcileech-DMA）]

> W2S
- https://github.com/DrNseven/D3D11-Worldtoscreen-Finder

> Overlay
- https://github.com/coltonon/D2DOverlay
- https://github.com/SurgeGotTappedAgain/Window-Hijack
- https://github.com/SeanPesce/Direct3D9-Overlay [DX9]
- https://github.com/Unkn0wnH4ck3r/GameOverlayUIHook [Steam]
- https://github.com/gmh5225/Steam-Hook-Render-PoC [Steam]
- https://github.com/xo1337/steam-overlay-x64 [Steam]
- https://github.com/Splitx12/StrongSteam [GDI + Steam]
- https://github.com/gmh5225/dwmhook [DWM]
- https://github.com/LoxTus/dwm-overlay [DWM]
- https://github.com/rlybasic/DWM_Hook [DWM]
- https://github.com/mfxiaosheng/dwmhook [DWM VFTable]
- https://github.com/gmh5225/nvidia-overlay-hijack [Hijack Nvidia]
- https://github.com/Brattlof/D3DOverlay-Nvidia-Hijack [Hijack Nvidia]
- https://github.com/gmh5225/NVIDIA-OVERLAY [Hijack Nvidia]
- https://github.com/Calvin-LLC/nvidia-overlay-hijack [Hijack Nvidia]
- https://github.com/es3n1n/nvidia-overlay-renderer [Nvidia]
- https://github.com/muturikaranja/overlay [SetWindowsHookEx]
- https://github.com/gmh5225/OBS-graphics-hook32-Hook [OBS Hook]
- https://github.com/gmh5225/OBS-Hook [OBS Hook]
- https://github.com/PierreCiholas/NotAnOverlay [Duplicating with GDI]
- https://github.com/SsageParuders/Android_Native_Surface [Android Native Overlay]
- https://github.com/gmh5225/Android_Native_Surface [Android Native Overlay]
- https://github.com/xBrunoMedeiros/eac-overlay [EAC Overlay]
- https://github.com/3r4y/imgui-external-overlay [imgui overlay]
- https://github.com/J0xna/Kernel-Overlay-Hider [Kernel Overlay Hider]
- https://github.com/geeksonsecurity/android-overlay-malware-example [Android]
- https://github.com/SamuelTulach/OverlayCord [Discord] 

> Render/Draw
- https://github.com/vmcall/dxgkrnl_hook
- https://github.com/thesecretclub/window_hijack [Hijacking thread contexts]
- https://github.com/r1cky33/krnl-gdi-render [Dxgkrnl + GDI]
- https://github.com/BadPlayer555/KernelGDIDraw [Kernel + GDI]
- https://github.com/NSG650/NtDOOM [Kernel + GDI]
- https://github.com/Splitx12/StrongSteam [GDI + Steam]
- https://github.com/Sentient111/KernelDrawing [Drawing from kernelmode without any hooks]
- https://github.com/wbaby/DoubleCallBack [DWM In Kernel]
- https://github.com/cs1ime/KernelDwm [DWM In Kernel]
- https://github.com/gmh5225/DWM-DwmDraw [DWM StackWalk]
- https://github.com/Yukin02/Dwm-Overlay [DWM Overlay without modify .text]
- https://github.com/Polarmods/PolarImGui [Imgui On Android]
- https://github.com/vrolife/android_native_app_imgui [Imgui On Android]
- https://github.com/LGLTeam/Android-Mod-Menu [Floating mod menu for Android]
- https://github.com/springmusk026/ImGui-Unity-With-Layout [Imgui For Unity]
- https://github.com/springmusk026/Imgui-Unity [Imgui For Unity]
- https://github.com/gmh5225/Android-Mod-Menu-ImGui [Imgui For Unity]
- https://github.com/Octowolve/Unity-ImGUI-Android [Imgui For Unity]
- https://github.com/lbertitoyt/ImGUI-Zygisk-Unity [Imgui For Unity]
- https://github.com/gmh5225/zygisk-imgui-modmenu [ImGui with Zygisk]
- https://github.com/gmh5225/ImGui-Unity-Android [Imgui For Unity]
- https://github.com/gmh5225/BepInEx-IL2CPPBase [IL2CPP Menu]
- https://github.com/springmusk026/Android-Mod-Menu-Kotlin [IL2CPP Menu]
- https://github.com/gmh5225/Android-OpenGL-ES-Chams [Chams]
- https://github.com/RequestFX/ImGUI-Advanced-Cheat-Menu [Imgui Menu]
- https://github.com/gmh5225/External-imgui-Cheat-Menu-Example-2023 [External Imgui Menu]
- https://github.com/gmh5225/External-ImGui-Android [External Imgui Menu for Android]
- https://github.com/xProHackerx/imgui-ios-mod-menu [Imgui Menu for IOS]
- https://github.com/gmh5225/egui-d3d11 [Menu]
- https://github.com/springmusk026/Android-ModMenu-SemiJni [Menu for imgui]
- https://github.com/fedes1to/Zygisk-ImGui-Menu [ImGui menu using Zygisk]
- https://github.com/reveny/Zygisk-ImGui-Mod-Menu [ImGui menu using Zygisk]
- https://github.com/s4m33r89/Imgui-Native-ModMenu [Imgui Menu for Android]
- https://github.com/joeyjurjens/iOS-Mod-Menu-Template-for-Theos [IOS mod menu]

> UI Interface
- https://github.com/adamhlt/ImGui-Standalone

> Vulnerable Driver 
- https://www.loldrivers.io/drivers [Living Off The Land Drivers]
- https://github.com/magicsword-io/LOLDrivers [Living Off The Land Drivers]
- https://github.com/ghostbyt3/BYOVDFinder [Identifies LOLDrivers that are not blocked by the active HVCI policy]
- https://github.com/rtfmkiesel/loldrivers-client [Scan loldrivers]
- https://github.com/FourCoreLabs/LolDriverScan [Scan loldrivers]
- https://github.com/trailofbits/HVCI-loldrivers-check [HVCI loldrivers check]
- https://github.com/hacksysteam/HackSysExtremeVulnerableDriver [Guide]
- https://github.com/xct/windows-kernel-exploits [Guide]
- https://github.com/namazso/physmem_drivers [Vulnerable Driver List]
- https://github.com/alfarom256/drivers_and_shit [Vulnerable Driver List]
- https://github.com/gmh5225/WinKernel-Resources/tree/main/Drivers [Vulnerable Driver List]
- https://github.com/CaledoniaProject/drivers-binaries [Vulnerable Driver List]
- https://github.com/Xxmmy/vulnerable-driver-scanner [Scans for vulnerable drivers]
- https://github.com/Sentient111/VulnerableDriverScanner [Scans for vulnerable drivers]
- https://github.com/shareef12/cpuz [CPU-Z]
- https://github.com/SamLarenN/CPUZ-DSEFix [CPU-Z]
- https://github.com/gmh5225/gdrv-loader/tree/1909_mitigation [gdrv.sys]
- https://github.com/backengineering/VDM [gdrv enhance]
- https://github.com/Compiled-Code/eac-mapper [gdrv.sys]
- https://github.com/gmh5225/CVE-2018-19320-LPE [gdrv.sys]
- https://github.com/gmh5225/CVE-2018-19320 [gdrv.sys]
- https://github.com/gmh5225/gdriver-lib [gdrv.sys]
- https://github.com/holi4m/gdrv-loader-v2 [gdrv.sys]
- https://github.com/gmh5225/KDP-compatible-driver-loader [gdrv.sys]
- https://github.com/1337kenzo/gdrv-loader-updated [gdrv.sys Win11]
- https://github.com/AmitMoshel1/gdrv_sys_exploit [gdrv.sys Win11]
- https://github.com/eddeeh/kdmapper [iqvw64e.sys]
- https://github.com/TheCruZ/kdmapper [iqvw64e.sys]
- https://github.com/Brattlof/kdmapper-1909 [iqvw64e.sys]
- https://github.com/paysonism/saturn-mapper [iqvw64e.sys]
- https://github.com/rmccrystal/kdmapper-rs [A kdmapper library for Rust]
- https://github.com/kkent030315/MsIoExploit [MsIo64.sys]
- https://github.com/gmh5225/VulnerableKernel_Driver [MsIo64.sys]
- https://github.com/kkent030315/evil-mhyprot-cli [Mhyprot2.sys]
- https://github.com/gmh5225/evil-mhyprot-cli [Mhyprot2.sys]
- https://github.com/gmh5225/mhydeath [Mhyprot2.sys]
- https://github.com/gmh5225/mhyprot2 [Mhyprot2.sys]
- https://github.com/gmh5225/Mhyprot2DrvControl [Mhyprot2.sys]
- https://github.com/gmh5225/CVE-2020-36603 [Mhyprot2.sys]
- https://github.com/gmh5225/AvastHV [Avast]
- https://github.com/gmh5225/KasperskyHook [Kaspersky]
- https://github.com/gmh5225/EvilKaspersky [Kaspersky]
- https://github.com/gmh5225/CVE-2021-21551 [dbutil_2_3.sys]
- https://github.com/gmh5225/CVE-2021-21551 [dbutil_2_3.sys]
- https://github.com/gmh5225/Kernel-Cactus [dbutil_2_3.sys]
- https://github.com/gmh5225/CVE-2021-21551-POC [dbutil_2_3.sys]
- https://github.com/gmh5225/TS-Fucker [dbutil_2_3.sys]
- https://github.com/gmh5225/imxyviMapper [AsUpIO.sys]
- https://github.com/gmh5225/vdk [Speedfan.sys]
- https://github.com/gmh5225/SpeedFan-Exploit [Speedfan.sys]
- https://github.com/gmh5225/CapcomLib [Capcom.sys]
- https://github.com/gmh5225/dolboeb-executor [Capcom.sys]
- https://github.com/gmh5225/CapcomDKOM [Capcom.sys]
- https://github.com/gmh5225/dbk64-vulnerability-driver [dbk64.sys]
- https://github.com/gmh5225/CVE-2015-2291 [IQVW64.sys]
- https://github.com/gmh5225/AsIO-Exploit [AsIO3.sys]
- https://github.com/gmh5225/AsusDrv [AsusBiosIoDrv64.sys]
- https://github.com/gmh5225/OpenHardwareMonitor-PoC [OpenHardwareMonitorLib.sys]
- https://github.com/gmh5225/PPLKiller [RTCore64.sys]
- https://github.com/gmh5225/PsNotifRoutineUnloader [RTCore64.sys]
- https://github.com/gmh5225/CYBERSEC2023-BYOVD-Demo [RTCore64.sys]
- https://github.com/gmh5225/RTCore64_Vulnerability [RTCore64.sys]
- https://github.com/gmh5225/CVE-2022-42045 [amsdk.sys]
- https://github.com/gmh5225/WatchDogKiller [amsdk.sys]
- https://github.com/gmh5225/CVE-2022-3699 [LenovoDiagnosticsDriver.sys]
- https://github.com/gmh5225/lenovo_mapper [LenovoDiagnosticsDriver.sys]
- https://github.com/gmh5225/lenovo_exec [LenovoDiagnosticsDriver.sys]
- https://github.com/gmh5225/CVE-2022-42046 [wfshbr64.sys]
- https://github.com/gmh5225/amd-ryzen-master-driver-v17-exploit [AMD's Ryzen Master Driver]
- https://github.com/gmh5225/RToolZ [ProcExp152.sys]
- https://github.com/gmh5225/nullmap [Afd.sys]
- https://github.com/gmh5225/Windows-10-22H2-Vulnerable-driver-communication [asromgdrv.sys]
- https://github.com/gmh5225/HPHardwareDiagnostics-PoC [etdsupp.sys]
- https://github.com/gmh5225/Blackout [gmer64.sys]
- https://github.com/gmh5225/Terminator [zam64.sys]
- https://github.com/gmh5225/zam64-zemina [zam64.sys]
- https://github.com/gmh5225/CVE-2017-9769 [rzpnk.sys]
- https://github.com/gmh5225/echoac-poc [echo_driver.sys]
- https://github.com/gmh5225/kur [echo_driver.sys]
- https://github.com/gmh5225/NVDrv [nvaudio.sys]
- https://github.com/gmh5225/UCMapper [nvaudio.sys]
- https://github.com/gmh5225/HITCON-2023-Demo-CVE-2023-20562 [AMDCpuProfiler.sys]
- https://github.com/gmh5225/BadRentdrv2 [rentdrv2.sys]
- https://github.com/gmh5225/S4Mapper [SignalRgbDriver.sys]
- https://github.com/gmh5225/dse_hook [winio64.sys]
- https://github.com/gmh5225/s4killer [probmon.sys]
- https://github.com/gmh5225/KExecDD [KSecDD.sys]
- https://github.com/gmh5225/KexecDDPlus [KSecDD.sys]
- https://github.com/gmh5225/CVE-2024-26229 [csc.sys]
- https://github.com/gmh5225/ZeroHVCI [csc.sys]
- https://github.com/gmh5225/Win-Driver-EXP/tree/main/CVE-2024-33218 [AsUpIO64.sys]
- https://github.com/gmh5225/Win-Driver-EXP/tree/main/CVE-2024-30804 [AsInsHelp64.sys]
- https://github.com/gmh5225/CVE-2020-14974 [IObitUnlocker.sys]
- https://github.com/gmh5225/ProcessKiller-BYOVD [viragt64.sys]
- https://github.com/CyberSecurityUP/UrekMazino-Malware [viragt64.sys]
- https://github.com/gmh5225/BYOVD/tree/main/Viragt64-Killer [viragt64.sys]
- https://github.com/CyberSecurityUP/ViGEmBus-Driver-Exploitation [ViGEmBus.sys]
- https://github.com/MrAle98/ATDCM64a-LPE [[atdcm64a.sys](https://security.humanativaspa.it/exploiting-amd-atdcm64a.sys-arbitrary-pointer-dereference-part-1/)]
- https://github.com/gmh5225/CVE-2024-35250 [ks.sys]
- https://github.com/gmh5225/CVE-2024-21338 [appid.sys]
- https://github.com/MrAle98/CVE-2024-49138-POC [CLFS.sys]
- https://github.com/gmh5225/CVE-2025-21333-POC [vkrnlintvsp.sys]
- https://github.com/Xacone/Eneio64-Driver-Exploit [eneio64.sys]
- https://github.com/gmh5225/BYOVD/tree/main/TfSysMon-Killer [SysMon.sys]
- https://github.com/gmh5225/BYOVD/tree/main/Ksapi64-Killer [ksapi64.sys]
- https://github.com/gmh5225/BYOVD/tree/main/BdApiUtil-Killer [BdApiUtil64.sys]
- https://github.com/0xJs/BYOVD_EDRKiller/tree/main/BdApiUtil [BdApiUtil64.sys]
- https://github.com/gmh5225/BYOVD/tree/main/Wsftprm-Killer [wsftprm.sys]
- https://github.com/0xJs/BYOVD_EDRKiller/tree/main/Wsftprm [wsftprm.sys]
- https://github.com/0xJs/BYOVD_EDRKiller/tree/main/truesight [truesight.sys]
- https://github.com/kyxiaxiang/360WFP_Exploit [BYOVD: Use 360netmon_x64.sys_wfp ​​WFP driver to block EDR/XDR network connection]
- https://blog.talosintelligence.com/decrement-by-one-to-rule-them-all [AsIO3.sys]
- https://github.com/gmh5225/Killer-Exercice [An Exercice for Red Team to Reverse & Exploit, that's a valide BYOVD Killer, not HVCI Blocklisted, and not in LOLBIN]
- https://github.com/gmh5225/ampa.sys-exp [ampa.sys]
- https://github.com/0xJs/BYOVD_read_write_primitive [BYOVD Read Write primitive]
- https://github.com/U65535F/ThrottleStopPoC [ThrottleStop.sys]
- https://github.com/ANYLNK/NSecSoftBYOVD [NSecKrnl.sys]
- https://github.com/moiz-2x/CVE-2025-24990_POC [ltmdm64.sys]
- https://github.com/symeonp/Lenovo-CVE-2025-8061 [PoC for popping a system shell against the LnvMSRIO.sys driver]
- https://github.com/gmh5225/Killer [Non HVCI Block listed - Microsoft signed driver exploited to kill AV/EDR's processes]

> Driver Communication
- https://github.com/gmh5225/Driver-Communication-List
- https://github.com/gmh5225/ida-find-.data-ptr [.data ptr lookup script]
- https://github.com/EBalloon/Common-Registry [Registry Callback]
- https://github.com/gmh5225/Common-Registry-Jmp-RCX [Registry Callback]
- https://github.com/0xGREG/registry-callbacks [Registry Callback]
- https://github.com/adrianyy/rw_socket_driver [Socket]
- https://github.com/zoand/BOOM [Hijack Beep.sys]
- https://github.com/gmh5225/Driver-read_write [Hijack IRP Beep.sys]
- https://github.com/isoadam/gina_public [Hijack IRP Null]
- https://github.com/Barracudach/Swap-control-ioctl [Hijack IRP SpeedFan.sys]
- https://github.com/adspro15/km-um-communication
- https://github.com/Spuckwaffel/Kernel-Thread-Driver [Thread]
- https://github.com/Astronaut00/DoubleDataPointer [Double Data Pointer]
- https://github.com/gmh5225/access [NtConvertBetweenAuxiliaryCounterAndPerformanceCounter]
- https://github.com/gmh5225/access_updated [NtConvertBetweenAuxiliaryCounterAndPerformanceCounter]
- https://github.com/paradoxwastaken/Poseidon [NtConvertBetweenAuxiliaryCounterAndPerformanceCounter]
- https://github.com/FarmEquipment69/umap-mapper [NtConvertBetweenAuxiliaryCounterAndPerformanceCounter]
- https://github.com/0mWindyBug/DataptrHooks [NtConvertBetweenAuxiliaryCounterAndPerformanceCounter]
- https://github.com/weak1337/EvCommunication [NtTokenManagerCreateFlipObjectReturnTokenHandle]
- https://github.com/gmh5225/Driver-kaldereta [NtTokenManagerGetAnalogExclusiveTokenEvent]
- https://github.com/UCFoxi/Shared-FlushFileBuffers-Communication [FlushFileBuffers]
- https://github.com/gmh5225/UCFoxi-Shared-FlushFileBuffers-Communication-Update FlushFileBuffers]
- https://github.com/Sinclairq/DataCommunication [NtCompareSigningLevels]
- https://github.com/ExpLife0011/NtCompareSigningLevel-hook [NtCompareSigningLevels]
- https://github.com/muturikaranja/AfdIrpCallDispatch [.data Pointer hook in Afd.sys]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/483093-vtable-kernel-function-hook-communication.html [NtUserMessageCall]
- https://github.com/EBalloon/MapPage [NtUserGetObjectInformation]
- https://github.com/Compiled-Code/eac-mapper [NtMapVisualRelativePoints]
- https://github.com/gmh5225/eac-bypass-1 [NtMapVisualRelativePoints]
- https://git.back.engineering/_xeroxz/NtWin32k [NtUserGetThreadState]
- https://github.com/sbsbsbssbsbs/boundcallback [KeRegisterBoundCallback]
- https://github.com/gmh5225/DataPtrSwap-driver [NtSetCompositionSurfaceAnalogExclusive]
- https://github.com/xPasters/.data-ptr-swap [NtSetCompositionSurfaceAnalogExclusive]
- https://github.com/ryan-weil/ReadWriteDriver [NtUserSetSysColors]
- https://github.com/D3DXVECTOR2/NtUserUpdateWindowTrackingInfo [NtUserUpdateWindowTrackingInfo]
- https://github.com/KiFilterFiberContext/windows-software-policy [clip]
- https://github.com/gmh5225/Interep-Driver-Leak [NtGdiPolyPolyDraw]
- https://github.com/gmh5225/Comm-data-ptr-driver [NtGdiPolyPolyDraw]
- https://github.com/JGonz1337/kernel-eac-be-comm [NtGdiPolyPolyDraw]
- https://github.com/Lynnette177/Rigel-Driver [NtGdiDdDDINetDispGetNextChunkInfo]
- https://github.com/NullTerminatorr/NullHook [NtDxgkGetTrackedWorkloadStatistics]
- https://github.com/gmh5225/Kernel-Cheat-for-directx3D [NtDxgkGetTrackedWorkloadStatistics]
- https://github.com/gmh5225/Comm-Data-Pointer-Swap [NtDCompositionSetChildRootVisual]
- https://github.com/gmh5225/Comm-NekoSwap [Win32kApiSetTable]
- https://github.com/gmh5225/kernel_payload_comms [Shared Memory]
- https://github.com/Chase1803/UCMiraka-ValorantExternal [NtUserGetPointerProprietaryId]
- https://github.com/gmh5225/Comm-ImMiraclela [NtDxgkGetTrackedWorkloadStatistics/NtDxgkGetAvailableTrackedWorkLoadIndex]
- https://www.unknowncheats.me/forum/2976731-post45.html [IsWin32KSyscallFiltered]
- https://github.com/J0xna/Kernel-Overlay-Hider [NtMITPostWindowEventMessage]
- https://github.com/gmh5225/Eac-Injector-Driver [NtQueryIntervalProfile]
- https://github.com/gmh5225/job_communication [NtQueryInformationJobObject]
- https://github.com/gmh5225/custom_data_ptr_swap_sample [NtQueryLicenseValue]
- https://github.com/zer0condition/ZeroThreadKernel [NtCreateCompositionSurfaceHandle]
- https://github.com/gmh5225/NullDriverCheat [NtOpenCompositionSurfaceSectionInfo]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/560809-firmwaretablehandler.html [FirmwareTableHandler]
- https://github.com/oakboat/DataPtrHookWin11 [NtUserSetGestureConfig]
- 
- https://github.com/GetRektBoy724/Win32kHooker [.data ptr swapper for newer win32k versions]

> EFI Driver
- https://github.com/mrexodia/EfiCMake
- https://github.com/tandasat/MiniVisorPkg
- https://github.com/Oliver-1-1/SmmInfect [SMM Driver]
- https://github.com/Shtan7/VisualUEFI-2.0 [Debug source with clion+clang+gdb]
- https://github.com/SamuelTulach/EasyUefi [Visual Studio template for GNU-EFI]
- https://github.com/btbd/umap [EFI Manual Map]
- https://github.com/ekknod/sumap [EFI Manual Map]
- https://github.com/xtremegamer1/xigmapper [EFI Manual Map]
- https://github.com/Valthrun/valthrun-uefi-mapper [EFI Manual Map]
- https://github.com/ekknod/KiSystemStartupMeme [Custom KiSystemStartup]
- https://github.com/SamuelTulach/efi-memory [RPM]
- https://github.com/gmh5225/EFI_Driver_Access [RPM]
- https://github.com/gmh5225/Driver-efi-bootkit
- https://github.com/SamuelTulach/rainbow [HWID]
- https://github.com/gmh5225/-Rainbow---EFI [HWID]
- https://github.com/gmh5225/Fortnite-EFI-External [Fortnite]
- https://github.com/ajkhoury/UEFI-Bootkit
- https://github.com/SamuelTulach/negativespoofer [HWID]
- https://github.com/gmh5225/EfiDump [Dump]
- https://github.com/ekknod/Nmi [Blocking NMI interrupts]
- https://github.com/ekknod/smm [Smm cheat]
- https://github.com/sa413x/UEFI-Bootloader [Simple mmapper which using UEFI runtime driver]
- https://github.com/gmh5225/bootlicker [Generic UEFI bootkit used to achieve initial usermode execution]
- https://github.com/ekknod/efi-monitor [Hooking MmCopyMemory PG safe]
- https://github.com/leap0x7b/luaboot [A fully scriptable UEFI bootloader]
- https://github.com/Cr4sh/SmmBackdoorNg [UEFI backdoor]
- https://github.com/Oliver-1-1/UEFI-Graphic [Simpel usage of graphic in UEFI]
- https://github.com/Jamesits/BGRTInjector [Changes the boot screen image on a UEFI computer]
- https://github.com/NoInitRD/Memory-Dump-UEFI [A UEFI application for dumping the contents of RAM]
- https://github.com/gmh5225/NoMoreBugCheckReloaded [NoMoreBugCheck Reloaded]
- https://github.com/x90skysn3k/x260-lenovo-opencore [Lenovo-X260-Hackintosh-BigSur-OpenCore-0.8.5]
- https://github.com/gmh5225/OfflineCrashDumpUefi [EDK2 UEFI implementation for writing an Offline Crash Dump]
- https://github.com/Twobot7/advanced-efi-driver-with-gdi-and-kernel-mouse-input [A UEFI-based driver for direct memory access and process manipulation, with built-in security features and stealth capabilities]

> QEMU/KVM/PVE/VBOX
- https://github.com/david942j/kvm-kernel-example [Guide]
- https://github.com/airbus-seclab/qemu_blog [Guide]
- https://github.com/VirtualBox/virtualbox [VirtualBox Git mirror]
- https://github.com/mirror/vbox [VirtualBox Git mirror]
- https://github.com/BigAnteater/KVM-GPU-Passthrough [GPU Passthrough]
- https://github.com/dmaivel/ntoseye [Kernel Debugger]
- https://github.com/ispras/qemu/tree/windbg [Windbg]
- https://github.com/cyberus-technology/virtualbox-kvm [VirtualBox with KVM Backend]
- https://github.com/quic/gunyah-hypervisor [Type-1 hypervisor for ARM64]
- https://github.com/Qemu-Gang
- https://github.com/memflow/memflow-kvm
- https://github.com/IntroVirt/IntroVirt [Guest introspection library]
- https://github.com/MisterY52/apex_dma_kvm_pub
- https://github.com/SamuelTulach/BetterTiming [Bypass CPU Timing]
- https://github.com/WCharacter/RDTSC-KVM-Handler [Bypass RDTSC]
- https://github.com/batusan/Hardened-qemu [Hidden QEMU]
- https://github.com/zhaodice/qemu-anti-detection [Hidden QEMU]
- https://wbenny.github.io/2025/06/29/i-made-my-vm-think-it-has-a-cpu-fan.html [I made my VM think it has a CPU fan]
- https://github.com/kila58/qemu-patched [Hidden QEMU]
- https://github.com/Scrut1ny/Hypervisor-Phantom [Hidden QEMU]
- https://github.com/zhaodice/proxmox-ve-anti-detection [Hidden PVE]
- https://github.com/tteck/Proxmox [PVE Helper Scripts]
- https://github.com/nyx-fuzz/QEMU-Nyx [Intel-PT]
- https://github.com/doomedraven/Tools/blob/master/Virtualization/kvm-qemu.sh [QEMU Script]
- https://github.com/GlacierW/MBA [QEMU Malware Behavior Analyzer]
- https://github.com/Qemu-Gang/Escape-from-TuxKov [EFT]
- https://github.com/LWSS/Ape-ex-Abominations [Apex]
- https://github.com/Qemu-Gang/QemuUnrealDumper-4.25 [UE SDK Dump By QEMU]
- https://github.com/panda-re/panda [Platform for Architecture-Neutral Dynamic Analysis]
- https://github.com/cs1ime/blacksun-framework [Framework for game cheat development]
- https://github.com/cs1ime/ceserver-rawmem [CE]
- https://github.com/gmh5225/kvm-csgo-cheat [CSGO]
- https://github.com/atombottle/cs2_kvm_dma [CS2]
- https://github.com/gmh5225/cs16-trigger-kvm [CS1.6]
- https://github.com/gmh5225/mvisor [C++ remake]
- https://github.com/gmh5225/docker-win [wsl2]
- https://github.com/gmh5225/KVM.Performance [ioapic]
- https://github.com/gmh5225/xqemu [Play original Xbox games]
- https://github.com/gmh5225/xnu-qemu-arm64 [xnu]
- https://github.com/ktock/qemu-wasm [QEMU on browser]

> Wine
- https://github.com/gmh5225/Proton [Steam]
- https://github.com/gmh5225/ptrace_read_teb [use ptrace to read the TEB of a process on Linux]

> Anti Screenshot
- https://github.com/gmh5225/NoScreen [Hide Window]
- https://github.com/gmh5225/dwmhook [DWM]
- https://github.com/gmh5225/wda_monitor_trick
- https://github.com/gmh5225/Screenshot-Detection-Bypass [BitBlt]
- https://github.com/gmh5225/DisableNvidiaScreenshot [DWM]

> Spoof Stack
- https://github.com/gmh5225/ThreadStackSpoofer
- https://github.com/gmh5225/x86RetSpoof
- https://github.com/gmh5225/return-address-spoofing
- https://github.com/gmh5225/Exception-Ret-Spoofing
- https://github.com/gmh5225/Ret-Spoofing
- https://github.com/gmh5225/CallStackSpoofer
- https://github.com/gmh5225/CallStackSpoofer-2
- https://github.com/gmh5225/CallStack-Spoofer
- https://github.com/gmh5225/NimicStack
- https://github.com/gmh5225/callout-poc
- https://github.com/gmh5225/Return-address-spoofer
- https://www.unknowncheats.me/forum/anti-cheat-bypass/512002-x64-return-address-spoofing.html
- https://github.com/gmh5225/Unwinder [Another approach to thread stack spoofing]
- https://github.com/gmh5225/SilentMoonwalk [a TRUE call stack spoofer]
- https://github.com/gmh5225/spoof-stack-SafeCall [header only]
- https://github.com/gmh5225/hw-call-stack [HWBP]
- https://github.com/gmh5225/ProxyAPICall [Custom stack call]
- https://github.com/gmh5225/Shelter [ROP-based sleep obfuscation]
- https://github.com/gmh5225/LoudSunRun [Stack Spoofing with Synthetic frames based on the work of namazso, SilentMoonWalk, and VulcanRaven]
- https://github.com/gmh5225/Fenrir [Stack spoofing using jmp rdi]
- https://github.com/gmh5225/StackSpoofer_Macro [An easy-to-use and powerful Macro for Stack Spoofing]
- https://github.com/gmh5225/Spoof-RetAddr [Spoofing the return address of a WinAPI call by modifying the stack]

> Hide
- https://github.com/gmh5225/hidden
- https://github.com/gmh5225/hide-file [Hide File]
- https://github.com/gmh5225/ANTfs [Delete File]
- https://github.com/gmh5225/NoScreen [Hide Window]
- https://github.com/gmh5225/WindowProtect [Hide Window]
- https://github.com/nlepleux/MappedCallback [Hide Callback]
- https://github.com/rogerxiii/kernel-codecave-poc [Find Codecave]
- https://github.com/gmh5225/SinMapper [Manual Map In Signed Driver]
- https://github.com/gmh5225/DSMM [Discarded Driver Section Manual Map]
- https://github.com/ekknod/sumap [EFI Manual Map]
- https://github.com/gmh5225/lpmapper [Manual Map To Large Page Driver]
- https://github.com/armvirus/CosMapper [Signed Driver Map]
- https://github.com/gmh5225/HideDriverTesting [Hide Driver]
- https://github.com/gmh5225/Drv_Hide_And_Camouflage [Hide Driver]
- [Exploring CI.dll and Bigpool Cache](https://github.com/gmh5225/hLunaaa.github.io/blob/4eb5450cb245217543733b475ce1198b812551a6/_posts/2025-04-25-Bypassing-CR3-Abuse-with-Physical-RW%20copy.markdown) [Driver Trace Cleaner]
- https://github.com/gmh5225/TraceCleaner [Driver Trace Cleaner]
- https://github.com/gmh5225/ClearDriverTraces [Driver Trace Cleaner]
- https://github.com/KelvinMsft/NoTruth [Hide Memory By VT]
- https://github.com/EBalloon/MapPage [Self Map Driver]
- https://github.com/Compiled-Code/eac-mapper [Self Map Driver]
- https://github.com/gmh5225/HideDriver [Hide Driver By Modify Flink/Blink]
- https://github.com/gmh5225/HideDriver [Hide Driver By MiProcessLoaderEntryk]
- https://github.com/gmh5225/Driver-HideKernelThread-IoCancelIrp [Hide Kernel Thread]
- https://github.com/gmh5225/blanket [Hide Kernel Thread]
- https://github.com/gmh5225/herpaderping [Hide Process/File]
- https://github.com/gmh5225/KaynStrike [Spoofs Thread Start Address]
- [Using .reloc section to replace the typical allocation calls](https://github.com/gmh5225/memory-relocalloc)
- https://github.com/longpoxin/hideroot [Magisk]
- https://github.com/gmh5225/Diglett [Hide Kernel Thread]
- https://github.com/gmh5225/Driver-SessionMapper [Session Driver]
- https://github.com/gmh5225/Map-file-in-system-space [MiMapViewInSystemSpace]
- https://github.com/gmh5225/Driver-DriverNoImage [Hijack Driver]
- https://github.com/gmh5225/Driver-Systemthread-from-PspCidTable-src [Hide Process/Thread/Handle]
- https://github.com/gmh5225/Android-Library-Remap-Hide [Remap a library for Android]
- https://github.com/gmh5225/BootExecuteEDR [BootExecute EDR Bypass]

> Anti Forensics
- https://github.com/gmh5225/Forensia
- https://github.com/ashemery/Anti-Forensics

> Triggerbot & Aimbot
- https://github.com/gmh5225/MouHidInputHook
- https://github.com/gmh5225/AcDrv [mouse hook]
- https://github.com/gmh5225/MouseClassServiceCallbackTrick
- https://github.com/gmh5225/MouseClassServiceCallbackMeme
- https://github.com/gmh5225/PareidoliaTriggerbot
- https://github.com/gmh5225/DirectInput
- https://github.com/nbqofficial/norsefire
- https://github.com/gmh5225/Pine [Neural Network]
- https://github.com/gmh5225/AI-FPS-b00m-h3adsh0t [Neural Network]
- https://github.com/gmh5225/input-overlay [Keyboard Mapper]
- https://github.com/Miffyli/gan-aimbots [Machine Learning]
- https://github.com/gmh5225/AI-Aimbot [Machine Learning YOLOv5]
- https://github.com/gmh5225/SF_TRT_61 [Machine Learning YOLO]
- https://github.com/gmh5225/Auto_aim [DXGI + TensorRT + driver-level input]
- https://github.com/gmh5225/RookieAI_yolov8 [Machine Learning YOLOv8]
- https://github.com/gmh5225/YOLOv8-Overlay-CS2 [YOLOv8 in CS2]
- https://github.com/gmh5225/pubg-ai-yolov4 [PUBG yolov4]
- https://github.com/gmh5225/yolov5_PUBG [PUBG yolov5]
- https://github.com/gmh5225/yolo-v8s [PUBG yolo dataset]
- https://github.com/gmh5225/yolo-v8m [PUBG yolo dataset]
- https://github.com/gmh5225/camera-triggerbot [Camera Triggerbot]
- https://github.com/gmh5225/KernelMoveMouse [gptCursorAsync]
- https://github.com/gmh5225/mouse-input-injection [NtUserInjectMouseInput]
- https://github.com/gmh5225/Overwatch-1-cheat-source [NtUserInjectMouseInput]
- https://github.com/gmh5225/NtUserInjectMouseInput-syscall [NtUserInjectMouseInput SYSCALL]
- https://github.com/gmh5225/ClickPic [OpenCV + Triggerbot]
- https://github.com/gmh5225/OpenCV-SmartAimBot [OpenCV + Triggerbot]
- https://github.com/gmh5225/AutoHotkey_L
- https://github.com/gmh5225/HumanMouseMovement
- https://github.com/AsfhtgkDavid/windmouse [Human-like mouse movement using WindMouse algorithm]
- https://github.com/gmh5225/IbInputSimulator [Simulating keyboard, mouse]
- https://github.com/gmh5225/logitech-cve [logitech]
- https://github.com/gmh5225/razer-rzctl [Razer]
- https://github.com/gmh5225/kernel-mouse [MouClass]
- https://github.com/gmh5225/android_touch [For Android]
- https://github.com/muchenspace/android_virtualTouch [For Android]
- https://github.com/gmh5225/PTFakeTouch [For IOS]
- https://github.com/gmh5225/mouse_input_injection [NtUserInjectMouseInput]
- https://github.com/gmh5225/Usugumo [Kernel-mode mouse_event]
- https://github.com/gmh5225/logitech-cve [A Rust library for interacting with Logitech virtual driver]

> WallHack
- https://github.com/gmh5225/D3D11-Wallhack

> HWID
- https://github.com/gmh5225/Ow-Anti-Flag
- https://github.com/gmh5225/hwid
- https://github.com/gmh5225/Driver-HWID-btbd-modified
- https://github.com/gmh5225/HWID-Permanent-HWID-Spoofer
- https://github.com/gmh5225/PrecisionSpoofer-CPP
- https://github.com/gmh5225/Hwid-Spoofer-EAC-BE
- https://github.com/gmh5225/hwidspoofer
- https://github.com/gmh5225/Hwid--Spoofer
- https://github.com/gmh5225/Hwid-Spoofer
- https://github.com/gmh5225/Apex-Spoofer
- https://github.com/gmh5225/HWID-EclipsedSpoofer-EAC-BE
- https://github.com/gmh5225/HWIDSpooferEAC
- https://github.com/SamuelTulach/rainbow [EFI]
- https://github.com/gmh5225/-Rainbow---EFI [EFI]
- https://github.com/gmh5225/wpp [Intercepting DeviceControl via WPP]
- https://github.com/gmh5225/owned_alignment [Abusing Alignment]
- https://github.com/gmh5225/HWID-Kernel-Spoofer
- [HWID-Spoofer-UD-Fortnite-WarZone-Apex-Rust-Escape-From-Tarkov-and-all-EAC-BE-Games-IMGUI-Loader-Base](https://github.com/gmh5225/HWID-Spoofer-UD-Fortnite-WarZone-Apex-Rust-Escape-From-Tarkov-and-all-EAC-BE-Games-IMGUI-Loader-Base)
- https://github.com/gmh5225/mutante
- https://github.com/Veuqx0/ImGui-Spoofer-Leaked
- https://github.com/gmh5225/HWID-Spoofer-for-Fortnite-and-Valorant
- https://github.com/gmh5225/Full-Hwid-Spoofer-V6
- https://github.com/gmh5225/HWID-SteamSpywareTerminator [Steam]
- https://github.com/SamuelTulach/negativespoofer [EFI]
- https://github.com/gmh5225/wmi-static-spoofer
- https://github.com/gmh5225/hwid-spoofer
- https://github.com/gmh5225/hdd_serial_spoofer
- https://github.com/gmh5225/EASY-HWID-SPOOFER
- https://github.com/gmh5225/Spoofer-AMIDEWIN
- https://github.com/gmh5225/HWID-Pasted-Hwid-Spoofer
- https://github.com/gmh5225/hwid_spoofer
- https://github.com/gmh5225/tpm-spoofer [TPM]
- https://github.com/gmh5225/TPM-SPOOFER [TPM]
- https://github.com/gmh5225/AndroidFaker [Android]
- https://github.com/gmh5225/Windows-Spoofer
- https://github.com/gmh5225/Nvidia-GPU-Spoof [Spoofing the NVIDIA GPU UUID by modifying "nvlddmkm.sys"]
- https://github.com/gmh5225/TrickyStore [trick of keystore. Android 12 or above is required]
- https://github.com/gmh5225/TrickyStore [A trick of keystore. Android 10 or above is required]

> Bypass Page Protection
- https://github.com/illegal-instruction-co/CountHook [WorkingSet]

> SDK CodeGen
- https://github.com/gmh5225/sdkgenny
- https://github.com/gmh5225/luagenny
- https://github.com/gmh5225/obfCoder

> Game Engine Explorer:Unreal
- https://github.com/UE4SS-RE [UE RE]
- https://github.com/gmh5225/UEVR [Universal Unreal Engine VR Mod (4.8 - 5.4)]
- https://github.com/gmh5225/shootergame-Hack [ShooterGame Demo]
- https://github.com/gmh5225/shootergame [ShooterGame Demo]
- https://github.com/gmh5225/CleanCheat [Game cheat base]
- https://github.com/gmh5225/patternsleuth [Unreal Engine address scanner and test suite]
- https://github.com/gmh5225/jmap [Unreal Engine reflection data format and extractor]
- https://github.com/gmh5225/Dumper-7 [SDK Dump for all of UE4 and UE5]
- https://github.com/gmh5225/UEDumper [SDK Dump for UE 4.19 - 5.2]
- https://github.com/gmh5225/UEDumper-MemProcFS [UEDumper+MemProcFS 4.19 - 5.2]
- https://github.com/Chuan212/UnrealSDKDumper [SDK Dump for UE 4.23 - 4.27]
- https://github.com/BobHUnrealTech/UnrealSDKDumper-4.25 [SDK Dump for UE 4.23 - 4.27]
- https://github.com/gmh5225/Shh0yaUEDumper [SDK Dump]
- https://github.com/gmh5225/UnrealDumper-4.25 [SDK Dump]
- https://github.com/gmh5225/UEDumper [SDK Dump]
- https://github.com/gmh5225/frida-ue4dump [SDK Dump For Android/IOS]
- https://github.com/gmh5225/AndUE4Dumper [SDK Dump For Android]
- https://github.com/gmh5225/UE4Dumper [SDK Dump For Android]
- https://github.com/gmh5225/UE4-Apk-Dumper [SDK Dump For Android]
- https://github.com/gmh5225/UE4Dumper_Emulator [SDK Dump For Android]
- https://github.com/gmh5225/BigWhiteTool [SDK Dump For Android]
- https://github.com/gmh5225/iOS_UE4Dumper [SDK Dump For IOS]
- https://github.com/yring-me/ts-ue4dumper [TypeScript and Frida UE4dumper]
- https://github.com/gmh5225/Unreal-Finder-Tool [SDK View]
- https://github.com/gmh5225/UnrealEngine4-SwissKnife [SDK View]
- https://github.com/gmh5225/UnrealSharp [SDK View]
- https://fearlessrevolution.com/viewtopic.php?f=23&t=14414 [UE4 CE Table]
- https://github.com/cursey/ue4genny [SDK Generator]
- https://github.com/gmh5225/UE4Injector [Inject]
- https://github.com/gmh5225/UE4-Silent-Aim [Aimbot]
- https://github.com/YMY1666527646/ue4_base [SDK Template]
- https://github.com/percpopper/UE4-Freecam [FOV Changer]
- https://github.com/gmh5225/UnrealModLoader [Mod Loader]
- [Intercept ProcessEvent calls on any game object (Unreal Engine 4)](https://github.com/gmh5225/ue4-processevent-intercept)
- [UE4 Cheat Source Code](https://github.com/gmh5225/UE4-Cheat-Source-Code)
- https://github.com/gmh5225/ue4_cheat_engine [UE4 Cheat For Android]
- [unpack, pack, list, check and mount Unreal Engine 4 .pak archives](https://github.com/gmh5225/rust-u4pak)
- https://github.com/Qemu-Gang/QemuUnrealDumper-4.25 [SDK Dump By QEMU]
- https://github.com/gmh5225/UE-UnrealEngineSDK [Universal Cheat development kit]
- https://github.com/atenfyr/UAssetGUI [Viewing and modifying UE4 game assets]
- https://github.com/gmh5225/UE-Explorer [Browser and decompiler for UE packages]
- https://github.com/gmh5225/RE-UE4SS [Re-Host of Unreal Engine 4/5 Scripting System]
- https://github.com/gmh5225/Unreal-Engine-5-PDB [UE5 PDB]

> Game Engine Explorer:Unity
- https://github.com/gmh5225/mono [mono]
- https://github.com/gmh5225/dnSpy-Unity-mono [mono]
- https://github.com/gmh5225/MonoHook [mono hook]
- https://github.com/gmh5225/Mono.Debugger.Soft [Mono Debugger]
- https://github.com/gmh5225/unispectDMAPlugin [Mono Dump + DMA]
- https://github.com/gmh5225/Il2CppDumper [Il2Cpp Dump]
- https://github.com/gmh5225/Il2CppDumper-YuanShen [Il2Cpp Dump for Genshin Impact]
- https://github.com/gmh5225/Il2CppDumper [Il2Cpp Dump GUI]
- https://github.com/gmh5225/Il2cppDumpDroidGUI [Il2Cpp Dump GUI]
- https://github.com/gmh5225/Il2CppRuntimeDumper [Il2Cpp Dump Runtime]
- https://github.com/gmh5225/Zygisk-Il2CppDumper [Il2Cpp Dump for Android Platform]
- https://github.com/gmh5225/IL2CPPDumper [Il2Cpp Dump for Android Platform]
- https://github.com/gmh5225/Il2cppSpy [Unity IL2CPP Disassembler (for apk)]
- https://github.com/gmh5225/Il2CppInspector [Il2Cpp Dump]
- https://github.com/gmh5225/android-il2cpp-modspeed [Il2Cpp hack speed]
- https://github.com/gmh5225/qiling-il2cpp-dump  [Il2Cpp Dump using qiling]
- https://github.com/gmh5225/UnityExplorer
- https://github.com/gmh5225/il2cpp [Il2Cpp Version]
- https://github.com/gmh5225/Il2CppVersions [Il2Cpp Version]
- https://github.com/gmh5225/IL2CPP_Resolver [IL2CPP resolver]
- https://github.com/gmh5225/IL2CPP_Resolver_External [IL2CPP resolver]
- https://github.com/gmh5225/Il2CppAssemblyUnhollower
- https://github.com/gmh5225/mono-external-lib [External Mono Example]
- https://github.com/gmh5225/external-il2cpp [Il2Cpp]
- https://github.com/gmh5225/Il2CppSDKGenerator [Il2Cpp SDK generator for Android]
- https://github.com/gmh5225/UnityDecompiled [An unofficial repo of decompiled Unity dll files]
- https://github.com/gmh5225/Il2CppAssemblyUnhollower [Managed->IL2CPP proxy assemblies]
- https://github.com/gmh5225/MegaDumper [Dump native and .NET assemblies]
- https://github.com/gmh5225/UABE [Extracting assets]
- https://devxdevelopment.com/Unpacker [Extracting assets]
- https://github.com/gmh5225/AssetRipper [Extracting assets]
- https://github.com/gmh5225/AssetStudio [Extracting assets]
- https://github.com/gmh5225/assetstudio [Extracting assets/2025 updated]
- https://github.com/gmh5225/Il2CppHookScripts [Il2Cpp Hook Scripts]
- https://github.com/gmh5225/Il2Cpp-HookScripts [Il2Cpp/Mono Hook Scripts]
- https://github.com/gmh5225/ACEPatcher [.NET Patcher]
- [A tool translate a apk file to common android project and support so hook include il2cpp c++ scaffolding](https://github.com/gmh5225/FakerAndroid)
- https://github.com/gmh5225/unitySpeedTools [IOS Speed Tools]
- https://github.com/gmh5225/il2cpp-finder [Il2Cpp Finder]
- https://github.com/gmh5225/frida-il2cpp-datacollector [Il2Cpp datacollector for Android/IOS]
- https://github.com/gmh5225/BepInEx [plugin/modding framework]
- https://github.com/gmh5225/IL22CPP [ReMake of Il2cpp internal reflection system in C++]
- https://github.com/gmh5225/UnityVulnerableEntryPoint [Looks for a vulnerable entry point]
- https://github.com/gmh5225/MatScan [A multi-threaded rust material scanner]
- https://github.com/gmh5225/frida-il2cpp-bridge [Frida dump Il2Cpp]
- https://github.com/gmh5225/UnityResolve.hpp [Unity cheat framwork]
- https://github.com/gmh5225/BNM-Android [Modding il2cpp games]
- https://github.com/SsageParuders/CheatUnityGames [Unity cheat framwork]
- https://github.com/gmh5225/AndroidCheatTemplate [Unity cheat framwork]

> Game Engine Explorer:Source
- https://github.com/gmh5225/Source2Dumps [Dump]
- https://github.com/gmh5225/ValveGen [SDK Generator]
- https://github.com/gmh5225/Source2Gen [SDK Generator]
- https://github.com/gmh5225/source2gen [SDK Generator]
- https://github.com/gmh5225/sourceengineexplorer [Explorer]
- https://github.com/gmh5225/source2sdk

> Explore UWP
- https://github.com/gmh5225/UWPDumper
- https://github.com/Francesco149/uwpinject [dll injector for uwp apps]
- https://github.com/gmh5225/uwpspy [dll that hooks uwp interfaces]

> Explore AntiCheat System:VAC
- https://github.com/gmh5225/VAC-Bypass-Loader
- https://github.com/gmh5225/vac-hooks
- https://github.com/gmh5225/Shtreeba [Injector]
- https://github.com/gmh5225/vac3_inhibitor
- https://github.com/gmh5225/Vook [VAC hook]
- https://github.com/gmh5225/vacation3-emu [VAC3 module emulator]
- https://github.com/gmh5225/Vac-Emulator [VAC Emulator]
- https://github.com/gmh5225/VACDumper [Dump]
- https://github.com/gmh5225/vac3-dumper [Dump]
- https://github.com/gmh5225/VAC-ModuleDumper [Dump]
- https://github.com/gmh5225/VAC-Bypass
- https://github.com/gmh5225/PreventVAC
- https://github.com/gmh5225/cozinha_loader [Injector]
- https://github.com/gmh5225/VACKeyRetrieval [Retrieves VAC module ice encryption key]
- https://github.com/gmh5225/DumpVAC [PoC to disable VAC and dump modules with automatic decryption]
- https://github.com/gmh5225/vac-bypass-kernel [Fully working kernel-mode VAC bypass]

> Explore AntiCheat System:EAC
- https://github.com/gmh5225/CVEAC-2020 [Integrity Checks]
- https://github.com/gmh5225/EAC_dbp [Debug]
- https://github.com/Compiled-Code/eac-mapper [Eac Mapper]
- https://github.com/EBalloon/MmCopyMemory [Bypass MmCopyMemory]
- https://github.com/gmh5225/EAC-Kernel-Packet-Fucker [Packet Fucker]
- https://github.com/gmh5225/EAC-HydraHook [Packet Fucker]
- https://github.com/gmh5225/EazyAntiCheatSRC [Reversed Source]
- https://github.com/gmh5225/eac-leak [EAC sdk's memory leak]
- https://github.com/gmh5225/EAC [SDK]
- https://github.com/gmh5225/Eac-Bypass
- https://github.com/gmh5225/EasyAntiCheat-SRC
- https://github.com/gmh5225/EAC-EasyAntiCheat-Src-1
- https://www.unknowncheats.me/forum/anti-cheat-bypass/458928-eacs-maskable-interrupt-callback.html [NMI]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/464943-eac-nmi-bypass-callbacks.html [NMI Bypass]
- https://github.com/gmh5225/EasyAntiCheat-Reversing
- https://github.com/gmh5225/hiearchy-eac [Integrity Checks]
- https://github.com/gmh5225/EAC_Emu [Simple EasyAntiCheat x64 emulator]
- https://github.com/xBrunoMedeiros/eac-overlay [EAC Overlay]
- https://github.com/gmh5225/ce-EasyAntiCheat-Bypass [UD CE]
- https://github.com/gmh5225/pooldump [Extract the DLL that EACs manualmaps into the game process]
- https://github.com/gmh5225/EAC-VmCheck.asm [Virtual machine checking]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/561479-eacs-instrumentation-callback-bypass.html
- https://github.com/gmh5225/Eac-Injector-Driver [Injector]
- https://github.com/gmh5225/EAC-EasyAntiCheatMemorySig [Memory sig maker]
- https://github.com/gmh5225/EAC-shellcode-1 [Shellcode]
- https://github.com/gmh5225/EAC-Driver-UD-for-now [Sample]
- https://github.com/gmh5225/EAC-Extractor-Utility [Decrypt and Extract the files from the EAC]
- https://advancedvectorextensions.github.io/posts/easyanticheat-eprocess-emulation [EProcess Emulation]
- https://advancedvectorextensions.github.io/posts/easyanticheat-cr3-protection [CR3 Protection]
- https://github.com/Sinclairq/hierarchy-eac [Bypassing self-integrity]
- https://github.com/gmh5225/eac_cr3_shuffle [Bypassing CR3 protection]
- https://github.com/gmh5225/Bypassing-EasyAntiCheat-Integrity-check [Bypassing integrity check]
- https://github.com/gmh5225/EasyAntiCheat-Emulator [EAC Emulator]
- https://github.com/gmh5225/EAC-Runtime-Extractor [Extracts eac's driver at runtime without it touching the disk]
- https://gist.github.com/gmh5225/b89938f55bcb65637168f88a433c3d4d [Skip EAC thread detection]
- https://github.com/gmh5225/EAC-CR3-BYPASS [A simple UM + KM example of how to bypass EAC CR3]


> Explore AntiCheat System:BE
- https://github.com/gmh5225/NoEye
- https://github.com/gmh5225/NoBastian_v2 [Elevating Handle By LSASS]
- https://github.com/gmh5225/splendid_implanter
- https://github.com/gmh5225/battleye-user-mode-bypass [SetWindowsHookExW]
- https://github.com/gmh5225/BE-Emulator
- https://github.com/gmh5225/BattlEye-Handler-BYPASS
- https://github.com/gmh5225/battleye-decryption
- https://github.com/dllcrt0/bedaisy-reversal
- https://github.com/gmh5225/battleye-shellcode [shellcode]
- https://github.com/gmh5225/BE-BattlEye_shellcode [shellcode]
- https://github.com/gmh5225/be-injector [Attack COW]
- https://github.com/gmh5225/BEDaisy
- https://github.com/gmh5225/BadEye
- https://github.com/gmh5225/BlindEye [Packet Fucker]
- https://github.com/gmh5225/goodeye
- https://github.com/gmh5225/BEClient
- https://github.com/gmh5225/Battleye-Shellcode-Dumper [BEClient2.dll Dumper]
- https://github.com/gmh5225/be-shellcode-tester [BattlEye shellcodes tester]
- https://github.com/gmh5225/battleye-rust [BattlEye RCON UDP connection]
- https://github.com/gmh5225/FakeEye [Emulator]
- https://github.com/gmh5225/FakeEye [Emulator]
- https://github.com/gmh5225/battleye-region-walking
- https://github.com/gmh5225/Pink-Eye
- https://github.com/gmh5225/beservice_intcallbacks [Instrumentation Callback]
- https://github.com/gmh5225/bedaisy-bypass [BEDaisy.sys report bypass]

> Explore AntiCheat System:EQU8
- https://blog.back.engineering/12/08/2021
- https://github.com/gmh5225/EQU8-PoC
- https://github.com/gmh5225/equ8_bypass

> Explore AntiCheat System:Ricochet
- https://github.com/gmh5225/ricochet_deobfuscator
- https://github.com/gmh5225/AurumRE
- https://github.com/gmh5225/ricochet-disabler

> Explore AntiCheat System:RIOT
- https://github.com/gmh5225/DecryptionDumper [Dump]
- https://github.com/gmh5225/val-exception-handler [ZwRaiseException Dump]
- https://github.com/gmh5225/Dump-val-exception-handler [RtlpCallVectoredHandlers Dump]
- https://github.com/gmh5225/VanguardImportResolver [Resolve vgk's protected imports]
- https://github.com/gmh5225/VanguardTrace [Decrypting and intercepting encrypted imports of Vanguards Kernel Driver]
- https://www.unknowncheats.me/forum/anti-cheat-bypass/578829-unveiling-unseen-vanguards-guarded-regions.html [CR3 Protection]
- https://github.com/gmh5225/vgk-illegal-pf-logger [VGK's illegal PF]
- https://github.com/gmh5225/KernelSnippets/blob/main/VGK_SwapContextHk.h [VGK's SwapContextHk]

> Explore AntiCheat System:XignCode
- https://github.com/gmh5225/XignCode-Dump
- https://github.com/gmh5225/XignCode3-bypass-alternative
- https://github.com/gmh5225/XignCode3-bypass

> Explore AntiCheat System:ACE
- https://github.com/gmh5225/sguard_limit
- https://github.com/gmh5225/ReadPhys

> Explore AntiCheat System:G-Presto
- https://github.com/gmh5225/G-Presto-Anti-Cheat-Reverse-Engineered/blob/main/Main.cpp

> Explore AntiCheat System:NeacSafe
- https://github.com/gmh5225/NeacSafe-Analysis

> Explore AntiCheat System:BadlionAnticheat
- https://github.com/gmh5225/BadlionLogger

> Explore AntiCheat System:Byfron
- https://byfron.com/
- https://www.unknowncheats.me/forum/anti-cheat-bypass/505486-byfron-tech-anti-cheat-released.html
- https://gist.github.com/gmh5225/cbe40345a9400b01329e025478ffb826 [hash]
- https://github.com/gmh5225/byfron-bypass
- https://github.com/gmh5225/vulkan [A PE dumper for processes protected by user mode anti-tamper solutions (hyperion, theia, etc.)]

> Explore AntiCheat System:NGS
- https://github.com/gmh5225/NexonGameSecurity-bypass
- https://github.com/gmh5225/NexonGameSecurity-bypass-alternative
- https://github.com/gmh5225/NexonGameSecurity-bypass-wow64

> Explore AntiCheat System:FACEIT
- https://github.com/gmh5225/EC_PRO-LAN

> Explore AntiCheat System:CS2
- https://github.com/gmh5225/cs2-anticheat

> Game:MapleStory
- https://forum.ragezone.com/threads/getting-packet-structures-opcodes-using-ida.792436/ [Packet]
- https://github.com/Bratah123/SpiritIDAPlugin [IDA-Plugin]
- https://github.com/gmh5225/mapleLemon [Private Server-CMS-027]
- https://github.com/gmh5225/MapleStory [Private Server-CMS-079]
- https://github.com/gmh5225/ms079 [Private Server-CMS-079]
- https://github.com/gmh5225/MapleStory143 [Private Server-CMS-143]
- https://github.com/gmh5225/MapleStoryEx [Private Server-CMS-079]
- https://github.com/gmh5225/maplestory-v83MaplestoryCPP [Private Server-GMS-083 C++]
- https://github.com/Fraysa/Destiny [Private Server-GMS-083 C#]
- https://github.com/Bratah123/ElectronMS [Private Server-KMS-316]
- https://github.com/gmh5225/MapleStory-v113-Server-Eimulator [Private Server-TMS-113]
- https://github.com/gmh5225/MapleEzorsia [v83 edits for creating a custom resolution client]
- https://github.com/Bratah123/BattleAnalysis176 [Battle Analysis]
- https://github.com/gmh5225/MapleStoryBuildFramework [AntiCheat]
- https://github.com/gmh5225/Maplestory-V179-Cheat-Engine [V179 CT]
- https://github.com/gmh5225/MapleStory-HeavenClient [Heaven Client]
- https://github.com/gmh5225/TWMS-Hacking-Data [TMS CT]
- https://github.com/Inndy/MSDoggy [TMS Old Hack]
- https://github.com/PrinceFroggy/MSB [GMS Old Hack 128-140]
- https://github.com/PrinceFroggy/MSC [GMS Bot]
- https://github.com/gmh5225/Rebirth [Private Server-GMS-095 C#]
- https://github.com/gmh5225/mnwvs196 [Private Server-TMS-196]
- https://github.com/Maxcloud/MapleResearch [GMS-095 Client Analysis]
- https://github.com/gmh5225/MapleStory-CMS95-Client-Address [CMS-095 Client Analysis]
- https://github.com/gmh5225/RustMS [Private Server-Rust]
- https://github.com/gmh5225/WzComparerR2 [Maplestory online Extractor]
- [Generate machine learning object detection samples from Maplestory in different formats](https://github.com/gmh5225/MapleStoryDetectionSampleGenerator)
- https://github.com/gmh5225/MapleStory-GM-Client [Offline MapleStory Client Emulator]
- https://github.com/gmh5225/maplestory-packer-ModPacker [MapleStory Wolrds .mod file packing/unpacking tools]
- https://github.com/gmh5225/JMSv186 [JMS v186]
- https://github.com/gmh5225/MapleStory-Client [HeavenMS Client]
- https://github.com/gmh5225/MapleStory-Server [HeavenMS Server]
- https://github.com/gmh5225/LibreMaple-Client [LibreMaple Client]
- https://github.com/gmh5225/MapleServerAndroid [GMS 083 server on Android]
- https://github.com/Bratah123/ElectronMS [Private Server-KMS-316]
- https://github.com/gmh5225/AzureV316 [Private Server-KMS-316]
- https://github.com/gmh5225/MapleNecrocer [MapleStory Client Emulator]
- https://github.com/gmh5225/maplestory-artale-explab [Experience gain & HP/MP cost lab for MapleStory Worlds Artale]
- https://github.com/gmh5225/MapleStoryAutoLevelUp [An auto level up script for Maple Story Artale]

> Game:Minecraft
- [A minecraft server backend written in c++](https://github.com/gmh5225/minecpp)

> Game:Sword With Sauce
- https://github.com/gmh5225/UE4-Cheat-Source-Code

> Game:Gunfire Reborn
- https://github.com/gmh5225/AutoGunfireReborn

> Game:Fall Guys
- https://github.com/gmh5225/FallGuysSharp
- https://github.com/gmh5225/FallGuys
- https://github.com/gmh5225/Flying-Guys-fully-modified
- https://github.com/gmh5225/FlyingGuys

> Game:Remnant
- https://github.com/gmh5225/RemnantESP

> Game:LostArk
- https://github.com/gmh5225/LostArkDumper
- https://github.com/gmh5225/LostArkLogger
- https://github.com/gmh5225/LOST-ARK-SDK
- https://github.com/gmh5225/Lost-Ark-SDK
- https://github.com/gmh5225/LostArk

> Game:Battlerite
- https://github.com/gmh5225/BattleriteBot

> Game:CrossFire
- https://github.com/gmh5225/titancf
- https://github.com/gmh5225/cfclap

> Game:TGame
- https://github.com/gmh5225/nzPerspective [D3D9]

> Game:LOL
- https://github.com/LeagueSharp
- https://github.com/gmh5225/LeagueSharp
- https://github.com/ensoulsharp-io
- https://ferrisbot.com/ferrisaio
- https://github.com/gmh5225/EloBuddy-Addons
- https://github.com/gmh5225/LeagueSharp
- https://github.com/gmh5225/LoLClient
- https://github.com/gmh5225/L-Assemblies
- https://github.com/gmh5225/LeagueSharp.Loader
- https://github.com/gmh5225/R3nzSkin [Skin]
- https://github.com/gmh5225/R3nzSkinTFT [Skin]
- https://github.com/gmh5225/LeagueSkinChanger [Skin]
- https://github.com/gmh5225/hh-lol-prophet
- https://github.com/gmh5225/DecryptionDumper [Dump]
- https://github.com/gmh5225/LeagueDumper [Dump]
- https://github.com/gmh5225/League-Unpacker [Dump]
- https://github.com/gmh5225/lol-offset-dumper [Dump]
- https://github.com/gmh5225/LeagueTeamBoost
- https://github.com/LeagueSandbox
- https://github.com/gmh5225/lol-unpackman
- [A bran-new League of Legends assistant software, a replacement for WeGame](https://github.com/gmh5225/frank)
- https://github.com/gmh5225/LViewLoL [Python based scripting platform]
- https://github.com/gmh5225/KBotExt [LCU]
- https://github.com/gmh5225/ayaya-league-external [Nodejs based scripting platform]
- https://github.com/gmh5225/TFT-OCR-BOT [TFT]
- https://github.com/gmh5225/VanderLeague [Hypervisor-assisted]
- https://github.com/gmh5225/League-DirectX11-Internal [Internal]
- https://github.com/gmh5225/league-base [External]
- https://github.com/gmh5225/lol_patcher

> Game:NARAKA
- https://www.unknowncheats.me/forum/other-fps-games/490052-naraka-bladepoint-reversal-structs-offsets.html
- https://github.com/gmh5225/DummyDlls_NARAKA_1_9_21 [Dump]
- https://github.com/gmh5225/Naraka-Hack

> Game:Thetan
- https://github.com/gmh5225/Thetan_ArenaSDK

> Game:Dota2
- https://github.com/gmh5225/dota2dumped [Offset dumper]
- https://github.com/gmh5225/Dota2-Overlay-2.0
- https://github.com/gmh5225/Dota2-Overlay-OffsetUpdater
- https://github.com/gmh5225/dota-cheat
- https://github.com/gmh5225/McDota [linux]
- https://github.com/gmh5225/Dota2Cheat

> Game:WOW
- https://github.com/gmh5225/wow-IAT-fix
- https://github.com/gmh5225/dumpwow
- https://github.com/gmh5225/WoWDumpFix
- https://github.com/gmh5225/x14.08-coverstory-blizzard
- https://github.com/gmh5225/OHack [An open-source hack for World of Warcraft]
- https://github.com/gmh5225/SkyEngine [Wow Lua Unlocker]
- https://github.com/gmh5225/WOW-WowAutoFishing [Auto Fishing]

> Game:Warcraft III
- https://github.com/gmh5225/HiveWE [editor]

> Game:Half-Life 2
- https://github.com/gmh5225/hl2aimbot
- https://github.com/gmh5225/hl2esp

> Game:CS1.6
- https://github.com/gmh5225/hpp-hack
- https://github.com/gmh5225/CSHackCreator-2-Demo
- https://github.com/gmh5225/oxware
- https://github.com/gmh5225/simple-cs-16-multihack
- https://github.com/gmh5225/sakura
- https://github.com/gmh5225/1.6_C2 [C2]
- https://github.com/gmh5225/Zodiak [CS 1.6 Fastcup Full Kernel Driver Cheat]
- https://github.com/gmh5225/Evelion [External]

> Game:CSS
- https://github.com/gmh5225/CounterStrikeSource-Linux-Trainer [Linux External]
- https://github.com/M3351AN/UkiaRPM [External]

> Game:CSGO
- https://github.com/csgohacks/master-guide [Guide]
- https://github.com/gmh5225/blazedumper [Offset]
- https://github.com/gmh5225/hazedumper [Offset]
- https://github.com/gmh5225/csgo-offsets [Offset]
- https://github.com/gmh5225/offsets [Offset]
- https://github.com/gmh5225/csgo_auto_dumper [Auto Dump]
- https://github.com/gmh5225/GarHal_CSGO
- https://github.com/gmh5225/Osiris
- https://github.com/gmh5225/GOESP [Cross-platform]
- https://github.com/gmh5225/Anubis
- https://github.com/gmh5225/Dainsleif
- https://github.com/gmh5225/csgo_sdk
- https://github.com/gmh5225/csgo-sdk [SDK for Rust]
- https://github.com/gmh5225/csf_w [Win SDK]
- https://github.com/gmh5225/csf [Linux SDK]
- https://github.com/gmh5225/ROP-COMPILER
- https://github.com/gmh5225/AimTux [Linux]
- https://github.com/gmh5225/gamesneeze [Linux]
- https://github.com/gmh5225/csgo-linux-cheat-sdk [Linux]
- https://github.com/gmh5225/DEADCELL-CSGO
- https://github.com/gmh5225/kernel-csgo
- https://github.com/gmh5225/CSGO-Cheats
- https://github.com/gmh5225/CSGO-FindMDL [Model Changer]
- https://github.com/gmh5225/nv_v2 [Sound ESP]
- https://github.com/gmh5225/Improved-CSGO_Simple
- https://github.com/0TheSpy/SpyExternal1337hax [External]
- https://github.com/0TheSpy/Seaside [Internal]
- https://github.com/whereisr0da/Lumina-Cheat [Internal]
- https://github.com/nbqofficial/norsefire [Driver + Mouse Emulation]
- https://github.com/boltgolt/boltobserv [Radar]
- https://github.com/gmh5225/csgo_external_ahk_hack [External]
- https://github.com/gmh5225/CSGO-P2C-Dumper [Dump]
- https://github.com/gmh5225/2k17-club
- https://github.com/gmh5225/csgo-xenforo-loader
- https://github.com/gmh5225/ezfrags
- https://github.com/gmh5225/CSGO-MAIN-INTERNAL
- https://github.com/gmh5225/digital-sdk
- https://github.com/gmh5225/CSGO_BacktrackPatch [Backtrack Patch]
- https://github.com/gmh5225/NullBase [External]
- https://github.com/krxdev-kaan/AqHax-CSGO
- https://github.com/gmh5225/csgo-dma-overlay [DMA]
- https://github.com/gmh5225/csgo-external-cheat
- https://github.com/gmh5225/Pine [Neural Network]
- https://github.com/gmh5225/csgo 
- https://github.com/gmh5225/NullHooks [Internal]
- https://github.com/gmh5225/CSGOCrosshair [Crosshair Generator]
- https://github.com/gmh5225/G37OBS [obs-studio plugin for csgo]
- https://github.com/gmh5225/Csgo-Full-kernel [Running from kernelmode]
- https://github.com/gmh5225/CompiledProtection [Cheat Compiler]
- https://github.com/gmh5225/EC
- https://github.com/gmh5225/heck_csgo_external [External]
- https://github.com/gmh5225/Sensum [Internal]
- https://github.com/gmh5225/kakhack [Internal]
- https://github.com/gmh5225/CSGO-Internal [Internal]
- https://github.com/gmh5225/cstrike-hack
- https://github.com/gmh5225/raybot-zero [Kernel-mode]
- https://github.com/gmh5225/CSGO-Loader [Loader]
- https://github.com/gmh5225/CSGO-NIXWARE-CSGO [Nixware]
- https://github.com/gmh5225/csgo-cheat-base [Internal]
- https://github.com/gmh5225/tiny-csgo-client [Tiny csgo client for connecting dedicated server]
- https://github.com/gmh5225/CSGO_AnimationCode_Reversed [CSGO animation code]
- https://github.com/gmh5225/CSGOSimple [Internal]
- https://github.com/gmh5225/CSGO-Ormbunke-x86 [Imgui Menu]
- https://github.com/gmh5225/legit-csgo-cheat-menu [Menu]
- https://github.com/gmh5225/autismware [HvH]
- https://github.com/gmh5225/solace-csgo [Internal]
- https://github.com/gmh5225/csgo-sdk-improved [Internal]
- https://github.com/gmh5225/cartmanv2 [Internal]
- https://github.com/gmh5225/CSGO-aw-v5.1.13 [aw-v5.1.13]
- https://github.com/gmh5225/csgo-bot
- https://github.com/gmh5225/csgo-external-esp [External]
- https://github.com/gmh5225/avhook
- https://github.com/gmh5225/csgo_cheat_external [External]
- https://github.com/gmh5225/nebulite-external [External]
- https://github.com/gmh5225/csgo_internal_base [Internal]
- https://github.com/gmh5225/Astra [External]
- https://github.com/gmh5225/CSGO-Alphen
- https://github.com/gmh5225/ExternalCheatV3 [External]
- https://github.com/gmh5225/Protobufs/tree/master/csgo [Protobuf]
- https://github.com/gmh5225/csgo_kns [Internal]
- https://github.com/gmh5225/saphire [Internal]
- https://github.com/gmh5225/GHInterfacesCSGO [Internal]
- https://github.com/gmh5225/memcs [External]
- https://github.com/gmh5225/sdk [SDK]
- https://github.com/gmh5225/csgo_sdk [SDK]
- https://github.com/gmh5225/SmKernel-CSGO [Driver]
- https://github.com/gmh5225/OsirisAndExtra [Internal]
- https://github.com/M3351AN/Echinoidea [External C#]
- https://github.com/gmh5225/le_chiffre [External]

> Game:CS2
- https://github.com/gmh5225/Osiris
- https://github.com/gmh5225/CS2-Offsets [Offset]
- https://github.com/gmh5225/CS2-OFFSETS [Offset]
- https://github.com/gmh5225/cs2-signature-list [Signature]
- https://github.com/gmh5225/cs2-sdk [SDK]
- https://github.com/gmh5225/Counter-Strike2-SDK [SDK]
- https://github.com/gmh5225/cs2-sdk [SDK]
- https://github.com/gmh5225/CS2-SDK-Source2Gen [SDK]
- https://github.com/gmh5225/SDK_CS2 [SDK]
- https://github.com/gmh5225/cs2_sdk [SDK]
- https://github.com/gmh5225/cs2-sdk [SDK]
- https://github.com/gmh5225/cs2-dumper [Dump]
- https://github.com/gmh5225/csgo2-cheat
- https://github.com/gmh5225/counterstrike2
- https://github.com/gmh5225/BakaWare4
- https://github.com/gmh5225/cs2-fov-changer [FOV changer]
- https://github.com/gmh5225/cs2_webradar [undetected counter strike 2 browser based radar cheat]
- https://github.com/gmh5225/CS2_DMA_Radar [DMA Radar]
- https://github.com/gmh5225/cs2_webradar [Browser based radar cheat]
- https://github.com/gmh5225/CS2_DMA_Extrnal [DMA External]
- https://github.com/gmh5225/vscript_lua51 [VScript]
- https://github.com/gmh5225/cs2_things [VScript]
- https://github.com/gmh5225/cs2-external-esp [External]
- https://github.com/gmh5225/CS2-external-base [External]
- https://github.com/gmh5225/cs2External [External]
- https://github.com/gmh5225/CS2_External [External]
- https://github.com/gmh5225/Valthrun [External]
- https://github.com/gmh5225/CS2-External [External]
- https://github.com/gmh5225/CS2-External-Cheat [External]
- https://github.com/gmh5225/tim_apple [External]
- https://github.com/gmh5225/tim_apple [External]
- https://github.com/gmh5225/CS2-Cheat [External]
- https://github.com/gmh5225/HPCS2 [External]
- https://github.com/gmh5225/CS2-External-1 [External]
- https://github.com/gmh5225/AimStar [External]
- https://github.com/gmh5225/Aeonix-Cs2 [External]
- https://github.com/gmh5225/CS-2-Glow [External]
- https://github.com/gmh5225/cs2-cheat-cpp [External]
- https://github.com/gmh5225/DragonBurn [External]
- https://github.com/yoshisaac/CounterStrike2-Linux-Cheat [Linux External]
- https://github.com/gmh5225/CS2-Cheat-Base [Internal]
- https://github.com/gmh5225/CS2-Internal [Internal]
- https://github.com/gmh5225/CS2-Cheat-Base [Internal]
- https://github.com/gmh5225/CS2Internal [Internal]
- https://github.com/gmh5225/csgo2-cheat [Internal]
- https://github.com/gmh5225/Aurora [Internal]
- https://github.com/gmh5225/cs2-internal-sdk [Internal]
- https://github.com/gmh5225/cstrike2-hack [Rust-based internal]
- https://github.com/gmh5225/CS2-DMA-Cheat [DMA]
- https://github.com/gmh5225/CS2-Dma-Radar [DMA]
- https://github.com/atombottle/cs2_kvm_dma [KVM] 
- https://github.com/gmh5225/Samidare [External Ring3/Ring0]
- https://github.com/gmh5225/PythonCS2 [Python External]
- https://github.com/gmh5225/asphyxia-cs2 [Internal]
- https://github.com/gmh5225/YOLOv8-Overlay-CS2 [YOLOv8 in CS2]
  
> Game:Assault Cube
- https://github.com/gmh5225/external-esp-hack-assaultcube [GDI overlay]
- https://github.com/gmh5225/AssaultCubeCheat
- https://github.com/gmh5225/AssaultCube_Cheat
- https://github.com/kotae4/lab-esp-and-aimbot [Walkthrough of an ESP and aimbot cheat from scratch]

> Game:Valorant
- https://github.com/gmh5225/valorant_offsets [Offset]
- https://github.com/gmh5225/ValorantOffsets [Offset]
- https://github.com/gmh5225/offsets [Offset]
- https://github.com/gmh5225/valorant-externals [Offset]
- https://github.com/gmh5225/valorant-offsets-autoupdater [Offset]
- https://github.com/gmh5225/ValorantOffsets-China-version [Offset]
- https://github.com/gmh5225/Valorant-SDK-2024 [SDK]
- https://github.com/gmh5225/valorant-gui-imgui-remake [GUI]
- https://github.com/gmh5225/valorant-internal
- https://github.com/gmh5225/Zenti-Valorant-Cheat-Hack-Internal-Spoofer-Driver-Injector-Protector-Auth
- https://github.com/gmh5225/Valorant-Hack-Esp-Aimbot-Driver-Injector-With-Spoofer-Temporary
- https://github.com/gmh5225/valorant-dumper [Dump]
- https://github.com/gmh5225/Valorant-Dumper-Tool [Dump]
- https://github.com/gmh5225/val-exception-handler [ZwRaiseException Dump]
- https://github.com/gmh5225/Valorant-Esp-Aimbot-Hack
- https://github.com/gmh5225/UE4-c- [External]
- https://github.com/gmh5225/Valorant-Cheat-External [External]
- https://github.com/gmh5225/Valorant-Cheat
- [Iterate And Decrypt FNamePool->Entries On Valorant](https://github.com/gmh5225/VALORANT-FNamePool)
- https://github.com/gmh5225/Valorant-External-1
- https://github.com/Chase1803/UCMiraka-ValorantExternal [NtUserGetPointerProprietaryId]
- https://github.com/gmh5225/Valorant-CheatExternal
- https://github.com/gmh5225/ValorantCC [Crosshair Setting]
- https://github.com/gmh5225/Internal-Valorant-Cheat
- https://github.com/gmh5225/VALORANT-HACK-ESP-AIMBOT-SKINCHANGER
- https://github.com/gmh5225/valorant-esp-hack-with-driver
- https://github.com/gmh5225/Valorant-Aimbot-Bypass
- https://github.com/gmh5225/CyberAntLoader
- https://github.com/gmh5225/Valorant.External
- https://github.com/gmh5225/valorant-internal-base [Internal]
- https://github.com/gmh5225/VALORANT-HACK-ESP-AIMBOT-SKINCHANGER-SOURCE [Internal]
- https://github.com/gmh5225/Valorant-External-Source [External]
- https://github.com/gmh5225/Valorant-cheat-internal [Internal]
- https://github.com/gmh5225/Valorant-Esp-Aimbot-Cheat-Hack [External]
- https://github.com/gmh5225/Valorant-Internal [Internal]
- https://github.com/gmh5225/Valorant-External-P2C-Leaked [External]
- https://github.com/gmh5225/valorant-internal-cheat [Internal]
- https://github.com/gmh5225/valo-driver [External]
- https://github.com/gmh5225/valorant-internal-cheat [Internal]
- https://github.com/gmh5225/ValorantCheatExternal [External]

> Game:VEILED EXPERTS
- https://github.com/gmh5225/VEILED-EXPERTS-SDK
- https://github.com/gmh5225/ProjectD-Win64-Shipping
- https://github.com/gmh5225/VeiledExpertsSDK
- https://github.com/gmh5225/VX-It [Decrypt]

> Game:COD1
- https://github.com/gmh5225/CoD_Hacks

> Game:COD7
- https://github.com/gmh5225/COD7-Tools

> Game:COD Black Ops 2
- https://github.com/gmh5225/t7-linker [100% accurate Black Ops 2 FastFile linker]

> Game:COD Black Ops 3
- https://github.com/gmh5225/COD-boiii [Reverse engineering and analysis]

> Game:COD Warzone
- https://github.com/YMY1666527646/Call-of-Duty-Warzone-MW-HACK-ESP-AIMBOT
- https://github.com/serjam/mwclap
- https://github.com/gmh5225/external-warzone-cheat
- https://github.com/gmh5225/warzone-internal
- https://github.com/gmh5225/Call-Of-Duty-Warzone-Hack-Esp-Slient-Aimbot-Internal-Unlock-ALL
- https://github.com/gmh5225/Call-Of-Duty-Vanguard-Hack-Esp-AImbot-Unlock-All
- https://github.com/gmh5225/Warzone-internal-Cheat
- https://github.com/gmh5225/Warzone-MW-Internal
- https://github.com/gmh5225/-Modern-Warfare-Warzone-Cheat

> Game:CODM
- https://github.com/gmh5225/CodMDumper [il2cpp dump]
- https://github.com/gmh5225/CODM-ESP-Aimbot-Mod-Menu [ESP]

> Game:Battlefield 1
- https://github.com/gmh5225/BF1-ESP-AND-AIMBOT
- https://github.com/gmh5225/BattleField-1-Internal

> Game:Battlefield 4
- https://github.com/gmh5225/BF4-Internal-overlay

> Game:Battlefield 2042
- https://github.com/gmh5225/battlefield-2042-internal-sdk

> Game:Apex Legends
- https://github.com/gmh5225/Apex-Legends-Offset-Dumper [Offset]
- https://github.com/gmh5225/offsets [Offset]
- https://github.com/gmh5225/Apex-Legends-SDK-Remaster
- https://github.com/gmh5225/ApexD3D_External
- https://github.com/gmh5225/apex-legends-cheat
- https://github.com/gmh5225/Apex-SIMPLE-AIMBOT-GLOW-APEX
- https://github.com/gmh5225/Direct-EFI-Apex-Cheat
- https://github.com/gmh5225/apex-external
- https://github.com/YMY1666527646/Phoenix-Valorant-Cheat
- https://github.com/CasualX/apexbot
- https://github.com/TheCruZ/Apex_Legends_Driver_Cheat
- https://github.com/gmh5225/Fortnite
- https://github.com/gmh5225/NuremX [AI]
- https://github.com/gmh5225/apex_full_cheat
- https://github.com/gmh5225/Apex-ApexCheeseTest
- https://github.com/gmh5225/Apex-Legends-Esp
- https://github.com/gmh5225/Apex-ApexCheat
- https://github.com/gmh5225/Apex_ESP_Old_Project
- https://github.com/gmh5225/apex-cheating
- https://github.com/LWSS/Ape-ex-Abominations [QEMU]
- https://github.com/gmh5225/EzApexDMAAimbot [KVM]
- https://github.com/gmh5225/Apex-CHEAT-FIXED
- https://github.com/gmh5225/apex_legends_sdk
- https://github.com/gmh5225/apex_linux [linux]
- https://github.com/gmh5225/project-tanya [linux]
- https://github.com/gmh5225/ayypex [linux]
- https://github.com/gmh5225/Project-Branthium
- https://github.com/gmh5225/Apex-Legends-External-Esp-Aimbot-Skinchanger
- https://github.com/gmh5225/Apex-ItemGlow [Item glow]
- https://github.com/gmh5225/UC-Apex-Remastered
- https://github.com/gmh5225/apex-external [External]
- https://github.com/gmh5225/nullptr-apex-external [External]
- https://github.com/gmh5225/R5Apex-UserMode [External]
- https://github.com/gmh5225/Apex-Mizu-Base [Internal]
- https://github.com/gmh5225/ApexDmaCheatUpdated [DMA]

> Game:Fortnite
- https://github.com/gmh5225/FortKit [Dump]
- https://github.com/gmh5225/offsets [Offset]
- https://github.com/gmh5225/fortnite-offsets [Offset]
- https://github.com/gmh5225/AutoOffsets [Offset]
- https://github.com/gmh5225/FortniteOffsetsAndSigs [Offset]
- https://github.com/gmh5225/Fortnite-Offsets [Offset]
- https://github.com/gmh5225/FortniteSigsUpdatedEveryUpdate [Offset]
- https://github.com/gmh5225/Fortnite-SigsUpdatedEveryUpdate [Offset]
- https://github.com/gmh5225/fortnite-W2S-offset-Fortnite [Offset]
- https://github.com/gmh5225/fortnite-offsets [Offset]
- https://github.com/gmh5225/Fortnite-Offset-dumper [Offset & Dump]
- https://github.com/gmh5225/fortnite-virtual-offsets [Virtual Table Offsets]
- https://github.com/gmh5225/fortnite-sigs [Signature]
- https://github.com/gmh5225/fortnite-sigs [Signature]
- https://github.com/gmh5225/fortnite-exploits [Exploits]
- https://github.com/gmh5225/Fortnite-Offsets-Sigs-and-more [Offset]
- https://github.com/gmh5225/FortConsole
- https://github.com/gmh5225/Fortnite-Leak5
- https://github.com/gmh5225/FortniteExternalW2S
- https://github.com/gmh5225/Fortnite-Internal-Cheat-Fixed-and-Updated
- https://github.com/gmh5225/Fortnite-EFI-External [EFI]
- https://github.com/gmh5225/Fortnite-External-Cheat-WinSense-Leak
- https://github.com/gmh5225/fortnite-cheat-source-internal
- https://github.com/gmh5225/Fortnite-Hack-Esp-Exploits-With-Menu
- https://github.com/YMY1666527646/nigusFN
- https://github.com/Sheeedsh78/Cheto-Fortnite-Source-External-EAC-BE-undetected
- https://github.com/CheaterRehab/GodFather-Fortnite-Cheat-Cracked
- https://github.com/gmh5225/Fortnite
- https://github.com/vk-nom/Basic-Fortnite-Cheat-Source-Internal
- https://github.com/gmh5225/Fortnite-UD-External
- https://github.com/gmh5225/Fortnite-Esp-Aimbot-Exploits-Hwid-Spoofer-Cleaner-Hack-Cheat
- https://github.com/gmh5225/Fortnite-Cheat-LEAK
- https://github.com/gmh5225/Fortnite-Fltokens-and-offsets
- https://github.com/gmh5225/VOLTO-EXTERNAL-SPOWAR-UD-EAC-BE-FORTNITE-EXTERNAL-CHEAT
- https://github.com/gmh5225/Serenity.gg-FN-and-Loader
- https://github.com/gmh5225/Fortnite-External-Cheat-Leak
- https://github.com/gmh5225/Spoofer [HWID]
- https://github.com/gmh5225/ritz-amazing-fortnite-internal
- https://github.com/gmh5225/Fortnite-Masterpasta-ihack-Source-Leak
- https://github.com/gmh5225/Fortnite-Evo.cc-Source-External-Cheat
- https://github.com/gmh5225/Fortnite-External
- https://github.com/gmh5225/Apple-Lite-Fortnite-Cheat
- https://github.com/gmh5225/Fortnite-External-Cheat-Source-Code
- https://github.com/gmh5225/BattleFN-cheat-analysis
- https://github.com/gmh5225/fortnite-internal-updated-ritz [Internal]
- https://github.com/gmh5225/Fortnite-Cheato-UD-EAC-BE
- https://github.com/gmh5225/BE-Forcer-Fortnite [BE forcer for fortnite]
- https://github.com/gmh5225/Fortnite-External [External]
- https://github.com/gmh5225/Fortnite-CameraCachePOV
- https://github.com/gmh5225/Fortnite-FNameEntry
- https://github.com/gmh5225/fortnite-external-evo.gj [External]
- https://github.com/gmh5225/Fortnite-External-P2C [External]
- https://github.com/gmh5225/FortniteExternalExploits [External Exploits]
- https://github.com/gmh5225/Fortnite-External-Source [External]
- https://github.com/gmh5225/fortnite-triadz [External]
- https://github.com/gmh5225/Fortnite-External-5 [External]
- https://github.com/gmh5225/ritz-amazing-fortnite-internal-updated [internal]
- https://github.com/gmh5225/flirtnite [External]
- https://github.com/gmh5225/Fortnite-3.5 [Internal]
- https://github.com/gmh5225/ZeroGui-Fortnite-Internal [Internal]
- https://github.com/gmh5225/Fortnite-VoyagerTF [Voyager]
- https://github.com/gmh5225/Fortnite-External-4 [External]
- https://github.com/gmh5225/fn-dma-cheat [DMA]

> Game:Bloodhunt
- https://github.com/ZZZ-Monster/bloodhunt_External
- https://github.com/gmh5225/BloodHunt-v1.1
- https://github.com/gmh5225/blood-hunt

> Game:Super People
- https://github.com/EBalloon/Super-People-sdk
- https://github.com/gmh5225/Super-People-Esp-Aimbot-Magic-Hack
- https://github.com/gmh5225/superpeople-client

> Game:Splitgate
- https://github.com/gmh5225/Splitgate-Internal

> Game:PUBG
- https://github.com/gmh5225/pubg-dumper [Dump]
- https://github.com/gmh5225/pubg_dump_offset [Offset]
- https://github.com/gmh5225/pubg-external-cheat
- https://github.com/gmh5225/pubg_internal
- https://github.com/gmh5225/pubg-internal
- https://github.com/gmh5225/pubg-public
- https://github.com/gmh5225/PlayerUnknown-s-Battlegrounds-Pubg-Steam-Hack-Esp-Aimbot
- https://github.com/gmh5225/lilypublic
- https://github.com/gmh5225/PUBG_Internal
- https://github.com/gmh5225/PUBG-DX
- https://github.com/gmh5225/PUBGSTAR

> Game:PUBG Lite
- https://github.com/gmh5225/Pubg-Lite-ESP

> Game:PUBGM
- https://github.com/gmh5225/pubgm_sdk_and_offsets [Offset]
- https://github.com/gmh5225/pubg_mobile_memory_hacking
- https://github.com/Mood-Coding/pubgm_shitty_source
- https://github.com/gmh5225/PUBGM-PUBGPatcher
- https://github.com/gmh5225/PUBGM1.6-DeadGame
- https://github.com/gmh5225/BYPASS-PUBG-MOBILE-IMGUI
- https://github.com/gmh5225/LastIslandOfSurvival-iOSCheat-Source
- https://github.com/gmh5225/pubg-mobile-pak-extract [pak extracting tool]
- https://github.com/gmh5225/pubg_mobile_memory_hacking_examples
- https://github.com/gmh5225/ChinaPubg
- https://github.com/gmh5225/pubg

> Game:Sausage Man
- https://github.com/gmh5225/AndroidCheatTemplate

> Game:The finals
- https://github.com/gmh5225/the-finals-interior-cheat

> Game:EFT
- https://github.com/gmh5225/TOG [Offsets Generator]
- https://github.com/fcancelog/EftStreamedCheat
- https://github.com/Nou4r/pKernelInterface-EFT
- https://github.com/sailro/EscapeFromTarkov-Trainer
- https://github.com/gmh5225/tiny_eft
- https://github.com/gmh5225/Nathans-Tarkov-Radar-Public [Vmread + Radar]
- https://github.com/gmh5225/eft-external
- https://github.com/gmh5225/eft
- https://github.com/gmh5225/eft-internal
- https://github.com/gmh5225/EFT-Veil-EFT
- https://github.com/Qemu-Gang/Escape-from-TuxKov [QEMU]
- https://github.com/gmh5225/Comm-ImMiraclela
- https://github.com/gmh5225/Simple-EFT-Base
- https://github.com/gmh5225/EFTLeecher [DMA]
- https://github.com/gmh5225/eft-dma-radar-1 [DMA Radar]
- https://github.com/gmh5225/EFT-MonoEFT
- https://github.com/gmh5225/simple-eft-superman-training-bot
- https://github.com/gmh5225/EFT-NewTarkovCheatProject

> Game:Arena Breakout Infinite
- https://github.com/gmh5225/UE426_ABInfinite-Win64-Shipping [SDK]
- https://github.com/gmh5225/hardware_bypass [GPU check bypass]

> Game:R6
- https://github.com/gmh5225/Rainbow-Six-Cheat
- https://github.com/gmh5225/OverflowR6V2
- https://github.com/gmh5225/Internal-Rainbow-Six-Cheat-V3
- https://github.com/gmh5225/epic-r6-v9
- https://github.com/Kix48/R6Updater
- https://github.com/gmh5225/R6Table_Internal
- https://github.com/gmh5225/r6-internal
- https://github.com/gmh5225/External-R6S-Cheat
- https://github.com/gmh5225/R6-Internal-V3
- https://github.com/gmh5225/R6S-internal-Cheat
- https://github.com/gmh5225/Rainbow-Six-Siege-Rs6-External-Esp-Aimbot-Hack-Cheat
- https://github.com/gmh5225/Rainbow-6-Siege-Cheat
- https://github.com/gmh5225/r6-external [External]
- https://github.com/gmh5225/Artemis [Internal]
- https://github.com/gmh5225/R6-Cheat-Dumper [External]
- https://github.com/gmh5225/R6S-External-V2 [External]
- https://github.com/gmh5225/R6-Chams-public [Chams]

> Game:Overwatch 
- https://github.com/gmh5225/PareidoliaTriggerbot [Triggerbot]
- https://github.com/gmh5225/Overwatch-1-cheat-source-.
- https://github.com/gmh5225/overwatch-iat-fixer [Overwatch IAT Fixer]
- https://github.com/gmh5225/ow_unpack
- https://github.com/gmh5225/OW-Aeternum
- https://github.com/gmh5225/Ow-FOV [FOV]

> Game:Overwatch2
- https://github.com/gmh5225/Overwatch2-colorbot-Cheats
- https://github.com/gmh5225/Overwatch-2-Cheat-Aimbot-Esp
- https://github.com/gmh5225/meowsense
- https://github.com/gmh5225/Ow-Outlines [Shows Players through walls]
- https://github.com/gmh5225/Overwatch-2-TOPE-EXTERNAL-CHEAT
- https://github.com/gmh5225/OW2-wardenrekter [Emulate OW2 AC]

> Game:Paladins
- https://github.com/gmh5225/Paladins-Internal-Esp-Aimbot-Hack-Cheat-Hack
- https://github.com/gmh5225/Paladins-internal-Cheat

> Game:DayZ
- https://github.com/gmh5225/DayZzz
- https://github.com/gmh5225/External-Dayz-Cheat
- https://github.com/gmh5225/DayZ-Cheat
- https://github.com/gmh5225/DayZ-Server-Battleye-Remover [Disable battleye]

> Game:Rust
- https://github.com/gmh5225/rust-auto-dumper [Auto Dump]
- https://github.com/gmh5225/OxideDumper [Auto Dump]
- https://github.com/gmh5225/OverflowRust
- https://github.com/gmh5225/simple-rust-hack
- https://github.com/gmh5225/rust-internal
- https://github.com/gmh5225/Rust-External
- https://github.com/gmh5225/Rico-Cheat-rust-external
- https://github.com/spyder1g/a-pasted-rust-script
- https://github.com/gmh5225/Rust-External-Cheat
- https://github.com/gmh5225/Kors_lol [Internal]
- https://github.com/gmh5225/Rust-Internal [Internal]
- https://github.com/gmh5225/CRC32
- https://github.com/gmh5225/Rust-Cheat-External
- https://github.com/gmh5225/Simple-Rust-Base
- https://github.com/gmh5225/sapphire
- https://github.com/gmh5225/Rust-Cheat-External-main
- https://github.com/gmh5225/Rust-RustInternal [Internal]
- https://github.com/gmh5225/rust-external-1 [External]
- https://github.com/gmh5225/Rust-External [External]
- https://github.com/gmh5225/Rust-ExternaL-and-Driver-AlienCheats [External]
- https://github.com/gmh5225/Rust-External-Source [External]
- https://github.com/gmh5225/immortal-rust
- https://github.com/gmh5225/RustDMACheat [DMA]

> Game:Arma3
- https://github.com/gmh5225/arma3-external-variable-manager
- https://github.com/gmh5225/3den-Enhanced [Mod Editor]
- https://github.com/gmh5225/arma3beclient [BattlEye Tool]

> Game:7 Days To Die
- https://github.com/gmh5225/7DTD

> Game:AVA
- https://github.com/gmh5225/AVA-Hack

> Game:Mordhau
- https://github.com/gmh5225/mordhau-simple-auto-block-cheat

> Game:Smite  [UE3]
- https://github.com/gmh5225/SmiteESPAimbot 

> Game:POLYGON [UE5]
- https://github.com/gmh5225/POLYGON_UE5

> Game:PalWorld [UE5]
- https://www.unknowncheats.me/forum/other-fps-games/620076-palworld-reversal-structs-offsets.html
- https://github.com/gmh5225/Palworld-SDK-Dump
- https://github.com/gmh5225/Palworld-Server-Modding
- https://github.com/gmh5225/PalWorld-ServerInjector
- https://github.com/gmh5225/PalWorld-NetCrack
- https://github.com/gmh5225/palworld_rcon [Server on Windows]
- https://github.com/gmh5225/palworld_rcon [Server on Windows]
- https://github.com/gmh5225/HowTo-Palworld [Server on Linux]
- https://github.com/gmh5225/docker-palworld-dedicated-server [Server based on Linux and Docker]
- https://github.com/gmh5225/PalWorld-Server-Unoffical-Fix [Server patch]
- https://github.com/gmh5225/PalWorld-Tools [Mod Patcher]
- https://github.com/gmh5225/PalworldModdingKit [A modding kit for Palworld]
- https://github.com/gmh5225/PalworldSaved [Save]
- https://github.com/gmh5225/palworld-save-tools [Save]
- https://github.com/gmh5225/PalEdit Save]
- https://github.com/gmh5225/PalWorldSettingGenerator [Setting Generator]
- https://github.com/gmh5225/palworld-helper [Helper]
- https://github.com/gmh5225/PalWorldAntiCheat [Anti Cheat]
- https://github.com/gmh5225/PalAntiCheat-poc [Anti Cheat]

> Game:Genshin Impact
- https://github.com/gmh5225/mhynot2
- https://github.com/gmh5225/genshinjumpfixer2 [Decode CFG]
- https://github.com/gmh5225/misc/tree/master/reversing/genshin [Decode CFG]
- https://github.com/DNLINYJ/Anti_miHoYo_Jcc_Obfuscate [Decode CFG By X64DBG]
- https://github.com/gmh5225/genshin-cheat
- https://github.com/gmh5225/Grasscutter [Private Server]
- https://github.com/gmh5225/Genshin-Akebi-GC [Cheat]
- https://github.com/gmh5225/Akebi-Cheat-3.3 [Cheat]
- https://github.com/gmh5225/Genshin-GenshinData [Game Data]
- https://github.com/gmh5225/YaeAchievement
- https://github.com/phonowell/genshin-impact-script [A sweet genshin impact script]
- https://github.com/gmh5225/GenshinImpact-Base
- https://github.com/gmh5225/Taiga74164-Akebi-GC
- https://github.com/gmh5225/EasyPeasy-GC
- https://github.com/gmh5225/GenshinDebuggerBypass
- https://github.com/gmh5225/Genshin-EasyPeasy-Bypass [Anti-Debug Bypass]
- https://github.com/gmh5225/genshin-remove-banner
- https://github.com/gmh5225/AutoOpenCAK [Bypass tool]
- https://github.com/gmh5225/Genshin-Cheetos [Menu]

> Game:Honkai Impact
- https://github.com/gmh5225/BetterHI3Launcher
- https://github.com/gmh5225/HI3-ACE-B

> Game:Honkai Star Rail
- https://github.com/gmh5225/StarRail-S-GC
- https://github.com/gmh5225/StarRail-ACE-B
- https://github.com/gmh5225/star_rail
- https://github.com/gmh5225/Pom-Pom
- https://github.com/gmh5225/StarRailCopilot [Script]
- https://github.com/gmh5225/Auto_Simulated_Universe [Script]

> Game:osu
- https://github.com/gmh5225/maniac [External]
- https://github.com/gmh5225/freedom [difficulty changer & bot]
- https://github.com/gmh5225/osu-aac [ANTI ANTI CHEAT]

> Game:EldenRing
- https://github.com/techiew/EldenRingMods [Mod]
- https://github.com/gmh5225/EldenRingLauncher [Launcher]
- https://github.com/gmh5225/Elden-Ring-Debug-Tool [Debug tool for Elden Ring modding]

> Game:Dark Souls
- https://github.com/igromanru/Dark-Souls-III-Cheat-Engine-Guide
- https://github.com/gmh5225/ds4-tools [Scripts I use to play and reverse-engineer the DualShock 4]

> Game:Sea Of Thieves
- https://github.com/gmh5225/SeaOfChoros

> Game:GTA III - Definitive Edition
- https://github.com/gmh5225/GTAIII-DE-GoldHook

> Game:GTA5
- https://github.com/gmh5225/gtav-sourcecode-build-guide [GTA V Source Code Build Tutorial]
- https://github.com/gmh5225/GTA-5-SIGS-1.59 [Offset]
- [About
Adds drag- to- resize functionality to the main GTA V window](https://github.com/gmh5225/GTAV_DragResize)
- [Open-source cheat software for Grand Theft Auto V (PC)](https://github.com/gmh5225/GrandTheftAutoV-Cheat)
- https://github.com/gmh5225/BigBaseV2
- https://github.com/YimMenu/YimMenu
- https://github.com/gmh5225/SpookiMystic-GTA-Leak [Menu]
- https://github.com/Rimmuru/gta-source
- https://github.com/gmh5225/gta5view [Viewer/Editor]
- https://github.com/gmh5225/pHake [Mod Menu]
- https://github.com/gmh5225/ExtendedCameraSettings [Extending functionality of the gameplay camera]
- https://github.com/gmh5225/gta5cheat
- https://github.com/gmh5225/gta5cheat_qt

> Game:Geometry Dash
- https://github.com/gmh5225/gd-internal

> Game:8ball pool
- https://github.com/gmh5225/Alaa-8ball-pool-source-exposed

> Game:Wizard101
- https://github.com/gmh5225/wizard101-spoofer [HWID]

> Game:QQTang
- https://github.com/gmh5225/QQTangCheatEngine

> Game:Chess
- https://github.com/gmh5225/lc0 [Chess Engine]
- https://github.com/gmh5225/Stockfish [Chess Engine]

> Game:BLOCKPOST
- https://github.com/gmh5225/BLOCKPOST-Cheat

> Game:Witch It
- https://github.com/gmh5225/CheatIt

> Game:RO
- https://github.com/gmh5225/rAthenaCN

> Game:PokemonGo
- https://github.com/gmh5225/PokemonGoDumper

> Game:L4D2
- https://github.com/gmh5225/L4D2-Cheat [Linux]
- https://github.com/gmh5225/L4D2Basic

> Game:mhxy
- https://github.com/gmh5225/mhxy_kernel
- https://github.com/gmh5225/mhxy

> Game:Ironsight
- https://github.com/gmh5225/Lazysight

> Game:Devour
- https://github.com/gmh5225/DevourClient
- https://github.com/gmh5225/DevourMenu [Menu]

> Game:Goose Goose Duck
- https://github.com/gmh5225/Goose_Goose_Duck_Hack

> Game:Team Fortress 2
- https://github.com/gmh5225/teamfortress2_internal
- https://github.com/gmh5225/Cunthook [linux]
- https://github.com/gmh5225/Fedoraware

## Anti Cheat
> Guide
- [An in-depth exploration of how C programs transform from source code to executable binaries. This repository contains a comprehensive guide to understanding linking, loading, and executable formats](https://github.com/gmh5225/underTheHoodOfExecutables)
- https://technology.riotgames.com/news/riots-approach-anti-cheat
- https://github.com/gmh5225/WeirdAntiCheatIdeas
- https://github.com/gmh5225/AntiCheat-chrysalis
- https://www.unknowncheats.me/forum/anti-cheat-bypass/481731-tutorial-ring3-anticheat-project.html
- https://github.com/gmh5225/awesome-executable-packing [Executable File Packing]
- https://anti-debug.checkpoint.com [Anti Debug]
- https://github.com/gmh5225/DVRT [DVRT]
- https://areweanticheatyet.com [A list of games using anti-cheats]
- https://github.com/gmh5225/alt-V-Anticheat-Guide [GTA5 MP servers]
- https://github.com/gmh5225/packer-tutorial [Packer]
- https://github.com/gmh5225/ghostbusters [Senior Design: Anit-Cheat Detection system]
- https://github.com/Solaree/pairipcore [Public researchings of the Google's Android apps protection]
- https://github.com/bad-antics/rce-shield [RCE Shield - Remote Code Execution hardening toolkit for PC gamers. Scans game launchers, anti-cheat, mods, overlays, peripherals & network for vulnerabilities]

> Stress Testing
- https://github.com/niemand-sec/AntiCheat-Testing-Framework [Testing Framework]
- https://github.com/gmh5225/MemWars [Testing Framework]
- https://github.com/gmh5225/EC [Testing Framework]
- https://github.com/stuxnet147/Known-Driver-Mappers [Known Driver Mappers]
- https://github.com/DanielRTeixeira/injectAllTheThings [Injection Testing]
- https://github.com/gmh5225/Process-Injection-Techniques [Injection Testing]
- https://github.com/zoand/Injectors [Injection Testing]
- https://github.com/gmh5225/GuidedHacking-Injector [Injection Testing]
- https://github.com/gmh5225/rust-dll-crab [Injection Testing]
- https://github.com/gmh5225/injection [Injection Testing]
- https://github.com/w1u0u1/kinject [Injection Testing]
- https://github.com/gmh5225/ThreadJect [Injection Testing]
- https://github.com/gmh5225/Windows-DLL-Injector [Injection Testing]
- https://github.com/gmh5225/code_injection [Injection Testing]
- https://github.com/gmh5225/Dirty-Vanity [Injection Testing:RtlCreateProcessReflection]
- https://github.com/gmh5225/ThreadHijackingInjector [Injection Testing]
- https://github.com/gmh5225/simple-SetWindowsHookExW-injector [Injection Testing:SetWindowsHookExW]
- https://github.com/gmh5225/SetWindowsHookEx-Injector [Injection Testing:SetWindowsHookExW]
- https://github.com/gmh5225/Jektor [Injection/Shellcode Testing]
- https://github.com/gmh5225/face-injector-v2 [Injection/ Testing]
- https://github.com/gmh5225/libelevate [Elevating Handle]
- https://github.com/gmh5225/NoBastian_v2 [Elevating Handle By LSASS]
- https://github.com/gmh5225/launcher-abuser [Elevating Handle]
- https://github.com/gmh5225/LSASS-Usermode-Bypass [Elevating Handle By LSASS]
- https://github.com/gmh5225/LSASS-DumpThatLSASS [Elevating Handle By LSASS]
- https://github.com/gmh5225/Van1338 [Elevating Handle By Timing Attack]
- https://github.com/gmh5225/Handle-Ripper [DuplicateHandle]
- https://github.com/gmh5225/Dumpy [Reuse opened handles By LSASS]
- https://github.com/gmh5225/EasyHandles [Driver + DLL which allows us to open handles to callback-protected processes]
- https://github.com/gmh5225/lsass-extend-mapper [Manual mapper from LSASS]
- https://github.com/gmh5225/EfiGuard [PG Testing]
- https://github.com/gmh5225/Shark [PG Testing]
- https://github.com/gmh5225/HideDriverTesting [Hide Driver Testing]
- https://github.com/gmh5225/HideDriver [Hide Driver Testing]
- https://github.com/gmh5225/HideDriver [Hide Driver Testing]
- https://github.com/gmh5225/TraceCleaner [Hide Driver Testing]
- https://github.com/gmh5225/disable-threat-tracing [ETW Testing]
- https://github.com/gmh5225/AMSI-ETW-Patch [ETW Testing]
- [EDRSandblast/KernellandBypass/ETWThreatIntel.c](https://github.com/gmh5225/EDRSandblast/blob/master/EDRSandblast/KernellandBypass/ETWThreatIntel.c) [ETW Testing]
- https://github.com/gmh5225/Battleye-VAC-EAC-Kernel-Bypass [FsFilter Testing]
- https://github.com/gmh5225/MMFCodeInjection [User APC + File Mapping Testing]
- https://github.com/gmh5225/TtdAntiDebugging [Debug Testing]
- https://github.com/gmh5225/cheat-attack-thread-slemu [Hearbeat Testing]
- https://github.com/gmh5225/cheat-driver [MmCopyVirtualMemory Testing]
- https://github.com/gmh5225/vt-debuuger [Hacked Hypervisor Testing]
- https://github.com/gmh5225/vt-debuger [Hacked Hypervisor Testing]
- https://github.com/gmh5225/hv [Hacked Hypervisor Testing]
- https://github.com/gmh5225/AetherVisor [Hacked Hypervisor Testing AMD]
- https://github.com/gmh5225/BareSVM [Hacked Hypervisor Testing AMD]
- https://github.com/noahware/hyper-reV [memory introspection and reverse engineering hypervisor powered by leveraging Hyper-V]
- https://github.com/LabGuy94/Diskjacker [Runtime Hyper-V Hijacking with DDMA]
- https://github.com/gmh5225/NovaHypervisor [NovaHypervisor is a defensive x64 Intel host based hypervisor. The goal of this project is to protect against kernel based attacks]
- https://github.com/gmh5225/LockFile-Poc [Lock File]
- https://github.com/gmh5225/UltraDriver-Game-Cheat [Cheat Driver]
- https://github.com/gmh5225/Kernel-Special-APC-ReadProcessMemory [RPM]

> Driver Unit Test Framework
- https://github.com/gmh5225/wdutf

> Anti Debugging
- https://github.com/gmh5225/al-khaser
- https://github.com/gmh5225/WubbabooMark
- https://github.com/gmh5225/ScyllaHideDetector2 
- https://github.com/gmh5225/AntiDebugging
- https://github.com/gmh5225/MAJESTY-technologies
- https://github.com/gmh5225/AntiCrack-DotNet [CSharp]
- https://github.com/weak1337/CEDetector [CE]
- https://github.com/gmh5225/Detection-CheatEngine [CE]
- https://github.com/gmh5225/Detection-CheatEngine-Ring0 [CE]
- https://github.com/gmh5225/AntiDbg-AmogusPlugin
- https://gtoad.github.io/2017/06/25/Android-Anti-Debug [Android]
- https://github.com/gmh5225/AntiDebugandMemoryDump [Android]
- https://github.com/gmh5225/ADB-Debug-Detect-Checker [Android]
- [Sample anti-debug with detect ScyllaHide/HyperHide and TitanHide](https://github.com/gmh5225/antidbg-Baka)
- [Linux anti-debugging techniques](https://github.com/gmh5225/adbg)
- https://github.com/gmh5225/AntiDBG
- https://github.com/gmh5225/LADD [Linux]
- https://github.com/gmh5225/debugoff [Linux]
- https://github.com/gmh5225/AntiKernelDebug-POC [Windows Kernel]
- https://github.com/gmh5225/cpp-anti-debug
- https://github.com/gmh5225/Anti-Debug
- https://github.com/gmh5225/GoDefender [Anti Debugging]
- https://github.com/gmh5225/RaceCondition
- https://github.com/gmh5225/AntiCrack-DotNet [DotNet]
- https://github.com/gmh5225/umium [C++/CLI]
- https://github.com/gmh5225/Anti-Debugger-Protector-Loader
- https://github.com/gmh5225/showstopper
- https://github.com/gmh5225/makin [Reveal anti-debugging and anti-VM tricks]
- https://github.com/gmh5225/brkida [C++ macro for x64 programs that breaks ida hex-rays decompiler tool]
- https://github.com/gmh5225/hint-break [A 25-year-old architectural blind spot affecting modern reverse engineering tools]

> Page Protection
- https://github.com/gmh5225/Self-Remapping-Code
- https://github.com/gmh5225/anti-crack-system
- https://docs.microsoft.com/en-us/windows/win32/api/winbase/nf-winbase-addsecurememorycachecallback
- https://github.com/weak1337/NO_ACCESS_Protection
- https://github.com/gmh5225/no-access-protection-x86
- https://github.com/gmh5225/page_no_access
- https://github.com/gmh5225/DeepSleep
- https://github.com/gmh5225/DeathSleep
- https://github.com/gmh5225/Sleep-obf-T.D.P.
- https://github.com/gmh5225/ShellcodeFluctuation
- https://github.com/gmh5225/veh-printf-hook [VEH + PAGE_GUARD]
- https://github.com/charliewolfe/PointerGuard [VEH + PAGE_GUARD]
- https://github.com/gmh5225/EATGuard [VEH + PAGE_GUARD]
- https://github.com/gmh5225/MemoryGuard [VEH + PAGE_GUARD]
- https://github.com/gmh5225/Voidmaw [VEH + PAGE_GUARD]
- https://github.com/gmh5225/veh_hide_memory [VEH + PAGE_NOACCESS]
- https://github.com/gmh5225/PAGE_NO_ACCESS-not-byfron [VEH + PAGE_NOACCESS]
- https://github.com/gmh5225/BinCon [VEH + PAGE_NOACCESS]

> Binary Packer
- https://github.com/gmh5225/awesome-executable-packing
- https://github.com/phra/PEzor
- https://github.com/gmh5225/PE-Packer [X86]
- https://github.com/gmh5225/Packer [X86]
- https://github.com/gmh5225/pe-protector [X86]
- https://github.com/gmh5225/ConfuserEx [.NET]
- https://github.com/iArtorias/debug_remover [Strip Debug Info]
- https://github.com/ytk2128/pe32-password
- https://github.com/gmh5225/Huan
- https://github.com/gmh5225/HintInject [Hint/Name Table]
- https://github.com/ClaudiuGeorgiu/Obfuscapk [Android]
- https://github.com/gmh5225/Embuche [ELF]
- https://github.com/gmh5225/amber
- https://github.com/gmh5225/PePacker
- https://github.com/gmh5225/wrappe [Rust]
- https://github.com/gmh5225/woody_woodpacker [ELF]
- https://github.com/gmh5225/m0dern_p4cker [ELF]
- https://github.com/gmh5225/peinjector
- https://github.com/gmh5225/AresFramework
- https://github.com/gmh5225/exe_packer
- https://github.com/gmh5225/Origami [Compressing .net assemblies]
- https://github.com/gmh5225/ELFpacker [ELF]
- https://github.com/gmh5225/shibari [Linking multiple PE\PE + files to one]
- [Simple ELF runtime packer for creating stealthy droppers](https://github.com/gmh5225/ward)
- [A simple packer working with all PE files which cipher your exe with a XOR implementation](https://github.com/gmh5225/xorPacker)
- https://github.com/gmh5225/petoy [PE]
- [An ELF / PE packer written in pure C](https://github.com/gmh5225/Silent_Packer)
- https://github.com/gmh5225/ELFcrypt [ELF RC4]
- https://github.com/gmh5225/elfuck [ELF]
- https://github.com/gmh5225/packer [PE]
- https://github.com/gmh5225/hXOR-Packer [PE XOR]
- https://github.com/gmh5225/midgetpack [ELF]
- https://github.com/gmh5225/netcrypt [.NET]
- https://github.com/gmh5225/pakkero [ELF]
- https://github.com/gmh5225/papaw [LZMA]
- https://github.com/gmh5225/sloader [ELF loader which aims to replace ld-linux.so of glibc]
- https://github.com/gmh5225/elfloader [ELF Loader for ps5-jar-loader]
- https://github.com/gmh5225/IAT-Obfuscation [IAT Obfuscation]
- https://github.com/gmh5225/shellcode-EntropyFix [Reducing entropy]
- https://github.com/gmh5225/AtomPePacker [PE X64]
- https://github.com/gmh5225/Win32.Nebula [PE X64]
- https://github.com/gmh5225/hm-pe-packer [PE X64]
- https://github.com/gmh5225/PEPacker [PE X64]
- https://github.com/gmh5225/x64-EXE-Packer [PE X64]
- https://github.com/gmh5225/Shoggoth [Polymorphic Encryptor]
- https://github.com/gmh5225/kiteshield [ELF X64]
- https://github.com/gmh5225/KitsuPE [PE]
- https://github.com/gmh5225/Evader [PE]
- https://github.com/gmh5225/GreyM [PE]
- https://github.com/gmh5225/stelf-loader [ELF X64 loader]
- https://github.com/gmh5225/oxide [Written by Rust]
- https://github.com/gmh5225/AwaitFuscator [.NET]
- https://github.com/gmh5225/Fatpack [A Windows PE packer with full TLS (Thread Local Storage) support]
- https://github.com/gmh5225/rel-fuscate [Modifying the jmprel_entry->r_offset]
- https://github.com/gmh5225/SuperMega [Stealthily inject shellcode into an executable]

> CLR Protection
- https://github.com/gmh5225/ClrGuard

> Anti Disassembly
- https://github.com/gmh5225/blackhat2012

> Sample Unpacker
- https://github.com/gmh5225/mal_unpack_drv
- https://github.com/gmh5225/android-unpacker [Android]

> Dump Fix
- https://github.com/gmh5225/unmapper
- https://github.com/gmh5225/DumpPE
- https://github.com/gmh5225/fix-arxan

> Encrypt Variable
- https://github.com/gmh5225/encrypted_value [C++]
- https://github.com/gmh5225/e3 [C++]
- https://github.com/gmh5225/xor-float [C++]
- https://github.com/gmh5225/xv [C++]
- https://github.com/gmh5225/obfuscxx [Header-only compile-time variables obfuscation library for C++20 and later. Compiler Support: MSVC (+WDM), LLVM, GCC. Architecture Support: x86-64, ARM]

> Lazy Importer
- https://github.com/gmh5225/lazy_importer
- https://github.com/gmh5225/kli
- https://github.com/gmh5225/kli-ex
- https://github.com/gmh5225/zeroimport
- https://github.com/gmh5225/blitz

> Anti-Cheat Programming
- https://github.com/gmh5225/thread-call-stack-scanner [Safely manage the unloading of DLLs that have been hooked into a process. Context]

> Compile Time
- https://github.com/gmh5225/malstring [Using c++23 compile-time magic to produce obfuscated PIC strings and arrays]
- https://github.com/gmh5225/Android-Native-Import-Hide [A library for hiding and retrieving imports in ELF binaries]
- https://github.com/gmh5225/blitz [a header-only library to dynamically resolve modules and exports while also being able to call them directly]
- https://github.com/gmh5225/xv [single-header pointer/value encryption]
- https://github.com/gmh5225/obfusheader.h [Obfusheader.h is a portable header file for C++14 compile-time obfuscation]
- https://github.com/gmh5225/DriverBase/blob/dev/Dependencies/obfusheader.h [obfusheader.h for windows driver]
- https://github.com/gmh5225/rust-obfuscator [Automatic Rust Obfuscator and Macro Library]
- https://github.com/gmh5225/XorData [A C++17 framework designed to enable obfuscation of constants, variables, and strings]
- https://github.com/gmh5225/crycall [Compile-Time Calls Obfuscator for C++14]
- https://github.com/gmh5225/inline_syscall [Inline syscalls made easy for windows on clang]
- https://github.com/gmh5225/inline-syscall [A simple direct syscall wrapper written in C++ with compatibility for x86 and x64 programs]
- https://github.com/gmh5225/syscalls-cpp [A modern C++20 header-only library for advanced direct system call invocation]
- https://github.com/gmh5225/STB [Compile-time conversion library, from IDA-style string to array]
- https://github.com/gmh5225/CompileTimeRandom [Compile time random implementation using C++11]
- https://github.com/gmh5225/limba [compile-time control flow obfuscation using mba]
- https://github.com/gmh5225/Polymorphic-Engine [Prototype runtime C++ polymorphic type engine]
- https://github.com/gmh5225/cthash [constexpr implementation of SHA-2 and SHA-3 family of hashes]
- https://github.com/gmh5225/Dynamizer [Reduce Dynamic Analysis Detection Rates With Built-In Unhooker, Anti Analysis Techniques, And String Obfuscator Modules]
- https://github.com/gmh5225/compile-time-regular-expressions [Compile Time Regular Expression in C++]
- https://github.com/gmh5225/obfstr [String Crypter for rust]
- https://github.com/gmh5225/obfuscatxor [String Crypter for golang]
- https://github.com/gmh5225/static_string_obfuscation [String Crypter for Zig]
- https://github.com/gmh5225/Swift-String-Obfuscator [String Crypter for Swift]
- https://github.com/gmh5225/crystr [String Crypter]
- https://github.com/gmh5225/Obfuscate [String Crypter]
- https://github.com/gmh5225/xorlit [String Crypter]
- https://github.com/gmh5225/xorstr [String Crypter]
- https://github.com/gmh5225/skCrypter [String Crypter]
- https://github.com/gmh5225/BloatedHammer [API Hammering with C++20 by folding (avoiding loops)]
- https://github.com/gmh5225/xor-float [xor float]
- https://github.com/gmh5225/oxorany [obfuscated any constant encryption in compile time on any platform]
- https://github.com/gmh5225/obfus.h [Macro-header for compile-time C obfuscation (tcc, win x86/x64)]
- https://github.com/gmh5225/Obfusk8 [Obfusk8: C++17-Based Obfuscation Library]
- https://github.com/gmh5225/obfuscxx [Header-only compile-time variables obfuscation library for C++20 and later. Compiler Support: MSVC (+WDM), LLVM, GCC. Architecture Support: x86-64, ARM]
- https://github.com/gmh5225/vm_str.hpp [Header only C++20 compile time string obfuscator]
- https://github.com/gmh5225/irql [Rust: compile-time IRQL safety for Windows kernel drivers]

> Shellcode Engine & Tricks
- https://github.com/gmh5225/scc [shellcode compiler]
- https://github.com/gmh5225/obj2shellcode
- https://github.com/lainswork/shellcode-factory
- https://github.com/gmh5225/GPU_ShellCode [hide the payload inside the gpu memory]
- https://github.com/gmh5225/Shellcrypt [A QoL tool to obfuscate shellcode. In the future will be able to chain encoding/encryption/compression methods]
- https://github.com/gmh5225/SuperMega [Stealthily inject shellcode into an executable]
- https://github.com/mrexodia/RiscyWorkshop [Payload Obfuscation for Red Teams workshop materials]
- https://github.com/gmh5225/byvalver [Shellcode bad-byte banisher with preserved functionalities]
- https://github.com/gmh5225/scfw [A cross-platform C++ framework for building Windows shellcode]

> Obfuscation Engine
- https://github.com/vi3t1/vmprotect-3.5.1
- https://github.com/gmh5225/obfus.h [Macro-header for compile-time C obfuscation (tcc, win x86/x64)]
- https://github.com/gmh5225/BinaryShield
- https://github.com/gmh5225/perses
- https://github.com/gmh5225/Alcatraz
- https://github.com/gmh5225/Alcatraz
- https://github.com/gmh5225/obfuscator
- https://github.com/gmh5225/furikuri
- https://github.com/gmh5225/RelocBonus [Attack Reloc]
- https://github.com/maoabc/nmmp [Dex]
- https://github.com/gmh5225/BlackObfuscator [Dex]
- https://github.com/gmh5225/CallObfuscator [Call Obfuscation]
- https://github.com/gmh5225/Milfuscator
- https://github.com/gmh5225/the-poor-mans-obfuscator [elf/macho]
- https://github.com/gmh5225/proguard [Java]
- https://github.com/gmh5225/WProtect
- https://github.com/gmh5225/WProtect
- https://github.com/gmh5225/WProtectSDK
- https://github.com/gmh5225/nb_obfuscator
- https://github.com/gmh5225/cerberus [VM]
- https://github.com/gmh5225/phantasm-x86-virtualizer [VM]
- https://github.com/gmh5225/guardian-rs [VM]
- https://github.com/gmh5225/covirt [VM]
- https://github.com/gmh5225/simplify [Java]
- https://github.com/gmh5225/dProtect [Java/Kotlin]
- https://github.com/gmh5225/EntropyReducer [Reduce Entropy]
- https://github.com/gmh5225/AwaitFuscator [.NET]
- https://github.com/gmh5225/stitch [X86: Rewrite and obfuscate code in compiled binaries]
- https://github.com/gmh5225/Ryujin [X86 PE BIN2BIN]
- https://github.com/gmh5225/shredder-rs [A high-fidelity x86_64 polymorphic mutation engine focused on instruction-level fragmentation and context preservation]

> Screenshot
- https://github.com/bavulapati/DXGICaptureApplication [Capture Desktop]
- https://github.com/Rick-laboratory/Windows-Screenshotcapture-DirectX/blob/master/main.cpp [DX9]
- https://github.com/gmh5225/dwm-screen-shot [DWM]
- https://github.com/gmh5225/screencapture [DX11]
- https://github.com/gmh5225/WindowsDesktopDuplicationSample [DXGI]
- https://github.com/gmh5225/GetPixel-vs-BitBlt_GetDIBits [GetPixel]
- https://github.com/gmh5225/ScreenShot [BitBlt]

> Game Engine Protection:Unreal
- https://github.com/gmh5225/Static-Variables-Obfuscator-UE4
- https://github.com/gmh5225/UE-Plugin-SCUE4-Plugin
- https://github.com/gmh5225/UnrealEngine-Protection

> Game Engine Protection:Unity
- https://github.com/gmh5225/USecurity
- https://github.com/gmh5225/Unity3D_Obfuscator
- https://github.com/gmh5225/Ether-Uprotector
- https://github.com/gmh5225/Il2cppEncrtypt
- https://github.com/gmh5225/obfuz

> Game Engine Protection:Source
- [Source Engine serverside anti-cheat plugin. (CS:S, CS:GO, CS:P, TF2)](https://github.com/gmh5225/NoCheatZ-3)

> Open Source Anti Cheat System
- https://github.com/gmh5225/NoMercy
- https://github.com/NoMercy-ac [NoMercy]
- https://github.com/gmh5225/BetaShield
- https://github.com/chztbby/RebirthGuard
- https://github.com/gmh5225/Avanguard
- https://github.com/gmh5225/Bloom-Anticheat
- https://github.com/gmh5225/Kernel-Anticheat [Kernel Anticheat]
- https://github.com/gmh5225/Stresser [Anti Virus in fact but also Anti Cheat]
- https://github.com/gmh5225/antivirus [Anti Virus in fact but also Anti Cheat]
- https://github.com/gmh5225/PeaceMaker [Anti Virus in fact but also Anti Cheat]
- https://github.com/gmh5225/VAC [Reversed VAC]
- https://github.com/gmh5225/anti-cheat-emulator
- https://github.com/gmh5225/EAC-Reversal [Reversed EAC]
- https://github.com/gmh5225/BE-Shellcode [Reversed BE Shellcode]
- https://github.com/gmh5225/be_shellcode_dump [Reversed BE Shellcode]
- https://github.com/gmh5225/AndroidAntiCheat [Android Platform]
- https://github.com/gmh5225/Lazenca-S [Android Platform]
- https://github.com/gmh5225/Scythe-AntiCheat [Minecraft]
- https://github.com/gmh5225/Grim [Minecraft]
- https://github.com/gmh5225/AntiCheat
- https://github.com/gmh5225/openedr [EDR]
- https://github.com/0xrawsec/whids [EDR]
- https://github.com/gmh5225/Raccine [EDR]
- https://github.com/gmh5225/BLUESPAWN [EDR]
- https://github.com/gmh5225/TheHive [EDR]
- https://github.com/gmh5225/Sanctum [Sanctum is an experimental proof-of-concept EDR, designed to detect modern malware techniques, above and beyond the capabilities of antivirus. Built in Rust]
- https://github.com/gmh5225/wazuh [XDR]
- https://github.com/gmh5225/UltimateAntiCheat
- https://github.com/gmh5225/Quack
- [Source Engine serverside anti-cheat plugin. (CS:S, CS:GO, CS:P, TF2)](https://github.com/gmh5225/NoCheatZ-3)
- [This is the Anti Cheat System for Knight Online Gamesoft vversion](https://github.com/gmh5225/GamesoftACS)
- [User-mode C++ Anti-Cheat written for German Roleplay Server GVMP.de](https://github.com/gmh5225/gvmp-anticheat)
- [Cheat developer platform](https://github.com/gmh5225/UAC)
- https://github.com/gmh5225/Anti-Cheat-TestBench [TestBench]
- https://github.com/gmh5225/Malicious-code-detection-bugu [Malicious code detection and obfuscation]
- [Kernel Security driver used to block past, current and future process injection techniques on Windows Operating System](https://github.com/gmh5225/pi-defender)
- https://github.com/gmh5225/Anticheat-android-cheap-engine [Sample implementation of anti-cheat in android]
- [Proof of concept Anti-Cheat plugin for CS:GO](https://github.com/gmh5225/CSGO-AC)
- [Deep Learning Anti-Cheat For CSGO](https://github.com/gmh5225/DLAC)
- [Deep Learning Anti-Cheat For CSGO](https://github.com/gmh5225/anti-cheat)
- https://github.com/gmh5225/anti-cheat
- https://github.com/gmh5225/ice9
- https://github.com/gmh5225/Reborn [Designed with Rust]
- https://github.com/gmh5225/Dynsec
- https://github.com/gmh5225/Basic_Anti-Cheat
- https://github.com/MegaAntiCheat
- https://github.com/gmh5225/ac
- https://github.com/gmh5225/AcDrv
- https://github.com/gmh5225/Mandragora [For Assault Cube]
- https://github.com/gmh5225/Little-Anti-Cheat [For Source Games]
- https://github.com/gmh5225/darken-anticheat [Kernel anti-cheat for protecting software]

> Analysis Framework
- https://github.com/gmh5225/pandora

> Detection:Hook
- https://github.com/gmh5225/pe-sieve
- https://github.com/mike1k/HookHunter
- https://github.com/gmh5225/hook-buster
- https://github.com/gmh5225/Driver-Detect-nullshit
- https://github.com/gmh5225/EtwTi-Syscall-Hook [Instrumentation Callback]
- https://github.com/gmh5225/device-control-hooks-scanner [device-control-hooks-scanner]
- https://github.com/gmh5225/KnownDllUnhook [Replace the .txt section of the current loaded modules from \KnownDlls\]
- https://github.com/gmh5225/nt_unhooker [demo unhooking functions in ntdll]

> Detection:Memory Integrity
- https://github.com/gmh5225/integrity
- https://github.com/gmh5225/QueryWorkingSetExample
- https://github.com/gmh5225/integrity_experiments [header only]
- https://github.com/DejavuSecure/DetectNtoskrnlIntegrity [Windows Kernel Security: Memory Integrity Verification with Disk Verification of ntoskrnl.exe]
- https://github.com/MatheuZSecurity/ksentinel [Linux kernel integrity monitor for detecting syscall hooking]

> Detection:ShellCode
- https://github.com/gmh5225/EtwTi-FluctuationMonitor [ETW]
- https://github.com/gmh5225/Etw-SyscallMonitor [ETW]
- https://github.com/gmh5225/CFG-FindHiddenShellcode [CFG]

> Detection:Attach
- https://github.com/gmh5225/Detect-KeAttachProcess

> Detection:Triggerbot & Aimbot
- https://github.com/gmh5225/Detect-MouseClassServiceCallback
- https://github.com/gmh5225/MouHidInputHook
- https://github.com/KelvinMsft/UsbMon
- https://github.com/gmh5225/DeepAimDetector [Deep Learning]
- https://github.com/gmh5225/waldo [Deep Learning]
- https://github.com/gmh5225/aimbot-detection-prototype [Deep Learning]
- https://github.com/gmh5225/anti-cheat [Deep Learning for CSGO]
- https://github.com/gmh5225/Karlann [Keyboard]
- https://github.com/gmh5225/HotkeybasedKeyloggerDetector [Detect RegisterHotKey API]
- https://github.com/gmh5225/MouseDetection [Mouse]
- https://github.com/chrisgdt/DELBOT-Mouse [Deep learning to distinguish human and bot from mouse movements]
- https://github.com/gmh5225/EtwKeyboardDetection [ETW]

> Detection:Hide
- https://github.com/gmh5225/Detect-HiddenThread-via-KPRCB
- https://github.com/gmh5225/Anti-Cheat-TestBench [KPRCB+PTE]
- https://github.com/gmh5225/SystemThreadFinder
- https://github.com/gmh5225/HiddenModuleDetector
- https://github.com/KelvinMsft/ThreadSpy
- https://github.com/gmh5225/Nomad [Mapped Driver]
- https://github.com/gmh5225/ModFinder [Mapped Dll]
- https://github.com/gmh5225/NMIStackWalk [Mapped Driver by NMI Callback]
- https://github.com/gmh5225/nmi-callback-handler [Mapped Driver by NMI Callback]
- https://github.com/gmh5225/Kernel_Anti-Cheat [NMI]
- https://github.com/gmh5225/modreveal [Find hidden Linux kernel modules]
- https://github.com/MatheuZSecurity/ksentinel [Linux kernel integrity monitor for detecting syscall hooking]
- https://github.com/gmh5225/Hidden-Thread-Finder [Detect hidden threads]
- https://github.com/gmh5225/StealthSytemThreadFinderBE [Detect hidden threads]
- https://github.com/gmh5225/unKover [Using NMI/APC to detect mapped drivers]
- https://github.com/gmh5225/Rootkit-2 [Using CsrRootProcess to detect hidden process]
- https://github.com/gmh5225/rootkit-detection-ebpf-time-trace [Detection of rootkit file hiding activities through analysis of shifts in kernel function execution times]

> Detection:Vulnerable Driver
- https://github.com/gmh5225/hygieia
- https://github.com/FaEryICE/MemScanner

> Detection:EFI Driver
- https://github.com/gmh5225/Detect-EFIGuard

> Detection: Hacked Hypervisor
- https://secret.club/2020/04/13/how-anti-cheats-detect-system-emulation.html
- https://github.com/helloobaby/Nmi-Callback [NMI Callback]
- https://github.com/gmh5225/ept-hook-detection [Detect EPT]
- https://github.com/gmh5225/rep_mov_ept_detecc [REP MOV based EPT detection]
- https://github.com/gmh5225/ermsb-meme [REP MOV based EPT detection]
- https://github.com/gmh5225/Detect-Hypervisor_detect_ring_0
- https://github.com/gmh5225/nohv
- https://github.com/gmh5225/Hypervisor-Detection
- https://github.com/gmh5225/VmdtStr [Detect VMMs with faulty handling of STR exit]
- https://github.com/gmh5225/hv-detect [Hypervisor IDT Detections (SIDT / LIDT)]
- https://github.com/gmh5225/Bloodhound [Various novel EPT/NPT hook detection mechanisms]

> Detection:Virtual Environments
- https://github.com/gmh5225/awesome-anti-virtualization [A curated list of awesome resources related to anti virtualization techniques]
- https://github.com/a0rtega/pafish
- https://github.com/gmh5225/Detection-Hyper-v [Hyper-v]
- https://github.com/gmh5225/Go-Detection-Hyper-v [Hyper-v]
- https://github.com/gmh5225/MAJESTY-technologies
- https://github.com/gmh5225/anticuckoo [Cuckoo]
- https://github.com/gmh5225/anti-emulator [Android Anti-Emulator]
- https://github.com/gmh5225/Android-Emulator-Detection [Android Anti-Emulator]
- https://github.com/gmh5225/Android-Emulator-Detection [Android Anti-Emulator]
- https://github.com/gmh5225/wsb-detect [Windows Sandbox ("WSB")]
- https://github.com/gmh5225/AntiDebug-AntiVM [Vbox]
- https://github.com/gmh5225/compact_vm_detector
- https://github.com/gmh5225/VMAware [VM detection library]
- https://github.com/gmh5225/conbeerlib [Android library for detecting Android virtual containers]
- https://github.com/gmh5225/hvdetecc [Collection of hypervisor detections]
- https://github.com/gmh5225/T-1 [T-1 is a shellcode loader that leverages ML techniques to detect VM environments]
- https://github.com/gmh5225/Anti-Sandbox [Detecting AnyRun sandbox]
- https://github.com/gmh5225/hv-detect [Hypervisor IDT Detections (SIDT / LIDT)]
- https://github.com/gmh5225/checkhv_um [CPUID leaf is explicitly defined for hypervisors to expose their presence and vendor ID; any honest vm stack should set this up]

> Detection:HWID
- [All methods of retrieving unique identifiers(HWIDs) on your PC](https://www.unknowncheats.me/forum/anti-cheat-bypass/333662-methods-retrieving-unique-identifiers-hwids-pc.html)
- https://github.com/gmh5225/hwid-checker-mg
- https://github.com/weak1337/NvidiaApi
- https://github.com/gmh5225/WindowsHardwareInfo
- https://github.com/gmh5225/query-gpu-name-rs [GPU name for windows]
- https://github.com/gmh5225/osx-cpu-temp [CPU temperature for OSX]
- https://github.com/gmh5225/WinRing0 [CPU temperature for windows]
- https://github.com/gmh5225/openhardwaremonitor
- https://github.com/gmh5225/LibreHardwareMonitor
- https://github.com/gmh5225/hwinfo [cross platform C++ library for hardware information (CPU, RAM, GPU)]
- https://github.com/gmh5225/PCIBan [A PoC for requesting HWIDs directly from hardware]
- https://github.com/gmh5225/hvdetecc [Collection of hypervisor detections]
- https://github.com/gmh5225/tpm-mmio [Using MMIO (Memory-Mapped I/O) to read TPM 2.0 public Endorsement Key]
- https://github.com/gmh5225/Uncloaking-RAID0-HWID-Serials [Gather original disk serials hidden behind RAID0]
- https://github.com/gmh5225/windows-rapl-driver [Windows driver to get RAPL metrics from a bare metal machine]
- https://github.com/gmh5225/trustdevice-android [Android]
- https://github.com/gmh5225/DeviceWarLock [Android]
- https://github.com/gmh5225/trustdevice-ios [IOS]

> Detection:SpeedHack
- https://github.com/gmh5225/cheap-engine [Android]

> Detection:Injection
- https://github.com/gmh5225/DLLThreadInjectionDetector
- https://github.com/gmh5225/ModFinder [Mapped Dll]
- https://github.com/gmh5225/Driver-WatchOwl [ImageNotify+Stack Trace]
- https://github.com/gmh5225/TiEtwAgent [ETW]
- https://github.com/gmh5225/Demo [A demo app to detect (Zygisk) library injections]

> Detection:Spoof Stack
- https://github.com/gmh5225/ShadowStackWalk
- https://github.com/gmh5225/RASD

> Detection:ESP
- https://github.com/gmh5225/PresentHookDetection

> Detection:DMA
- https://github.com/gmh5225/DmaProtect [VT-d/AMD-Vi IOMMU]
- https://github.com/gmh5225/DieDMAProtection [IOMMU]
- https://github.com/gmh5225/HelloIommuPkg [The sample DXE runtime driver demonstrating how to program DMA remapping]
- https://github.com/gmh5225/drvscan [Scanner]
- https://github.com/gmh5225/PCIE-Detector [Config Space]

> Detection:Wall Hack
- https://github.com/gmh5225/CornerCulling
- https://github.com/gmh5225/CornerCullingSourceEngine

> Detection:Obfuscation
- https://github.com/gmh5225/obfuscation_detection

> Detection:Android root
- https://github.com/gmh5225/detection [Collection of Various Root Detection Apps for Android]
- https://github.com/gmh5225/KeyAttestation [Bootloader]
- https://github.com/gmh5225/KeyAttestation [Bootloader]
- https://github.com/gmh5225/Android-Native-Root-Detector [A tool for detecting root on android]
- https://github.com/gmh5225/MemDetection [Calculate the CRC of libc.so and libart.so in memory and compare it with the file]
- https://github.com/gmh5225/RootAppDetector [Small POC code that detects known root-related apps by attempting to launch their activities and monitoring security exception]
- https://github.com/gmh5225/meowna_detector [Prove of concept of detecting meowna module]

> Detection:Magisk
- https://github.com/gmh5225/MagiskDetector
- https://github.com/gmh5225/MagiskKiller
- https://github.com/gmh5225/ApplistDetector
- https://github.com/gmh5225/MagiskDetection
- https://github.com/canyie/MagiskEoP [exploit]
- https://github.com/gmh5225/Demo [A demo app to detect (Zygisk) library injections]
- https://github.com/gmh5225/DetectZygisk [A POC to detect zygisk]

> Detection:Frida
- https://github.com/gmh5225/DetectFrida
- https://github.com/gmh5225/AntiFrida
- https://github.com/gmh5225/frida-detection
- https://github.com/gmh5225/Anti-Frida [Some Of Anti-Frida Stuff]

> Detection:Overlay
- https://github.com/gmh5225/TOPMOST-Detection [Detect simple top most windows]
- https://github.com/gmh5225/android-overlay-protection [Android]

> Signature Scanning
- https://github.com/gmh5225/binlex
- https://github.com/gmh5225/aho-corasick

> Information System & Forensics
- https://lolc2.github.io [collection of C2 frameworks that leverage legitimate services to evade detection]
- https://github.com/gmh5225/Qvoid-Token-Grabber
- https://github.com/gmh5225/dfirtriage
- https://github.com/gmh5225/LaZagne
- https://github.com/gmh5225/ntfstool
- https://github.com/gmh5225/ntfs-journal-viewer
- https://github.com/gmh5225/volatility
- https://github.com/gmh5225/volatility3
- [Decrypt and export browser password, including Chromium,Edge and Firefox](https://github.com/gmh5225/BrowserPasswordExportor)
- https://github.com/gmh5225/VolatileDataCollector
- https://github.com/gmh5225/netview
- https://github.com/gmh5225/USN
- https://github.com/gmh5225/SearchEx
- https://github.com/gmh5225/ANTfs
- https://github.com/gmh5225/ntfs-linker
- https://github.com/gmh5225/ntfs_parse
- https://github.com/gmh5225/PWF [Windows Forensics Training]
- https://github.com/gmh5225/Pillager [For exporting and decrypting useful data from target computer]
- https://github.com/gmh5225/windows-forensic-artifacts [Guide to the various Windows forensic artifacts]
- https://github.com/gmh5225/fibratus [Windows kernel exploration and tracing]
- https://github.com/gmh5225/grr [remote live forensics]
- https://github.com/gmh5225/FTK-imager-OSX [Forensics Tools For MAC OS X]
- https://github.com/gmh5225/DumpIt-mirror [DumpIt for windows]
- https://github.com/gmh5225/dumpit-linux [DumpIt for linux]
- https://github.com/gmh5225/sherloq [An open-source digital image forensic toolset]
- https://github.com/kyxiaxiang/CobaltStrikeBeaconCppSource [Out-of-the-box CobaltStrike Beacon source code use C++]
- https://github.com/gmh5225/BamboozlEDR [A comprehensive ETW (Event Tracing for Windows) event generation tool designed for testing and research purposes]
- https://github.com/gmh5225/TeleParser [Simple parser for Telegram chats and channels with lemmatizer. Writes data in JSON, CSV and MongoDB]

> Dynamic Script
- https://github.com/gmh5225/NtLua
- https://github.com/gmh5225/NtPhp
- https://github.com/gmh5225/minivm
- https://github.com/gmh5225/q3vm

> Kernel Mode Winsock
- https://github.com/gmh5225/libwsk [Kernel-Mode Winsock library]

> Fuzzer
- https://github.com/gmh5225/wtf

> OpenCV
- https://github.com/gmh5225/Rust-Auto-Weapon-Detection-OpenCV-Example

> Windows Ring3 Callback
- https://github.com/gmh5225/AlternativeShellcodeExec
- https://github.com/gmh5225/function-collections [A collection of PoCs to do common things in unconventional ways]
- https://github.com/gmh5225/IDLE-Abuse
- https://github.com/gmh5225/FlavorTown
- https://github.com/gmh5225/instrumentation_callbacks [Instrumentation Callback]
- https://github.com/gmh5225/beservice_intcallbacks [Instrumentation Callback]
- https://github.com/gmh5225/Hooking-via-InstrumentationCallback [Instrumentation Callback]
- https://github.com/gmh5225/EtwTi-Syscall-Hook [Instrumentation Callback]
- https://github.com/gmh5225/syscall-detect [Instrumentation Callback]
- https://github.com/gmh5225/anticheat-poc [Instrumentation Callback]
- https://github.com/gmh5225/InstrumentationCallbacks [Instrumentation Callback]
- https://github.com/gmh5225/NastyAlignment [Instrumentation Callback to handle unaligned access exceptions]
- [Register VEH by hooking RtlpCallVectoredHandlers](https://github.com/gmh5225/custom-VEH)
- [ATPMiniDump Callback](https://github.com/gmh5225/ATPMiniDump)
- https://github.com/gmh5225/readdirectorychanges [ReadDirectoryChangesW]
- https://github.com/gmh5225/dllnotif [DllNotification]
- https://github.com/gmh5225/LdrRegisterDllNotification-modify-testing [DllNotification]
- https://github.com/gmh5225/KiUserExceptionDispatcherHook [Hooking the Windows usermode exception handler]
- https://github.com/gmh5225/function-collections/tree/main/hijack_callbacks/vkAllocateMemory [vkAllocateMemory]
- https://github.com/gmh5225/function-collections/tree/main/hijack_callbacks/InternetSetStatusCallback [InternetStatusCallback]
- https://github.com/gmh5225/function-collections/tree/main/winapi_alternatives/NtAllocateMemoryEx [tprtdll.dll.NtAllocateVirtualMemoryEx]

> Windows Ring0 Callback
- https://github.com/gmh5225/kernel-callback-functions-list [Callback List]
- [Enumerate Callback](https://github.com/gmh5225/WinObjEx64/blob/7284d711b2eeebfd965713fc79353b9b76e23083/Source/WinObjEx64/extras/extrasCallbacks.c#L117)
- [ImageNotify Callback With RtlWalkFrameChain](https://github.com/gmh5225/PsImageNotifyRoutineSpamFilter)
- [SymlinkCallback](https://github.com/gmh5225/SymlinkCallback)
- https://github.com/gmh5225/PowerHook [Hooking KPRCB IdlePreselect]
- https://github.com/gmh5225/BamExtensionTableHook [bam!BampCreateProcessCallback]

> Winows User Dump Analysis
- https://github.com/gmh5225/udmp-parser

> Winows Kernel Dump Analysis
- https://github.com/gmh5225/Tool-DIYSystemMemoryDump [DIY Dump Type]
- https://github.com/gmh5225/kdmp-parser [Python 3 bindings]
- https://github.com/gmh5225/dumpulator [Emulating code in minidump files]
- https://github.com/gmh5225/symbolizer [Execution trace symbolizer]
- https://github.com/gmh5225/libmdmp [Minidump]
- https://github.com/gmh5225/miniDumpReader [Minidump]

> Sign Tools
- https://github.com/gmh5225/osslsigncode
- https://github.com/gmh5225/chainoffools [CVE]
- https://github.com/gmh5225/WDACTools [Decrypt p7b]
- https://github.com/utoni/PastDSE [Sign Leaked Cert]
- https://github.com/Jemmy1228/HookSigntool [Sign Leaked Cert]
- https://github.com/gmh5225/MagicSigner [Sign Leaked Cert]
- https://github.com/hzqst/FuckCertVerifyTimeValidity [Sign Leaked Cert]
- https://github.com/gmh5225/sign-expired [Sign Leaked Cert]
- https://github.com/gmh5225/SignToolEx [Sign Leaked Cert]

> Backup File
- https://github.com/guidoreina/minivers [Generates Backup Copies]

> Backup Drivers
- https://github.com/gmh5225/ezDrvBAK [Backup & restrore the Windows-Drivers]

> Black Signature
- https://github.com/gmh5225/BlackSignatureDriver
- https://github.com/gmh5225/MSFT_DriverBlockList
- https://github.com/gmh5225/CodeIntegrity-DriverBlocklist
- https://github.com/gmh5225/MS-Vulnerable-Driver-List [Convert Microsoft's blocklist to a hash list]

## Some Tricks
> Windows Ring0
- https://www.unknowncheats.me/forum/general-programming-and-reversing/495279-messagebox-kernel-mode.html [Msgbox]
- https://back.engineering/01/12/2020/ [Page Table Manipulation]
- https://git.back.engineering/_xeroxz/PSKP [PTE Hook]
- https://github.com/gmh5225/PageTableHook [PTE Hook]
- https://github.com/gmh5225/windows-kernel-pagehook [PTE Hook]
- https://github.com/gmh5225/Yumekage [PTE Hook]
- https://github.com/gmh5225/FastPFHook [PF Hook]
- https://github.com/gmh5225/be-injector [Attack COW]
- https://github.com/Compiled-Code/eac-mapper [Vulnerable MmCopyMemory]
- https://github.com/EBalloon/MmCopyMemory [Bypass MmCopyMemory]
- https://github.com/gmh5225/be-injector [Attack COW]
- https://github.com/gmh5225/Allocating-individual-pages [MmAllocateIndependentPagesEx]
- https://github.com/gmh5225/Hook-HvlSwitchVirtualAddressSpace [HvcallCodeVa]
- https://github.com/gmh5225/HookHvcallCodeVa [HvcallCodeVa]
- https://github.com/gmh5225/Driver-HypercallPageHook [HvcallCodeVa]
- https://github.com/gmh5225/HyperDeceit [HvcallCodeVa]
- https://github.com/gmh5225/CallMeWin32kDriver [Load your driver like win32k.sys]
- https://github.com/gmh5225/DSEDodge-Signed-Kernel-Driver [Leveraging PTT to defeat DSE]
- https://github.com/gmh5225/KSOCKET [Kernel Berkeley socket]
- https://github.com/gmh5225/windows-kernel-rs [Writing Windows kernel drivers in Rust]
- https://github.com/ekknod/smm [Smm cheat]
- https://github.com/gmh5225/KPDB [Parsing PDB in Driver]
- https://github.com/gmh5225/KPDB [Parsing PDB in Driver]
- https://github.com/gmh5225/FakeEnclave [A poc that abuses Enclave]
- https://github.com/gmh5225/LetMeGG [A POC about how to prevent windbg break]
- https://github.com/gmh5225/NotifyRoutineHijackThread [Hijack PspCreateThreadNotifyRoutine]
- [GetWindowName In Kernel Mode](https://www.unknowncheats.me/forum/anti-cheat-bypass/517022-getwindowname-kernel-mode.html)
- [GetWindowInfo In Kernel Mode](https://www.unknowncheats.me/forum/anti-cheat-bypass/519261-getwindowinfo.html)
- [Hook KdTrap(Windows global exception hander)](https://www.unknowncheats.me/forum/anti-cheat-bypass/500156-hook-kdtrap-windows-global-exception-hander.html) [Hook KdTrap]
- https://github.com/gmh5225/Hook-KdTrap [Hook KdTrap]
- https://github.com/gmh5225/AcDrv [Global exception/KdpDebugRoutineSelect]
- https://github.com/gmh5225/HookGuard [Global exception/KdpDebugRoutineSelect]
- https://github.com/gmh5225/AcDrv [SwapContext hook]
- https://github.com/gmh5225/HookSwapContext [SwapContext hook]
- https://github.com/gmh5225/Driver-SoulExtraction [Extracting cert information]
- https://github.com/gmh5225/CiDllDemo [Use ci.dll API for validating Authenticode signature of files]
- https://github.com/gmh5225/pedigest [Calculating the authenticode digest]
- https://github.com/gmh5225/Kernel-Special-APC-ReadProcessMemory [Kernel APC RPM]
- https://github.com/gmh5225/Bad-BugCheck-Old [BSOD]
- https://github.com/gmh5225/Bad-Bugcheck [BSOD]
- https://github.com/gmh5225/NoMoreBugCheck [BSOD]
- https://github.com/gmh5225/BugCheckHack [BSOD]
- https://github.com/gmh5225/BugCheck2Linux [BSOD]
- https://github.com/gmh5225/KmdfMandelcheck [BSOD]
- https://github.com/gmh5225/PiDqSerializationWrite-Example [PiDqSerializationWrite]
- https://github.com/gmh5225/enum_real_dirbase [Find real dirbase]
- https://github.com/backengineering/POC-ExFlushTb [A POC for monitoring Tb]
- https://github.com/Cr4sh/KernelForge [A library to develop kernel level Windows payloads for post HVCI era]
- https://gist.github.com/gmh5225/ab00f831ffdf4ef608ab3b6eb0d37250 [Create process from KernelMode via APC]
- https://github.com/gmh5225/Map-file-in-system-space [MiMapViewInSystemSpace]
- https://github.com/gmh5225/PwnedBoot [Using Windows' own bootloader as a shim to bypass Secure Boot]
- https://github.com/gmh5225/PowerHook [Hooking KPRCB IdlePreselect]
- https://github.com/gmh5225/IoCreateDriver [IoCreateDriver Implementation]
- https://github.com/brew02/BudgetEPT [Create stealthy, inline, EPT-like hooks using SMAP and SMEP]
- https://github.com/gmh5225/Smep-Bypass [Various techniques used to bypass SMEP in the Windows Kernel]
- https://github.com/gmh5225/CovertThread [Creating covert system threads on Windows by leveraging the page tables and IDT]


> Windows Ring3
- https://secret.club/2021/01/04/thread-stuff.html [Anti Debug]
- https://github.com/utoni/PastDSE [Sign Leaked Cert]
- https://github.com/Jemmy1228/HookSigntool [Sign Leaked Cert]
- https://github.com/gmh5225/MagicSigner [Sign Leaked Cert]
- https://github.com/hzqst/FuckCertVerifyTimeValidity [Sign Leaked Cert]
- https://github.com/gmh5225/sign-expired [Sign Leaked Cert]
- https://github.com/gmh5225/StealingSignatures [Stealing signatures from pe files]
- https://github.com/gmh5225/SigThief [Stealing signatures from pe files]
- https://github.com/gmh5225/SignatureKid [Stealing signatures from pe files]
- https://github.com/gmh5225/LazySign [Fake Cert]
- https://github.com/gmh5225/Limelighter [Fake Cert]
- https://github.com/gmh5225/chainoffools [Fake Cert]
- https://github.com/gmh5225/FakeSign [Fake Cert]
- https://github.com/gmh5225/MiniDumpWriteDumpPoC [Dump Memory]
- [A x64 Write-What-Where exploit+shellcode execution vulnerability](https://www.unknowncheats.me/forum/anti-cheat-bypass/503519-wwwaryasinject-x64-write-exploit-shellcode-execution-vulnerability.html)
- [Dll injection through code page id modification in registry](https://github.com/gmh5225/NlsCodeInjectionThroughRegistry)
- https://github.com/gmh5225/Etw-Syscall [ETW Syscall]
- https://github.com/gmh5225/SkipHook [Skip Hook]
- https://github.com/gmh5225/SetWindowHookEx [Using SetWindowHookEx for preinjected DLL's]
- [A tool for patching authenticode signed PE files (exe, dll, sys ..etc) without invalidating or breaking the existing signature](https://github.com/gmh5225/SigFlip)
- [Simple program to stream offsets for your game cheat](https://github.com/gmh5225/OffsetStreaming)
- https://github.com/gmh5225/HIGU_ntcall [Direct System Calls]
- https://github.com/gmh5225/LockFile-Poc [Lock File]
- https://github.com/gmh5225/IDontLikeFileLocks [Dump locked files by stealing memory-mapped section handle]
- [A kernel exploit leveraging NtUserHardErrorControl to elevate a thread to KernelMode and achieve arbitrary kernel R/W & more](https://github.com/gmh5225/ANGRYORCHARD)
- https://github.com/gmh5225/dll-encryptor [Able to stream a dll without touching your disk]
- [Running Shellcode Through EnumDisplayMonitors](https://marcoramilli.com/2022/06/15/running-shellcode-through-windows-callbacks/?utm_source=twitter&utm_medium=social&utm_campaign=ReviveOldPost)
- [open-source windows defender manager can disable windows defender permanently](https://github.com/gmh5225/defender-control)
- [Read Memory without ReadProcessMemory for Current Process](https://github.com/gmh5225/CReadMemory)
- [get process token whose integrity level is system and manipulate it to get privilege escalation](https://github.com/gmh5225/manipulating_token)
- [A library that meant to perform evasive communication using stolen browser socket](https://github.com/gmh5225/Venom)
- https://github.com/gmh5225/trinity [Fully disables & removes Windows Defender]
- https://github.com/gmh5225/Disable-Windows-Defender- [Disable Windows Defender]
- https://github.com/gmh5225/ShadowStackWalk [Finding Truth in the Shadows]
- https://github.com/gmh5225/r0ak [r0ak]
- https://github.com/gmh5225/Wizard-Loader [Abuse Xwizard.exe for DLL Side-Loading]
- https://github.com/gmh5225/shellcode-plain-sight [Hiding shellcode in plain sight within a large memory region]
- https://github.com/gmh5225/process-cloning [Clone process]
- https://github.com/backengineering/msrexec [Elevate arbitrary MSR writes to kernel execution]
- https://github.com/gmh5225/Dirty-Vanity [Abusing RtlCreateProcessReflection]
- https://github.com/gmh5225/ShimCacheParser [Shim Cache parser]
- https://github.com/gmh5225/pmctrace [Real-time collection of PMCs via ETW]
- https://github.com/gmh5225/EtwLeakKernel [Leaking kernel addresses from ETW consumers. Requires Administrator privileges]
- https://github.com/gmh5225/SecureGame [POC game using VBS enclaves to protect itself from cheating]
- https://github.com/gmh5225/moonwalk [find dll base addresses without PEB WALK]
- https://github.com/gmh5225/KiUserExceptionDispatcherHook [Hooking the Windows usermode exception handler]
- https://github.com/gmh5225/MountSystemPartition [Mounting the system partition on Windows]
- https://github.com/gmh5225/delete-self-poc [A way to delete a locked file, or current running executable, on disk]
- https://github.com/gmh5225/BootExecuteEDR [BootExecute EDR Bypass]
- https://github.com/gmh5225/Solemn [A command-line tool for Windows that automates adding drivers to the HVCI (HvciDisallowedImages) custom blocklist]
- https://github.com/gmh5225/CreateProcessAsPPL [This is the loader that supports running a program with Protected Process Light (PPL) protection functionality]
- https://github.com/gmh5225/WaryasSWHE [Usermode exploit to bypass any AC using a 0day shatter attack]
- https://github.com/gmh5225/VPGATHER [Using the peculiar behaviour of the VPGATHER instructions to determine if an address will fault before it is truly accessed]

> Linux
- https://github.com/gmh5225/RingReaper [Linux post-exploitation agent that uses io_uring to stealthily bypass EDR detection by avoiding traditional syscalls]

> Android
- https://github.com/gmh5225/bypassHiddenApiRestriction [Bypass hidden api restriction]
- https://github.com/gmh5225/AndroidHiddenApiBypass [Bypass hidden api restriction]
- https://github.com/gmh5225/ASCTool [Apk Signature Crack Tool]
- https://github.com/gmh5225/usbsn [USB serial number changer (root only)]
- https://github.com/gmh5225/Android-privilege-CVE-2022-20452-LeakValue [Privilege Escalation]
- https://github.com/tiann/KernelSU [A Kernel based root solution for Android GKI]
- https://github.com/MlgmXyysd/KernelSU_Debug [KernelSU modified for debugging]
- https://github.com/gmh5225/kernel-su-huawei-nova2 [KernelSU for huawei]
- https://github.com/gmh5225/android_kernel_huawei_hi6250-8_Exp [KernelSU for huawei]
- https://github.com/abcz316/SKRoot-linuxKernelRoot [Kernel root]
- https://github.com/Dr-TSNG/ZygiskOnKernelSU [Run Zygisk on KernelSU]


## Windows Security Features
- https://github.com/gmh5225/cet-research [CET]
- https://github.com/gmh5225/CET-win10 [CET]
- [HyperGuard](https://windows-internals.com/hyperguard-secure-kernel-patch-guard-part-1-skpg-initialization)
- https://github.com/gmh5225/QueryShadowStack [Shadow Stack]
- https://github.com/synacktiv/windows_kernel_shadow_stack [Shadow Stack]
- https://namazso.github.io/x86/html/INCSSPD_INCSSPQ.html [CET]
- https://techcommunity.microsoft.com/t5/windows-os-platform-blog/understanding-hardware-enforced-stack-protection/ba-p/1247815 [CET]
- https://reviews.llvm.org/rG21b25a1fb32ecd2e1f336123c2715f8ef1a49f97 [CET]
- https://www.osronline.com/article.cfm%5earticle=469.htm [SEH]


## WSL
- https://github.com/gmh5225/WSL
- https://github.com/gmh5225/WSL2-Linux-Kernel
- https://github.com/gmh5225/windows-subsystem-linux
- https://github.com/gmh5225/WSL2-Linux-Kernel-Rolling [Stable Kernel for WSL2]

## WSA
- https://github.com/gmh5225/How-to-download-and-install-WSA [Guide]
- https://github.com/gmh5225/wsa-kernel-build [Build WSA Kernel with Docker]
- https://github.com/gmh5225/win11_apk_installer
- https://github.com/gmh5225/MagiskOnWSA
- https://github.com/gmh5225/wsa_pacman
- https://github.com/gmh5225/WSA-Linux-Kernel
- https://github.com/gmh5225/BuildWSA
- https://github.com/gmh5225/MagiskOnWSALocal
- https://github.com/gmh5225/WSAPatch [Make WSA run on Windows 10]
- https://github.com/gmh5225/WSABuilds
- https://github.com/gmh5225/WSA-Kernel-SU [WSA with KernelSU]

## Windows Emulator
- https://github.com/gmh5225/winlator [Android application for running Windows applications with Wine and Box86/Box64]
- https://github.com/gmh5225/WinVisor [A hypervisor-based emulator for Windows x64 user-mode executables using Windows Hypervisor Platform API]
- https://github.com/momo5502/sogen [Windows User Space Emulator]
- https://github.com/gmh5225/emulator [Windows User Space Emulator]
- https://github.com/gmh5225/KUBERA [A x86 environment emulator for Windows user and kernel binaries]
- https://github.com/gmh5225/KDemu [A hybrid semi-emulated, semi-native Windows kernel driver emulator designed for advanced rootkit and anti-cheat analysis, addressing the limitations of existing emulation solutions]

## Linux Emulator
- https://github.com/gmh5225/felix86 [Run x86-64 programs on RISC-V Linux]

## Android Emulator
- https://github.com/Genymobile
- https://github.com/gmh5225/genymotion-kernel
- https://github.com/gmh5225/anbox
- https://github.com/gmh5225/android-emulator
- https://github.com/gmh5225/android-emulator-hypervisor-driver
- https://github.com/gmh5225/rudroid [Rust]
- https://github.com/gmh5225/qemu-gvm [QEMU]
- https://github.com/gmh5225/AERoot [Root]

## IOS Emulator
- https://github.com/ChefKissInc/qemu-apple-silicon

## Game Boy
- https://github.com/gmh5225/kevboy [Emulator]
- https://github.com/gmh5225/feather-gb [Emulator]
- https://github.com/chrismaltby/gb-studio [GB Studio]

## Nintendo Switch
- https://github.com/yuzu-mirror
- https://github.com/gmh5225/Ryujinx
- https://github.com/gmh5225/Nintendo-Switch-Emulator-yuzu
- https://github.com/gmh5225/yuzu-android
- https://github.com/gmh5225/yuzu-archive
- https://github.com/gmh5225/Yuzu-Backup
- https://github.com/gmh5225/nuzu [Yuzu based repository]
- https://github.com/gmh5225/hekate [A GUI based Nintendo Switch Bootloader]
- https://github.com/gmh5225/Atmosphere [Customized firmware]
- https://github.com/gmh5225/SE-tools [Memory hacking]
- https://github.com/gmh5225/nstool [General purpose read/extract tool]

## Xbox
- https://github.com/gmh5225/xemu [Xbox Emulator for Windows]
- https://github.com/gmh5225/xenia [Xbox 360 Emulator Research Project]
- https://github.com/wmarti/xenia-mac [MacOS Port of the Xbox 360 Emulator]
- https://github.com/rexdex/recompiler [Porting Xbox360 executables to Windows]
- https://github.com/gmh5225/collateral-damage [Kernel exploit for Xbox SystemOS using CVE-2024-30088]
- https://github.com/gmh5225/XenonDumper [Dumps files & data required to use the Xenon Xbox 360 Low Level Emulator]
- https://github.com/gmh5225/xbox360-emu [A xbox 360 emulator]

