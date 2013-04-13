EVE Online STL models of ships and other things.

## Notes
* These are raw exports from the .stuff using Triexporter with no textures and only using the high detail `.gr2`'s
* Some of the larger capital ships came out awkward; I'm not sure why this is.
* I don't know 3D modeling at all so pull request are welcomed if you wanted to clean/fix them up.

## Tools Used
[TriExporter](http://dl.eve-files.com/media/corp/SeriousM/TriExporter_2009.zip) (Windows only, maybe works in wine)

[Blender](http://www.blender.org/download/get-blender/) (Windows/Linux/OSX/FreeBSD)

## How I Did It So You Can Too
#### TriExporter
Open Triexporter and `File > Set EVE Folder` and navigate to your Eve install (default is typically C:\Program Files\CCP\EVE\).

After the "res" folder shows up, expand it to `res > dx9 > model > ship > [whatever you want] `. 

You can double click any `.gr2` to load the model into triexporter; sometimes the model will look really messed up, don't worry - it doesn't mean anything until you import it in to blender.

Now that you've picked a ship you like, we need to export the file to a `.3ds` - you can do that by going to `File > Export Tri-model`, give it a name and save it somewhere you can remember it.

#### Blender

Ignore the splash screen and go to `File > Import > 3D Studio (.3ds)`, navigate to where you just saved the `.3ds` file and double click it.

Now, you may or you may not see some of your ship, but what you sure are seeing is that stupid cube blender places into new files, let's get rid of that. 

Look to the top right and you should see the "Outliner" - in there, you should see the "Scene" and it may or may not be expanded, if not expand it. In that list, you should see an object called "Cube". Right click it and Delete.

Now you should be able to see your ship but it's facing straight up. If that's how you like it, ignore this step. In the "Outliner" select "shape" in the list. Move your mouse over the ship and hit `Tab` to enter "Edit mode". (Your ship should turn orange if you're in edit mode)

In the list to the left of the screen "Rotate" should near the top double click it. Still on the left side, now towards the bottom you should see the "Rotate" properties. Check the `X` Axis box and set the angle to 90 degrees.

Next, let's move the ship up some. To do that, double click "Translate" from the top part of the list on the left. Change the `Z` Vector to 1 or 2 depending on the size of the ship.

Time to make it big! In that top left list, you should see "Scale" - click this once and type in `10` on your keyboard.

All that's left is to export it as a `.stl` and you can do that by going to `File > Export > Stl (.stl)`, pick a place to save it. 

## CCP Copyright Notice

Need to figure this out.
