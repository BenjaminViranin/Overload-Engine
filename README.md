# Overload-Engine

Overload is a C++/Opengl Game Engine realised as a team of 3 peoples : [Adrien Givry](https://github.com/adriengivry), [Max Brun](https://github.com/maxbrundev) and myself, in the given time of 5 months.

![](https://github.com/BenjaminViranin/Overload-Engine/blob/master/Screenshots/home.jfif)

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

![Simple physic add impulse](https://github.com/BenjaminViranin/Overload-Engine/blob/master/Screenshots/Physics.gif)
*Simple physic add impulse*

- The Audio Engine using IrrKlang ([OvAudio](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvAudio)), and the entity components in the ECS ([Components](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvCore/include/OvCore/ECS/Components)). 
- The Debug tools used by the engine and the user ([OvDebug](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Sources/Overload/OvDebug))
- I also made some scripts for the fps/puzzle Game ([Demo Game Scripts](https://github.com/BenjaminViranin/Overload-Engine/tree/master/Demo/Scripts)).

![Game realized with Overload](https://github.com/BenjaminViranin/Overload-Engine/blob/master/Screenshots/Gameplay-light.gif)
*Game realized with Overload*

# Libraries used

- Bullet
- OpenGl
- IrrKlang
- Assimp
- ImGui
- Lua (sol)

# Source Code

- You can ask me for the source code on my email ben.viranin@gmail.com

# Build Instruction

- You can get the Build of the Editor and the demo Game on our website [Overload.org](http://overloadengine.org/)
