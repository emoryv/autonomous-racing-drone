# Autonomous Racing Drone

**Anduril AI Grand Prix · Software Developer · Summer–Fall 2026**

A technical case study of my contributions to a team-built GPS-denied racing-drone autonomy stack. Our team placed in the **top 10 of the virtual qualifiers**, in a competition with more than 3,000 teams entered.

## Engineering problem

Autonomous racing connects perception, state estimation, and control: the system needs usable gate observations and a reliable estimate of motion to navigate without GPS.

## My contributions

- Built and tested the autonomy stack as part of the team, working with camera/IMU fusion, a 15-state error-state extended Kalman filter, and 90 Hz geometric control.
- Curated and cleaned flight-log data for perception-model training and evaluation.
- Supported the training and evaluation data workflow for an eight-keypoint gate-detection CNN trained on 52,000 auto-labeled frames.

## System context

| Subsystem | Project approach |
| --- | --- |
| Perception | Eight-keypoint gate-detection CNN |
| Pose observations | Perspective-n-Point (PnP) fixes from gate observations |
| State estimation | Camera/IMU fusion with a 15-state error-state EKF |
| Control | 90 Hz geometric control |
| Model deployment | FP16 TensorRT |

## Team results

- Top-10 placement in the virtual qualifiers.
- A **23% increase in usable PnP fixes**.
- Deployment of the perception model using FP16 TensorRT.

These are team outcomes. My particular focus included flight-log data preparation and participation in building and testing the autonomy stack; the model and full system were collaborative work.

## Repository scope

This repository is a portfolio case study, not a release of the original team source code, flight logs, or trained model. The figures above describe the project results; a reproducible benchmark package is not included here.

**Technologies:** camera/IMU fusion, error-state EKF, computer vision, geometric control, TensorRT

[Back to my profile](https://github.com/emoryv)
