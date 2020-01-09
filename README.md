# Himan-2-Black-Screen-and-Resolution-Fix

1.Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play

2.Go To Hitman 2 Silent Assassin Directory C:\Program Files (x86)\Steam\steamapps\common\Hitman 2 Silent Assassin

3.Find the Hitman2.ini file

4.Download and paste the d3d8.dll into the Hitman 2 Silent Assassin directory.

Use the following settings in Hitman2.ini file(also in this repository,so you can just copy/paste):


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


