# Vertical Farm Controller Automated Watering

Build a smart agriculture prototype that uses LoRa module, EC sensor, SHT31 to control watering from moisture and schedule data. Include setup instructions, a circuit diagram, tested firmware, and sample output.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 171 |
| Category | Smart Agriculture |
| Platform | LoRa + Arduino |
| Difficulty | Intermediate |
| Estimated build time | 32 hours |
| Connectivity | GSM |
| Core components | LoRa module, EC sensor, SHT31 |
| Control mode | closed loop control |

## Repository layout

- `firmware/vertical-farm-controller-automated-watering/vertical-farm-controller-automated-watering.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/vertical-farm-controller-automated-watering/vertical-farm-controller-automated-watering.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **LoRa + Arduino**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Automated Watering demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
