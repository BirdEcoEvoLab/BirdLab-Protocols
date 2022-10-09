.. include:: ../../links.rst
.. |date| date:: %d %B %Y %H:%M %Z (%z)

Qiaxcel handling
===============================


:Author: Vinay K L (Originally compiled by Samriddha Ghosh and Saniya Patel in 2018)
:Copyright: None
:Date: 07/10/2022

Purpose
-------
To assess the fragment profile of NGS libraries

Before run
-----------

#. Keep the gel cartridge, buffer and tray out for at least 30 min before run. NOTE: The cartridge should always be in upright position.
#. First switch on the laptop and then the instrument. Open the software.
#. Check pressure on the instrument. Pressure through out should be more than 30.
#. If not adjust the pressure with nitrogen cylinder valve and regulator for the inflow. NOTE: First the valve should be open, then adjust the regulator.
#. Add 6ml QX wash buffer and 2ml Mineral oil to W1 and WP slot of the buffer tray
#. Add 16ml of separation buffer and 4ml of Mineral oil to Buffer slot of the buffer tray
#. Add 15 ul of alignment marker compatible with size marker (check for compatibility chart) in a 12-strip tube and place it in the Marker1 position in the buffer tray.
#. Dilute samples to ~ 10ng/ul and add to another 12 strip tube / plate (for 95 samples)
#. Dilute size marker to 5, 10 or 20ng/ul based on method. Add this to a empty tube in the samples strip tube  or plate.
      NOTE: Size marker 50bp - 1.5kb is only compatible with fast kit/ screening kit. Do not run this with High Res kit.
#. Insert the cartridge and smart key (plastic node on back). Click on “Latch” under “process” in the software for the instrument to attach the cartridge.
#. Click on “load position” and open the lid to place the buffer tray, close the lid and then click on “park position”.
#. Place sample tubes/plate to sample tray.
#. Go to “Service” >  “Maintenance” > “Purge” click on “short purge”, once it is over go for “long purge”.


Software settings
-----------------

#. “Process profile” > “process profile” - choose “default highness V 2” for High Resolution kit. Fast profile for screening kit.
#. “Run parameters” - choose method (OM500 OM800 etc based on fragment size). Right click on size marker position (eg. A1) to define the position.
#. “Analysis” > check in the box for “smear analysis profile” (only for smear profile ex. library prep).
#. “Marker” > “marker selection” - check box for “run marker side by side with sample”. Choose appropriate size marker and alignment marker that is being used.
#. “Sample selection” - enter plate name.
#. “Sample info” - add sample names.
#. “Run check” - check box if the 3 criteria are fulfilled. NOTE: If any parameter is not compatible it will show up in yellow, readjust the settings.
#. Check pressure once more. (preferably stable at ~35).
#. Start the run.


Post run
--------

#. After a successful run, select all sample (ctrl + A), go to “Analysis” tab.(on your right side) - Do a analysis with “no marker” - This will align samples with capillary migration.
#. Do analysis again with the marker table.
#. Band size and peak height should be available for each sample.
#. Save report.

Pre-shutting down processes
---------------------------

#. Open the lid and remove samples and discard them, close the lid.
#. Click on “load position” to take the buffer tray out. Click on park position after closing the lid.
#. Keep the buffer tray and alignment marker separately covered with foil in 4 degrees.
#. Click on “unlatch” and remove the smart key and cartridge. Keep it upright in 4 degrees.
#. Log out and exit the software.
#. Switch of the instrument.
#. close the nitrogen cylinder.
#. Have a cup of strong coffee.
