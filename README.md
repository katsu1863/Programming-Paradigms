# Programming-Paradigms
Public repository for CSCE 31903 Programming Paradigms at the University of Arkansas. Each project builds on the previous, adding new features with every iteration being in a different programming language. The projects are a rudimentary 2D game inspired by old Zelda games. The player controls Link and can navigate around a small map, shooting boomerangs and collecting rupees.

## Controls
- [Arrow Keys] - Control player movements
- [Space Bar] - Throw boomerang
- [Q/ESC] - Quit program
- [L] - Load map
- [S] - Save map
- [E] - Toggle edit mode
- [C] - Clear map
- [A] - Enter add map item mode
- [R] - Enter remove map item mode
- [Mouse Click] - Remove/add map item or rotate between different map items

## Project 1
Programmed in Java. To run, execute `./build.bash` for Linux or `./build.bat` for Windows.

## Project 2
Programmed in JavaScript & HTML. To run, open game.html in a Web browser and drop the given map.json file into the provided box.

Editing capabilities are removed due to security constraints; map can also not be saved or loaded. It is instead loaded by uploading a JSON file. Counter for the number of rupees collected is added.

## Project 3
Programmed in Python. To run, install the pygame Python library and execute `python3 game.py`.

Editing capabilities are included except for removing map items. Cuccos are added and will roam around the map. If Link runs into them or hits them with boomerangs, they will attack him then disappear. At least 1 Cucco must be present on the map at all times.
