# Giraffe World Website

A playful interactive website hosted on GitHub Pages featuring a Minecraft-style voxel giraffe greeting visitors!

## Features

- **Minecraft Voxel Aesthetics**: Retro pixel font, dynamic biome badge, and voxel layout.
- **Dynamic Picture in the Middle of the Screen**:
  - The centerpiece picture changes dynamically to match each of the 5 biomes:
    - 🦒 **Savanna**: Classic voxel giraffe with acacia trees and sunny savannah grassland ([giraffe.png](giraffe.png)).
    - 🌾 **Plains**: Voxel giraffe on lush green rolling hills with oak trees and wildflowers ([giraffe_plains.png](giraffe_plains.png)).
    - 🔥 **The Nether**: Voxel giraffe in the fiery crimson Nether with glowing lavafalls and netherrack ([giraffe_nether.png](giraffe_nether.png)).
    - 🌻 **Sunflower Plains**: Voxel giraffe surrounded by giant blocky yellow sunflowers and warm golden sunlight ([giraffe_sunflower.png](giraffe_sunflower.png)).
    - 🌌 **The Void**: Cosmic voxel giraffe under starry deep purple space with glowing void particles ([giraffe_void.png](giraffe_void.png)).
- **Dynamic Hearts System (Red Base Hearts & Yellow Golden Hearts)**:
  - **3 Base Red Hearts (`HP: ❤️ ❤️ ❤️`)**: The giraffe starts with 3 red base hearts. Eating grass restores damaged base hearts.
  - **Extra Yellow Hearts (`💛 💛`)**: Finding Golden Hearts in the Sunflower Lawn grants up to 2 extra absorption hearts (hearts 4 & 5).
  - **Damage & Broken Hearts**: Taking damage removes extra yellow hearts first. Once lost, they can only be recovered by visiting the Sunflower Plains!
- **5 Unique Biomes**:
  - **The Void 🌌**: Cosmic dark biome with End Stone and Void Turf. Contains the **Boombox** in the mystery layer!
  - **The Nether 🔥**: Volcanic crimson biome with a **10% chance of Lava** in the mystery layer (-2 hearts!).
  - **Sunflower Plains 🌻**: Sunny golden meadow where you can dig up Golden Hearts to get extra yellow hearts (up to 5 hearts total)!
  - **Savanna 🦒**: The classic warm savanna biome with balanced stone and grass.
  - **Plains 🌾 (Less Common)**: Rocky grasslands with high stone density underground.
- **The Void Boombox & 30-Second Curse 📻**:
  - Located as a special surprise in **The Void**'s mystery layer—the sinister opposite of the health box!
  - **Instant Explosion**: Blasts the giraffe for **2 hearts damage** with a screen-shaking bass detonation.
  - **30-Second Void Decay Curse**: Has a chance to curse the giraffe for 30 seconds! During the curse, **it turns one heart black every 10 seconds** (at 10s, 20s, and 30s) with spooky decay sound effects and purple particles.
- **Mystery Biome Button (10-Second Cooldown & Smart Rotation)**:
  - Click **"Mystery Biome 🎲"** with a **10-second cooldown**.
  - **Different Biomes Go First**: Unvisited biomes are prioritized, ensuring you visit all different biomes without immediate repeats.
- **Reset Button 🔄**:
  - Instantly resets everything: returns to Savanna (and restores the Savanna giraffe picture), resets health to 3 base red hearts (clears extra yellow hearts), cancels any active 30s Void Curse, regrows all grass, re-rolls mystery blocks, and clears the 10-second biome cooldown immediately!
- **Procedural Sound Effects**:
  - Synthesized Web Audio API sound effects for eating crunches, stone clangs, lava sizzling, boombox bass blast, void curse gong, wither heart decay ticks, and golden heart upgrade fanfares.

## Files

- [index.html](index.html): The complete interactive web application.
- [giraffe.png](giraffe.png): Savanna giraffe.
- [giraffe_plains.png](giraffe_plains.png): Plains giraffe.
- [giraffe_nether.png](giraffe_nether.png): Nether giraffe.
- [giraffe_sunflower.png](giraffe_sunflower.png): Sunflower Plains giraffe.
- [giraffe_void.png](giraffe_void.png): The Void giraffe.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Change center picture dynamically with each biome"
   git push
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
