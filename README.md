# WokWi-Chip-nJK
## Description
Simulates a negative edge-triggered JK flipflop chip.

3 inputs: J, clk, K

2 outputs: Q and Q_bar (not Q)

## Usage
To use this chip in your project, include it as a dependency in your `diagram.json` file:

```json
"dependencies": { "chip-nJK": "github:rozw-m/Wokwi-Chip-nJK@2.0.1" }
```

Then, add the chip to your circuit by adding a `chip-scope` item to the `parts` section of `diagram.json`:

```json
  "parts": {
    ...,
    "type": "chip-nJK", "id": "chip2", "top": 105.6, "left": 192, "attrs": {},
```

The actual source code for the chip lives in [src/main.c](https://github.com/rozw-m/Wokwi-Chip-nJK/blob/main/src/main.c), and the pins are described in [chip.json](https://github.com/rozw-m/Wokwi-Chip-nJK/blob/main/chip.json).

## Example of usage
An example [WokWi project](https://wokwi.com/projects/436091135882005505) using this chip.
