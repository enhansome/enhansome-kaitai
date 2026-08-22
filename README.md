# Awesome Kaitai with stars

A curated list of Kaitai Struct tools and resources

* [Main Website](https://kaitai.io/) ([Umbrella Repository](https://github.com/kaitai-io/kaitai_struct) ⭐ 4,660 | 🐛 526 | 🌐 Shell | 📅 2026-08-17, [Github Pages](https://github.com/kaitai-io/kaitai-io.github.io) ⭐ 5 | 🐛 5 | 🌐 HTML | 📅 2026-01-19, [Issues](https://github.com/kaitai-io/kaitai_struct/issues) ⭐ 4,660 | 🐛 526 | 🌐 Shell | 📅 2026-08-17)

## Compiler

* Kaitai Struct: compiler to translate .ksy => .cpp / .cs / .dot / .java / .js / .php / .pm / .py / .rb ([Repository](https://github.com/kaitai-io/kaitai_struct_compiler) ⭐ 656 | 🐛 74 | 🌐 Scala | 📅 2026-05-04, [Releases](https://github.com/kaitai-io/kaitai_struct_compiler/releases) ⭐ 656 | 🐛 74 | 🌐 Scala | 📅 2026-05-04)
* [nimitai](https://github.com/sealmove/nimitai) ⭐ 19 | 🐛 0 | 🌐 Nim | 📅 2020-11-18: The compiler implemented as macro in Nimlang (.ksy => Nim AST)
* [kaitaigo](https://github.com/cugu/kaitaigo) ⚠️ Archived: alternative compiler to translate .ksy => .go, written in Golang

## Visualizers, IDEs, hex editors

### Arbitrary file formats

These tools allow to develop your own Kaitai Struct specifications in
iterative fashion by visualizing data locations in hex dump as one
develops .ksy.

* Hobbits ([Repository](https://github.com/Mahlet-Inc/hobbits) ⭐ 749 | 🐛 33 | 🌐 Python | 📅 2025-04-16)
* Kaitai Struct: visualizer and hex viewer tool ([Repository](https://github.com/kaitai-io/kaitai_struct_visualizer) ⭐ 340 | 🐛 18 | 🌐 Ruby | 📅 2025-10-21)
* [Kaitai Web IDE](https://ide.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_webide) ⭐ 317 | 🐛 94 | 🌐 TypeScript | 📅 2026-01-01, [Github Page](https://github.com/kaitai-io/ide-kaitai-io.github.io) ⭐ 20 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-19, [Wiki Documentation](https://github.com/kaitai-io/kaitai_struct_webide/wiki/Features) ⭐ 317 | 🐛 94 | 🌐 TypeScript | 📅 2026-01-01)
  * [webide-usercontent.kaitai.io](https://github.com/kaitai-io/webide-usercontent.kaitai.io) ⭐ 1 | 🐛 0 | 🌐 HTML | 📅 2017-07-12 - Used in sandboxing for the WebIDE
  * [Web IDE Docs](https://github.com/kaitai-io/kaitai_struct_webide_docs) ⭐ 0 | 🐛 0 | 📅 2017-09-20 - Images for the documentation
* Kaitai Struct: visualizer and hex viewer tool GUI in Java ([Repository](https://github.com/kaitai-io/kaitai_struct_gui) ⭐ 23 | 🐛 8 | 🌐 Java | 📅 2023-08-01, [Issues](https://github.com/kaitai-io/kaitai_struct_gui/issues) ⭐ 23 | 🐛 8 | 🌐 Java | 📅 2023-08-01)
* Kaitai Struct extension for VSCode ([Marketplace](https://marketplace.visualstudio.com/items?itemName=fudgepops.kaitai-struct-vscode), [Overview video](https://www.youtube.com/watch?v=4c7UuZ33JYE), [Repository](https://github.com/fudgepop01/fudgedit) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2023-08-03)
* [Development version of the IDE](https://ide.kaitai.io/devel/) ([Github Page](https://github.com/kaitai-io/ide-devel-kaitai-io.github.io) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2017-06-25)

### Fixed set of file formats

These visualizers / hex editors allow only fixed set of precompiled file
format specifications to be used.

* Veles ([Homepage](https://codisec.com/veles/), [Repository](https://github.com/codilime/veles) ⚠️ Archived)
* pytai ([Repository](https://github.com/Dvd848/pytai) ⭐ 133 | 🐛 2 | 🌐 Python | 📅 2025-09-24)
* Kaitai Struct plugin for Binary Ninja ([Repository](https://github.com/Vector35/kaitai) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2026-07-28)

## Tools

* [ksylint](https://github.com/kaitai-io/ksylint) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2021-08-15 - A linter for .ksy files
* [ksy-dl](https://github.com/tins2831/ksy-dl) ⭐ 6 | 🐛 6 | 🌐 Python | 📅 2021-11-01 - Downloads .ksy files and their dependencies straight from the official kaitai-struct format gallery.
* kaitaiStructCompile.py - Automate ksy compilation into python files ([Repository](https://gitlab.com/kaitaiStructCompile.py/kaitaiStructCompile.py))

### CI

#### Docker images

* [`registry.gitlab.com/kaitaistructcompile.py/kaitai_struct_python_docker:latest`](https://gitlab.com/kaitaiStructCompile.py/kaitai_struct_python_docker) - an image with [CPython](https://www.python.org/downloads/), [GraalVM](https://github.com/oracle/graal/releases) ⭐ 21,666 | 🐛 849 | 🌐 Java | 📅 2026-08-22, [GraalPython](https://github.com/oracle/graalpython) ⭐ 1,636 | 🐛 57 | 🌐 Python | 📅 2026-08-21, KSC, python runtime, `kaitaiStructCompile.py`, and its CLI backend. Unstable versions of the software are used. Currently Debian-based, but sometimes this will be migrated to Alpine.
* [`davefr/kaitai-ksc`](https://hub.docker.com/r/davefr/kaitai-ksc) — Kaitai Struct compiler in a container ([Repository](https://github.com/anonymousatc/kaitai-ksc) ⭐ 0 | 🐛 5 | 🌐 Dockerfile | 📅 2018-09-03)
* [`blacktop/kaitai`](https://hub.docker.com/r/blacktop/kaitai/)
* [`librespace/kaitai`](https://hub.docker.com/r/librespace/kaitai) — docker image of the kaitaistruct-compiler used in the Libre Space Foundation Database

## Converter

* Convert C to ksy file ([Snippet](https://gist.github.com/GreyCat/9dba530b0d2cb8ccec4e1d6e90a0b565))
* Convert Synalyze It! Grammars to ksy files ([Repository](https://gitlab.com/KOLANICH/synalysis2kaitai))
* Converting Kaitai structs to wireshark LUA plugins ([Repository](https://github.com/joushx/kaitai-to-wireshark) ⭐ 43 | 🐛 1 | 🌐 Lua | 📅 2022-04-07) - *deprecated*

## Formats

* [Kaitai Struct library of binary file formats](https://formats.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_formats) ⭐ 794 | 🐛 409 | 🌐 Kaitai Struct | 📅 2026-08-21, [Github Pages](https://github.com/kaitai-io/formats-kaitai-io.github.io) ⭐ 8 | 🐛 0 | 🌐 HTML | 📅 2026-08-20)
* APFS (apple file system) format ([Repository](https://github.com/cugu/apfs.ksy) ⚠️ Archived, [Issues](https://github.com/cugu/apfs.ksy/issues) ⚠️ Archived)
* EDID (VESA Enhanced Extended Display Identification Data) structure for Kaitai Struct ([Repository](https://github.com/kaitai-io/edid.ksy) ⭐ 8 | 🐛 0 | 🌐 Kaitai Struct | 📅 2021-07-11)
* Java bytecode spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/java_bytecode.ksy) ⭐ 7 | 🐛 0 | 🌐 Ruby | 📅 2020-11-23, [Issues](https://github.com/kaitai-io/java_bytecode.ksy/issues) ⭐ 7 | 🐛 0 | 🌐 Ruby | 📅 2020-11-23)
* DICOM (Digital Imaging and Communications in Medicine) file format spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/dicom.ksy) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2019-10-09, [Issues](https://github.com/kaitai-io/dicom.ksy/issues) ⭐ 3 | 🐛 0 | 🌐 Ruby | 📅 2019-10-09)
* Windows resource file spec for Kaitai Struct ([Repository](https://github.com/kaitai-io/windows_resource_file.ksy) ⭐ 2 | 🐛 0 | 📅 2019-10-09, [Issues](https://github.com/kaitai-io/windows_resource_file.ksy/issues) ⭐ 2 | 🐛 0 | 📅 2019-10-09)

## Help, Documentation & Community

* [Kaitai Struct Documentation](https://doc.kaitai.io/) ([Repository](https://github.com/kaitai-io/kaitai_struct_doc) ⭐ 18 | 🐛 9 | 🌐 CSS | 📅 2026-04-25, [Github Pages](https://github.com/kaitai-io/doc-kaitai-io.github.io) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-04-25)
* [Stackoverflow](https://stackoverflow.com/questions/tagged/kaitai-struct)
* [Gitter channel](https://app.gitter.im/#/room/#kaitai_struct_Lobby:gitter.im)
* [Official Twitter account](https://twitter.com/kaitai_io)

## Runtimes

* Python ([Repository](https://github.com/kaitai-io/kaitai_struct_python_runtime) ⭐ 107 | 🐛 14 | 🌐 Python | 📅 2026-08-08, [Issues](https://github.com/kaitai-io/kaitai_struct_python_runtime/issues) ⭐ 107 | 🐛 14 | 🌐 Python | 📅 2026-08-08)
  * [PyPI package](https://pypi.org/project/kaitaistruct/)
* C++ using STL ([Repository](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime) ⭐ 92 | 🐛 18 | 🌐 C++ | 📅 2026-08-20, [Issues](https://github.com/kaitai-io/kaitai_struct_cpp_stl_runtime/issues) ⭐ 92 | 🐛 18 | 🌐 C++ | 📅 2026-08-20)
* Go ([Repository](https://github.com/kaitai-io/kaitai_struct_go_runtime) ⭐ 89 | 🐛 5 | 🌐 Go | 📅 2025-11-14, [Issues](https://github.com/kaitai-io/kaitai_struct_go_runtime/issues) ⭐ 89 | 🐛 5 | 🌐 Go | 📅 2025-11-14)
* Rust ([Repository](https://github.com/kaitai-io/kaitai_struct_rust_runtime) ⭐ 78 | 🐛 6 | 🌐 Rust | 📅 2025-11-14, [Issues](https://github.com/kaitai-io/kaitai_struct_rust_runtime/issues) ⭐ 78 | 🐛 6 | 🌐 Rust | 📅 2025-11-14)
* C#/.NET ([Repository](https://github.com/kaitai-io/kaitai_struct_csharp_runtime) ⭐ 71 | 🐛 4 | 🌐 C# | 📅 2026-04-17, [Issues](https://github.com/kaitai-io/kaitai_struct_csharp_runtime/issues) ⭐ 71 | 🐛 4 | 🌐 C# | 📅 2026-04-17)
  * [NuGet package](https://www.nuget.org/packages/KaitaiStruct.Runtime.CSharp/)
* Java ([Repository](https://github.com/kaitai-io/kaitai_struct_java_runtime) ⭐ 51 | 🐛 15 | 🌐 Java | 📅 2026-08-08, [Issues](https://github.com/kaitai-io/kaitai_struct_java_runtime/issues) ⭐ 51 | 🐛 15 | 🌐 Java | 📅 2026-08-08)
  * [Java .jar package at Maven Central](https://search.maven.org/artifact/io.kaitai/kaitai-struct-runtime)
* JavaScript ([Repository](https://github.com/kaitai-io/kaitai_struct_javascript_runtime) ⭐ 43 | 🐛 7 | 🌐 JavaScript | 📅 2026-07-30, [Issues](https://github.com/kaitai-io/kaitai_struct_javascript_runtime/issues) ⭐ 43 | 🐛 7 | 🌐 JavaScript | 📅 2026-07-30)
  * Webpack loader for kaitai-struct .ksy definitions ([Repository](https://github.com/kaitai-io/kaitai_struct_loader) ⭐ 9 | 🐛 13 | 🌐 JavaScript | 📅 2026-04-08, [Issues](https://github.com/kaitai-io/kaitai_struct_loader/issues) ⭐ 9 | 🐛 13 | 🌐 JavaScript | 📅 2026-04-08)
  * Examples ([Repository](https://github.com/kaitai-io/kaitai_struct_examples) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2017-08-09)
  * [npm package](https://www.npmjs.com/package/kaitai-struct)
* Lua ([Repository](https://github.com/kaitai-io/kaitai_struct_lua_runtime) ⭐ 23 | 🐛 12 | 🌐 Lua | 📅 2026-05-02, [Issues](https://github.com/kaitai-io/kaitai_struct_lua_runtime/issues) ⭐ 23 | 🐛 12 | 🌐 Lua | 📅 2026-05-02)
* Ruby ([Repository](https://github.com/kaitai-io/kaitai_struct_ruby_runtime) ⭐ 19 | 🐛 2 | 🌐 Ruby | 📅 2026-08-04, [Issues](https://github.com/kaitai-io/kaitai_struct_ruby_runtime/issues) ⭐ 19 | 🐛 2 | 🌐 Ruby | 📅 2026-08-04)
  * [Ruby gem](https://rubygems.org/gems/kaitai-struct)
* PHP ([Repository](https://github.com/kaitai-io/kaitai_struct_php_runtime) ⭐ 13 | 🐛 1 | 🌐 PHP | 📅 2026-04-07, [Issues](https://github.com/kaitai-io/kaitai_struct_php_runtime/issues) ⭐ 13 | 🐛 1 | 🌐 PHP | 📅 2026-04-07)
* Nim ([Repository](https://github.com/kaitai-io/kaitai_struct_nim_runtime) ⭐ 10 | 🐛 0 | 🌐 Nim | 📅 2025-12-07, [Issues](https://github.com/kaitai-io/kaitai_struct_nim_runtime/issues) ⭐ 10 | 🐛 0 | 🌐 Nim | 📅 2025-12-07)
* Swift ([Repository](https://github.com/kaitai-io/kaitai_struct_swift_runtime) ⭐ 10 | 🐛 1 | 🌐 Swift | 📅 2019-10-03, [Issues](https://github.com/kaitai-io/kaitai_struct_swift_runtime/issues) ⭐ 10 | 🐛 1 | 🌐 Swift | 📅 2019-10-03)
* Perl ([Repository](https://github.com/kaitai-io/kaitai_struct_perl_runtime) ⭐ 6 | 🐛 1 | 🌐 Perl | 📅 2025-11-14, [Issues](https://github.com/kaitai-io/kaitai_struct_perl_runtime/issues) ⭐ 6 | 🐛 1 | 🌐 Perl | 📅 2025-11-14)

## Testing

* Tests for all languages ([Repository](https://github.com/kaitai-io/kaitai_struct_tests) ⭐ 17 | 🐛 42 | 🌐 Kaitai Struct | 📅 2026-05-04)
* Benchmarking suite ([Repository](https://github.com/kaitai-io/kaitai_struct_benchmarks) ⭐ 7 | 🐛 0 | 🌐 Kaitai Struct | 📅 2023-08-04)
* Compiled test files ([Repository](https://github.com/kaitai-io/ci_targets) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2026-07-30)
* [Test results](https://ci.kaitai.io/) ([Test Artifacts Repository](https://github.com/kaitai-io/ci_artifacts) ⭐ 0 | 🐛 0 | 📅 2026-07-27)

## Misc

* KaitaiFS: mount any filesystem specified with a .ksy as a real file system ([Repository](https://github.com/kaitai-io/kaitai_fs) ⭐ 58 | 🐛 7 | 🌐 Python | 📅 2023-10-13, [Issues](https://github.com/kaitai-io/kaitai_fs/issues) ⭐ 58 | 🐛 7 | 🌐 Python | 📅 2023-10-13)
* Compression processing libraries ([Repository](https://github.com/kaitai-io/kaitai_compress) ⭐ 11 | 🐛 10 | 🌐 Shell | 📅 2024-09-04)

## Other Resources

* <https://kaitai.io/workshop/>
* <https://avatao.com/blog-kaitai/>
* <https://archive.fosdem.org/2017/schedule/event/om_kaitai/> - Presentation on Kaitai from Mikhail Yakshin (GreyCat)
* <https://vaughanhilts.me/blog/2016/11/16/reverse-engineering-trails-in-the-sky-ed-6-game-engine.html>  - Blog post on game reverse engineering
* <https://pythonistac.wordpress.com/2017/03/09/python-network-packet-dissection-frameworks-shootout-scapy-vs-construct-vs-hachoir-vs-kaitai-struct/> - Blog post comparing different network packet dissection frameworks
* <https://medium.com/@MorteNoir/database-reverse-engineering-part-2-main-approaches-ae9355b2d429> - A blog post about reverse-engineering unknown file formats with a proprietary car parts database as an example.

## Similar projects / tools

* [construct](https://github.com/construct/construct) ⭐ 1,013 | 🐛 36 | 🌐 Python | 📅 2025-04-22 - Python library to create declarative parsers
* [bindata](https://github.com/dmendel/bindata) ⭐ 653 | 🐛 0 | 🌐 Ruby | 📅 2026-08-04 - Binary data parsing for Ruby
* <https://github.com/j3pic/lisp-binary> ⭐ 102 | 🐛 7 | 🌐 Common Lisp | 📅 2026-07-09 - A library to easily read and write complex binary formats (Common Lisp)
* <https://github.com/renyxa/re-lab/tree/master/oletoy> ⭐ 84 | 🐛 2 | 🌐 Python | 📅 2021-09-19
* <https://github.com/fox-it/dissect.cstruct> ⭐ 66 | 🐛 15 | 🌐 Python | 📅 2026-08-10
* <https://github.com/0xdabbad00/icebuddha> ⭐ 59 | 🐛 22 | 🌐 JavaScript | 📅 2014-11-14
* [BeeSchema](https://github.com/Michael-Kelley/BeeSchema) ⚠️ Archived - Binary Schema Library for C#
* <https://github.com/frodef/binary-types> ⭐ 41 | 🐛 5 | 🌐 Common Lisp | 📅 2024-05-08 - Read and write binary records for Common Lisp
* [vstruct2](https://github.com/vivisect/vstruct2) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2017-07-25 - Python structure definition and parsing library
* <https://github.com/padsproj/pads> ⭐ 22 | 🐛 1 | 🌐 C | 📅 2015-11-19
* [dtfabric](https://github.com/libyal/dtfabric) ⭐ 13 | 🐛 17 | 🌐 Python | 📅 2026-07-09
* [3D Model Researcher](http://mr.game-viewer.org/) - Studying binary files of 3D models

### Hex Editors

* [hecate](https://github.com/evanmiller/hecate) ⭐ 675 | 🐛 3 | 🌐 Go | 📅 2022-05-03 - Terminal hex editor
* [hexalepis](https://github.com/sealmove/hexalepis) ⭐ 7 | 🐛 0 | 🌐 Nim | 📅 2020-08-22 - Win/Unix gui+terminal, [tweak](https://www.chiark.greenend.org.uk/~sgtatham/tweak/btree.html) engine, .ksy visualization
* [Hexinator](https://hexinator.com/) - Windows Version of Synalyze It!
* [HxD](https://mh-nexus.de/de/hxd/) - Small, fast hex editor for Windows
* [iBored](https://apps.tempel.org/iBored/) - Cross-platform, sector based hex editor
* [Synalyze It!](https://www.synalysis.net/) - Hex editor with templates for binary analysis
* [wxHex Editor](https://www.wxhexeditor.org/) - Cross-platform editor with file comparison
* [Hex Editor Neo](https://www.hhdsoftware.com/hex-editor) - fast binary file editor for Windows (supports Kaitai Struct [in its Structure Viewer](https://hhdsoftwaredocs.online/hex/definitive-guide/structure-viewer/kaitai.html))

### File Grammars

* [Wireshark dissectors](https://github.com/wireshark/wireshark/tree/master/epan/dissectors) ⭐ 9,756 | 🐛 2 | 🌐 C | 📅 2026-08-22 - Parsers for Wireshark
* [Sleuth Kit file system grammars](https://github.com/sleuthkit/sleuthkit/tree/develop/tsk/fs) ⭐ 3,135 | 🐛 475 | 🌐 C | 📅 2026-08-19 - Grammars for different file systems
* [TestDisk grammars](https://github.com/cgsecurity/testdisk/tree/master/src) ⭐ 2,537 | 🐛 92 | 🌐 C | 📅 2026-08-19 - Grammars used by TestDisk and PhotoRec
* [Construct formats](https://github.com/construct/construct/tree/master/deprecated_gallery) ⭐ 1,013 | 🐛 36 | 🌐 Python | 📅 2025-04-22 - Parser for different file formats for the python construct package
* [HFSPlus Grammars](https://github.com/mac4n6/HFSPlus_Resources/tree/master/HFSPlus_Grammars) ⭐ 38 | 🐛 0 | 📅 2015-11-15 - HFS+ grammars for Synalysis
* [010 Editor Templates](https://www.sweetscape.com/010editor/templates/) - Templates for the 010 Editor
* [iBored Templates](https://apps.tempel.org/iBored/#:~:text=fix%20them%20ASAP.%29-,Templates,-Some%20data%20is) - Templates are packed inside the .app
* [Synalyse It! Grammars](https://www.synalysis.net/formats.xml) - File type grammars for the Synalyze It! editor
* [WinHex Templates](https://www.x-ways.net/winhex/templates/) - Grammars for the WinHex editor and X-Ways

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-22._
