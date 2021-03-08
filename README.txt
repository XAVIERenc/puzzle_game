--- Disclaimer ---
Puzzle Game Version 1.0 written and created by Jeffrey B. Madden.
All rights reserved. Any use of Puzzle Game Version 1.0 can only be granted with permission of the owner Jeffrey B. Madden.
This project is intended to showcase my work and my ability to program, build, design, and implement features using Javascript and HTML. The design, images, and concepts contained are purely made from scratch. I have no affiliation with any game companies.

--- Standalone ---
Built as a standalone feature. One external javascript document, one script tag at the end of the body, one wrapper div for the game wrapper, and one stylesheet. All functions are constructed and loaded in one, self executing, anonymous function.

--- About Puzzle Game Version 1.0 ---
A simple Real-Time Puzzle Game built using pure vanilla Javascript. The Javascript is written as a standalone feature. An object constructor organizes all functions. A function closure frees the global namespace while executing commands AFTER the DOM is ready.

The "grid" acts like a matrix, but relying on the DOM to remember positions and to keep all blocks in their proper position would be taxing the user's cache and makes cheating much easier. So I came up with the idea to create a matrix stored in arrays. This matrix is always referred to for positions and creates, what I feel, is a more solid approach to keeping positions of all elements correct.

Minimal coding, neat and pretty. :)

--- Controls ---
(keyboard required)
Left, Right Arrow keys: Move left/right.
Up Arrow key: Holds movement.
Down Arrow key: Moves down faster.
"N": rotates counter-clockwise.
"M": rotates clockwise.

--- Thank You ---
You are free to use and share my code. It would be very kind of you to credit me if you do.
Thank you for reading this far. And thank you to any contributors.
