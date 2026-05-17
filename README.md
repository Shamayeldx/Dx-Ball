DX Ball — Short Note
Project Overview
DX Ball is a classic arcade-style brick breaker game implemented in C++ using the OpenGL/GLUT library for the Computer Graphics Lab (CSE 426) course. The player controls a paddle at the bottom of the screen to bounce a ball and destroy all the colored bricks at the top without letting the ball fall.
Computer Graphics Algorithms Used
AlgorithmPurposeBresenham's Line DrawingDrawing the paddle, borders, brick edges, and falling dropsMidpoint Circle DrawingRendering the ball as a smooth filled circleBoundary Fill (concept)Filling the interior of each brick after drawing its boundary
Game Features
Core Gameplay:

3 lives, score tracking, and live game timer
Paddle controlled by both keyboard (arrow keys) and mouse
Ball speed gradually increases with each level
5×10 grid of colorful bricks to break

Menu System:

Start New Game, Resume, High Score, Help, and Exit options
Pause (P) and return to menu (M) anytime during gameplay

Power-Ups & Debuffs (drop randomly from bricks):

🔴 LIFE — Grants an extra life
🟡 SPEED — Increases ball speed
🟢 WIDE — Makes the paddle wider
🟠 FIRE — Fireball pierces through bricks
🟣 DEATH — Penalty: lose a life

Bonus Features:

Multi-level progression (clear all bricks → next level)
High score tracking
Detailed help screen
Weighted random drops so power-ups feel special and rewarding

Objective
Clear all the bricks in the shortest possible time while keeping your lives intact. Catch helpful drops, avoid the deadly ones, and progress through increasingly fast levels to achieve the highest score!
