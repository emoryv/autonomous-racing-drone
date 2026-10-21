# Autonomous Racing Drone — Case Study

**Anduril AI Grand Prix · Software Developer · Summer–Fall 2026**

Contributed to a team-built GPS-denied racing-drone autonomy stack, with a focus on flight-log data preparation and participation in system development and testing.

## My contributions

- Built and tested the autonomy stack as part of the team, working with camera/IMU fusion, a 15-state error-state extended Kalman filter, and 90 Hz geometric control.
- Curated and cleaned flight-log data for perception-model training and evaluation.
- Supported the data workflow for an eight-keypoint gate-detection CNN trained on 52,000 auto-labeled frames.

## System context

| Subsystem | Team approach |
| --- | --- |
| Perception | Eight-keypoint gate-detection CNN |
| Pose observations | Perspective-n-Point (PnP) fixes |
| State estimation | Camera/IMU fusion with a 15-state error-state EKF |
| Control | 90 Hz geometric control |
| Model deployment | FP16 TensorRT |

The engineering problem connects usable gate observations with state estimation and control so the drone can navigate without GPS.

## Reported team results

- Top-10 placement in the virtual qualifiers.
- A 23% increase in usable PnP fixes.
- Perception-model deployment using FP16 TensorRT.

The placement and measurements above are reported team outcomes. A team-specific results link and the measurement baseline for the PnP improvement are not included in this repository.

[Official AI Grand Prix website](https://www.theaigrandprix.com/) provides competition background; it is not a citation for this team's placement.

**Source and attribution:** This personal case study documents collaborative work. Team code, flight logs, trained models, and a reproducible benchmark package are not distributed here.

**Technologies:** camera/IMU fusion, error-state EKF, computer vision, geometric control, TensorRT

[Back to my profile](https://github.com/emoryv)
