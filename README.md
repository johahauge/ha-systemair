# Systemair on Home Assistant
Systemair modbus yaml-files for Home Assistant with modbus over TCP. 

## Applies to
These registers applies to following older models:
    VR400
    VR700
    VR700DK
    VR400DE
    VTC300
    VTC700
    VTR150K
    VTR200B
    VSR300
    VSR500
    VSR150
    VTR300
    VTR500
    VSR300DE
    VTC200
    VTC100

Does not apply to the newer SAVE-series. Note: Only tested with VR400.

## Requirements
- Home Assistant
- Systemair model that supports modbus communication. You might need to replace the motherboard with the newer PCU-EC4
- A device to send Modbus as TCP connected to the motherboard

## Implementing
Copy the content or files to your Home Assistant installation in the config directory. You can include the content directly into the configuration.yaml file, but that will be messy.

Not all registers are included. Please reference the Systemair modbus PDF for more information and registers. 
You might have to do some manual editing to make it work with your setup.

## Registers
In the Modbus reference, use the register address - 1.
