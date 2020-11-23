Batch Render
========================================

.. image:: batchLogoNoBG.png
   :scale: 70%
   :align: center

**Batch Render** is a *command line tool* that makes use of **Blender** to quickly render multiple objects from multiple angles.

**Features:**

* **Recursive rendering**, renders all objects from current folder and it's subfolders.
* Support for **.obj** and **.fbx**
* Automatic material creation and assignment

   * **Albedo** support
   * **Opacity** support
   * **Emissive** support
   * **Metallic** support
   * **Roughness** support
   * **Normal Map** support
   * **Height** support

* Automatically **fits the camera to the object**
* Easy **selection and creation of rendering presets**
* Easy **turntable generation** with custom amount of frames
* Render engine defined by render preset (supports **Eevee**, **Cycles** and **Workbench**)

|

.. image:: crateTurntable.gif
   :scale: 90%
   :align: center

*Example of turntable rendered with Batch Render*

.. toctree::
   :maxdepth: 1
   :caption: Contents:

   installation
   usage
   batchRename
   contact