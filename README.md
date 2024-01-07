# MultiProject-MDK_1.12
Example MultiProject Files

### How To
1. Get the Forge MDK ([link](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html))
2. Unpack it into where your Main/Placeholder MultiProject will be located.
3. Paste the `build.gradle` and `settings.gradle` from this repository.
4. Edit the lines after the commends with `//MARKER:` like in the example.
5. Import to your IDE

### If you want to work on Fexcraft Mods / Addons / Extensions
If you want to make an addon/extension for a Fexcraft Mod, here's some important things to note / tips:
- Most of my projects are setup in a way that they expect all to be located relative to each other.
If you do the same, there is nothing more you have to do, they should work automatically!    
(IDE should detect them).    
Example Folder Structure:
```
./Github/
  FCL/
  FCLN/
  Json/
  FSMM/
  FVTM/
  FVTM-Core/
  OtherMod/
```
- FCL and FVTM may not work with Eclipse due to how those are setup with submodules/subdeps.
- It is best if your mod is also a sub-project/module, just grab the normal Forge MDK,   
  from my observation as long the main project has fancy gradle, the sub projects work too.    
  (I used the IntelliJ grandle `runClient`)
- Use `GitHub Desktop` or another git client to clone the repositories, this will make easier to fetch updated code if there is new commits.
  
### Discord
If you need further help or spot anything not working, feel free to join the [Discord](https://discord.gg/AkMAzaA) server.
