Video Games
===========

.. contents:: Table of Contents

Real-Time Strategy (RTS)
------------------------

Strategies
~~~~~~~~~~

These are common strategies that apply to most RTS games:

-  Half of the units should be units that gather resources.
-  Focus on economy. A good economy helps to fund large armies and upgrades.
-  Larger armies normally beat smaller optimized armies.
-  Only get upgrades in the late-game. It is important to first focus on the size of the army.
-  Always spend most, if not all, of the available funds to make units and buildings.
-  Learn the macro (simple and big concept) strategies before learning the micro (hard and small concept) strategies.
-  Learn keyboard shortcuts to save time.

Sandbox
-------

Minecraft
~~~~~~~~~

Java Versions
^^^^^^^^^^^^^

Each version of Minecraft only works with a specific version of Java. [1]

.. csv-table::
   :header: Minecraft, Java
   :widths: 20, 20

   18, 17
   17, 16
   16 or older, 8

Resource Packs
^^^^^^^^^^^^^^

Resource packs used to be known as texture packs. They allow for more customization beyond textures and can include animations, fonts, sounds, and support for other languages. [2]

The default texture size for Minecraft is 16x16 pixels. [3] The texture resolution size used by resource packs vary. 32-bit Java can only handle 64x64 textures. It is recommended to use a 64-bit installation of Java for bigger textures. [4]

Server (Self-Hosted)
^^^^^^^^^^^^^^^^^^^^

Depending on the use-case of the server, different Minecraft servers are recommended.

-  Vanilla = `SpigotMC <https://www.spigotmc.org/>`__
-  Plugins = SpigotMC
-  Mods, game-changing:

    -  <= Minecraft 1.13 = `Forge <https://forums.minecraftforge.net/>`__
    -  >= Minecraft 1.14 = `Fabric <https://fabricmc.net/>`__

-  Raspberry Pi = `Cuberite <https://cuberite.org/>`__

Forge Mods
^^^^^^^^^^

Mekanism
''''''''

Mekanism provides many tools and machines that help improve efficiency. This is important for other mods, such as Galacticraft, that require a large amount of resources.

Increase Ore Processing Yields
&&&&&&&&&&&&&&&&&&&&&&&&&&&&&&

**1x ore processing (tier 0):**

- Estimated time to create from scratch: 30 minutes.

::

   Energized Smelter

**2x ore processing (tier 1):**

- Estimated time to create from scratch: 45 minutes.

::


   Enrichment Chamber --> Energized Smelter

**3x ore processing (tier 2) [5]:**

- Estimated time to create from scratch: 2 hours.

::

   (Water)
      |
      |
      V
   Electric Pump
            |
            | *Mechanical Pipe*
            V
   Electrolytic Separator
            |
            | *Pressurized Pipe*
            V
   (Oxygen and Hydrogen)
       |           |
       |           ---> [Dump excess]
       V
   Purification Chamber --> Crusher --> Enrichment Chamber --> Energized Smelter

**4x ore processing (tier 3):**

-  Estimated time to create from scratch: 3 hours.
-  Create a Thermal Evaporation Plant. [6][7]

   -  These can be as short as 3 blocks high and as tall as 18 blocks high.
   -  Create the structure with a base of 4x4 Thermal Evaporation Blocks.
   -  Build up walls as high as desired. Leave a 2x2 opening in the middle. Do not cover.
   -  Replace one of the Thermal Evaporation Blocks with a Thermal Evaporation Controller.
   -  Replace two of the Thermal Evaporation Blocks with a Thermal Evaporation Valve.

      -  When complete, the entire Thermal Evaporation Plant will have a special particle effect to showcase that it has been properly built.
      -  Each Valve has two spots that can each be used as input (default) or output.
      -  Use one Valve for input of water via an Electric Pump and Mechanical Pipes.
      -  Use a second Valve for input of heat via a Resistive Heater and Thermodynamic Conductors.

          -  The brine will be created faster the hotter it is. The optimal temperature is 400 degrees Kelvin.

      -  Use a third Valve for output of brine via Mechanical Pipes.

         -  Use the Configurator tool to change the Valve to be an output instead of the default of input.

            -  Use either (1) an Energy Cube or (2) a Chargepad to charge up the Configurator tool.


::

   (Water)
      |
      |
      V
   Electric Pump
              |
              | *Mechanical Pipe*
              V
   Electrolytic Separator
              |
              | *Pressurized Pipe*
              V
   (Hydrogen and Oxygen)
        |           |
        |           -----------------------------------------------
        |                                                         |
        V                                                         V
   Chemical Infuser --> Chemical Injection Chamber --> Electrolytic Separator --> Purification Chamber --> Crusher --> Enrichment Chamber --> Energized Smelter
        ^
        |
        |*Pressurized Pipe*
        |
   (Chloride and Sodium)
        ^          |
        |          ---> [Dump excess]
        |
   Electrolytic Infuser Separator
        ^
        |
        |
   (Brine)
        ^
        | *Mechanical Pipe*
        |
   Thermal Evaporation Plant

[8]

**5x ore processing (tier 4):**

-  This is the highest tier of ore processing in Mekanism. [9]
-  Estimated time to create from scratch: 5 hours.

History
-------

-  `Latest <https://github.com/ekultails/lifepages/commits/master/src/games/video.rst>`__

Bibliography
------------

1. "Tutorials/Update Java. Minecraft Wiki. August 27, 2022. Accessed November 13, 2022. https://minecraft.fandom.com/wiki/Tutorials/Update_Java
2. "What is the difference between texture packs and resource packs in Minecraft?" Sportskeeda. August 2, 2021. Accessed November 13, 2022. https://www.sportskeeda.com/minecraft/minecraft-texture-packs-vs-resource-packs-what-s-difference
3. "How to Make a Minecraft Texture Pack." Beebom. April 8, 2022. Accessed November 13, 2022. https://beebom.com/how-to-make-a-minecraft-texture-pack/
4. "Best 64x or 128x?" Minecraft Forum. July 9, 2011. Accessed November 13, 2022. https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/resource-packs/1231175-best-64x-or-128x
5. "Minecraft Mekanism Tutorial Ore Processing Tier One and Two (Double and Triple ingots per ore)." YouTube UrbanCowGaming. November 12, 2020. Accessed December 11, 2022. https://www.youtube.com/watch?v=4VH99Mr2jvc
6. "Thermal Evaporation Plant." Official Mekanism Wiki. Accessed December 11, 2022.  https://wiki.aidancbrady.com/wiki/Thermal_Evaporation_Plant
7. "Modded Minecraft Tutorial : Brine, Evaporation Tank "NO solar & Self Powered"." YouTube K1 Inc. February 19, 2019. Accessed December 11, 2022. https://www.youtube.com/watch?v=0UgEmRco_Lc
8. "Minecraft Mekanism Tier 3 Ore Processing (4x Ingots per Ore) Tutorial." YouTube UrbanCowGaming. December 19, 2020. Accessed December 11, 2022. https://www.youtube.com/watch?v=dpYvPcIyQKk
9. "Ore Processing." Official Mekanism Wiki. Accessed December 11, 2022. https://wiki.aidancbrady.com/wiki/Ore_Processing
