# JackFredLib — Shared Library for JackFred Mods

JackFredLib 9minecraft Mod provides shared code tools and background systems for compatible mods. It does not add new blocks, items, or standalone world elements on its own. Instead, this mod supplies the internal framework needed to run features like death markers and customized configs. Players install it alongside dependent mods to keep everything running without game errors.

Provides the required shared code for companion mods such as Lenient Death.

## What this build is

An unofficial rebuild of **JackFred**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

This build is released under **MIT**. The complete corresponding source ships inside the downloadable file under `META-INF/sources/`, next to the original licence text.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, fabric |
| 26.2 | Fabric, fabric |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/jackfredlib-9minecraft-mod](https://www.9minecraft.net/jackfredlib-9minecraft-mod/)

## Credits

Original work by **JackFred**. Port and maintenance by 9Minecraft Studios. Licensed MIT; the upstream licence text ships inside every build.
