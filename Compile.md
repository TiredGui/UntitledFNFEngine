## Installation:
### Automatic
Just run `art/setup.bat`\
Make sure to check this(and other batch scripts you run) for weird commands (Stay safe :D)\
Might make a linux/bash version

### Manual
Install [Haxe](https://haxe.org/) and [Git](https://git-scm.com/) if you do not already have them\
Then run (CASE SENSITIVE) 
```properties <!--wow terminal-->
haxelib install hxcpp > nul
haxelib install lime
haxelib install openfl
haxelib --never install flixel
haxelib run lime setup flixel
haxelib run lime setup
haxelib install flixel-tools
haxelib install flixel-ui
haxelib install flixel-addons
haxelib install tjson
haxelib install hxjsonast
haxelib install hscript
haxelib install hxcpp-debug-server
haxelib run flixel-tools setup
haxelib git polymod https://github.com/larsiusprime/polymod.git
haxelib git linc_luajit https://github.com/nebulazorua/linc_luajit
haxelib git hscript-ex https://github.com/ianharrigan/hscript-ex
haxelib git discord_rpc https://github.com/Aidan63/linc_discord-rpc
haxelib install hxCodec 2.5.1
```
To install all libraries.

Install visual studio with the components,
* Windows 10 SDK (10.0.19041.0)
* MSVC v143 - VS 20(19 or 22) x64/x86 build tools
I do not know how you compile to Mac/Linux though.

### Compiling
This is as easy as `lime test Windows` (windows)