# Sector 07 Arena

A browser FPS built with three.js: wave-based rusher drones, a pulse rifle and a pump shotgun, aim-down-sights zoom, Low/Medium/High graphics presets and synthesized 3D audio.

Play: open `index.html` in a browser, or host it with GitHub Pages.

## Controls
- Desktop: WASD move, mouse look, left click fire, right click aim, Q or 1/2 switch weapon, Space jump, Shift sprint, R reload, Esc menu
- Touch: left thumb moves, right thumb looks; hold Fire and drag it to aim while shooting; buttons for Aim, Reload, Switch and Jump

## Publish on GitHub Pages
1. Create a public repository and upload `index.html` and this README.
2. In the repository, open Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute the game is live at `https://<your-username>.github.io/<repo-name>/`.

Everything is in one file. three.js r147 loads from the jsDelivr CDN; all textures and sounds are generated in code.
