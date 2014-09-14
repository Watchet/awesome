>![zhaopuming](https://avatars0.githubusercontent.com/u/304143?v=2&s=15) [zhaopuming/awesome-d](https://github.com/zhaopuming/awesome-d)

# Awesome D
=========

  A curated list of awesome D frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

  I created this list so that when I needed something in the future, it would be easy to find. Most of the documents and links are collected from the [D forum](http://forum.dlang.org), the [D wiki](http://wiki.dlang.org), and the [D package repository](http://code.dlang.org). Exploring GitHub also helps as many of the libs are hosted there.

  If you know an interesting lib/app in D, please tell me by issue or a pull request :-).
## 目录

- [Awesome D](#awesome-d)
	- Basic Information
		- [Official Website](#official-website)
		- [People](#people)
		- [Organizations](#organizations)
	- Documents
		- [Books](#books)
		- [Tutorials](#tutorials)
		- [Blogs](#blogs)
		- [Articles](#articles)
		- [API Doc](#api-docs)
	- Language Related
		- [Package Management](#package-management)
		- [Compilers](#compilers)
		- [Build Tools](#build-tools)
		- [IDE](#ide)
		- [Lexers, Parsers, Generators](#exers-parsers-parser-generators)
		- [Preprocessors](#preprocessors)
	- Web Related
		- [Web Frameworks](#web-frameworks)
		- [Data&Serialization](#data-serialization)
	- Database
		- [Database clients](#database-clients)
	- GUI
		- [GUI Libs](#gui-libs)
	- Gaming
		- [Bindings](#game-bindings)
		- [Frameworks](#game-frameworks)
		- [Games](#games)
	- Video
		- [Applications](#video-appilcations)
	- Image Processing
		- [Applications](#image-processing)
	- Others
		- [Command Line](#command-line)
		- [Logging](#logging)
		- [Configuration](#configuration)

- [Other Awesome Lists](#other-awesome-lists)


## 官方网站

*Official Website URLs.*

* [dlang.org](http://dlang.org) - Official website for D.
* [wiki.dlang.org](http://wiki.dlang.org) - Official Wiki for D.
* [code.dlang.org](http://code.dlang.org) - Offical Library/Module Registry for D.
* [Github Organization](https://github.com/D-Programming-Language) - Official GitHub organization for D. Repo for all official D tools & code.
* [forum.dlang.org](http://forum.dlang.org/) - Official forum. Many interesting discussions occurring on a daily basis.
* [Language Specification](http://dlang.org/spec.html) - D programming language specification.
* [Issue tracking](https://issues.dlang.org/) - Official issue tracking/reporting system for D. If you find bugs in the D compiler and/or libraries, please come and report them!

## People

*The people that made D the language it is.*

* [Walter Bright](http://www.walterbright.com/) - Father of D. Walter Bright is the creator and first implementer of the D programming language and has implemented compilers for several other languages.
* [Andrei Alexandrescu, PhD](http://erdani.com/) - C++ guru. Author of *The D Programming Language* and *Modern C++ Design*. With Walter Bright, Andrei co-designed many important features of D and authored a large part of D's standard library. Andrei works as a research scientist in Facebook and is now actively envangelizing D in the organization.
* **YOU** - Please add your information if you've done something interesting in D. It is you, the awesome people that made D awesome. Also, I plan to make a request on the forum to *interview* all D contributors and complete this List.

## 组织

*Organizations that contribute to D projects.*

* [D Programming Language](https://github.com/D-Programming-Language) - Official Organiaztion, hosts DMD, phobos and other official tools and libs.
* [Facebook](https://github.com/facebook) - Facebook hosts a lot of libraries in many languages. Their contribution to D is the [warp](https://github.com/facebook/warp)--a preprocessor for C/C++ written in D, and [flint](https://github.com/facebook/flint)--an open-source lint program for C++.

* [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including:
	* OpenGL 3 (DerelictGL3),
	* Bgfx (DerelictBgfx),
	* ENet (DerelictENet),
	* SDL 2 (DerelictSDL2),
	* GLFW 3 (DerelictGLFW3),
	* OpenGLES (DerelictGLES),
	* Free Image (DerelictFI),
	* Assimp3 (DerelictASSIMP3),
	* libtheora (DerelictTheora),
	* libogg (DerelictOgg),
	* libvorbis (DerelictVorbis),
	* SFML 2 (DerelictSFML2),
	* libpq (DerelictPQ),
	* PhysicsFS (DerelictPHYSFS),
	* Open Dynamics Engine (DerelictODE),
	* Lua (DerelictLua),
	* DevIL (DerelictIL),
	* OpenAL (DerelictAL),
	* ALURE (DerelictALURE).
* [Circular Studios](https://github.com/Circular-Studios) - We are a group of game developers at Rochester Institute of Technology building games and game tech. Hosts [Dash](https://github.com/Circular-Studios/Dash), a 3D game engine written in D, and other related libs.
* [d-gamedev-team](https://github.com/d-gamedev-team) - An organization of gamedev related repos, including a D gamedev toolkit called [gfm](https://github.com/d-gamedev-team/gfm) and an [opengl tutorial in D](https://github.com/d-gamedev-team/opengl-tutorials).
* [EMSI](https://github.com/economicmodeling) - A Career building company that uses D as their main language. Hosts their opensource projects.
* [infognition](http://www.infognition.com/company.html) - Infognition is a self-funded and self-sustained company specializing in video processing and compression technologies for end-users and developers. They provide several opensource video related applications & tools written in D, hosted on [bitbucket](https://bitbucket.org/infognition). They are also porting their main product--[Video Enchanser](http://www.infognition.com/VideoEnhancer/) from C/C++ to D.

## 书籍
*D related books.*
* [TDPL](http://www.amazon.com/The-Programming-Language-Andrei-Alexandrescu/dp/0321635361/) - *The D Programming Language* by Andrei Alexandrescu.
* [Programming in D](http://ddili.org/ders/d.en/index.html) - A very detailed book about programming in D by Ali Çehreli  covering many areas of the language. Has a free online version and is suitable for beginners.
* [D Cookbook](http://www.packtpub.com/discover-advantages-of-programming-in-d-cookbook/book) - A recipe-packed reference guide filled with practical tasks that are concisely explained to develop and broaden the user's abilities with the D programming language. by Adam D. Ruppe. Here is an interesting [review of the book](http://www.bfilipek.com/2014/08/review-of-d-cookbook.html).

## 文档
*D related tutorials.*
* [Pragmatic D tutorial](http://qznc.github.io/d-tut/index.html) - This is a pragmatic introduction to the D Programming Language. by Andreas Zwinkau.
* [D Template Tutorial](https://github.com/PhilippeSigaud/D-templates-tutorial) - A tutorial dedicated to D Templates. Very good explanation about templates. Has pdf version. by Philippe Sigaud.
* [Component programming in D](http://www.drdobbs.com/architecture-and-design/component-programming-in-d/240008321) - An article written by Walter Bright that details how D's functional support leads to a flexible and beautiful component programming style.
* [Component programming with ranges](http://wiki.dlang.org/Component_programming_with_ranges) - A detailed blog post about how to do component programming in a idiomatic D way with ranges, with a full working example.
* [Functional image processing in D](http://blog.thecybershadow.net/2014/03/21/functional-image-processing-in-d/) - A very interesting tutorial about writing an image processing lib in D. Shows the power of D's templates/CTFE/Ranges/UFCS for functional style programming.
* [OpenGL tutorials](https://github.com/d-gamedev-team/opengl-tutorials) - OpenGL tutorials in D.

## 日志
*D related blogs.*

* [Planet D](http://planet.dsource.org) - A repository of co-authored D-specific blogs maintained by Vladimir Panteleev.

## 文档
*D related Aritcles.*

* [Purity in D](http://klickverbot.at/blog/2012/05/purity-in-d/) - An article that explains the design principles behind D's purity feature.
* [Hidden treasures in the D standard library](http://nomad.so/2014/08/hidden-treasure-in-the-d-standard-library/) - An article talking about several useful functions and templates in phobos.

## 包管理

*Libraries for package and dependency management.*

* [code.dlang.org](http://code.dlang.org/) - Official D library repository. Backed by dub.
* [dub](https://github.com/D-Programming-Language/dub) - Official package and build management system for D.


## 编译

*从源代码编译软件.*

* [dmd](https://github.com/D-Programming-Language/dmd) - The reference compiler for the D programming language. Stable, builds insanely fast, very good for learning and rapid prototyping/development. Currently implemented in C++, but is in the process of being converted to D.
* [ldc](https://github.com/ldc-developers/ldc) - The LLVM-based D compiler. Uses the DMD frontend and LLVM backend. Builds slower than dmd, but generates more optimized code than DMD. It supports all the target platforms of LLVM.
* [gdc](https://github.com/D-Programming-GDC/GDC) - GNU D Compiler. Use DMD frontend and GCC backend. Currently targets the most platforms due to the use of GCC. Generated code runs faster than DMD in most cases, on par with LDC. In the process of integration with the official GCC toolchain.
* [sdc](https://github.com/deadalnix/SDC) - The Stupid D Compiler. Written in D. Grows Smarter every day.
* [dil](https://code.google.com/p/dil/) - A compiler for the D programming language. Written in D.


## 编译工具

*管理项目和从源代码编译软件.*

* [dub](https://github.com/D-Programming-Language/dub) - De facto official package and build management system for D. Will be included officially soon.
* [scons-d](http://scons.org/) - Scons has built-in support for building D projects, thanks to Russel Winder.

## IDE

*集成开发环境.*

* [Mono-D](https://github.com/aBothe/Mono-D) - A D language addon for [Xamarin Studio](http://xamarin.com/)/[MonoDevelop](http://monodevelop.com). With dub support.
* [Visual D](https://github.com/D-Programming-Language/visuald) - Visual Studio extension for the D programming language.
* [DDT](http://code.google.com/p/ddt/) - Eclipse plugin for the D programming language.
* [DCD](https://github.com/Hackerpilot/DCD) - Independent auto-complete program for the D programming language. Could be used with editors like vim, emacs, sublime text, textadept, and zeus. See [editors support](https://github.com/Hackerpilot/DCD/tree/master/editors).


## 词法分析器，语法分析器，解析器生成器

* [libdparse](https://github.com/Hackerpilot/libdparse) - A D language lexer and parser, (possibly) future standard D parser/lexer.
* [Martin Nowak's Lexer](https://github.com/MartinNowak/lexer) - A lexer generator.
* [Mono-D's DParser](https://github.com/aBothe/D_Parser) - A D parser written in C# and used in Mono-D.
* [Pegged](https://github.com/PhilippeSigaud/Pegged) - A Parsing Expression Grammar (PEG) module written in D.
* [Goldie](https://bitbucket.org/Abscissa/goldie/wiki/Home) - Goldie Parsing System.
* [ctpg](https://github.com/youkei/ctpg) - Compile-Time Parser (with converter) Generator written in D.
* [dunnart](https://github.com/pwil3058/dunnart) - LALR(1) Parser Generator written in D.

## 预处理器

* [warp](https://github.com/facebook/warp) - A fast preprocessor for C and C++ used in facebook infrastructure. Written by Walter Bright.

## Web框架
*Full stack web frameworks.*
* [vibe.d](http://vibed.org/) - Asynchronous I/O Web Framework that doesn’t get in your way, written in D.
* [arsd](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's web framework.
* [cmsed](https://github.com/rikkimax/Cmsed) - A component library for Vibe that functions as a CMS.

## 数据序列化
*Json, XML, protobuf and other data serialization libs.*

* [vibe.data.json](http://vibed.org/api/vibe.data.json/) - JSON functions in Vibe.d. Currently the best implementation I used.
* [std.json](http://dlang.org/phobos/std_json.html) - D's standard library JSON module. Needs refinement.
* [dproto](https://github.com/msoucy/dproto) - Google Protocol Buffer support in D.



## 数据库客户端
*Clients and bindings to C bliencts for relational and nosql databases.*

* [vibe.d](https://github.com/rejectedsoftware/vibe.d) - Vibe.d has internal support for Redis and MongoDB, which are very stable. Soon, the database drivers will be separated into independent projects.
* [mysql-native](https://github.com/rejectedsoftware/mysql-native) - A MySQL client implemented in native D.
* [ddb](https://github.com/pszturmaj/ddb) - Database access for D2. Currently only supports PostgreSQL.
* [arsd](https://github.com/adamdruppe/arsd) - Adam D. Ruppe's library; in addition to a Web backend, it also has support for database access with database.d, sqlite.d, mysql.d and postgres.d.
* [ddbc](https://github.com/buggins/ddbc) - DDBC is a DB Connector for D language (similar to JDBC). HibernateD (see below) uses ddbc for database abstraction.
* [hibernated](https://github.com/buggins/hibernated) - HibernateD is an ORM for D (similar to [Hibernate](http://hibernate.org/)).
* [dvorm](https://github.com/rikkimax/Dvorm) - An ORM for D with Vibe support. Works with vibe.d and mysql-d, giving it the ability to access MongoDB and MySQL.

## 命令行
* [scriptlike](https://github.com/Abscissa/scriptlike) - Utility library to aid writing script-like programs in D.
* [todod](https://github.com/BlackEdder/todod) - Todod is a command line based todo list manager. It also has support for shell interaction based on [linenoise](https://github.com/antirez/linenoise).
* [d-colorize](http://code.dlang.org/packages/colorize) - A port of the ruby library [colorize](https://github.com/fazibear/colorize). It add some methods to set color, background color and text effect on console easier using ANSI escape sequences.
* [terminal.d](https://github.com/adamdruppe/arsd/blob/master/terminal.d) - Part of Adam Ruppe's [arsd](https://github.com/adamdruppe/arsd) library supporting cursor and color manipulation on the console.


## GUI 库
*Libraries for working with graphical user interface applications.*

* [GtkD](https://github.com/gtkd-developers/GtkD) - GtkD is a D binding and OO wrapper of GTK+. GtkD is actively maintained and is currently the most stable GUI lib for D.
* [DWT](https://github.com/d-widget-toolkit/dwt) - A library for creating cross-platform GUI applications. GWT is a port of the Java SWT library to D.
* [tkD](https://github.com/nomad-software/tkd) - GUI toolkit for the D programming language based on Tcl/Tk.

*Note*: You can also find a list of GUI libs on [wiki.dlang.org](http://wiki.dlang.org/Libraries_and_Frameworks#GUI_Libraries), but not all of the libraries are actively maintained now.

## 游戏绑定

*Bindings to game development related C libraries.*

* [DerelictOrg](https://github.com/DerelictOrg) - A GitHub organization hosting all Derelict bindings including:
	* OpenGL 3 (DerelictGL3),
	* Bgfx (DerelictBgfx),
	* ENet (DerelictENet),
	* SDL 2 (DerelictSDL2),
	* GLFW 3 (DerelictGLFW3),
	* OpenGLES (DerelictGLES),
	* Free Image (DerelictFI),
	* Assimp3 (DerelictASSIMP3),
	* libtheora (DerelictTheora),
	* libogg (DerelictOgg),
	* libvorbis (DerelictVorbis),
	* SFML 2 (DerelictSFML2),
	* libpq (DerelictPQ),
	* PhysicsFS (DerelictPHYSFS),
	* Open Dynamics Engine (DerelictODE),
	* Lua (DerelictLua),
	* DevIL (DerelictIL),
	* OpenAL (DerelictAL),
	* ALURE (DerelictALURE).

## 游戏框架

* [DGame](https://github.com/Dgame/Dgame) - A 2D framework for the D programming Language. see <http://dgame-dev.de/>.
* [gfm](https://github.com/d-gamedev-team/gfm) - D gamedev toolkit. see <http://d-gamedev-team.github.io/gfm/>.
* [Dash](https://github.com/Circular-Studios/Dash) - A free and open 3D game engine written in D. see <http://circularstudios.com/dash>.


## 游戏

* [Spacecraft](https://github.com/Ingrater/Spacecraft) - A 3d multiplayer deathmatch space game written in D 2.0.

## 视频应用

## 图像处理

* [ArmageddonEngine](https://github.com/CyberShadow/ae/tree/master/utils/graphics) - Vladimir Panteleev's ae library has a package for image processing in functional style, which is described in the article [Functional Image Processing in D](http://blog.thecybershadow.net/2014/03/21/functional-image-processing-in-d/).
* [Blogsort](https://bitbucket.org/infognition/bsort/) -  A simple Windows app for viewing photos and preparing them for a blog.

## 日志
*Print with care.*

- [logger](https://github.com/burner/logger) - Phobos logger proposal.
- [dlogg](https://github.com/NCrashed/dlogg) - Logging for concurrent applications and daemons with lazy and delayed logging, [logrotate](http://linuxcommand.org/man_pages/logrotate8.html) support.

## 配置
*Parsing configuration files*

- [sdlang](https://github.com/Abscissa/SDLang-D) - An SDL (Simple Declarative Language) library for D.
- [D:YAML](https://github.com/kiith-sa/D-YAML) - YAML parser and emitter for the D programming language.

## 其它 Awesome 列表
Other amazingly awesome lists can be found in the [awesome-awesome](https://github.com/emijrp/awesome-awesome) and  [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) projects.

