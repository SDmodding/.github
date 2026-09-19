## Info
This GitHub organization is based around modding - [Sleeping Dogs: Definitive Edition](https://store.steampowered.com/app/307690/Sleeping_Dogs_Definitive_Edition/).

> [!TIP]
> - Compatibility game executable: [sdhdship.exe (Steam)](https://mega.nz/file/fK5SWARD#1fAWkxAHaKCIMDaJ5XAQKvjs6gK4RCQo5ZlvvtHWtVw)
> - Non-Steam Patch (GOG Version): [SteamAPI Offline](https://github.com/SDmodding/SteamAPI_Offline/releases/latest/download/Release.rar)
> - Debug Symbols (PDB): [Download](https://mega.nz/file/aThlWBSB#7hG3yh6G5hUjX2Dy-1Kqjqwq9gSAREJJeWqyeS1K_m8)
> - Debug/Fast Boot game executable: [sdhdship_debug.exe](https://mega.nz/file/baRj0YSa#YJkW779PBNv6ALetThazisFoe9-PyHaH8xe0GOoJI4Y)
>   - This is modification of the original game executable.
>   - It has separate folder for game saves/settings called "dbg".
>   - It will instantly boot the game instead going to main menu, which allows easier modding testing, etc...
>   - **To fix sound you will need to open pause menu once, controller might not work (requires alt tabbing out of the game once)**

## Development Status

> [!IMPORTANT]
> Public development of the SDK and Theory Engine is currently paused.
> 
> Existing work will remain available, but future development and new projects, particularly projects built around or dependent on the SDK and Theory Engine, will generally remain private.
> 
> This decision is largely a result of how the work has been used and maintained over time.
> A significant amount of the work in this organization has been created and maintained primarily by a single person, while receiving relatively little contribution or attribution in return.
> 
> I've also become increasingly uncomfortable with the way AI is being used within the modding community. I don't have an issue with AI being used as a tool, but one of the original purposes of the SDK was to help people understand how the underlying systems work, learn through reverse engineering, and build things themselves.
> 
> When that work is instead treated as something to be consumed or reproduced without understanding, contribution, or proper credit, it takes away much of the motivation behind maintaining it publicly.
> 
> For that reason, I'm stepping back from public development for the time being. The existing repositories and work are still available, but I don't intend to continue making future foundational work or projects publicly available in the same way.

## Modding
If you're interested in modding the game yourself, we provide enough repositories at this organization that will give you enough information to do mods by yourself.

- Modifying game files:
  - **This is still kind of tedious thing to do since there are not an appropriate tools to handle this easily so bare in mind while trying to do anything.** 
  - Here is list of tools:
    - [Big File Explorer](https://github.com/sneakyevil/SD-BigFileExplorer)
    - [BIG Unpacker](https://mega.nz/file/CeJhwIaZ#gL0Byx7utvwSNVdVdn49319_2RPu-5_PzkL4_F_xPDY)
    - [Ultimate Texture Tool](https://github.com/sneakyevil/SD-UltimateTexTool)
    - [Model Scriber](https://github.com/SDmodding/ModelScriber)
    - [Perm To FBX](https://github.com/SDmodding/PermToFBX)
    - [True Crowd DataBase Converter](https://github.com/SDmodding/TCDatabaseConv)
    - [Big File System (Unpacker Only)](https://github.com/SDmodding/BigFileSystem)
    - [ShaderBin](https://github.com/SDmodding/ShaderBin)
- Writing own plugins/mods:
  - You will need to have knowledge of C/C++ and take some time to understand how the game engine works.
  - We provide repository that is essentially [SDK "dev-kit"](https://github.com/SDmodding/SDK) for the game itself.
  - You will essentially need to use reverse-engineering tool like Ghidra or IDA for finding desired hooks to run/add code to the game.
- Writing own tools:
  - If you're trying to write own tool, we recommend to use [TheoryEngine](https://github.com/SDmodding/TheoryEngine), which is essentially re-implementation of the game engine.
  - The [ModelScriber](https://github.com/SDmodding/ModelScriber) is based on it and could be useful to understand how the file structure even works in general.
