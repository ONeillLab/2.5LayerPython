# 2.5LayerPython
My translated version of Prof. O'Neill's 2.5 layer shallow-water model with moist convection.


TODO: 
  - The AB = 3 case has some bugs.
  - The colour bar scale on the video does not update, leading to the "0" colour shifting but the bar staying constant. This just makes it look like everything starts moving one way or another when it is not.
  - Currently saving a bunch of stuff for testing. Stop saving everything in later code.
  - This is a very line by line translation. There are definitely optimizations to be made...
  - Need to make it able to run multiple simulations with multiple lists of parameters to try.

From a long simulation, seem to have gotten a large polar cyclone. It persisted for basically indefinitely after forming early into the simulation.
![large_central_vortex](https://github.com/ONeillLab/2.5LayerPython/assets/168764017/9f7fc426-3972-4420-a4d9-2e06184f21ef)
