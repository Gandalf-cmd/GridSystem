# GridSystem
#### This is a demo of how I implemented a dual-grid tilemap system in Unity

Note:
It does NOT use `RuleTiles` directly, but does act similarly to them. It uses a custom script with hard-coded "rules" to control the placement of regular tiles.

Compared to a normal RuleTiles: 
- reducing the number of tiles needed for visually complex terrains only 5-15 tiles as opposed to 47 
- less tile data means faster loading and rendering
- rounded corners and not ambiguous align with the world grid

It is possible to get a dual-grid system working using custom RuleTiles too, however it did become quite convoluted when I tried

References and Inspirations
SGC21 Oskar Stålberg's original proposition of a dual-grid system
ThinMatrix - Programming Terrain Generation for my Farming Game
