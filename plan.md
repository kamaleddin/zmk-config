# Battle-Tested Cross-Platform Programmer Layout Plan

## Phase 1: Foundation - Home Row Mods & Thumb Optimization
1. **Home Row Mods (BATTLE-TESTED)** [x]
   - Left hand: D=GUI/CMD, F=Alt/Option, S=Control, A=Shift
   - Right hand: K=GUI/CMD, J=Alt/Option, L=Control, ;=Shift
   - Uses OS-neutral modifier names in ZMK: (LGUI, LALT, LCTRL, LSHFT)

2. **Strategic Thumb Cluster** [x]
   - Optimized positions for frequently used keys
   - Configures for Kinesis Advantage 2 layout
   - Works identically on Windows and macOS

## Phase 2: Cross-Platform Operations
1. **Common Shortcuts** [x]
   - GUI+Space (Win: Start Menu, Mac: Spotlight): Left D (hold) + Right Space
   - GUI+Tab (app switching on both OS): Left D (hold) + Right Tab
   - GUI+Backspace (file deletion): Left D (hold) + Left Backspace

2. **OS Detection Layer** [ ]
   - Add conditional layer based on connected device
   - Configure in ZMK using `if-else` preprocessor in keymap
   - Allows automatic adaptation between Windows and macOS

## Phase 3: Layer System
1. **Symbol/Number Layer** [x]
   - Symbol layer activated by Space key (momentary toggle)
   - Number layer activated by Delete key (momentary toggle)
   - Symbol layer: Opening symbols on left hand, closing symbols on right hand
   - Number layer: Digits on home row, arithmetic operators below

2. **Navigation Layer** [x]
   - Arrow keys in vim-style HJKL positions
   - Page Up/Down, Home/End nearby
   - Word navigation with Ctrl+arrows

## Phase 4: IDE & Windows-Specific Functions
1. **Function Keys Layer** [x]
   - F1-F12 accessible on the top row
   - Enter/F10 as dual-function key

2. **Context Menu Key** [ ]
   - Add dedicated right-click context menu key for Windows
   - Can be placed on an accessible layer

## Phase 5: Cross-Platform Optimization
1. **OS-Detection Macros** [ ]
   - Screenshot shortcuts (different between Windows and Mac)
   - File explorer shortcuts (Finder vs Explorer)
   - System navigation (Mission Control vs Task View)

2. **Auto-Switching Profile** [ ]
   - Configure ZMK to detect and switch based on connected device
   - Maintains consistent finger memory across platforms

## Phase 6: Ergonomic Optimizations
1. **Seamless Layer Integration** [x]
   - Layer access through hold-tap keys
   - Space produces space character on tap, activates Symbol layer on hold
   - Delete produces delete character on tap, activates Number layer on hold

2. **Matching Symbol Pairs** [x]
   - Organized symbol placement for programmer efficiency
   - Opening symbols on left hand, closing symbols on right hand
   - Placement mirrors the physical finger use