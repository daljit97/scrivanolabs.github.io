# Version 0.14.5
- Improved line snapping algorithm.
- Minor bug fixes.

# Version 0.14.4
- Show shortcuts in side menu.
- Improved drawing of shapes with grid snapping enabled.
- Increase performance of vertical space tool on multicore machines.
- FIX: crash when using the vertical space tool.
- FIX: bug that caused stickers and pasted strokes to dissappear.
- FIX: pinch to zoom now cancels drawing if finger drawing is enabled.
- Other minor improvements and fixes.

# Version 0.14.3
- Various bug fixes and crashes

# Version 0.14.2
- NEW: Option to draw using fingers.
- NEW: Optional input prediction algorithm to reduce input latency.
- NEW: Experimental two fingers gesture to erase ink.
- NEW: Option to disable hiding the cursor when drawing.
- Further reductions in energy consumption while drawing.
- Ink strokes are now smoothed out when drawing with a mouse.
- Various other bug fixes.

# Version 0.14.1
- Restore "Erase everything option".
- Noticeably improved speed and power consumption of rendering engine.
- Improved ink smoothness (Windows only).
- Other small bug fixes.

# Version 0.14.0
- NEW: area eraser mode to delete all strokes inside or intersecting a path.
- NEW: option to enable eraser for highlighted strokes only.
- NEW: option to change eraser size.
- NEW: option to enable/disable automatic switching of tools.
- NEW: option to exclude images when using the selection tool.
- NEW: automatic snapping of lines to other lines or shapes.
- NEW: 2D axis shape
- NEW: selection now automatically snaps to grid when grid snapping is enabled.
- Major internal rewrite of application's data structures.
- Minor bug fixes and improvements.

# Version 0.13.9
- FIX: bug that prevented thickness changes to be applied immediately.
- FIX: dialog to switch pen types not large enough when app window is small.

# Version 0.13.8
- FIX: crash when using "Erase everything" option
- FIX: improved scrollbar behaviour to prevent accidental scrolling

# Version 0.13.7
- FIX: dashed and dotted styles are now remembered when switching between pens.
- FIX: drawing lines with highlighter by pressing and holding.
- FIX: custom fill colors are now correctly assigned when using dark mode.
- Improve PDF rendering quality on high DPI screens.
- Other minor tweaks.

# Version 0.13.6
- FIX: bug that caused scrolling and pinching to stop working.

# Version 0.13.5
- FIX: bug causing change in ink color and thickness when inserting stickers.
- Improved rendering quality of thick ink strokes.
- Minor improvements for rendering of selected strokes.

# Version 0.13.3
- NEW: Fountain pen style
- Eraser type and selection are now remembered between different app sessions.
- Improved selection of shape strokes when using lasso.
- Improved selection implementation for small strokes.
- FIX: bugs with undo/redo when using the partial eraser.
- Minor improvements in the detection of two fingers tap gesture.

# Version 0.13.2
- NEW: ability to start application in fullscreen mode
- FIX: wrong colors when drawing shapes and strokes in dark mode
- FIX: strokes occasionally disappearing after being drawing
- Reduced delay that prevents scrolling after drawing on canvas
- Minor improvements to the highlighter tool
- Improved detection of two finger taps

# Version 0.13.1
- NEW: Added the possibility of customising fill color and opacity.
- Improved rendering of ink strokes.
- You can now scroll and pinch when using laser mode.
- You can now pinch and scroll with two fingers when in selection mode.
- Small improvements to the file dialog.
- FIX: rotation of ellipses now works correctly.
- FIX: prevent accidental strokes when using main colour picker.

# Version 0.13.0
- NEW: HEX code field in color picker.
- NEW: Custom background and pattern colors.
- NEW: Press and hold pen to prevent lines from automatic snapping.
- Moved default format settings to a new dialog.
- FIX: bug that caused the screen to go back when resizing windows.
- Other minor improvements.

# Version 0.12.6
- FIX: bug that caused canvas to move at the bottom of the document.

# Version 0.12.5
- FIX: Exporting PDF files with dark theme now works again.
- FIX: Occasional crashes when opening PDF files.
- Slightly improved startup times.
- Increased resolution of PDF rendering.

# Version 0.12.4
- Further performance improvements for PDF rendering and drawing on low end devices
- FIX: bug that caused edges of pages in the document to not be painted

# Version 0.12.3
- Selection handles no longer disappear when resizing or rotating
- Major improvements for rendering large documents and smoother pinch to zoom.
- Minor improvements in the behaviour of the partial eraser tool.
- FIX: Duplicating images now preserve the angle of rotation.

# Version 0.12.2
- Small bugfixes
- Compile using C++20

# Version 0.12.1
- NEW: PDF files are now rendered as vectors
- NEW: Exporting PDF in native format

# Version 0.12.0
- NEW: Ability to import PDF files.
- NEW: Ability to change orientation of documents.
- FIX: Crash at starup when using Wayland (Linux).
