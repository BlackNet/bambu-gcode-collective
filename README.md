# bambu-gcode-collective
Bambu Studio gcode for start/stop/layer change/change filament/etc. 

Combined effort!  This is a work in progress, and please, please, PLEASE backup your config BEFORE adding any of these changes to your settings and save these as a NEW PROFILE to not overwrite the existing ones.  Also, this is a work in progress, and please let us know of any changes that need to be made.

Contact us either me or on Cinderwing discord. 3D Printing Experimentation and Discussion (All Printers)

Merger of other sets:
1) https://github.com/bambulab/BambuStudio/issues/1661  - speeds up filament changes
2) https://www.printables.com/model/582382-bambulab-profile-for-up-to-60-purge-reduction  - waste reduction

Source for the gcode files can be found here:
* change filament / layer change / end gcode / pause:  https://github.com/bambulab/BambuStudio/blob/master/resources/profiles/BBL/machine/fdm_bbl_3dp_001_common.json
* machine start is MACHINE + NOZZLE SPECIFIC:  https://github.com/bambulab/BambuStudio/tree/master/resources/profiles/BBL/machine
