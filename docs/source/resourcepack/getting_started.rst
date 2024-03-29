Getting Started
===================================

This will cover how to install the resourcepack, and how to rename rename an item to change it's texture.

Installation
----------

#. Install **ANY** of these

   * `Optifine <https://www.optifine.net/downloads>`_ 

   * `Lunar Client <https://www.lunarclient.com>`_ 

   * `CIT Resewn Fabric Mod <https://www.curseforge.com/minecraft/mc-mods/cit-resewn>`_ 
      
      * You can install the :doc:`modpack` which contains CIT Resewn + other common mods

#. Join the server and type /resourcepack
#. Press install.

That's it!

Your first custom item
------------
We will be creating a Meteor Client Sword.

#. Find the item you want (in this case, it's the Meteor Client sword in :doc:`items`)
#. Look at the text pattern to figure out what to name:

   * "Name: "Meteor Tool", Text: "meteor", ID: meteor_sword, Items:"All Tools and Weapons""
   
   * We are looking for the Text field, so we will rename our item to something containing Meteor (case insensitive, can contain formatting like colours)
   
   * Examples:

      * Meteor Sword
      * meteor
      * METEOR AXE
      * <red>METEOR
    
    * The Items field tells you what items can be renamed, in this case all tools and weapons can be renamed to make the meteor tool.
    
#. Rename your item using /itemname, or an anvil.

.. note::
  This simple tutorial does **not** apply to custom blocks, as it requires extra item frame work to be done.
  
  You can find more information on how to creat custom blocks in :doc:`blocks`


Uninstalling
------------
#. Run /resourcepack
#. Click "Uninstall"
#. Rejoin the server
