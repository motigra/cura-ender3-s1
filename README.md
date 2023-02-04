# Creality Ender 3 S1 - Cura Profiles

This repo contains slicer settings for the **Creality3D Ender 3 S1** 3d printer (with stock hardware), used in **Cura 5.1.0**.

> The contents of the repo represent the contents of `%appdata%\cura\5.1`

## Why?

As of version 5.1, Cura slicer still doesn't have dedicated profiles for the Ender 3 S1 model, meanwhile the Creality Slicer software which is a Cura clone is behind on features.

My goal is to create customized, reliable set of profiles & configurations for Cura and the Ender 3 S1, and as I adjust and improve my prints keep track of the changes via git change history.

## Custom stuff

Under [`definition_changes`](definition_changes/Creality+Ender-3+S1_settings.inst.cfg) you can find customized start+end gcode, that heats the bed and nozzle to the print's 1st layer temperature and follows the recommended start/end flow from Creality.

Under [`quality_changes`](quality_changes/) you can find custom profiles for eSun PLA+ and PETG filaments for 0.2mm and 0.3mm layer heights, that work for me.
