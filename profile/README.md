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

## Modding
If you're interested in modding the game yourself, we provide enough repositories at this organization that will give you enough information to do mods by yourself.

- Modifying game files:
  - **This is still kind of tedious thing to do since there are not an appropriate tools to handle this easily so bare in mind while trying to do anything.** 
  - Here is list of tools:
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
