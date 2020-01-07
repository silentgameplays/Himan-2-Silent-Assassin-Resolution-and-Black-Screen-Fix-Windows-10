# Himan-2-Black-Screen-and-Resolution-Fix

1.Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play

2.Go To Hitman 2 Silent Assassin Directory C:\Program Files (x86)\Steam\steamapps\common\Hitman 2 Silent Assassin

3.Download and paste the d3d8.dll into the Hitman 2 Silent Assassin directory

4.Find the Hitman2.ini file

5.(Optional)For a glitchless free experience limit your overall refresh rate for older games:
NVIDIA>Control Panel>Change Resolution to 60Hz

6.Use the following settings in Hitman2.ini file:

DefaultScene=AllLevels/Logos.gms

SoundDll SoundEngine.dll

ScriptDll SDL_Engine.dll

ScriptIfDll ScriptInterfaces.dll

DrawDll RenderD3D.dll

LocaleFile=Locale\English.xml

AutoDumpName ScreenDump0000.jpg

ColorDepth 32

ErrorLog error.log

EnableConsole

Anisotropy 1

Antialias 8

ShadowDetail 2

TextureResolution 0

UseDirectInputMouse

UseDirectInputKeyboard

HeroControlMode 1

MouseSpeed 0.848789

SpeechVolume 100

MusicVolume 88

SoundEffectsVolume 100

ConfigFile=Keyboard.cfg

DisablePolyLimit

UseEAX 1

NumSoundBuffers 16

DrawDistance 1.200000

LevelOfDetail 2

Subtitles 1

WeatherEffects 1

GammaValue 1.000000

DisableTrilinearFiltering 1

Resolution 1920x1080

DisableHWTnL 0

Window 1

EnableP5 1
