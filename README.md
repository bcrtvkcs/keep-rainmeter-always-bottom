# Keep Rainmeter Always on Desktop

Keeps Rainmeter windows to stay on desktop. Rainmeter skin windows can unexpectedly appear on top of other windows during window switching events (e.g. Alt+Tab), application focus changes, or when triggered by external scripts. This mod forces all Rainmeter windows to remain below all other windows at all times, using a `EVENT_SYSTEM_FOREGROUND` event hook to push them to the bottom of the Z-order whenever any window comes to the foreground.

## Compatibility
- Windows 10 and Windows 11
- Targets `windhawk.exe` only
