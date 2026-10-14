# Presentation cheat-sheet

One-page notes to use during the Siemens meeting.

Introduction (10–15s)
- "I’m Ziad Medhat (Zaid) — I design production-ready embedded systems and industrial IoT solutions focused on reliability, maintainability, and integration."

Project highlight — AgriFlow (30–45s)
- Problem: automating field sensors and actuator control under intermittent connectivity.
- Approach: STM32-based edge gateway running FreeRTOS, secure MQTT/TLS to edge server, local rules engine, OTA updates, and local buffering to tolerate outages.
- Outcome: production-ready prototype prepared for pilot deployments. Key metrics: uptime >99.5% (pilot), reduced manual checks by ~40% (pilot).

Technical bullets to mention (10–20s)
- Platforms: STM32, FreeRTOS, Edge Linux where applicable.
- Protocols: MQTT (TLS), Modbus, CAN.
- Hardware: PCB layout, BOM management, conformal coating for harsh environments.
- Quality: unit tests, CI for firmware builds, environmental testing, OTA strategies.

Talk track closing (10–15s)
- "You can download my one-page CV from the site. I’d be happy to dive into system design, deployment, or safety/testing strategies — which would you like to discuss?"

Extra tips for demo
- Keep the demo short (30–60s), muted, and annotated with captions.
- Have the CV printed and a USB with project PDFs as a backup.
