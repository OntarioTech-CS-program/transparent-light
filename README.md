# Transparent Texture Light Source
<img width="668" height="345" alt="image" src="https://github.com/user-attachments/assets/c7144d09-0429-42b3-98ae-a92c75704ffd" />

For our cyberpunk themed yearlong game, we have an orthogonal camera, so we needed to come up with light sources for our rooms that are recognizable from above. Our solution is neon wall lights like this one, where you can see the light inside through a grate. To create the grate, I used a transparency shader like the one shown in class, but I also added a smaller emissive material inside of it. Because of global illumination, the emissive material actually casts light upon its surroundings. Because our yearlong game is in Godot, I also made this light source in godot. 

<img width="133" height="143" alt="image" src="https://github.com/user-attachments/assets/b3275528-b24d-4d8f-be7b-79388a46c8f5" />

This ended up being perfect to create a light source that is recognizable from all angles
