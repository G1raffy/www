# Giraffe World Website

A playful static website hosted on GitHub Pages featuring a Minecraft-style voxel giraffe greeting visitors!

## Features

- **Minecraft Voxel Aesthetics**: Retro pixel font, savanna biome badge, and cubic layout.
- **Interactive Giraffe**: Click directly on the giraffe to feed it grass.
  - The giraffe dips its head with a munching animation.
  - Authentic procedural Minecraft crunchy eating sound effects and floating leaf particles (`*NOM*`, `*CRUNCH*`).
  - Each bite consumes a grass block from the savanna lawn below, turning it into bare dirt (just like sheep in Minecraft!).
- **Dynamic Grass Regrowth**:
  - After a few seconds, little green sprouts pop up and each dirt block dynamically regrows back into vibrant grass, complete with a chime sound.
  - Real-time counter tracks the lawn's condition (`X / 10 GRASS`).
- **Interactive Buttons**: "Feed Grass 🌿" and "Say Hello Back! 💬".

## Files

- [index.html](index.html): The main interactive webpage.
- [giraffe.png](giraffe.png): A blocky, voxel-art Minecraft giraffe in a savanna biome.

## Deploying to GitHub Pages

1. Commit and push your changes:
   ```bash
   git add .
   git commit -m "Add interactive grass eating and regrowth feature"
   git push -u origin main
   ```
2. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
3. Your website will be live at `https://<your-username>.github.io/<repo-name>/`!
