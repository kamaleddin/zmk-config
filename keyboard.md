# Kinesis Advantage 2 ZMK Firmware User Manual

## Overview

This custom ZMK firmware for the Kinesis Advantage 2 keyboard features a range of ergonomic enhancements and productivity-boosting layers to improve your typing experience.

## Key Features

### Home Row Modifiers

Home row modifiers allow you to access modifier keys without moving your fingers from the home row.

| Key | Tap Function | Hold Function |
|-----|-------------|---------------|
| A   | Types "a"    | Left Shift    |
| S   | Types "s"    | Left Control  |
| D   | Types "d"    | Left GUI (Win/Cmd) |
| F   | Types "f"    | Left Alt     |
| J   | Types "j"    | Right Alt    |
| K   | Types "k"    | Right GUI (Win/Cmd) |
| L   | Types "l"    | Right Control |
| ;   | Types ";"    | Right Shift   |

**Usage:** Tap for letter, hold for modifier. For example, hold S and press F to get Ctrl+F.

### Symbol Layer

Access symbols quickly with the Space key.

**Activation:** Hold Space key (right thumb cluster, inward position)

| Row | Left Hand (Opening) | Right Hand (Closing) |
|-----|---------------------|----------------------|
| Home Row | [ ( { < `       | ` > } ) ]          |
| Bottom Row | ! @ # $ \|   | \| & * ? \\         |

**Design Philosophy:** Matching brackets and symbols are placed on corresponding fingers on opposite hands for intuitive typing.

**Usage:** 
- Hold Space + press key to type symbol
- Tap Space for normal space character

### Number Layer

Numeric keypad with arithmetic operators.

**Activation:** Hold Delete key (left thumb cluster, middle position)

| Row | Left Hand | Right Hand |
|-----|-----------|------------|
| Home Row | 1 2 3 4 5 | 6 7 8 9 0 |
| Bottom Row | - / * + = | . , _ % ^ |

**Design Philosophy:** Numbers are placed on the home row for the strongest fingers, with arithmetic symbols below for quick calculations.

**Usage:**
- Hold Delete + press key to type number or symbol
- Tap Delete for normal delete function

### Navigation Layer

Cursor and text navigation controls.

**Activation:** Hold Escape key

| Function | Keys |
|----------|------|
| Arrows | Right hand: ←↓↑→ (HJKL) |
| Page Navigation | Right hand top row: Home, Page Down, Page Up, End |
| Word Navigation | Right hand bottom row: Ctrl+←, Ctrl+↓, Ctrl+↑, Ctrl+→ |

**Usage:** Hold Escape + press keys to navigate

### Other Special Keys

| Key | Tap Function | Hold Function |
|-----|-------------|---------------|
| Escape | Types Escape | Activates Navigation Layer |
| Enter | Types Enter | F10 key |

## Layer Structure

1. **Default Layer (0):** Standard QWERTY layout with home row mods
2. **Numpad Layer (1):** Traditional numpad (toggle with top-right key)
3. **System Layer (2):** Reserved for system functions
4. **Navigation Layer (3):** Cursor movement and text navigation
5. **Symbol Layer (4):** Brackets, punctuation, and special symbols
6. **Number Layer (5):** Numeric keys and arithmetic operators

## Thumb Cluster Layout

### Left Thumb Cluster (from left to right)
- Backspace
- Delete (tap) / Number Layer (hold)
- End

### Right Thumb Cluster (from left to right)
- Tab
- Enter (tap) / F10 (hold)
- Space (tap) / Symbol Layer (hold)

## Tips for Efficient Use

1. **Home Row Modifiers:** Start with simple combinations and gradually build up to more complex ones as you adapt.

2. **Symbol Pairs:** Notice how opening and closing symbols are on corresponding fingers of opposite hands (e.g., left index finger for '(' and right index finger for ')').

3. **Number Entry:** For calculations or data entry, hold Delete with your left thumb and type numbers with both hands in their normal positions.

4. **Navigation:** Use the Escape+HJKL combination for efficient arrow key navigation without leaving the home row.

5. **Adaptation Period:** Allow 1-2 weeks to fully adapt to the home row modifiers and layer system.

## Troubleshooting

- **Accidental Layer Activation:** If you're accidentally activating layers, try to be more deliberate with your taps versus holds. The system uses a 200ms threshold to distinguish between them.

- **Modifier Timing:** Home row modifiers are designed to activate only when another key is pressed. If you press and release a home row key without pressing another key, it will output the normal character.

- **Layer Persistence:** Layers activated by hold deactivate when you release the key. If a layer seems "stuck," check if you're still holding a thumb key.