# Giraffe World Website

A playful interactive website hosted on GitHub Pages featuring a Minecraft-style voxel giraffe greeting visitors!

## Features

- **Minecraft Voxel Aesthetics**: Retro pixel font, dynamic biome badge, and voxel layout.
- **Dynamic Heart System (Up to 5 Hearts!)**:
  - The giraffe starts with 3 classic Minecraft pixel hearts (`HP: ❤️ ❤️ ❤️`).
  - **Stone**: Costs 1 heart (`-1 💔`).
  - **Lava**: Found in the Nether, costs 2 hearts (`🔥 -2 💔`) with sizzling lava sound!
  - **Grass**: Eating grass restores lost hearts!
  - **Golden Heart Containers**: Discovered in Sunflower Plains, permanently increases maximum health up to **5 hearts** (`💛 +1 MAX HEART!`) for the whole game!
- **Mystery Biome Button (30-Second Cooldown)**:
  - Click **"Mystery Biome 🎲"** to warp to a new biome! Has a 30s countdown cooldown.
  - **Savanna (35%)**: The classic warm savanna biome.
  - **Plains (30%)**: Rocky grasslands with higher stone density underground.
  - **The Nether (15%)**: Fiery Nether with crimson nylium and a **10% chance of Lava** in the mystery layer (-2 hearts!).
  - **Sunflower Plains (20%)**: Peaceful golden biome with a chance to uncover Golden Heart Containers to reach up to 5 hearts!
- **Surface Lawn & Mystery Underlayer**:
  - **Layer 1 (Surface Grass)**: Dynamic turf matching the current biome that regrows after being eaten.
  - **Layer 2 (Mystery Underlayer)**: Contains stones, grass, lava (in Nether), and golden hearts (in Sunflower Plains).
- **Reset Button 🔄**:
  - Instantly resets everything: returns to Savanna, resets hearts to 3, regrows all grass, re-rolls mystery blocks, and clears the 30-second biome cooldown immediately!
- **Procedural Sound Effects**:
  - Synthesized Web Audio API sound effects for eating crunches, stone clangs, lava sizzling, portal warping, and heart upgrade fanfares.

## Files

- [index.html](index.html): The complete interactive web application.
- [giraffe.png](giraffe.png): A blocky, voxel-art Minecraft giraffe in a savanna biome.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add 4 mystery biomes, 30s cooldown, lava, 5 hearts, and reset button"
   git push
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
