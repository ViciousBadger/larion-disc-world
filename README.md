This is a simple add-on for my Larion World Generation mod that limits land
generation to a circle of approximately 3500 blocks in radius. The shape of the
landmass(es) within this circle vary wildly between seeds. 90% of the time, most
of Minecraft's biomes are present despite the limited world size.

Only two files from Larion have been changed to make this possible - continents
and the temperature sinewave, which has been made slightly smaller and capped so
it doesn't repeat.

If you want to make the generated area larger or smaller it's easy to do so, just edit the file `data/laron/worldgen/density_function/overworld/circle.json` file and change two really small numbers (`0.00025`) to something else, or even make them not the same number for an ellipsis world. You can adjust the other small number in `temperature_sine.json` to fit with the new size. 

This mod/datapack depends on Larion to work and must be loaded **after**
Larion. If you use the Fabric mod versions, this should happen automagically,
but if you use the datapack versions, you may have to look into Paxi or similar
tools to get them to order correctly.

You may have a hard time finding woodland mansions - if your world has none,
you'll have to create one yourself with cheats!

