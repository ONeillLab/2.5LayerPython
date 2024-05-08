# 2.5LayerPython
My translated version of Prof. O'Neill's 2.5 layer shallow-water model with moist convection.


TODO: 
  - The AB = 3 case has some bugs.
  - ~~The colour bar scale on the video does not update, leading to the "0" colour shifting but the bar staying constant. This just makes it look like everything starts moving one way or another when it is not.~~ (FIXED)
  - Currently saving a bunch of stuff for testing. Stop saving everything in later code.
  - This is a very line by line translation. There are definitely optimizations to be made...
  - Need to make it able to run multiple simulations with multiple lists of parameters to try.

From a long simulation, seem to have gotten a large polar cyclone. It persisted for basically indefinitely after forming early into the simulation. This is a high EpHat simulation with low a/LD2. So from [https://www.nature.com/articles/ngeo2459] we should expect this.
![largeElowB](https://github.com/ONeillLab/2.5LayerPython/assets/168764017/c4e46b18-853b-41c7-b93e-a0070b084d40)
