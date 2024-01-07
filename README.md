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
Example:
```
./Github/
  FCL/
  FCLN/
  Json/
  FSMM/
  FVTM/
  FVTM-Core
```
- FCL and FVTM are split into 2-3 repositories, which does not work well with Eclipse, using IntelliJ is advised.
  - This also means that if you clone FCL (which all of my mods use!) you also have to clone `FCLN` and `Json`
    (please note they are under the [fexcraft-net](https://github.com/fexcraft-net/) organisation!)
  - Similarly for FVTM you also need `FVTM-Core` which is also located at [fexcraft-net](https://github.com/fexcraft-net/) rather than my Github Profile.
- It is best if your mod is also a sub-project/module, just grab the normal Forge MDK, from my observation as long the main project has fancy gradle, the sub projects work too.
  (I used the IntelliJ grandle `runClient`)
  
### Discord
If you need further help or spot anything not working, feel free to join the [Discord](https://discord.gg/AkMAzaA) server.
