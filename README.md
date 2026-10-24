# Giraffe World Website

A playful interactive website hosted on GitHub Pages featuring a Minecraft-style voxel giraffe greeting visitors!

## Features

- **Minecraft Voxel Aesthetics**: Retro pixel font, dynamic biome badge, and voxel layout.
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
  - Instantly resets everything: returns to Savanna, resets health to 3 base red hearts (clears extra yellow hearts), cancels any active 30s Void Curse, regrows all grass, re-rolls mystery blocks, and clears the 10-second biome cooldown immediately!
- **Procedural Sound Effects**:
  - Synthesized Web Audio API sound effects for eating crunches, stone clangs, lava sizzling, boombox bass blast, void curse gong, wither heart decay ticks, and golden heart upgrade fanfares.

## Files

- [index.html](index.html): The complete interactive web application.
- [giraffe.png](giraffe.png): A blocky, voxel-art Minecraft giraffe in a savanna biome.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add The Void biome, Boombox block, and 30-second heart decay curse"
   git push
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
