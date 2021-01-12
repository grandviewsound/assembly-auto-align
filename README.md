# assembly-auto-align
Keyboard Maestro macros for Pro Tools assembly.

## Setup
- Setup an MXF Guide track to align sound rolls too
- Open Auto-Align Post and set MXF Guide as the reference track
- Switch to static view and collapse plugin, which makes it easier to read sample offset
- Select a clip and preview it, to confirm sample offset displays
- Create a group for the sound rolls
- Switch nudge value type to samples
- With groups on, select a clip of sound rolls and trigger macro (default is Command-Option-Control-Shift-*)
- Manually enter offset value in Auto-Align Post window, into the Keyboad Maestro user input window, be sure to include (+/-) in front of number
- Hit enter and give it a second to change nudge value, then nudge clips
- Confirm sync if needed and then move onto next clip
