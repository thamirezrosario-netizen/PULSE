# PULSE – Vibration Monitoring System

## Overview
PULSE is an open-source system for monitoring vibrations in urban and mining environments.  
It is designed to be low-cost, scalable, and capable of continuous data acquisition, processing, and visualization.

## Objectives
- Monitor vibration levels in real time  
- Support structural safety assessment  
- Evaluate environmental impact  
- Improve control of mining and urban operations  

## System Architecture

The system is divided into two main components:

### Hardware
Responsible for capturing vibration data:
- Geophone (vibration sensor)
- Signal amplifier (AD620)
- Analog-to-Digital Converter (ADC)
- Raspberry Pi (data acquisition unit)

### Software
Responsible for processing and analyzing data:

#### Modules:
- **Acquisition** → Reads incoming data (JSON format)  
- **Processing** → Signal filtering and analysis  
- **Interpretation** → Detection of anomalies and events  
- **Visualization** → Generation of graphs and images  


## Data Flow
1. Sensor captures vibration signal  
2. Signal is converted to digital data (ADC)  
3. Data is structured in JSON format  
4. Software reads and processes the data  
5. Results are interpreted and visualized  

## Technologies
- Python  
- Raspberry Pi  
- Analog sensors (geophone)  
- Signal processing techniques
  

## 📚 Documentation
Detailed technical documentation is available in the `/docs` folder.


## Open-Source Approach
This project is developed as an open-source solution, allowing:
- Reproducibility  
- Collaboration  
- Future scalability  


## Future Work
- Real-time monitoring dashboard  
- Integration with IoT networks  
- Automated alert system  


## Authors
Project developed within the scope of the Integrated Project in Mining Engineering.
