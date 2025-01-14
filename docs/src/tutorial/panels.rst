Different panels and settings
=============================

The default chemiscope visualizer is organized in three main panels: the map,
the structure viewer and the environment information display. Additionally,
clicking on the dataset title (on top of the map) will display some metadata
about the dataset (description, authors, references). This section will
present each one, as well as the main settings accessible to customize the
display.

The map is a 2D or 3D scatter plot showing properties for all the environments
in the dataset. You can set which properties (structural or physical) should be
used a the x, y, and potentially z axis; as well as for color and size of the
points. Additionally, properties which have string values (an not numeric
values) can be used as category data to set the symbols used for the points. To
open the settings modal window, click on the hamburger menu (the ☰ symbol) on
the left of the dataset title.

.. figure:: ../img/map.png
    :width: 80 %

    The map panel in 2D mode and the related settings

The structure panel is a 3D molecular viewer based on `3Dmol.js`_. The settings are
accessible through the hamburger menu (☰) on the right of the viewer. The
settings are grouped into **representation** (how is the molecule rendered);
**supercell** (how many copies of the unit cell to display); **environments**
(how atom-centered environments are displayed); **camera** (reset the camera in
along one of the given axis); and **trajectory** (playback related settings).

.. figure:: ../img/structure.png
    :width: 80 %

    The structure panel and related settings

Finally, the environments information panel features sliders and text input to
allow for an easy selection of the environment of interest. The play button on
the left of the sliders activates the trajectory playback, looping over the
structures in the datasets or the atoms in a structure. By clicking on the
labels at the top (*structure XXX* and*atom XXX*), one can hide or show the
full property tables. These tables show all properties in the dataset for the
currently selected environment.

.. figure:: ../img/info.png
    :width: 40 %

    The environment information panel fully expanded

.. _3Dmol.js: https://3dmol.csb.pitt.edu/
