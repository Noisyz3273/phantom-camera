![phantom-camera-banner](https://user-images.githubusercontent.com/5159399/209484593-79c169d7-5220-4abc-8e0f-02c4e9cb6970.png)
Control and dynamically tween 2D and 3D cameras in Godot 4.0 projects. 

## Features
### Follow
Keeps a persistent position relative to a target node.

### Look At (3D scenes only)
Retains the forward vector at a specified target.

### Tween
Change how the camera transitions and eases between PhantomCameras.

## Installation
TBD

## How to use
See the [[Phantom Camera - Wiki]].

## Roadmap
See the [project page](https://github.com/users/MarcusSkov/projects/3/views/8) for upcoming features.

## FAQ
### _What is the intent behind the plugin?_
Cameras are an essential part of practically any game for rendering what you see on the screen. But rarely do they remain static and immoveable, but instead dynamic and changes based on what happens in the game.

The plugin is meant to simplify some common camera behaviour, such as smoothly moving between different points in space at specified points in time or retain a particular positional/rotational value relative to other elements.

The end goal is to make it functional enough to become a generalised camera extension for Godot projects.

### _What is the state of the plugin?_
Ongoing, but still in early stages. Core features have been implemented, but may change as more get added. Things will likely break or change along the way. It's also worth keeping in mind that lots of key and, likely, frequently used features are yet to be done.

See the [project page](https://github.com/users/MarcusSkov/projects/3/views/8) to see planned features.

### _Does this work for Godot 3.5 or older?_
Unfortunately not.

GDScript has received a lot of changes and improvements in 4.0, but as a result it would require a rather large rewrite to make it compatible with older versions.

### _When will X feature be added?_
There's no deadline or precise timeframe for when things get implemented. The [milestones page](https://github.com/MarcusSkov/phantom-camera/milestones) should give a good idea for what has, will, and currently being looked at.

## Contribution
Issues, PRs, suggestions and feedback are welcome. Please create an Issue for bugs or a Discussion post for suggestions or general discussions.

## Credits
- [Unity's Cinemachine Package](https://unity.com/unity/features/editor/art-and-design/cinemachine) for the key inspiration
- [Godot](https://godotengine.org/) for their amazing work creating the engine
