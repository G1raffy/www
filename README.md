# Giraffe World Website

A playful static website hosted on GitHub Pages featuring a Minecraft-style voxel giraffe greeting visitors!

## Features

- **Minecraft Voxel Aesthetics**: Retro pixel font, savanna biome badge, and cubic layout.
- **3 Hearts Health System**:
  - The giraffe starts with 3 full Minecraft hearts displayed at the top (`HP: ❤️ ❤️ ❤️`).
  - Animated heart pulses for taking damage and healing.
- **Surface Grass Lawn (Layer 1)**:
  - 10 interactive surface grass blocks.
  - Eating surface grass restores lost hearts!
  - Blocks dynamically regrow after a few seconds with a sprout animation (`🌱`) and chime.
- **Mystery Sub-Layer (Layer 2 - Stone & Grass)**:
  - Located directly beneath the lawn with hidden `?` mystery blocks.
  - Clicking them (or clicking the giraffe) uncovers the underground block:
    - **Stone**: Ouch! The giraffe bites hard stone, triggers a Minecraft red damage flash, plays a metallic clang/crunch, and loses 1 heart (`-1 💔`). If it eats stone 3 times, it loses all 3 hearts and gets dizzy!
    - **Grass**: A sweet hidden grass block! It plays a crunch munch sound, restores a lost heart, and helps the hearts go back (`+1 ❤️`)!
- **Sound & Animation**:
  - Real-time procedural audio synthesis using Web Audio API (crunch sound, stone clatter, and healing chime).
  - Floating pixel particles (`*NOM*`, `*CLANG*`, `+1 ❤️ RESTORED!`).

## Files

- [index.html](index.html): The main interactive webpage.
- [giraffe.png](giraffe.png): A blocky, voxel-art Minecraft giraffe in a savanna biome.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add mystery layer with stone and grass, 3 hearts system"
   git push
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
