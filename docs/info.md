## How it works

The project generates a VGA video pattern animated circular patterns.

The VGA synchronization module generates the horizontal and vertical synchronization signals and provides the current pixel position. 

A hardware-friendly approximation of the distance from the center of each cell is used to generate concentric circular patterns without requiring expensive square-root calculations. The animation is controlled by an internal frame counter, which changes the position of the circular patterns over time.

## How to test

The project can be tested by connecting the Tiny Tapeout VGA outputs to a compatible VGA display or VGA interface.

After powering the design and providing the required clock and reset signals, the display should show circular patterns.

## External hardware

No external hardware is required beyond a compatible VGA display or VGA interface for visualizing the generated pattern.

KFL
