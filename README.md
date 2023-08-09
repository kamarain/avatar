# Avatar - Talking AI Head
Avatar is a conversational AI bot that can be used to study human AI interaction. The bot wake-up word is "Avatar" after which it expects a question and then it answers. It remembers the dialog and is thus more intelligent than a simple question-answer machine.

<p align="center">
    <img height="300" src="resources/kandityo_avatar.jpg">
</p>

Avatar has a modular structure since parts of it have been made as Signal Processing and Machine Learning BSc theses in Tampere University, Finland:

 * [Talking head](#talking-head) - Unity animated virtual head by Konsta Jurvanen (2023) - [Thesis](https://urn.fi/URN:NBN:fi:tuni-202211068199) [Code](https://github.com/konstajurvanen/AvatarFace)

## Talking head
Konsta's original code is available at [konstajurvanen/AvatarFace](https://github.com/konstajurvanen/AvatarFace). The code, however, does not contain much documentation is thus difficult to use. However, his thesis gives a lot of details that help to replicate the Avatar's talking head. Since this part is implementation-wise more interesting than it sounds, some details are given in this section. The following four animated heads can be reproduced:

 * Level 0 - static head that does not move
 * Level 1 - static head that nods when its name is mentioned
 * Level 2 - eyes follow the closest person
 * Level 3 - mouth moves when the Avatar speaks

### Head blender model
The used head model is the the Public Domain (CC0) lisenced "Male Head" blender model from the blendswap.com site: [https://blendswap.com/blend/11745](https://blendswap.com/blend/11745) (you need to register to be able to download the model). 

<p align="center">
    <img height="200" src="resources/male_head_11745.jpg">
</p>

### Install Blender for visualization and editing the animation rigs
The downloaded head model is solid in the sense that its mouth or eyes cannot be controlled (animated) by Unity scripts. In order to do that, the rigs need to be added. A great tutorials are available:

 * [Eye Rigging Tutorial in Blender](https://www.youtube.com/watch?v=pzfKz8NX1rQ)
 * [Blender - Mouth Rigging Tutorial](https://www.youtube.com/watch?v=Map_ro-xUwg)

### Install Unity for animation scripting and building a standalone app
[Unity](https://en.wikipedia.org/wiki/Unity_(game_engine)) is a game engine that is used to animate the Avatar face. The Unity projects and installs are handled by the Unity Hub tool that can be installed to Windows, Linux or MacOS by following these simple instructions at the [Install the Unity Hub](https://docs.unity3d.com/hub/manual/InstallHub.html) page of the Unity project. A lot of instructions and teaching material is available at the Unity Web page
[unity.com](https://unity.com/), but perhaps you benefit by reading this very simple example (based on this [Beginner's guide](https://forum.unity.com/threads/linux-beginners-guide-for-developers.978321/)):

 * [Unity 2D Pong Game](https://noobtuts.com/unity/2d-pong-game)

Otherwise, after installing the Unity Hub, the Avatar head functionality can be edited.

### Editing the head project

Open Unity Hub, then open 

### Deploying for Avatar
