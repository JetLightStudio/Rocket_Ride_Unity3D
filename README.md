# Rocket_Ride_Unity3D
A doodle jump like game, made from scratch using unity3D. Feel free to use it however you want, a little mention would help a lot! 


## Screenshots and GIFs:
![rocket ride image](https://user-images.githubusercontent.com/17766221/44610815-e8d68880-a7f5-11e8-8316-c7c03eab6abc.png)

## Project Overview
Requires Unity3D (tested with 2017.x, but should also work with 2018.x & 5.x)

```
.
├── Prefabs
|   └── rechagePad.prefab        - The predefined game object of the recharge pad.
|   └── superRechagePad.prefab   - The predefined game object of the recharge pad that gives extra boost.
|   └── ship.prefab              - The predefined game object of the playable ship.
├── Scenes
|   └── Main.unity               - The project's main scene.
├── Sprites                       
└── Scripts                      - Simply contains graphical game assets. 
    ├── GameManager.cs           - The main code of creation and interaction.
    ├── PadBehaviour.cs          - Handles the pad's boost and collisions.
    ├── PlayerBehaviour.cs       - Handles the horizental moves of ship.
    └── CameraBehaviour.cs       - Movement of the camera and score count is covered here.
```

## Running the Project
To run the project, open _Scenes/Main.unity and click on the play button.

Use the left and right arrows to move the rocket, land on the platforms and indrease your score! 
