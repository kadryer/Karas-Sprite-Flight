# Kara's Sprite Flight

## Play the Game
**Unity Play Link**: [Kara's Sprite Flight](https://play.unity.com/en/games/172eff36-98a6-439d-9a1e-08eba3300f5b/karas-sprite-flight)

## Game Overview
In this game, you control a car to avoid hitting mechanics. You gain score by surviving.

### Controls
- Left Mouse Button: Move Car

### How to Play
The game starts immediately upon loading. Use the Left Mouse Button to direct your car to avoid mechanics and the wall.

## Base Game Implementation

### Completion Status
- [x] Player movement and controls
- [x] Obstacle spawning system
- [x] Collision detection
- [x] Score system
- [x] Game over state

### Known Bugs
- [List any bugs in base game]

### Limitations
- [List any limitations]

## Extensions Implemented

### 1. [Create a Cohesive Colour Scheme] (2 points)
**Implementation**: Created a colour palette (Yellow/Orange on Dark Blue/Green)
**Game Impact**: None
**Technical Details**: None
**Known Issues**: None

### 2. [Change Your Entire Game Concept] (3 points)
**Implementation**: Changed the Spaceship/Asteroid sprite to match a Racecar/Mechanic concept
**Game Impact**: Mechanics are moderately harder to dodge than hexagons, and bounce off of walls less predictably.
**Technical Details**: None
**Known Issues**: None

### 3. [Swap Out Your Sprites] (3 points)
**Implementation**: See #2
**Game Impact**: See #2
**Technical Details**: None
**Known Issues**: None

### 4. [Destroy the Borders on Game Over] (4 points)
**Implementation**: Made the borders be removed upon game loss (and reappear on restart).
**Game Impact**: None
**Technical Details**: None
**Known Issues**: None

### 5. [Increase Difficulty Over Time] (5 points)
**Implementation**: Increased Bounciness physics factor of obstacles from 1 -> 1.05
**Game Impact**: The game will slowly get harder over time.
**Technical Details**: None
**Known Issues**: None

## Credits
- [2D Race Cars](https://opengameart.org/content/2d-race-cars)

## Reflection
**Total Points Claimed**: [Base: 70 + Extensions: 17 + Documentation: 10 = 97]
**Challenges**: I was having major difficulties with rendering that were only solved by forcing Unity to run in DX11.
**Learning Outcomes**: Foundational 2D sprite creation and management, and beginner C#. 
