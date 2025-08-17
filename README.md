# mini-flappy

## Description
Flappy Box is a simplified mini-game inspired by *Flappy Bird*.  
The player controls a yellow square that must jump through gaps between green pipe obstacles.  
The game includes gravity, a scoring system, and increasing difficulty as the score rises.  
It is lightweight and built entirely in a single HTML file.

## Technologies Used
- HTML5 for game structure and canvas rendering  
- CSS3 for styling and layout  
- JavaScript (Vanilla JS) for game logic, physics, obstacles, and scoring  
- LocalStorage for saving high scores in the browser

## Features
- Yellow square character controlled with mouse click, tap, or Space key  
- Green pipe obstacles with adjustable minimum spacing and random gaps  
- Score increases by +1 for each obstacle passed  
- Highscore stored persistently using LocalStorage  
- Game speed gradually increases with score  
- Start screen and reset highscore functionality

## Setup Instructions
1. Clone or download the repository:  
   git clone https://github.com/Facray05/mini-flappy.git
2. Open the project folder.
3. Launch the game by opening `index.html` directly in any modern browser (Chrome, Firefox, Edge).
4. To deploy online:

   * Option A (Quick): Drag & drop the folder into Netlify for instant hosting.
   * Option B (Recommended): Import the GitHub repo into Netlify for automatic deployment on each commit.

### Demo Links

* GitHub Repository: https://github.com/Facray05/mini-flappy
* Live Demo (Netlify): https://miniflappygame.netlify.app

## AI Support Explanation

During development, **AI Granite** was used to refine the pipe obstacle spawning system.
AI suggested introducing a `minPipeDistance` variable to ensure pipes do not spawn too close together.
This allows horizontal spacing to be adjustable, while vertical gaps remain adaptive with parameters such as `baseGap`, `gapReductionPerScore`, and `maxGapReduction`.

Prompt used:

remake the code so the pipe obstacles aren't too close too each other in the game i made below with a minimum distance that i can adjust (the horizontal and vertical pipe distances)

All AI outputs were reviewed, tested, and manually adjusted by the developer.
AI served only as a development helper, not as part of the runtime game.


