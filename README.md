# Overload-Engine

Overload is a C++/Opengl Game Engine realised as a team of 3 peoples : [Adrien Givry](https://github.com/adriengivry), [Max Brun](https://github.com/maxbrundev) and myself, in the given time of 5 months.

![alt text](https://github.com/BenjaminViranin/Overload-Engine/blob/master/Screenshots/main.jpg)

# Project Description

Overload is a student project, and the Goals are: 
- Making a C++ game engine from scracht
- Make a fps/puzzle game with the engine

# Constraints

- The Engine must run on Windows 
- We have to make our own mathematics library

# My part

- I made the Vector and Matrix part of the math library ([OvMaths](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvMaths))
- The Physic Engine using Bullet 3 ([OvPhysics](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvPhysics)), and the entity components in the ECS ([Components](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvCore/include/OvCore/ECS/Components)). 
- The Audio Engine using IrrKlang ([OvAudio](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvAudio)), and the entity components in the ECS ([Components](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvCore/include/OvCore/ECS/Components)). 
- The Debug tools used by the engine and the user ([OvDebug](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvDebug))
- I also made some scripts for the fps/puzzle Game ([Demo Game Scripts](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Demo/Scripts)).

# Libraries used

- Bullet
- OpenGl
- IrrKlang
- Assimp
- ImGui
- Lua (sol)

# Project Status

- The project is currently in progress, so some features will come on future updates.
- The deadline is 14 june 2019.

# Build Instruction

- You can run the Editor using the Build ([Editor.exe](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Build))
- You can run the Project using Visual Studio and set "Editor" as startup project
