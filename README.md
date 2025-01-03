Backup for my Ender 3v2, currently mostly stock with a CR Touch w/stock metal bracket. Mostly small mods such as magnetic PEI plate, capricorn tube, and the mini satsana duct (remix) from thingiverse.

If you're setting up Klipper for the first time with an E3v2 4.2.2 Mainboard everything should be pretty dialed in. Can be adjusted for mostly any printer if you know what to change. Run a PID tune (see macros.cfg) for the bed,nozzle, as well as [input shaper] calibration, e-steps, and tune z offset (tune it, then tune current filament flow, then tune z offset again).
A few things should be changed/tuned in the slicer as well, i.e. pressure advance as well as retraction per filament. Included samples and links to useful tools and guides. See [firmware_retraction] and [extruder] pressure_advance in printer.cfg.

I highly recommend Orcaslicer (https://github.com/SoftFever/OrcaSlicer).

If you're setting up Klipper for the first time, use KIAUH (https://github.com/dw-0/kiauh). Very straightforward.

# Klipper-Backup 💾 

Klipper backup script for manual or automated GitHub backups. This backup is for Klipper+Moonraker, with Mainsail interface.

This backup is provided by [Klipper-Backup](https://github.com/Staubgeborener/klipper-backup).
