-------
Schrottii's 1.18.2 Minecraft mod template
-------

Step 1) Download or get the repo or something

Step 2) Replace all instances of 'modname' with the name of the mod
In IntelliJ, this can be easily done by selecting all files (in src) and then right clicking and selecting "Replace In Files..."

Step 3) Update the build.gradle and META-INF\mods.toml files, potentially also modlogo.png

Step 4) Rename com.moddername.modname, assets.modname, and data.modname

Step 5) Maybe edit changelog.txt and credits.txt, and delete this file

Step 6) Add content, it already has a placeholder block (ModBlocks) and a placeholder item (ModItems),
as well as an English translation file and a recipe

After compiling/building the mod, the .jar can be found in build\libs

-------