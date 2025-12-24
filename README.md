# Robot Vision – Green Ball Tracking (Lab 3)

**Authors:** Trenton Pham, Alex Anderson, Rafael Copado

This project implements a vision-based object detection system for a mobile robot.
Using OpenCV image processing, the robot detects and tracks a green beach ball by
filtering camera input based on color thresholds and image morphology.

---

## Project Overview

The goal of this lab was to use the robot’s onboard camera to recognize and isolate
a specific object (a green ball) while ignoring background noise.
Color thresholds were tuned and morphological filtering was applied to improve
detection reliability in real-world conditions.

---

## Result

### Vision Mask Output

![Green Ball Detection](vision_mask.png)

The image above shows the robot’s camera output after applying the vision mask.
Only the green ball remains visible while most background elements are filtered out.

---

## Reflection

This lab demonstrated the challenges of object detection using color-based vision.
Lighting changes and background colors sometimes interfered with detection.
With additional time, the vision mask could be improved to further reduce noise
and increase robustness.

Overall, the robot successfully detected and tracked the green ball, validating
the effectiveness of the vision pipeline.

---

## Files

- `lab3Robot.py` — Main robot control and image processing code
