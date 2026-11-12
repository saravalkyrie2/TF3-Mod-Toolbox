# Credits

[Back to the Readme](Readme.md)

## The games

Transport Fever 2 and Transport Fever 3 are made by Urban Games. The TF3 Mod Toolbox is a fan project, not affiliated
with or endorsed by Urban Games. The game's own scripts were the reference for nearly every fix in it.

## Where the converter began

**GCT TPF3 Konverter** by GermanChickenT (Python). The Toolbox's converter started as a C# port of it; its readme invites
people to copy and improve it.

## Open source libraries

| Library | Version | Used for | Licence |
|---|---|---|---|
| [MoonSharp](https://www.moonsharp.org/) | 2.0.0 | Running TF2 Lua, and TF3's station scripts, in a sandbox | BSD 3-Clause |
| [SixLabors ImageSharp](https://github.com/SixLabors/ImageSharp) | 4.1.3 | Converting textures, icons and preview pictures | Six Labors Split License 1.0 |
| [Pfim](https://nickbabcock.github.io/Pfim/) | 0.11.4 | Reading DDS textures | MIT |
| [OpenTK](https://github.com/opentk/opentk) (Graphics, Windowing.Desktop) | 4.9.3 | OpenGL for the 3D views | MIT |
| [OpenTK GLControl](https://github.com/opentk/GLControl) | 4.0.2 | The 3D view control in the WinForms windows | MIT |
| [Microsoft.Extensions.DependencyModel](https://dot.net/) | 11.0.0 | .NET support library used by the app | MIT |
| [.NET](https://dot.net/) and Windows Forms | 10 | The runtime and the user interface | MIT |

Used for testing only (not part of the app):

| Library | Version | Licence |
|---|---|---|
| [xUnit.net](https://xunit.net/) and its Visual Studio runner | 2.9.3 / 4.0.1 | Apache 2.0 |
| [Microsoft.NET.Test.Sdk](https://github.com/microsoft/vstest) | 18.11.0 | MIT |

## Tools you install yourself

The Toolbox finds these if they're installed; it doesn't include them.

| Tool | Used for | Licence |
|---|---|---|
| [FFmpeg](https://ffmpeg.org/) | Converting TF2 sounds to TF3's format | LGPL 2.1 or later (some builds GPL) |
| [Teal](https://github.com/teal-language/tl) (`tl`) | Compiling TF3's Teal scripts for the station preview | MIT |

## Mods shown in the screenshots and videos

The TF2 mods shown in the conversion steps:

- **Oppie's** NL Modular Stations
- **Scotchbob & Mezzie's** Desiro Class 350 & 450
- **Jotrain Gamer's** Gold Coast G:link light rail
- **Lexygone's** Boeing 747 Passenger & Cargo

The bogie bug in the origin story:

- **cw_315's** CAF Mark 5a Coaches - TransPennine Express Nova 3

They are their authors' work. They appear converted, for private use, only to show what the Toolbox does; the
conversions aren't distributed here.
