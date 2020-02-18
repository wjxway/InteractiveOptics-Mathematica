# InteractiveOptics-Mathematica

This is a package used to Interactively draw illustrations of optical hardware and light rays bended by the hardware.

**Included optical hardwares: Aperture, Traverser, Lens, Mirror, Plane Mirror, Point light sourse and Line light sourse.**



## Usage##

1. Open ***BOTH*** `GUI.nb` and `light tracking.nb` in *Mathematica*.
2. Evaluate all Initialization Cells in `light tracking.nb` by Clicking **Evaluation -> Evaluate Initialization Cells** in the menu bar.
3. Do the same for `GUI.nb`
4. Evaluate `mainpanel[extraoptions]` in Mathematica to start the interactive drawing panel
5. Enjoy~



The window you should get should be like this:

![demo](https://raw.githubusercontent.com/wjxway/image-storage/master/interactiveopt1.png)



The panel on the left controls the selection status and grouping status. the panel on the bottom controls modification actions. the two columns on the right controls styling and addition of optical hardwares.

One can mainpulate the setup by mouse-click buttons(**Note that one can know what a button do by hovering above it!**) or keyboard. Opeations in keyboard are similar to those in *Blender* where:

**Nothing**: drag select

**a**: select all objects

**c**: cancel all selection and reset operation to drag select mode.

**g**: enter move mode

**s**: enter scale mode

**r**: enter rotate mode

**f**: enter fly mode(move camera)

**X&Y**: specify movement direction, useful in **g, s, f** modes.

**numbers**: specify amount, useful in virtually all modes.



After all things are done, press the **NUKE** button and get image with higher resolution and adjust the effect you want. A typical image could be like:

![microscope](https://raw.githubusercontent.com/wjxway/image-storage/master/interactiveopt2.png)

which illustrates the mechanism of microsope.



## Further Work

If I'm happy, I may create a small notebook which simplify the initialization process.



##For Devs

I've written detailed explanation of the structure and code in both notebooks, those should be adequate if you want to further develope this program or make better quality images by yourself.
