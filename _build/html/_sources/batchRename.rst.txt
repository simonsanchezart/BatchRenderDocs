Batch Rename
============

**Batch Rename** is a tool included with **Batch Render** that allows you to *suffix and posfix* to the name of all the files in the current folder **from the terminal**.

This can be useful in case you want to add the name of a material to all the maps in the current folder so the material is matched properly by **Batch Render**. And of course, it can also be used for other stuff outside *Batch Render*.

To use this tool, from the terminal, you must navigate to the folder where the files you want to modify are located, beware that **this will modify the name of all the files in that folder**, you might want to isolate them in temporary subfolders.

Arguments
^^^^^^^^^

* **-s**: *Adds* a **suffix** to all the files
* **-rs**: *Removes* a **suffix** to all the files
* **-p**: *Adds* a **posfix** to all the files
* **-rp**: *Removes* a **posfix** to all the files

For this example, let's suppose we have 3 files in the current folder:

* baseColor.png
* roughness.png
* height.png

Running the command ``batchRename.py -s red_`` *(insert suffix red_)* will leave us with:

* red_baseColor.png
* red_roughness.png
* red_height.png

Running the command ``batchRename.py -p _myObject`` *(insert posfix _myObject)* will leave us with:

* red_baseColor_myObject.png
* red_roughness_myObject.png
* red_height_myObject.png

Running the command ``batchRename.py -rs red_`` *(removes suffix red_)* will leave us with:

* baseColor_myObject.png
* roughness_myObject.png
* height_myObject.png

Running the command ``batchRename.py -rp _myObject`` *(removes posfix _myObject)* will leave us with:

* baseColor.png
* roughness.png
* height.png