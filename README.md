# Vercidium Audio for Unity
A plugin for Vercidium Audio that enables compatibilty with Unity.

> [!IMPORTANT]  
> This plugin is under development and will be released soon.

## Requirements
This plugin requires the following:
- [Vecidium Audio SDK](https://vercidium.com)
- A Windows, Mac, Linux and/or Android build target
- Unity 2021.3 LTS+

## FAQ
- Q: Why does the C# SDK not work in Unity?
- A: The VAudio C# SDK was built in .NET 8, which only Unity 6.8+ supports, due to the scripting backend change from Mono to CoreCLR. Unity 6.7 LTS and below are stuck with the Mono runtime, which only supports up to .NET Standard 2.1, so the C SDK is used for those versions.


## Disclaimer
This project is not associated with Vercidium Audio or Vercidium in any way.<br>
By using this plugin, you agree to the [Vercidium Audio EULA](https://vercidium.com/eula).