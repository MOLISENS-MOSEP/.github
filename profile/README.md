# MOSEP — Modular Hardware and Software System for Multi-Sensor Environment Perception

This is a collection of repositories surrounding the measurement systems MOLISENS (MObile LIdar SENsor System) [1] and MOSEP (Modular Hardware and Software System for Multi-Sensor Environment Perception) [2]. 
MOSEP (as a successor to MOLISENS) is a ROS 2-based multi-sensor platform for environmental and meteorological data acquisition. It supports multiple sensor configurations for stationary monitoring and handheld mapping, with automated precipitation-triggered recording.

## Repository Structure

Repositories are grouped by category:

- **development.*** — Development environment (Docker images, Compose setup, workspace configuration)
- **data.*** — ROS 2 launch files, sensor kit configurations, and URDF descriptions
- **drivers.*** — ROS 2 sensor drivers (weather stations, LiDAR, radar, GNSS, IMU)
- **tools.*** — Additional tools for recording, monitoring, and SLAM
- **analysis.*** — Data analysis packages
- **dissemination.*** — Repositories corresponding to publications

## Getting Started

See [development.ade](https://github.com/MOLISENS-MOSEP/development.ade) for installation and setup instructions.

## References

[1] Goelles T., Hammer T., Muckenhuber S., Schlager B., Abermann J., Bauer C., Expósito Jiménez V.J., Schöner W., Schratter M., Schrei B. & Senger K. 2022. MOLISENS: MObile LIdar SENsor System to exploit the potential of small industrial lidar devices for geoscientific applications. Geoscientific Instrumentation, Methods and Data Systems 11, 247–261, doi: 10.5194/gi-11-247-2022.

[2] WIP
