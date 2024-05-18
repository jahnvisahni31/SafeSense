# SafeSense

## Introduction

SafeSense is a Driver Drowsiness Detection System designed to detect and alert drivers when they show signs of drowsiness or fatigue while operating a vehicle. This README file provides an overview of the system, its features, and instructions for installation and usage.

## Features

- **Real-time Drowsiness Detection**: The system uses computer vision techniques and machine learning algorithms to analyze the driver's facial features and detect signs of drowsiness in real-time.
- **Eye State Monitoring**: The system tracks the driver's eye movements and monitors the eye state to detect if the eyes are closed or if the driver is blinking excessively, indicating potential drowsiness.
- **Yawning Detection**: The system identifies instances of yawning, which is a common symptom of drowsiness, by analyzing facial landmarks and mouth movements.
- **Alarm and Alert System**: When drowsiness is detected, the system triggers an alarm to alert the driver. The alert can be in the form of a sound, vibration, or visual notification, depending on the implementation.
- **Adjustable Sensitivity**: The system allows users to adjust the sensitivity of drowsiness detection based on their preferences or specific requirements.
- **Robust Performance**: The system is designed to work in various lighting conditions and can handle different driver positions and orientations.

## Requirements

- Python (version 3.6 or higher)
- OpenCV (computer vision library)
- dlib (machine learning library)

## Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/jahnvisahni31/SafeSense.git
    cd SafeSense
    ```

2. **Create a virtual environment (optional but recommended)**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Start the application**:
    ```sh
    python main.py
    ```

2. **Adjust the sensitivity** (if needed):
   - Open the settings in the application interface and adjust the sensitivity slider to match your preferences.

3. **Monitor for drowsiness**:
   - The system will continuously monitor your facial features, eye state, and yawning to detect signs of drowsiness.
   - When drowsiness is detected, an alarm will trigger to alert you.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to open an issue or submit a pull request.

To contribute:

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m "Description of changes"
    ```
5. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
