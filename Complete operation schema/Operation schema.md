# Lab Task 5
## Smart Museum Artifact Conservation System

| ID | Precondition | Event/Input | Post-condition |
|---|---|---|---|
| OP_01 | Conservation chamber is powered on and system components are connected. | System startup/power-on event occurs. | All essential sensors and environmental-control devices are checked. |
| OP_02 | Artifact is ready to be placed inside the conservation chamber. | Artifact identification information is entered. | Artifact information is recorded in the system. |
| OP_03 | Artifact information is available and conservation requirements are known. | Environmental profile is selected or loaded. | Required environmental limits for the artifact are loaded. |
| OP_04 | Chamber is operating and environmental sensors are active. | Temperature and humidity sensor readings are received. | Environmental conditions are continuously monitored against permitted limits. |
| OP_05 | Temperature sensor is working and temperature is outside the permitted range. | Temperature reading exceeds the permitted range. | Temperature-control mechanism is activated to restore the required temperature. |
| OP_06 | Humidity sensor is working and humidity is outside the permitted range. | Humidity reading exceeds the permitted range. | Humidity-control mechanism is activated to restore the required humidity. |
| OP_07 | Temperature or humidity correction has been attempted. | Updated temperature and humidity readings are received. | System verifies whether temperature and humidity have returned to permitted ranges. |
| OP_08 | Environmental conditions remain outside acceptable limits after normal correction. | Normal environmental recovery fails. | Additional protection mechanisms are activated and light exposure is reduced. |
| OP_09 | An abnormal environmental condition has been detected. | Environmental recovery fails or a critical condition occurs. | An alert is generated for the museum operator. |
| OP_10 | Artifact is inside the chamber and vibration monitoring is active. | Vibration sensor detects significant vibration. | Risky activities are temporarily suspended to protect the artifact. |
| OP_11 | Normal operation is suspended because of vibration. | Vibration remains below the permitted threshold for the required stabilization period. | Normal operation is allowed to resume. |
| OP_12 | Conservation system is operating using main electrical power. | Main power failure is detected. | System switches to emergency power if available; otherwise, safe shutdown is initiated. |
