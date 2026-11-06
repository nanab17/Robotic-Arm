# Safety and Electrical Stop Review
**Not a substitute for school/qualified-supervisor approval. No powered motor test is authorized by this file.**
- Review an independently functional physical motor-power stop before first energized motion; a dashboard stop is not enough.
- Do not rewire powered hardware or hot-plug stepper motors.
- Never power servos from ESP32 GPIO/3.3V or its board power rail.
- Verify exact module datasheets/pinouts, supply and fuse ratings, motor current limits and grounding before connecting.
- Document and test physical limits and stop behavior under controlled supervision.
- Confirm which motor design is actually approved first.
