# Independent Programming Projects
Below are personal projects I have completed February 2021 onwards.

# Chess AI (Python & C)
<https://github.com/maniha7/ChessAI>

This program launches a chess game with a complete GUI implemented with PyGame. Users may choose if they would like to play against an AI, or watch the AI play against itself. The AI aspect of the program is implemented using C, to take advantage of the language's much faster computation when compared to Python. 

The AI uses a custom algorithm derived from a combination of a standard depth-first-search game-tree exploration phase, and a Monte-Carlo tree search based node scoring phase. After exploring the game-tree to a given depth and performing a heuristic evaluation of all leaf nodes, parent nodes up to the root are scored with the average score of all their children, resulting in "top-level" immediate move scores representing the average outcome of making that move (to the given depth).

This algorithm in C evaluates on average approximately 700,000 moves per second during its computation, representing a speed increase of over 1000x from Python, which running the same algorithm can only process around 600 moves per second.

**VIDEO DEMO**

<a href="https://www.youtube.com/watch?v=eJibH-Cjmc8
" target="_blank"><img src="http://img.youtube.com/vi/eJibH-Cjmc8/0.jpg" 
alt="Game of Life" width="240" height="180" border="10" /></a>


# Cellular Automata (Python)

- Conway's Game of Life
- Langton's Ant
- Wolfram's Elementary Cellular Automata


## Conway's Game of Life
<https://github.com/maniha7/Game-of-Life>

Utilizing Pygame, this program runs a Conway's Game of Life cellular automata with extensive user control. Users draw the the active starting cells on the screen and start the automata with the spacebar. Users may undo changes they've made during the drawing process, and can pause mid-animation and draw additional cells before then continuing the animation. When the user is done, they may clear the screen or reset the drawing they just simulated. Users can also control animation speed, as well as paste in specific preset shapes with interesting evolutions.


**VIDEO DEMO**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=ajelLPL6CUA
" target="_blank"><img src="http://img.youtube.com/vi/ajelLPL6CUA/0.jpg" 
alt="Game of Life" width="240" height="180" border="10" /></a>
<br>
<br>
<br>
## Langton's Ant
<https://github.com/maniha7/Langton-s-Ant>

This program runs a Langton's Ant algorithm using 5 randomized colors, as well as turn directions that are randomized at the beginning of each simulation.  Random picking of turn directions is optimized to prevent starting values that cause the simulation to get caught in a confined loop in the beginning of the simulation.


**VIDEO DEMO**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=OglhjBUFO00
" target="_blank"><img src="http://img.youtube.com/vi/OglhjBUFO00/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<br>
<br>
<br>
## Wolfram's Elementary Cellular Automata
<https://github.com/maniha7/Wolframs-Elementary-Cellular-Automata>

This program runs the Elementary Cellular Automata using a randomized starting rule.

**VIDEO DEMO**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=PHBKFyh4U20
" target="_blank"><img src="http://img.youtube.com/vi/PHBKFyh4U20/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
<br>
<br>
<br>
# Tree Growing Algorithm (Python)
<https://github.com/maniha7/Tree-Growing-Algorithm>

This project comprises a set of several algorithms which together draw a randomly generated tree on the users screen, before infinitely cycling through the 4 seasons. Separate algorithms control branch generation, leaf generation, and each of the respective seasons. Each time the simulation is reset with the r key, a differently shaped tree is grown. Seasonal aspects including leaf growth/fall patterns and snowfall are also randomly generated, but are less visually apparent.

**VIDEO DEMO**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=EyXyJo-bQBQ
" target="_blank"><img src="http://img.youtube.com/vi/EyXyJo-bQBQ/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
