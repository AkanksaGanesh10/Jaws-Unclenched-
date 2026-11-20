# Tech Stack & Hosting Strategy

## Defined Tech Stack

- **JavaScript:** Used for the main application logic, interactive features, and connecting application components.
- **React:** Used to build the front-end interface, including the dashboard, nightly summaries, and user controls.
- **Python:** Used for developing and testing the AI-based jaw-clenching detection model and processing sensor data.
- **Firebase:** Used for storing user information, nightly activity records, and detection results.
- **Web Audio API:** Used to play calming audio when a potential jaw-clenching event is detected.

## Hosting & Deployment Strategy

The application will initially be hosted using **Vercel**, which supports React applications and allows users to access the product through a web browser.

Firebase will handle database and storage requirements. During the initial development stage, simulated sensor data will be used to test the detection system before attempting integration with specialized wearable hardware.

This approach keeps development affordable and allows the application to be tested without requiring fully developed hardware from the beginning.
