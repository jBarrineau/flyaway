# FLYAWAY 🤸

An arcade gymnastics rings game built with three.js. Swing, let go, flip, and catch the next ring.

## Play
- **GRIP**: Space, left click, or the right side of the screen. Hold it to hang on, let go to fly, and hold it again in the air to catch a ring.
- **TUCK**: F, Shift, ↓, right click, or the left side of the screen. Tap it at the bottom of the swing to pump higher, and hold it in the air to flip.
- **H** turns the aim assist on or off. **M** mutes the sound.

To catch a ring, you have to open up from your tuck and be hands-up. Layouts and perfect catches score ×1.5, chained catches build a combo, and gold rings give you an extra life.

### Extras
- **Stars**: Grab ★ in mid-air. Each star in a streak is worth more than the last. Pink **mega-stars** sit high up and are worth 1,000.
- **FEVER**: Chain 5 catches to double all your points. The arena goes rainbow and the music kicks into full gear. Landing in the pit ends it.
- **Bullet time**: Time slows down when you flip toward a fresh ring.
- **Clutch**: Catch a ring with your grip almost gone for +500.
- **Zones**: The arena changes color every 10 rings.
- The soundtrack adds layers as your combo grows.

## Host on GitHub Pages
1. Create a repo and add `index.html` to its root.
2. Go to **Settings → Pages → Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. Your game will be live at `https://<your-username>.github.io/<repo>/`.

There's no build step. three.js loads from a CDN.
