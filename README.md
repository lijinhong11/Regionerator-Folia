# Regionerator
[![Build status](https://ci.appveyor.com/api/projects/status/4enx36sic8j3f0my?svg=true)](https://ci.appveyor.com/project/Jikoo/regionerator/build/artifacts)  
A Bukkit plugin for gradually deleting unused area, allowing you to free up disk space and get rid of old builds or devastated land.

### This is a fork version for 1.20.6+ and Paper/Folia servers!  
### Changes on many classes! So won't support Spigot!!!
  
## Features compared to the original plugin
1. Linear format support
2. Folia support
3. Can configure interaction times and inhabitedtime checks to the region  
   (If you don't know what inhabited time is, see: https://minecraft.wiki/w/Chunk_format)

## Notes

Please refer to [the wiki](https://github.com/Jikoo/Regionerator/wiki) for more information.

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).  
  
The [LinearRegion class](/src/main/java/com/github/jikoo/regionerator/world/impl/linear/LinearRegion.java) is from [LuminolMC/Luminol](https://github.com/LuminolMC/Luminol)(The repo is deleted, you can also see [Leaf](https://github.com/Winds-Studio/Leaf)) under [GPL v3 License](LinearRegion_LICENSE.md).

## Disclaimer
Regionerator directly modifies and deletes region files.    
**This cannot be undone — keep regular backups!**  
You are solely responsible for any damages to your world or server incurred by using this plugin. Use at your own risk.
