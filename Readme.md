# PACKABUNCHAS
You are Spacey, from the PACKABUNCHAS, a group of space rangers specialized in packing and rescuing creatures around the galaxy!
Solve tons of colorful tiling puzzles, in five different game modes. 
Any mode is fine as long as you rescue everyone, and there is no hurry, so relax and take your time!
PACKABUNCHAS!


### HOW TO PLAY
Click or Tap, Drag and drop, Double Click to rotate

### COMPATIBILITY
Tested browsers:  
- Desktop: Chrome, Firefox, Safari
- Mobile: Firefox, Chrome, Opera 

Please use Chrome on both Desktop and Mobile for the best performance.

### BUILD
The build process is what really makes it possible to pack everything under 13kb.

1) Use [google closure compiler](https://developers.google.com/closure/compiler) on game.js
2) Use [terser](https://github.com/terser/terser) on the generated code.
3) Use [roadroller](https://lifthrasiir.github.io/roadroller/) on the generated code
4) Put the roadrolled code into the index file inside <script></script> (removing <script src = "game.js"></script>)
5) Zip index.html at maximum compression (with any zipper)
6) use [ECT](https://github.com/fhanau/Efficient-Compression-Tool/releases/tag/v0.8.3) on the zip

### AUDIO
Background music and sounds effects are made with [ZzFXM](https://github.com/keithclark/ZzFXM) and [ZzFX](https://github.com/KilledByAPixel/ZzFX).
I highly suggest you to check these projecs out :)

### THANKS
Many thanks to all the people around me who supported me with feedbacks, tips, ideas, and testing sessions on their devices.
I couln't have done it without you! (´｡• ω •｡`) ♡


### CREDITS

PACKABUNCHAS
developed by Mattia Fortunati
for [js13kGames](https://js13kgames.com/) 2021

feel free to contact me at:  
https://github.com/MattiaFortunati  
http://www.mattiafortunati.com  
mattia@mattiafortunati.com

### LICENSE
Released under the MIT license.     
See LICENSE file for more information.