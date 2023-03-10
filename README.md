# Friday Night Funkin' - Untitled Engine
Based on [Psych](https://github.com/ShadowMario/FNF-PsychEngine)\
Made to improve on psych\
~~Stole ideas~~ Got inspired from [ImpostorV4](https://vsimpostor.com/ "Offical website") and [Forever Engine](a "No link")

## Customization:

if you wish to disable things like *Lua Scripts* or *Video Cutscenes*, you can read over to `Project.xml`

inside `Project.xml`, you will find several variables to customize Psych Engine to your liking

to start you off, disabling Videos should be simple, simply Delete the line `"VIDEOS_ALLOWED"` or comment it out by wrapping the line in XML-like comments, like this `<!-- YOUR_LINE_HERE -->`

same goes for *Lua Scripts*, comment out or delete the line with `LUA_ALLOWED`, this and other customization options are all available within the `Project.xml` file

## Credits:
PLEASE IF YOU USE THIS ENGINE FOR A MOD/FORK PLEASE CREDIT (＃°Д°)

### Psych Engine
* Shadow Mario - Psych Programmer
* RiverOaken - Artist
* Yoshubs - Psych Assistant Programmer

### Untitled engine
* TiredGui - Main/Only Programmer

### Special Thanks
* bbpanzu - Ex-Programmer (Psych)
* Yoshubs - New Input System (Psych)
* SqirraRNG - Crash Handler and Base code for Chart Editor's Waveform (Psych)
* KadeDev - Fixed some cool stuff on Chart Editor and other PRs (Psych)
* iFlicky - Composer of Psync and Tea Time, also made the Dialogue Sounds (Psych)
* PolybiusProxy - .MP4 Video Loader Library (hxCodec) (Psych)
* Keoiki - Note Splash Animations (Psych)
* Smokey - Sprite Atlas Support (Psych)
* Nebula the Zorua - LUA JIT Fork and some Lua reworks (Psych)
_____________________________________

# Features

## Attractive animated dialogue boxes:

![](https://user-images.githubusercontent.com/44785097/127706669-71cd5cdb-5c2a-4ecc-871b-98a276ae8070.gif)


## Mod Support
* Probably one of the main points of this engine, you can code in .lua files outside of the source code, making your own weeks without even messing with the source!
* Comes with a Mod Organizing/Disabling Menu.

## Cool new Chart Editor changes and countless bug fixes
![](https://github.com/ShadowMario/FNF-PsychEngine/blob/main/docs/img/chart.png?raw=true)
* You can now chart "Event" notes, which are bookmarks that trigger specific actions that usually were hardcoded on the vanilla version of the game.
* Your song's BPM can now have decimal values
* You can manually adjust a Note's strum time if you're really going for milisecond precision
* You can change a note's type on the Editor, it comes with two example types:
  * Alt Animation: Forces an alt animation to play, useful for songs like Ugh/Stress
  * Hey: Forces a "Hey" animation instead of the base Sing animation, if Boyfriend hits this note, Girlfriend will do a "Hey!" too.

## Multiple editors to assist you in making your own Mod
![Screenshot_3](https://user-images.githubusercontent.com/44785097/144629914-1fe55999-2f18-4cc1-bc70-afe616d74ae5.png)
* Working both for Source code modding and Downloaded builds!

## Credits menu
![Screenshot_1](https://user-images.githubusercontent.com/44785097/144632635-f263fb22-b879-4d6b-96d6-865e9562b907.png)
* You can add a head icon, name, description and a Redirect link for when the player presses Enter while the item is currently selected.

## Awards/Achievements
* The engine comes with 16 example achievements that you can mess with and learn how it works (Check Achievements.hx and search for "checkForAchievement" on PlayState.hx)

## Options menu:
* You can change Note colors, Delay and Combo Offset, Controls and Preferences there.
 * On Preferences you can toggle Downscroll, Middlescroll, Anti-Aliasing, Framerate, Low Quality, Note Splashes, Flashing Lights, etc.

## Other gameplay features:
* When the enemy hits a note, their strum note also glows.
* Lag doesn't impact the camera movement and player icon scaling anymore.
* Some stuff based on Week 7's changes has been put in (Background colors on Freeplay, Note splashes)
* You can reset your Score on Freeplay/Story Mode by pressing Reset button.
* You can listen to a song or adjust Scroll Speed/Damage taken/etc. on Freeplay by pressing Space.
* Camera moveing on note press
* Cool score color
* And more
