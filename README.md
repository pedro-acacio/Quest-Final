# Quest Final

Early prototype of a game in the Godot Engine, still at a very preliminary stage. The repository only contains the scene setup: a background, a decorative "big screen" and a playable character (`Player`, of type `CharacterBody2D`) with a two-frame animation ("Neymar"-themed sprites). There are no GDScript scripts in the project — that is, there is no movement, collision, scoring or any other game logic implemented yet, only the visual elements placed in the scene.

## Technologies

- Godot Engine 4.4 (no GDScript scripts in the project so far)
- PNG/JPG sprites (`Sprites/` folder)

## How to run

1. Open the project folder in Godot Engine 4.4 (or a compatible version).
2. Run the main scene `main.tscn` (set as the startup scene in `project.godot`).

Since there are no gameplay scripts, running the project only displays the scenes and sprites, with no interaction.
