# ActionRoguelike

# Unreal Engine 5.0
The new engine for Unreal is out. 5.0 adds a lot of new features to an already really impressive and great engine. Some of the new features involve rendering which are enabled by default. On a lower end machine it is required to turn these off. You can do this through the Project Settings
or the config INI file.

## DefaultEngine.ini
```ini
r.ReflectionMethod-1 ;lumen reflection
r.GenerateMeshDistanceFields=True
r.DynamicGlobalIlluminationMethod=1 ;lumen global illumination
r.Shadow.Virtual.Enable-1 ;virtual shadow maps

[/Script/WindowsTargetPlatform.WindowsTargetSettings]
DefaultGraphicsRHI-DefaultGraphicsRHI_DX12 // Forcing to use DX12 for improved performance

Game Assets: Licensed for use with the Unreal Engine only. Without a custom license you cannot use to create sequels, remasters, or otherwise emulate the original game or use the original game's trademarks, character names, or other IP to advertise or name your game. (Unreal Engine EULA applies)
(Please note this applies to the Game Assets that refer to Epic's Paragon, you can still use the project code and content to build your own Unreal Engine game)
