
# GuardianX – A Child Safety Wearable

**GuardianX** is my final-year phase-1 engineering project focused on developing an intelligent child safety wearable using embedded technologies, Edge AI, TinyML, sensors, and wireless connectivity. The project aims to improve conventional child safety monitoring systems by incorporating automated activity recognition and detection of potential safety-related incidents rather than relying solely on GPS tracking and manual SOS alerts.

## Project Overview

GuardianX uses the **Arduino Nicla Vision** as its primary embedded processing platform. An inertial measurement sensor collects motion data from the child, which is processed locally using a **Decision Tree-based machine learning model** to recognize different activities and identify potentially abnormal or emergency-related situations.

The system is designed to detect conditions such as:
- Sitting, Standing, Walking, Jumping, Walking upstairs, Walking downstairs.
- Sudden movements, Prolonged inactivity, Maximum vibration.

By implementing **Edge AI**, the system performs activity classification directly on the embedded device, reducing dependence on continuous cloud processing and enabling faster local analysis.

A GPS module provides location information, while wireless connectivity enables communication between the wearable device and a smartphone-based monitoring application. During emergency events, the system is also designed to support image snapshots and short audio recordings.
