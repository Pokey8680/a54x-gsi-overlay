# v1.0.5 - 8.Oct.24
- Sync source code

# v1.0.4 - 8.Oct.24
- Enable 25W fast charging
- ~~Add update.json so you can update the module directly from Magisk/KernelSU app~~ Not working, update manually for now

# v1.0.3
- Fix Always-On Display (AOD)
  - Wouldn't refresh before, now it does
  - Enabled by default
- Set default refresh rate to 120hz

#  1.0.2
- Use proper overlay values from the Galaxy A54 to obtain a holepunch cutout that's exactly the same as stock firmware
  - Hole punch location and size is now properly defined
  - Statusbar completely overlaps camera hole (Like on stock firmware)
  - Rounded corner padding more accurate
 
# 1.0.1
- Migrate strings.xml, integers.xml, dimens.xml, bools.xml and arrays.xml into one config.xml as per PHH's documentation
- SystemUI overlays are taken from incorrect values, some users may have experienced issues. Version 1.0.2 will fix these
- 

# 1.0.0
- Add power profile to prevent unneccesary power usage/battery drain
- Status bar height fixed
- Android respects the presence of the hole punch
- Status bar elements bottom aligned, similar to stock firmware
- Rounded corner padding fixed

# Alpha releases
# v0.6-alpha
- Reworked strings (again)

# v0.5-alpha
- Statusbar height adjusted

# v0.3-alpha
- Test overlays
- Adjust statusbar height

# v0.4-alpha
- Added SystemUI overlay
- Fix strings
- Statusbar elements now bottom aligned

  # v0.2-alpha
  - Adjusted status bar height

# v0.1-alpha
- Respect hole punch behavior
