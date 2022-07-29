# Singularity
Mod Loader for all games using the Unity engine

# 3 ways the mod loader works
## 1. Modify unity assembly
* Mono only, il2cpp X
* Compatible with all platforms (Windows, Linux, Mac)
* ex) UnityModManager

## 2. Edit [RuntimeInitializeOnLoads](https://docs.unity3d.com/ScriptReference/RuntimeInitializeOnLoadMethodAttribute.html).json
* Mono O, il2cpp, I don't know if it runs properly in il2cpp, maybe yes
* Compatible with all platforms (Windows, Linux, Mac)

## 3. Using APIs used by Unity
version.dll is the Windows API used by Unity
* Compatible with both Mono and il2cpp
* Windows Only, Linux X, Max X
* ex) BepinEx, MelonLoader



# How do Singularity work?





