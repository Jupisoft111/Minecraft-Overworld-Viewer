# Minecraft Overworld Viewer

Note: to download either the executable or the full source code go to the releases tab and there click on the files with a full date and time followed by "_EXE" for the executable or "_Source" for the full source code (which also comes with a precompiled executable).

Free application capable of loading all the region files (.mca) of any Minecraft world and it's selected dimension and export all of them as 5 different image types of 512 x 512 pixels.

Then it can load all those images and join them into a single massive image to view the full world at once. It's highly suggested to use "IrfanView 64-bit", since after several tests is the only free tool that can load even the biggest images without any error.

Each pixel represents a Minecraft block, and the average color of each Minecraft texture was calculated with very high quality (see attached image). It also has an option to modify each block color based on it's current world height (vertical position), making it darker at lower levels and brighter at higher ones.

While it fails to generate a full world image (in the case the regions are too far away form each other), it will analyze the zones of the map with less blocks on them and recursively remove them until it gets the bigger map possible with the biggest quantity of blocks in it.

In that case it will also export images up to 8.192 x 8.192 pixels with all the excluded regions, but out of place, just to quickly see what was removed from the final massive map.

This tool was inspired by all the awesome work of all the members of the Hermitcraft server, specially Xisumavoid, so thanks a lot to everyone, and have a nice day :-)

[Update: 2021_11_30_05_31_27_573]
Thanks to brandond25 for the suggestion of adding height maps. Thanks to him, it now includes 18 unique map types and finally it supports all existing Minecraft versions at once, even 1.18+ or the future "deep_dark" biome. Also fixed several bugs and improved perfonmance in some functions, although 1.13+ worlds still are very slow (for now)...
