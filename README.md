# zmk-config-totem-dongle

Please see [here](https://github.com/GEIGEIGEIST/zmk-config-totem/tree/master) for all details

- Changed the default keymap to colemak-dh

## Debug firmware builds

- Normal CI builds (push/PR) use `build.yaml`.
- To build debug firmware, run the GitHub Actions workflow manually and set `debug_build` to `true`.
- Debug builds use `build-debug.yaml` and enable the `zmk-usb-logging` snippet for:
  - `totem_right_debug.uf2`
  - `totem_dongle_debug.uf2`
