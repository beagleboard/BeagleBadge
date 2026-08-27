# BeagleBadge

BeagleBadge is an open hardware, battery-powered Linux computer in a badge form factor. It combines a 4.2-inch black-and-white e-paper display with physical controls, sensors, indicators, and wireless connectivity for interactive badges, portable demos, education, and experimentation.

## Hardware overview

- Texas Instruments AM62L processor with two 64-bit Arm Cortex-A53 cores running at up to 1.25 GHz
- 256 MB LPDDR4 and 32 MB OSPI flash
- 4.2-inch, 400 Ã— 300 black-and-white e-paper display
- 2.4 GHz Wi-Fi 6 and Bluetooth Low Energy 5.4 using the TI CC3301
- LoRa connectivity using a Wio-SX1262 module
- microSD card slot, USB-C, and USB 2.0 Type-A host port
- Five-way joystick, four push buttons, RGB LED, indicator LEDs, and buzzer
- Six-axis accelerometer and gyroscope, ambient-light sensor, and temperature sensing
- Single-cell battery charging, power-path management, and fuel gauge
- Grove, 1 mm-pitch, and 2.54 mm-pitch expansion connectors

Specifications are based on the current bill of materials and are subject to change while the design is being finalized.

## Repository contents

| Path | Contents |
| --- | --- |
| [`design/`](design/) | Board source, bill of materials, and manufacturing files |
| [`docs/`](docs/) | Documentation source |

## Contributing

Contributions to the hardware and documentation are welcome. Please open an issue before making a substantial change so that the proposed direction can be discussed. Keep hardware changes accompanied by updated design and manufacturing files, and update the documentation when user-visible behavior changes.

## License

The files under [`design/`](design/) are licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](design/LICENSE). The documentation under [`docs/`](docs/) is licensed under the [MIT License](docs/LICENSE).
