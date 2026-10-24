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
- **Mystery Biome Button (10-Second Cooldown & Smart Rotation)**:
  - Click **"Mystery Biome 🎲"** with a quick **10-second cooldown**!
  - **Different Biomes Go First**: Ensures you warp to a new, different biome on every roll, prioritizing unvisited biomes so you experience the full variety before repeats.
  - **Plains is Less Common**: Plains has a reduced spawn rate (~10% relative weight), making Nether, Sunflower Plains, and Savanna more frequent!
  - **The 4 Biomes**:
    - **The Nether**: Fiery Nether with crimson nylium and a **10% chance of Lava** in the mystery layer (-2 hearts!).
    - **Sunflower Plains**: Peaceful golden biome with a chance to uncover Golden Heart Containers to reach up to 5 hearts!
    - **Savanna**: The classic warm savanna biome with balanced stone and grass.
    - **Plains (Less Common)**: Rocky grasslands with high stone density underground.
- **Surface Lawn & Mystery Underlayer**:
  - **Layer 1 (Surface Grass)**: Dynamic turf matching the current biome that regrows after being eaten.
  - **Layer 2 (Mystery Underlayer)**: Contains stones, grass, lava (in Nether), and golden hearts (in Sunflower Plains).
- **Reset Button 🔄**:
  - Instantly resets everything: returns to Savanna, resets hearts to 3, regrows all grass, re-rolls mystery blocks, and clears the 10-second biome cooldown immediately!
- **Procedural Sound Effects**:
  - Synthesized Web Audio API sound effects for eating crunches, stone clangs, lava sizzling, portal warping, and heart upgrade fanfares.

## Files

- [index.html](index.html): The complete interactive web application.
- [giraffe.png](giraffe.png): A blocky, voxel-art Minecraft giraffe in a savanna biome.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Update biomes: 10s cooldown, different biomes go first, plains less common"
   git push
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
