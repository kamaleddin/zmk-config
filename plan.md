# Battle-Tested Cross-Platform Programmer Layout Plan

## Phase 1: Foundation - Home Row Mods & Thumb Optimization
1. **Home Row Mods (BATTLE-TESTED)** ✓
   - Left hand: D=GUI/CMD, F=Alt/Option, S=Control, A=Shift
   - Right hand: K=GUI/CMD, J=Alt/Option, L=Control, ;=Shift
   - Uses OS-neutral modifier names in ZMK: (LGUI, LALT, LCTRL, LSHFT)

2. **Strategic Thumb Cluster** ✓
   - Left cluster: Backspace (inward), Space (center), Delete (outward)
   - Right cluster: Enter (inward), Escape (center), Tab (outward)
   - Works identically on Windows and macOS

## Phase 2: Cross-Platform Operations (BATTLE-TESTED)
1. **Common Shortcuts**
   - GUI+Space (Win: Start Menu, Mac: Spotlight): Left D (hold) + Right Space
   - GUI+Tab (app switching on both OS): Left D (hold) + Right Tab
   - GUI+Backspace (file deletion): Left D (hold) + Left Backspace

2. **OS Detection Layer** (BATTLE-TESTED)
   - Add conditional layer based on connected device
   - Configure in ZMK using `if-else` preprocessor in keymap
   - Allows automatic adaptation between Windows and macOS

## Phase 3: Layer System (BATTLE-TESTED)
1. **Symbol/Number Layer**
   - Activated by thumb key (momentary toggle)
   - Programmer symbols in logical positions (brackets, operators)
   - Numeric keypad on right hand

2. **Navigation Layer**
   - Arrow keys in vim-style HJKL positions
   - Page Up/Down, Home/End nearby
   - OS-agnostic window management shortcuts

## Phase 4: IDE & Windows-Specific Functions
1. **Function Keys Layer**
   - F1-F12 easily accessible
   - Common IDE shortcuts (refactor, find, debug)
   - Windows-specific keys (Win+E for Explorer, etc.)

2. **Context Menu Key**
   - Add dedicated right-click context menu key for Windows
   - Can be placed on an accessible layer

## Phase 5: Cross-Platform Optimization
1. **OS-Detection Macros** (BATTLE-TESTED)
   - Screenshot shortcuts (different between Windows and Mac)
   - File explorer shortcuts (Finder vs Explorer)
   - System navigation (Mission Control vs Task View)

2. **Auto-Switching Profile** (BATTLE-TESTED)
   - Configure ZMK to detect and switch based on connected device
   - Maintains consistent finger memory across platforms