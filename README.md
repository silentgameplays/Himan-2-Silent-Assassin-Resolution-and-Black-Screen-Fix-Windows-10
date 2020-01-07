# Himan-2-Black-Screen-and-Resolution-Fix

1.Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play

2.Go To Hitman 2 Silent Assassin Directory C:\Program Files (x86)\Steam\steamapps\common\Hitman 2 Silent Assassin

3.Find the Hitman2.ini file

4.(Optional)For a glitchless free experience limit your overall refresh rate for older games:
NVIDIA>Control Panel>Change Resolution to 60Hz

5.For Windows 10 (1909) Use the following settings in Hitman2.ini file:

SoundDll SoundEngine.dll
ScriptDll SDL_Engine.dll
ScriptIfDll ScriptInterfaces.dll
DrawDll RenderOpenGL.dll

Resolution 1920x1080
DisableHWTnL 0
Window 1

6.For Windows 10 (1809) and other versions where you experience black models of main character with OpenGL

1.Download and paste the d3d8.dll into the Hitman 2 Silent Assassin directory.

2.Use the following settings in Hitman2.ini file:

SoundDll SoundEngine.dll
ScriptDll SDL_Engine.dll
ScriptIfDll ScriptInterfaces.dll
DrawDll RenderD3D.dll

Resolution 1920x1080
DisableHWTnL 0
Window 1



