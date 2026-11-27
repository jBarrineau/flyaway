# FLYAWAY 🤸

An arcade flying trapeze game built with three.js. Swing, let go, flip, and catch the next bar.

### ▶ [Play now](https://jbarrineau.github.io/flyaway/)

## Play
- **GRIP**: Space, left click, or the right side of the screen. You hang on automatically. Press it to let go and fly, then press it again in the air to reach for the next bar. You'll catch it and keep holding on until your next press.
- **TUCK**: F, Shift, ↓, right click, or the left side of the screen. Tap it at the bottom of the swing to pump higher, and hold it in the air to flip.
- **H** turns the aim assist on or off. **M** mutes the sound.

You can catch a bar two ways:
- **Hands**: open up from your tuck and be hands-up.
- **Knees**: be upside-down, feet-up, and you hook the bar with your knees. Tucked or not, it works. A knee hang scores +200, but your grip runs out faster (7 seconds instead of 11).

When you reach in the air, your body turns to whichever is closer, hands-up or feet-up. Tricks count in half-turns, so a knee catch after a hands release is a half turn, 1½, 2½ and so on. Layouts and perfect catches score ×1.5, chained catches build a combo, and gold bars give you an extra life.

### Practice mode
Press **P** on the title screen, or tap **PRACTICE**, to play without lives or a grip timer. You can fall into the pit as often as you like and hang on as long as you want, and every trick still scores. Press **Esc** or tap **END** to finish the run and see your results. Practice has its own best score, so it never replaces your real high score. On the results screen, Space plays the same mode again, and **N** or **P** switches modes.

### Extras
- **Stars**: Grab ★ in mid-air. Each star in a streak is worth more than the last. Pink **mega-stars** sit high up and are worth 1,000.
- **FEVER**: Chain 5 catches to double all your points. The arena goes rainbow and the music kicks into full gear. Landing in the pit ends it.
- **Bullet time**: Time slows down when you flip toward a fresh bar.
- **Clutch**: Catch a bar with your grip almost gone for +500.
- **Zones**: The arena changes color every 10 bars.
- The soundtrack adds layers as your combo grows.

## Host on GitHub Pages
1. Create a repo and add `index.html` to its root.
2. Go to **Settings → Pages → Deploy from a branch**, pick `main` and `/ (root)`, and save.
3. Your game will be live at `https://<your-username>.github.io/<repo>/`.

There's no build step. three.js loads from a CDN.
