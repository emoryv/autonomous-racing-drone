# Autonomous Racing Drone — Case Study

**Anduril AI Grand Prix · Software Developer · Summer–Fall 2026**

I helped build and test software for an autonomous racing drone that navigated without GPS. My work focused on preparing flight-log data for perception models and testing the team's system.

## My contributions

- Helped build and test the team's autonomy software, working with camera/IMU fusion, a 15-state error-state extended Kalman filter, and 90 Hz geometric control.
- Selected and cleaned flight-log data for training and evaluating perception models.
- Helped prepare data for an eight-keypoint gate-detection CNN trained on 52,000 automatically labeled frames.

## System context

| Subsystem | Team approach |
| --- | --- |
| Perception | Eight-keypoint gate-detection CNN |
| Pose observations | Perspective-n-Point (PnP) fixes |
| State estimation | Camera/IMU fusion with a 15-state error-state EKF |
| Control | 90 Hz geometric control |
| Model deployment | FP16 TensorRT |

The system uses gate detections and camera/IMU data to estimate the drone's motion and guide it through the course.

## Reported team results

- Top-10 placement in the virtual qualifiers.
- A 23% increase in usable PnP fixes.
- Perception-model deployment using FP16 TensorRT.

These are team results. This write-up does not include a public placement record or the baseline measurements for the 23% improvement.

[About the AI Grand Prix](https://www.theaigrandprix.com/)

**About this repository:** This write-up describes my contributions to the team project. Team code, flight logs, models, and benchmark files are not included.

**Technologies:** camera/IMU fusion, error-state EKF, computer vision, geometric control, TensorRT

[Back to my profile](https://github.com/emoryv)
