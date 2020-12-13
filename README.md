# RE:Flex Dance Pad Hardware Designs
This repository contains source documents and manufacturing files for the RE:Flex Dance Pad's mechanical parts. It was created using [Fusion 360](https://www.autodesk.com/products/fusion-360/). However, future versions will be built with FreeCAD, due to Fusion's new pricing plan.

In this repository you will find:
- Fusion 360 source archives for the v1 (deprecated, and non-final) and v2 dance pads. These archives can be used to act as a reference model of RE:Flex Dance Pads, and future revisions.
- A folder of parts to be 3D printed in PLA.
- Parts lists for building a pad, bar, and doubles connectors. Currently this only lists the European vendor 'Motedis' parts for the base frame. It can be replicated with similar parts from 8020 and other vendors.

![](https://raw.githubusercontent.com/ReflexCreations/hardware-design/master/images/cad-model.PNG?raw=true "CAD Pad")

## Getting your own

Under part-lists.txt you can see a full list of parts required to complete this project. You can treat it as your own checklist. Please also save a list of where you have your parts, and feel free to submit it along with your country. 

### Tools
Currently, you will also require a soldering iron for the through-hole electronics parts, and an M8 allen key to secure the entire framework together.

## Future Improvements

The following changes could help in the future to provide for a better project:
- More investigation into different bar options would be nice. Currently the bars holding screws have to be tightened strongly to avoid it slipping, which is a bit of a hazard if someone leans their full weight on the bar and hasn't tightened the screws very well. In some cases there may also be a need to have support behind the bar, since the pad may tip backwards for players that like to launch themselves off the pad at high velocity.
- The feet only support 150kg each, which may be a problem if someone were to go out of their way to break them. So other options could be useful here.
- Previous iterations of the panel to sensor adapters have been the weak point most likely to break. The current version seems good, but this is still worth looking at, considering it's fundamental to the pad functioning.
- Better cable routing. It's currently a bit ugly all around. It'd be nice if it didn't travel underneath the pad, too.
- Less manual positioning of parts. Currently, you have to 'eyeball it' a little bit as you place panels down onto their velcro holders. It's also a little bit of a manual task to ensure aluminium extrusion spacings and sensor holder positions. Sometimes this requires re-doing certain steps of the build as a result. I've included some 'spacers' that can be 3D printed for the latter tasks, but the former is still going to be a bit difficult.
- A method to connect pads for doubles while removing the outer pad extrusions to reduce distance between pads.
- A more dedicated placement for the I/O board (potentially extending the front of the pad) so that it can fit within a 9 panel pad.
- A configuration utility to provide parameterized 3D printed parts would be very useful here so that the end user doesn't have to deal with CAD software.
- We should have a 'sourcing' folder that lists parts and how they can be easily acquired in multiple different countries.
- We should also really have a nicely formatted build guide, as currently the user has to use the CAD model as their own reference.
- Switching the sources to FreeCAD would be a huge improvement.
- Other panel format CAD specifications. SMX, Pump, RH, and Technomotion formats would be great.
- A 'travel pad' fork of this project. Utilizing less parts in a much smaller form factor could make this a more accessible project to those not looking to spend a small fortune.
- 3D printing these parts takes significant time (several days). Building out a reliable source of parts that are mass-produced would make this more accessible. If you'd like to sell parts, feel free to get in touch.
- Panels are also a bit more difficult to source. Having a reliable seller of finished aluminium/acrylic panels built to specification for this project would make this more accessible.
- Some parts would be nice to have in a sold kit form. The load cell sensors, velcro dots, cables, cable ties and power supply are all extra parts that require a bit of internet sleuthing to get ahold of.
- Finding a reliable source for a comfortable bar cover would be nice. We use a 40mm inner diameter foam insulation, which is nice, but a little difficult to source.
- One issue by experimentation is that the sensors don't have the same response to equal mass (seemingly 0.7-1.3 range of certainty). This isn't necessarily a problem, but is worthy of investigation nonetheless. It's likely due to the way the panel to sensor standoffs are implemented, which a redesign may rectify. If not, we would be able to calibrate the sensors in the software utility. 

## License

For license details, see LICENSE file