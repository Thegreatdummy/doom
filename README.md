# Yet Another Doom Clone

![](image_large.png)

It's yet another doom clone, but implemented in 13kb of (compressed) JavaScript.

Writeup of the development process: [https://nicholas.carlini.com/writing/2019/javascript-doom-clone-13k.html](https://nicholas.carlini.com/writing/2019/javascript-doom-clone-13k.html).

## I JUST WANT TO PLAY

If you just want to play the game (and don't want to play it [https://nicholas.carlini.com/writing/2019/javascript-doom-clone-13k.html](online)) then you can get started by cloning this repository:

```git clone git@github.com:carlini/js13k2019-yet-another-doom-clone.git```

and then just directly view the file [doom.html](doom.html) from your browser.


### I want to see developer mode

From the main repository view the file [src/doom.html](doom.html) from your browser.

This file additionally displays the frame rate, some statistics on how many frames took longer than 16ms to render, and shows the map editor.


## BUILDING

If you actually want to be able to build the small 13k version of the code and run it in this small version, there are a few more steps.

You'll want to run `python3 make.py`.

This will generate a few files, most importantly `build/index.html` which will run the game from there.

The additional files it outputs are also in build/, and consists of javascript files compressed with varying sophistication of techniques.


## LICENSE

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.

