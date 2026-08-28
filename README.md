# Awesome USD Projects and Resources with stars

Projects and resources relating to Pixar's [Universal Scene Description](http://openusd.org)

## Contents

* [USDZ]($USDZ)
* [Reference](#reference)
* [Tools](#tools)
* [Integrations](#integrations)
* [Samples](#samples)
* [Building](#building)
* [Distros](#distros)
* [Syntax Highlighters](#syntax-highlighters)
* [Hydra](#hydra)
* [Resolvers](#resolvers)

## USDZ

* [UsdSkel](https://github.com/pkanyuk/PkUsdUtils/blob/master/usdSkelAppleFixup.py) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2019-01-22 for Apple's ArKit
* [Apple's Reality Composer](https://developer.apple.com/documentation/realitykit/creating_3d_content_with_reality_composer/exporting_a_reality_composer_scene_to_usdz) exports scenes to USDZ
* [Sketchfab](https://sketchfab.com/blogs/community/sketchfab-adds-usdz-3d-file-conversion) has nearly a half million USDZ files available for download
* [USDZ at Apple](https://developer.apple.com/videos/play/wwdc2018/603/) WWDC 2018 presentation
* [Apple News](https://developer.apple.com/documentation/apple_news/arkit) USDZ files can be embedded in Apple News articles
* [ARKit](https://developer.apple.com/arkit/gallery/) USDZ format assets from Apple
* [Samples from FusionAR](https://www.fusionar.app/) USDZ format assets
* [GiDiOdev](http://gidiodev.altervista.org/joomla/) a few USDZ format assets

## Reference

* [USD Cookbook](https://github.com/ColinKennedy/USD-Cookbook) ⭐ 691 | 🐛 3 | 🌐 Mathematica | 📅 2024-08-17 Colin Kennedy's USD code and asset samples
* [openusd.org](http://openusd.org) The official website
* [USD Interest Google Group](https://groups.google.com/forum/#!forum/usd-interest)
* [Introductory Videos](http://graphics.pixar.com/usd/downloads.html) Several video presentations by Pixar
* [UsdSkel](http://graphics.pixar.com/usd/files/SkinningOM.md.html) All about skinning schemas for USD
* [USD based pipelines](https://vimeo.com/188191100) 2016 presentation on Pixar's use of USD in the pipeline
* [Using USD with Apple's technologies](https://developer.apple.com/videos/play/wwdc2017/610/) WWDC 2017 presentation
* [USD at UTS Animal Logic Academy](https://www.youtube.com/playlist?list=PLNUaMVwYjKk8QDlM8gQSLbl8jxLRgc7d6) video presentations
* \[<https://graphics.pixar.com/usd/docs/Simple-Shading-in-USD.html>] USD's preview material
* [Dreamworks USD Integration](https://research.dreamworks.com/wp-content/uploads/2020/01/Zero-to-USD-with-notes.pdf)
* [Luma USD Integration](https://beforesandafters.com/2020/05/25/how-does-usd-actually-get-used-at-a-vfx-studio/) Brief notes on Luma's pipeline

## Tools

* [gltf2usd](https://github.com/kcoley/gltf2usd) ⭐ 277 | 🐛 28 | 🌐 Python | 📅 2023-10-03 Convert gltf 2.0 files to USD
* [ptc2usd](https://github.com/virokannas/ptc2usd) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-01-04 Pixar PTC and Houdini JSON point cloud to USD converter
* [holopointer](https://github.com/virokannas/holopointer) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2021-01-06 Record from a Kinect USB device to USD (MacOS/Swift)
* [animated cubes script](https://groups.google.com/forum/#!topic/usd-interest/dj9tUT8NcpI) Generate an animated file for testing
* [USD Manager](http://www.usdmanager.org/) USD Manager by Dreamworks

## Integrations

* [Gaffer](https://github.com/GafferHQ/gaffer) ⭐ 1,089 | 🐛 361 | 🌐 Python | 📅 2026-08-28 USD is available for SceneReader node and SceneWriter node from v0.42.0.0
* [Maya](https://github.com/Autodesk/maya-usd) ⭐ 900 | 🐛 333 | 🌐 Wolfram Language | 📅 2026-08-27 Autodesk Maya plugin
* [Unity USD SDK](https://github.com/Unity-Technologies/usd-unity-sdk) ⭐ 524 | 🐛 48 | 🌐 C# | 📅 2024-11-25 Full C# bindings to the USD SDK
* [USD for Unity](https://github.com/unity3d-jp/USDForUnity) ⚠️ Archived USD and Alembic importer/exporter plugin for Unity
* [AL\_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) ⭐ 267 | 🐛 34 | 🌐 C++ | 📅 2019-11-04 Animal Logic's plugin (now unified with the Autodesk Maya plugin)
* [AL\_USDMaya](https://github.com/AnimalLogic/AL_USDMaya/wiki/Asset-Resolution-and-Version-Selection-at-Animal-Logic) ⭐ 267 | 🐛 34 | 🌐 C++ | 📅 2019-11-04 Animal Logic's Asset Resolution system
* [OpenWalter](https://github.com/rodeofx/OpenWalter) ⭐ 215 | 🐛 8 | 🌐 C++ | 📅 2019-04-13 Rodeo FX's USD plugin suite for Arnold, Houdini, Katana and Maya.
* [USD Qt](https://github.com/LumaPictures/usd-qt) ⭐ 171 | 🐛 5 | 🌐 Python | 📅 2023-10-10 Luma Pictures has created some reusable Qt widgets to work with USD
* [3ds Max](https://github.com/Autodesk/3dsmax-usd) ⭐ 94 | 🐛 16 | 🌐 C++ | 📅 2026-07-24 Autodesk 3ds Max plugin
* [Arnold](https://github.com/LumaPictures/usd-arnold) ⭐ 68 | 🐛 7 | 🌐 C++ | 📅 2020-09-22 Luma Pictures USD bridge for Arnold
* [SketchUp](https://github.com/drwave/usd-sketchup) ⭐ 66 | 🐛 13 | 🌐 C++ | 📅 2019-08-12 Dr. Wave's USD Sketchup plugin
* [UsdVol for Katana](https://github.com/UTS-AnimalLogicAcademy/usd-renderman) ⭐ 11 | 🐛 1 | 🌐 CMake | 📅 2025-03-10 UsdVol to Renderman bridge for Katana
* Apple's Finder and Preview application can display USD files natively
* [Aero](https://www.adobe.com/products/projectaero.html) Adobe's Project Aero
* [AL\_USDMaya](https://www.youtube.com/watch?v=RluuvOAXvnk) Presentation about the AL\_USDMaya workflow
* [Blender](https://code.blender.org/2019/07/first-steps-with-universal-scene-description/) Work in Progress Blender Exporter
* [Houdini](https://graphics.pixar.com/usd/docs/Houdini-USD-Plugins.html)
* [Katana](https://graphics.pixar.com/usd/docs/Katana-USD-Plugins.html)
* [Model I/O](https://developer.apple.com/documentation/modelio) Apple's Model I/O brings USD to Metal
* [Millefiori](https://www.mpc-rnd.com/millefiori-a-usd-based-sequence-editor/) MPC's USD based Sequence Editor
* [Multiverse](http://multi-verse.io/) Scene assembly, set dressing, and inter-op with DCC applications
* [nVidia RTX](https://www.nvidia.com/en-us/design-visualization/technologies/rtx) USD is supported for asset interchange on the RTX platform
* [SceneKit](https://developer.apple.com/documentation/scenekit) Apple's SceneKit can read and write USD files for native rendering on all Apple platforms
* [TiltBrush](https://docs.google.com/document/d/11ZsHozYn9FnWG7y3s3WAyKIACfbfwb4PbaS8cZ_xjvo/preview) TiltBrush v15 can export USD camera tracks
* [Unreal](https://github.com/epicgames/unrealengine) Unreal 4.18 includes a USD importer
* [Unity USD SDK](https://www.youtube.com/watch?v=FnKWixYmSRY) Presentation about the Unity USD SDK
* [Unity USD SDK](https://medium.com/@jcowles/unity-c-api-for-usd-6ea6a4282f03) Design notes on the Unity USD SDK's API
* [Unity USD SDK](https://blogs.unity3d.com/2019/03/28/pixars-universal-scene-description-for-unity-out-in-preview/) Details on using the Unity USD SDK
* [UsdView Live coding](https://groups.google.com/d/msg/usd-interest/w3-KivsOuTE/psDcH9p-AgAJ) Live Coding in USD

## Hydra

* [AMD ProRender](https://github.com/GPUOpen-LibrariesAndSDKs/RadeonProRenderUSD) ⭐ 243 | 🐛 43 | 🌐 C++ | 📅 2025-08-05 AMD ProRender raytracing Hydra delegate
* [Intel hdOSPRay](https://github.com/ospray/hdospray) ⚠️ Archived Hydra + Intel's Open-Source OSPRay interactive path tracer
* [Hydra Houdini](https://github.com/dreamworksanimation/dwa_usd_plugins) ⭐ 102 | 🐛 1 | 🌐 Python | 📅 2020-11-17 Dreamworks' Hydra plugin for Houdini
* [USD-tests](https://github.com/dboogert/USD-tests) ⭐ 30 | 🐛 0 | 🌐 C++ | 📅 2017-09-10 Examples for learning USD and Hydra APIs
* [Tutorials](https://github.com/dboogert/USD/tree/tutorials/extras/usd/tutorials/IETutorials) ⭐ 22 | 🐛 0 | 🌐 C++ | 📅 2018-07-21 Tutorials on using Hydra as a stand-alone render system
* [GTC 2015](http://on-demand.gputechconf.com/gtc/2015/presentation/S5327-Jeremy-Cowles.pdf) Jeremy Cowles' GTC2015 presentation introducing Hydra
* [HydraNSI](https://gitlab.com/3DelightOpenSource/HydraNSI) Usdview Hydra delegate for 3Delight NSI
* [Switch](https://github.com/VictorYudin/switch) Victor Yudin has built a game using Hydra as the render engine

## Samples

* [Samples from Nvidia](https://developer.nvidia.com/usd#sample)
* [Samples from Pixar](https://graphics.pixar.com/usd/downloads.html)

## Building

There are a variety of strategies for building USD.

* [Official USD repo](https://github.com/PixarAnimationStudios/USD) ⭐ 7,460 | 🐛 1,004 | 🌐 C++ | 📅 2026-08-27 The repo includes a robust build script that pulls canonical dependency sources, and can build for all supported platforms.
* [USD Build Club](https://github.com/vfxpro99/usd-build-club) ⭐ 232 | 🐛 3 | 🌐 Shell | 📅 2020-05-27 This is the most thorough and flexible method for building USD and all its dependencies for macOS and Windows. Dependencies are fetched from canonical sources.
* [Ubuntu scripts](https://github.com/tlorach/USD_build) ⭐ 14 | 🐛 1 | 🌐 Shell | 📅 2017-05-24
* [Rez](https://github.com/piratecrew/rez-usd) ⭐ 5 | 🐛 0 | 🌐 CMake | 📅 2021-02-07
* [RodeoFX's dependency builds](https://github.com/rodeofx/usd-deps) Includes tarred sources for USD dependencies at vfxplatform point revisions.

## Distros

* [Saturn](https://github.com/VictorYudin/saturn) ⭐ 122 | 🐛 1 | 🌐 Makefile | 📅 2020-05-21 Windows build recipes, and AppVeyor build of binaries.
* [Docker Container](https://github.com/AnimalLogic/docker-usd) ⭐ 79 | 🐛 4 | 🌐 Shell | 📅 2021-04-01
* [macOs, linux, windows](https://developer.nvidia.com/usd#binaries) nVidia has a distro, and Python3 bindings
* [Apple, macOS](https://developer.apple.com/go/?id=python-usd-library) Apple has a build availble here with USDZ tools

## Syntax Highlighters

* [PyCharm Plug-in](https://github.com/justint/usd-idea) ⭐ 51 | 🐛 5 | 🌐 Java | 📅 2023-07-28 (.usda)
* \[JetBrains] (<https://github.com/justint/usd-idea> ⭐ 51 | 🐛 5 | 🌐 Java | 📅 2023-07-28) A plugin for JetBrains IDEs; PyCharm, IntelliJ, etc.
* [Animal Logic VSCode Highlighting](https://github.com/AnimalLogic/AL_usd_vscode_extension) ⭐ 41 | 🐛 4 | 🌐 JavaScript | 📅 2023-11-15 (.usd, .usda, .usdc)
* [Syntax Highlighting](https://github.com/superfunc/usda-syntax) ⭐ 27 | 🐛 1 | 🌐 Emacs Lisp | 📅 2018-09-17 for vim, emacs & sublime (.usda)
* [Notepad++ Highlighter](https://github.com/AndrewHazelden/PIXAR-USD-Syntax-Highlighter) ⭐ 11 | 🐛 1 | 🌐 PHP | 📅 2022-10-28 (.usda)
* [Sublime Syntax Highlighter](https://github.com/davidlatwe/PixarUSD-Sublime) ⭐ 8 | 🐛 0 | 📅 2017-10-14 (.usd, .usda)
* [Animal Logic VSCode Highlighting at VS Marketplace](https://marketplace.visualstudio.com/items?itemName=AnimalLogic.vscode-usda-syntax)

## Resolvers

* [RodeoFX resolver](https://github.com/rodeofx/rdo_replace_resolver) ⭐ 68 | 🐛 3 | 🌐 C++ | 📅 2019-05-03 RodeoFX's Replace Resolver
* [URI resolver](https://github.com/LumaPictures/usd-uri-resolver) ⭐ 51 | 🐛 7 | 🌐 CMake | 📅 2023-08-24 by Luma Pictures
* [S3 URI resolver](https://github.com/westerndigitalcorporation/usd-s3-resolver) ⭐ 31 | 🐛 0 | 🌐 C++ | 📅 2018-11-26 Western Digital's S3 asset store resolver

## Contribute

Contributions are welcome - see the[contribution guidelines](contributing.md)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
