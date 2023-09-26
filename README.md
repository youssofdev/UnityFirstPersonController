# First Person Movement Controller README

## Overview
This Unity project includes a basic First Person Movement Controller script that allows you to control a character in a first-person perspective. The controller handles character movement and camera rotation.

## Features
- WASD keys for character movement.
- Mouse input for looking around.
- Adjustable movement speed and mouse sensitivity.
- Optional cursor lock to center the mouse cursor for an immersive experience.

## How to Use
1. **Attach the Script:**
   - Create a new empty GameObject in your Unity scene to represent your first-person character.
   - Attach the `FirstPersonController` script to the character GameObject.

2. **Adjust Settings:**
   - In the Unity Inspector for the character GameObject, you will find the script's variables:
     - `moveSpeed`: Adjust this to set the character's movement speed.
     - `sensitivity`: Adjust this to control the mouse sensitivity for camera movement.
     - `lockCursor`: Set this to `true` if you want to lock the cursor to the center of the screen.

3. **Set Up Your Character and Camera:**
   - Create or import a 3D model for your character.
   - Create a Camera GameObject as a child of your character GameObject.

4. **Input Configuration:**
   - Ensure that your Unity Input settings are set up correctly with the following axis names:
     - `Mouse X`: For horizontal mouse input (looking left and right).
     - `Mouse Y`: For vertical mouse input (looking up and down).
     - `Horizontal`: For character movement left and right.
     - `Vertical`: For character movement forward and backward.

5. **Character Controller:**
   - Attach a `CharacterController` component to your character GameObject to enable basic character physics.

6. **Play the Game:**
   - Run your Unity game, and you'll be able to control your first-person character using the WASD keys for movement and the mouse for looking around.
