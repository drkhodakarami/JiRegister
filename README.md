<p align="center">
<a href="https://discord.gg/jEtwguzZ4R"><img alt="" src="https://img.shields.io/badge/Discord-Channel-blue" height="20"/></a>
<a href="https://www.youtube.com/@YourTradeMaster"><img alt="" src="https://img.shields.io/badge/Youtube-Channel-db2e73" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/commit-activity/t/drkhodakarami/JiRegister" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/last-commit/drkhodakaramiJiRegister" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/downloads/drkhodakarami/JiRegister/total" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/github/license/drkhodakarami/JiRegister" height="20"/></a>
<a href=""><img alt="" src="https://img.shields.io/badge/Maintained-YES-31ad31" height="20"/></a>
	</p>

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#thelibrary)

## ➤ What is this library?

This is a simple yet useful library for registering everything in your Fabric mod. There are lots of register overload methods inside the Registers
class that you can utilize. The class is heavily documented and should be self explanatory. You just need to add a static import to the subclass and
call different register methods as you need and have easier life registering your entries into Minecraft's Registry system.

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#dependency)

## ➤ Depending Your Mod

there are two different options that you can use. If you want to use jit pack you can use the jitpack maven. If you want to use repsy, you can use
it's maven. Both work however, the prefered way is to use repsy because jit pack sometimes have problem indicating the correct version numbers.

### ➤ Using jitpack : 1.0.0-MC1.21.3

First you need to add the maven to your `build.gradle` repositories:

```Maven Repository
repositories 
{
	mavenCentral()
    maven { url 'https://jitpack.io' }
}
```

Now you can add the dependency to this library inside `build.gradle`. Take note that we will use `include` because with including the library into
your mod, we will utilize the Jar In Jar mechanism and by doing it, players won't need to add an extra library mod into their game.

```dependencies
dependencies 
{
    modImplementation include("com.github.drkhodakarami:JiRegister:${jiregister_version}")
}
```

Finally, we need to add an entry inside `gradle.properties` using the version indicator of the jitpack bellow:

[![](https://jitpack.io/v/drkhodakarami/JiRegister.svg)](https://jitpack.io/#drkhodakarami/JiRegister)

```gradle.properties
jiregister_version=x.x.x-MCx.x.x
```

### ➤ Using repsy : 1.0.0+MC_1.21.3

First you need to add the maven to your `build.gradle` repositories:

```Maven Repository
repositories 
{
	mavenCentral()
    maven { url 'https://repo.repsy.io/mvn/jiraiyah/jiregister' }
}
```

then you need to add the dependency into your dependency section in `build.gradle`

```dependencies
dependencies 
{
    modImplementation include("jiraiyah.register:jiregister:${jiregister_version}")
}
```

Finally, we need to add an entry inside `gradle.properties` using the version from the maven repository. The version should look like x.x.x-MCx.x.
x for sub versions of Minecraft, and for the main versions of the game it should be like x.x.x-MCx.x

Look into [MAVEN REPOSITORY](https://repo.repsy.io/mvn/jiraiyah/jiregister/) for the proper versioning.

```gradle.properties
jiregister_version=x.x.x+MC_x.x.x
```

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#contributors)

## ➤ Contributors

| [<img alt="Alireza Khodakarami" src="https://avatars.githubusercontent.com/u/77685668?v=4" width="100">](https://www.youtube.com/@YourTradeMaster) |
|:--------------------------------------------------------------------------------------------------------------------------------------------------:|
|                                          [Alireza Khodakarami](https://www.youtube.com/@YourTradeMaster)                                           |
|                                          [khodakarami_dr@outlook.com](mailto:khodakarami_dr@outlook.com)                                           |
|                                                                        🔥🔧                                                                        |

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#license)

## ➤ License

Licensed under [MIT](https://opensource.org/licenses/MIT).

[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)](#table-of-contents)

## ➤ Table of Contents

* [➤ The Library Info](#-thelibrary)
* [➤ Depending to Library](#-dependency)
* [➤ Contributors](#-contributors)
* [➤ License](#-license)