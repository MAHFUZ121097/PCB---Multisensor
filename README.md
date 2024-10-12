# PCB---Multisensor

## Overview

**EcIPoTH** is a custom-designed Printed Circuit Board (PCB) intended for the acquisition of multiple physiological signals. This versatile board integrates various sensors to measure and track vital parameters. It is designed for research and development in physiological signal monitoring, and can be easily adapted for a wide range of applications.

### PCB Image
![PCB Design](Diagrams/EcIPoTH_device.jpg)

### Sensors Included:
1. **Ec** - Electrocardiogram (ECG) Sensor
2. **I** - Inertial Measurement Unit (IMU) Sensor
3. **Po** - Pulse Oximeter Sensor
4. **TH** - Temperature and Humidity Sensor

### Key Features:
- Multisensor PCB layout (2-layer) for real-time physiological data acquisition
- Operating voltage: ~3.3 V
- Compact dimensions: 60 mm x 50 mm
- Modular design for easy integration into wearable or portable devices
- Designed for medical and research applications

### Design Environment:
- KiCad EDA 6.0.10

## Dimensions

- **PCB Size:** 60 mm x 50 mm

## Sensors Overview

### ECG Sensor (Ec)
- AD8232 chip: Captures electrical activity of the heart, includes instrumentation amplifier.
  
### IMU Sensor (I)
- MPU6050 chip: Inertial measurement unit (IMU) to capture breathing patterns, includes accelerometer and gyroscope.

### Pulse Oximeter Sensor (Po)
- Max30101 chip: Captures LED data to measure pulse rate and oxygen saturation, includes infrared (IR) and red LED.

### Temperature and Humidity Sensor (TH)
- Si7021 chip: Records core body temperature and humidity measurements.


