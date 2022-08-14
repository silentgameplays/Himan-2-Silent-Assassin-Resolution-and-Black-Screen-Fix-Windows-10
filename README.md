# Himan-2-Black-Screen-and-Resolution-Fix
# NB! The creator of this fix is not responsible if something will go wrong during install,or for any issues that arise on your OS/hardware.This fix is distributed under GPL 3.0 license.This tutorial is meant for enthusiasts,tinkerers and gamers who want the the game to work and are not affraid to take the risk of learning some new stuff in the process.

0.For Steam versions only:

Go into C:\Program Files (x86)\Steam find a file Steam.dll and Copy/Paste it into your Hitman 2 Silent Assassin  directory 

1.Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play

2.Go To Hitman 2 Silent Assassin Directory C:\Program Files (x86)\Steam\steamapps\common\Hitman 2 Silent Assassin

3.Download,extract and paste the Hitman2.ini, d3d8.dll and wined3d.dll into the Hitman 2 Silent Assassin directory.

4.(Optional) Input the values provided below into the Hitman2.ini manually
* DefaultScene=AllLevels/Logos.gms

* SoundDll SoundEngine.dll
* ScriptDll SDL_Engine.dll
* ScriptIfDll ScriptInterfaces.dll
* DrawDll RenderD3D.dll

* LocaleFile=Locale\English.xml
* Resolution 1920x1080

* AutoDumpName ScreenDump0000.jpg
* ColorDepth 32
* ErrorLog error.log
* EnableConsole

* Anisotropy 0
* AntiAlias 0
* ShadowDetail 2
* TextureResolution 0
* UseDirectInputMouse
* UseDirectInputKeyboard
* HeroControlMode 1
* MouseSpeed 0.8

* SpeechVolume 100
* MusicVolume 88
* SoundEffectsVolume 100

* ConfigFile=Keyboard.cfg

* DisablePolyLimit
* UseEax 1
* Window 1

# 5.(Optional Line) for Multiple monitor setup
* StartUpperPos 0,0

# NB! If you are experiencing issues such as something glitching after installing this fix on top of other configurations and mods you need to do the following:

1. Uninstall game
2. Delete Hitman 2 Silent Assassin directory from C:\Program Files (x86)\Steam\steamapps\common\
3. Install the game again 
4. Apply the fix again

# NB for all the users,please report any issues to the issues section in the github repo,not on my gaming youtube channel under unrelated videos!
# Credit goes to silentgamepls


