# Anet-Cura-dual-extruder
Dual Extruder Cura settings for the Anet A8

I couldnt find this anywhere so thought id put it here in case others need it. Its important to note these settings assume that the printer firmware deals with the dual nozzle offset.

## things you will need
- An Anet a8 with a dual extruder, this will also work with the Anet A8-M
- Cura (as of writing its 4.6.x) > [Download from here](https://ultimaker.com/software/ultimaker-cura "Cura Download")
- 2 merged prints, these need to be 2 separate STL files that get merged in Cura

## Instructions
- Open Cura and import the profile from this repo via preferences > profiles
- Drop both STL files into Cura once the profile is imported 
- Select both STL models, then go Edit > Merge models. This should put them both together in the one view. 
- Select Nozzle one for the base print, 2nd nozzle for the second print. 

## Notes 
You can set different print settings (layer height and infil) for each nozzle or for all the settings. I find the goo tower very handy for cleaning the nozzles between colour changes (makes the print cleaner). The nozzles will likely pause every 2 layers to make sure they are running at the right heat (so dont be alarmed). 
