# Interface Contract (NOT APPROVED)
No interface is frozen. Agree on names, units, timestamps, rates and dropped-packet behavior **before** separate firmware/backend coding.

Example proposal ONLY, never real measured data:
```json
{
  "schema_version": 1,
  "device_id": "arm-prototype-01",
  "test_run_id": "example-001",
  "timestamp_ms": 0,
  "joint_id": "J1",
  "temperature_c": 27.3,
  "accelerometer_samples_g": [[0.01, -0.02, 1.01]],
  "motor_speed_steps_per_s": 100,
  "fault_label": "normal"
}
```
The example assumes a stepper; it MUST be revised if the team selects servos. `fault_label` may be applied on the laptop rather than the ESP32. Do not add motor current until an actual sensor is installed and the schema is versioned.

## Pending agreement
- Hardware platform / motor type and joint IDs
- Timestamp reference and synchronization
- Sensor sample rate vs transmission packet rate
- Units, ranges, packet validation and dropped packet behavior
- Fault label vocabulary and ownership
- Wi-Fi transport and command acknowledgement
