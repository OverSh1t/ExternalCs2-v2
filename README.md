## CS2 External ESP Overlay
Lightweight, single-file external overlay for Counter-Strike 2 written in Python using PyQt6. Features 2D bounding boxes, bone skeleton rendering, dynamic health bars, and distance tracking directly from game memory.

## Features
* Single-File Implementation: Complete logic (memory polling, screen projection, coordinate math, and rendering) within one script.

* Bounding Boxes: Full or corner-only 2D bounding boxes with distinct visible and occluded colors.

* Skeleton Overlay: 2D bone structure mapping built from a 17-point bone hierarchy.

* Health Bar: Offset vertical indicators showing entity health with background contrast.

* Distance Tracking: Readouts calibrated in meters with dropped shadow formatting for clarity.

* Fixed Polling Rate: Memory sampling and repaint loop locked to 8 ms (~125 Hz).

## Technical Stack
## Language: Python 3.10+

## UI & Graphics: PyQt6 (QPainter, QColor)

## Target Application: Counter-Strike 2 (64-bit, Borderless Windowed mode)
