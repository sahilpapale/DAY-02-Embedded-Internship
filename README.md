## Day 02 – LED Pattern Generation using GPIO

### Objective
- To generate different LED patterns using digital output pins.
- To understand sequential control of multiple GPIO pins.

### Hardware Used
- Arduino Uno
- 4 LEDs
- 4 Current limiting resistors
- Breadboard and jumper wires

### LED Configurations
- 4 LEDs connected to digital pins.
- LEDs arranged side-by-side.
- All pins configured as OUTPUT using pinMode().

### Patterns Implemented

1. Running LED (Left to Right)
   - One LED turns ON at a time.
   - Sequence moves from left to right.
   - Previous LED turns OFF before next turns ON.

2. One-by-One ON then All OFF
   - LEDs turn ON sequentially.
   - After all LEDs turn ON, all turn OFF simultaneously.
   - Pattern repeats continuously.

3. Alternate 2-LED Pattern
   - LED1 & LED3 ON, LED2 & LED4 OFF.
   - Then LED2 & LED4 ON, LED1 & LED3 OFF.
   - Pattern alternates repeatedly.

### Concepts Learned
- Digital output control of multiple GPIO pins.
- Timing control using delay().
- Sequential logic implementation.
- Basic embedded programming logic building.

### Learning Outcome
- Improved understanding of GPIO manipulation.
- Learned pattern generation using loops.
- Developed logical thinking for embedded applications.
