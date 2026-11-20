# Risk Mitigation & Technical Constraints

## Core Technical Risks

- **Highest Risk Feature:** AI Clenching Detection.
- **The Hazard:** Accurately detecting jaw clenching during sleep may be difficult because ordinary earbuds cannot directly measure jaw-muscle activity. The application may require specialized sensors, such as surface EMG technology, to collect reliable data. Inaccurate readings could also result in unnecessary audio interruptions or missed clenching events.

## The Pivot Strategy

If our primary implementation for this feature fails or takes too long, our backup plan is to:

1. Use simulated sensor data or a pre-recorded sample dataset to test a basic detection model instead of immediately integrating specialized hardware.
2. Develop a simplified detection system using manually entered or sample clenching events. This would allow us to demonstrate the audio intervention and nightly dashboard without depending on real-time sensor integration.

The initial version will be treated as a prototype rather than a medically validated diagnostic tool. More accurate detection and hardware integration can be developed in future versions.
