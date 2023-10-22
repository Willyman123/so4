# Spaced Out 4

Spaced Out 4 is a 2D, top-down space-themed action-adventure game with RPG elements. It is inspired by the Spaced Out series of games by Sean Hunter and intended as a spiritual successor.

The game is written primarily in C++, using SFML for graphics, audio and rendering, as well as Dear ImGUI for UI. SO4 is in a pre-alpha state; everything you see is subject to change, and lots of it.

SO4 is intended to be heavily moddable, with most game data and settings stored in INI files. In addition, the game has a Lua script processor, and missions, systems, and events are represented as Lua scripts.

## Considerations

Seeing as the game is in a pre-alpha state, many of the assets (primarily graphics and audio assets) are temporary, and taken from various freely available collections found on the Web.

I've attempted to credit as many authors as I can. The credits list can be found in the credits folder.

IMPORTANT: If you notice that your work is included in this repository, and your name was not properly recorded in the credits file, don't hesitate to contact me so that I can credit you for your work.

## Compiling

SO4's project files work with VS2019. SO4 uses the VS2015 Platform Toolset (v140), which must be installed for the project to compile correctly. 

After cloning the repository, open the solution in VS2019 and ensure the NuGet packages for SFML and Lua are downloaded. 

Once the game is compiled, copy settings.ini and imgui.ini from the root of the repository to the location the game was compiled to.

You may need to adjust the working directory for the game to work properly when started under debugging in VS. In the Project Properties, set the working directory to the folder the location the game was compiled to.

## Contributing

Take a look at CONTRIBUTING.md for more information.

## License

SO4 is published under the terms of the GNU GPLv2.