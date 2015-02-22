#ChiselTones

Chisel compatibility for ZTones blocks.

##Downloads

Downloads can either be found on my [Jenkins](http://tehnut.info/jenkins/job/ChiselTones/) or [CurseForge](http://minecraft.curseforge.com/mc-mods/228004-chiseltones).

##Dependencies

This mod requires both [Chisel2](http://minecraft.curseforge.com/mc-mods/225236-chisel-2) and [Ztones](http://minecraft.curseforge.com/mc-mods/224369-ztones).

##Variation Modes

Currently, there are 2 modes to choose from when adding variations:

###Mode 0
Allow chiseling of the Ztones Tile into each of the different types Ztones adds at a meta of 0. Then you cycle through from there. This makes the crafting recipes useless. 

![Mode 0](http://puu.sh/g78H2/7c0fb92bd7.png)

---

###Mode 1
Allow chiseling between all the blocks within their type. This requires the user to still craft the type, but makes the cycling useless.

![Mode 1](http://puu.sh/g78DN/8fa161af1b.png)

##Dev setup

1. Clone/Fork/Whatever you need to do to get it on your local machine.
2. Run `gradlew [setupDevWorkspace|setupDecompWorkspace] [eclipse|idea]` This will automatically setup your workspace for you. It also downloads the correct version of Chisel 2.
3. Drop a Deobfuscated version of Ztones in `../libs/` and add it as a library.
4. Do things.
