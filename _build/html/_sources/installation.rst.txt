Installation
============

This section details instructions to install **Batch Render** in your computer, the tutorial is focused on *Windows* devices, but the steps are pretty much the same for *MacOs/Linux*.

Having **Blender** installed is a pre-requesite.

#. **Download** `Python <https://www.python.org/downloads/>`_

    #. When installing **Python**, make sure to check the **'Add Python X.x to PATH'**

#. After downloading **Batch Render**, you can place the folder anywhere you want
#. On *Windows*, search for **'Edit environment variables for your account'**
#. Click on **'Environment Variables...'**
#. Double click on the variable **'Path'** either on *User variables* or *System variables*
#. Click **'New'** and paste the *address* of **Batch Render's** folder
#. Click **'New'** again and paste the *address* of **Blender's** installation folder
#. **Confirm** all changes

To add a variable to **PATH** in *Linux and MacOs* run the following command from the terminal

``export PATH=$PATH:/direction/to/folder``

You might need to restart your computer for the installation to take effect.

Why do we need to do this?
++++++++++++++++++++++++++

Adding **Blender** and **Batch Call** to **PATH** means that you can call them from the terminal without including the full path to the file, it's much more convenient.

To check if the installation was successful open cmd/terminal:

* **Run** ``Blender``, if **Blender** launches, it's correct
* **Run** ``batchCall.py``, if **preset selection** shows up, it's correct