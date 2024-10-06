What are these files?

* tahoe_a.json: this is a metadata file for use with https://nickcoutsos.github.io/keymap-editor/.
  it stores a bunch of position and orientation info for each keys. a lot/all of this info is now
  already kept in zmk physical matrices for use with ZMK studio. 
* Kconfig.board: just defines the name for this keyboard for use when building via west
* Kconfig.defconfig: set new defaults for configuration settings
* tahoe_a.dts: contains most/all of the devicetree customization for tahoe's specific hardware config
* tahoe_a.keymap: determines what behavior a keypress maps to.
* taho_a.yaml: pure metadata file that can be used to auto-populate website lists and things
  (https://zmk.dev/docs/development/hardware-integration/hardware-metadata-files)
