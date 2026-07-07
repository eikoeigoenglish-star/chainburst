# ChainBurst

**ChainBurst** is a relaxing chain-reaction particle puzzle game built with a single HTML file.

Click once to create an expanding burst.  
If nearby particles touch the burst, they trigger, expand, and can trigger even more particles.  
Clear each stage by triggering the required number of particles before your lives run out.

## Demo

Play here:

https://eikoeigoenglish-star.github.io/chainburst/

## Features

- Single-file browser game
- No external libraries
- No external assets
- Canvas-based particle animation
- Responsive design for desktop and mobile
- 12-stage progression
- 3-life system
- Score and best score
- Best score saved with localStorage
- Smooth glowing chain-reaction effects

## How to Play

1. Press **Start**.
2. Click or tap once on the play area.
3. Your click creates an expanding burst.
4. Particles touched by a burst will trigger and expand.
5. Triggered particles expand and can trigger nearby particles.
6. Clear the stage by triggering at least the required number of particles.
7. You have 3 lives. Losing all lives results in Game Over.
8. Clear Stage 12 to win.

## Stage Progression

| Stage | Particles | Goal |
|---:|---:|---:|
| 1 | 5 | 1 |
| 2 | 10 | 2 |
| 3 | 15 | 3 |
| 4 | 20 | 5 |
| 5 | 25 | 7 |
| 6 | 30 | 10 |
| 7 | 35 | 15 |
| 8 | 40 | 21 |
| 9 | 45 | 27 |
| 10 | 50 | 33 |
| 11 | 55 | 44 |
| 12 | 60 | 55 |

## Running Locally

Clone this repository and open `index.html` in your browser.

Example:

    git clone https://github.com/eikoeigoenglish-star/chainburst.git
    cd chainburst
    open index.html

Alternatively, you can simply download `index.html` and open it directly in your browser.

## Deploying with GitHub Pages

1. Put `index.html` in the root of your repository.
2. Go to **Settings** → **Pages**.
3. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ root**
4. Save the settings.
5. Wait for GitHub Pages to publish the site.

The published URL for this repository is:

https://eikoeigoenglish-star.github.io/chainburst/

## Customization

Most game settings are defined near the top of the JavaScript section inside `index.html`.

You can adjust:

- Stage particle counts
- Stage clear goals
- Number of lives
- Particle colors
- Expansion speed
- Burst radius
- Scoring rules
- Visual effects

## Credits

This game is an open-source clone inspired by the classic Flash game **Boomshine**, created for educational and recreational purposes.

The implementation, visual design, responsive layout, stage system, scoring system, and code structure were rebuilt as an original single-file HTML5 canvas game.

## License

MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files, to deal in the Software
without restriction, including without limitation the rights to use, copy,
modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, subject to the conditions of the MIT License.

See the `LICENSE` file for details.
