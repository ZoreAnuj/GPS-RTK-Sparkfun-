# Map Visualization with OpenCV and Google Static Maps API

This Python script provides real-time map visualization by reading GPS coordinates from a serial device and displaying them on a map fetched from the Google Static Maps API using OpenCV. The coordinates are plotted on the map, which updates dynamically as new data is received.

## Setup (Arduino & Sensor)

# Arduino (SDA & SCL connections)

![WhatsApp Image 2024-05-11 at 14 33 56_aaec9670](https://github.com/ZoreAnuj/GPS-RTK-Sparkfun-/assets/95142805/3c446e95-d004-4406-a0cb-b44a40316a63)


# Antenna and Tripod

![WhatsApp Image 2024-05-11 at 14 33 55_aea2ba09](https://github.com/ZoreAnuj/GPS-RTK-Sparkfun-/assets/95142805/35a5962a-1e98-4e91-80d6-54abc5074381)


## Requirements

- Python 3.x
- OpenCV-Python
- NumPy
- Requests
- PySerial

Install the required Python packages using pip:

```bash
pip install opencv-python numpy requests pyserial
