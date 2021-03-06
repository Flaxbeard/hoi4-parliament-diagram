# HOI4 Parliament Diagram

A handy Python generator which will generate code for a dynamic parliament diagram which can be slotted into any Hearts of Iron IV Scripted GUI. Created for use in [Cold Southern Springs](https://discord.gg/HZpcwUuaSH) and its parent mod, [The New Order: Last Days of Europe](https://steamcommunity.com/sharedfiles/filedetails/?id=2173766180).

These diagrams can have an arbitrary number of seats and can use any set of icons. They are fairly lightweight and low-code, relying on three arrays and a dynamic list.
In addition, tooltips, rings to highlight coalition members, and more can be added without much additional effort.

This repo also includes a code sample to help you get started.

## Usage
The diagram creator tool requires Python 3 and the [Pillow](https://pillow.readthedocs.io/en/stable/) library (`pip install Pillow`). The tool is a GUI built in tkinter and is fairly self-explanatory, simply move your sliders to design a nice looking diagram, select an icon, fill in the fields below the preview, and click "Generate Output." Resulting code is all included in the `parliament_gui_code.txt` file, comments explain where to put each part.

## Guides
Guides are coming soon. For now, take a look at the sample code provided in this repo, and the commented output of the diagram creator tool. You can also look to a [handy example](https://steamcommunity.com/linkfilter/?url=https://github.com/Flaxbeard/hoi4-parliament-diagram) someone has published on the Steam workshop (I am not affiliated with this example).

## License / Credit
No credit needed, but feel free to shoot me a PM on Discord (Flaxbeard#6752) if you make anything neat with this, I love to see what people can make. If so inclined, feel free to thank "Flaxbeard" in your mod credits, but this is not nececssary.

Additional thanks goes to fedacking for some helpful changes to the program.

## Ingame Example
![An example parliament diagram](https://i.imgur.com/8dginEz.png) ![An animated version](https://i.imgur.com/istu01c.gif)

## Diagram Creator Tool
![An example of the GUI tool](https://i.imgur.com/CeGxgJh.gif)

## Related Tools
Looking for other neat HOI4 GUI widgets? Check out:
- My [HOI4 Scripted Graphs](https://github.com/Flaxbeard/hoi4-scripted-graphs) repo with examples and documentation for making line or radar graphs.
- [Yard1's fantastic Pie Chart](https://github.com/Yard1/HoI4-Scripted-GUI-Pie-Chart) repo for custom pie charts.
