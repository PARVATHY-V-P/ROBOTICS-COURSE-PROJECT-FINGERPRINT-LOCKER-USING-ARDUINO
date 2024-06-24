# ROBOTICS-COURSE-PROJECT-FINGERPRINT-LOCKER-USING-ARDUINO


## Description
The Fingerprint Locker System is a cutting-edge biometric authentication system designed to enhance security and user experience. By registering unique fingerprints, users establish secure identities within the system. When presented to unlock the door, the device compares the presented fingerprint with the stored data. A successful match prompts the door to open, displaying a reassuring message, while mismatches result in an unsuccessful message. The design prioritizes functionality and user-friendliness, ensuring seamless integration into various environments.

## Proposed System

### High Security
- Uses unique fingerprint identification.
- Unlike traditional keys or PIN codes, fingerprints are unique and difficult to forge.

### Convenient
- Users simply place their finger on the sensor for authentication.
- No need to remember combinations or carry keys.

### Faster Access
- Fingerprint scan is quicker than using keys/combinations.

### Potential for Multi-User Access
- Grant access to authorized users.

## Applications
- Home security
- Office security
- Gym or club access control
- Laboratory equipment security
- Medical cabinet security
- School or university lockers

## Components Required
- Fingerprint Sensor R307
- Arduino UNO
- Solenoid Lock
- IRFZ44N MOSFET
- LCD Display
- LED
- Adapter
- Wires

## Installation

### Hardware Requirements
- Fingerprint Sensor R307
- Arduino UNO
- Solenoid Lock
- IRFZ44N MOSFET
- LCD Display
- LED
- Adapter
- Wires

### Software Requirements
- Arduino IDE
- Adafruit Fingerprint Library
- SoftwareSerial Library

### Steps
1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/ROBOTICS-COURSE-PROJECT-FINGERPRINT-LOCKER-USING-ARDUINO.git
    ```
2. Open the `src/enroll.ino` and `src/fingerprint_locker_arduino.ino` files in Arduino IDE.
3. Connect your hardware as per the schematics in the `docs/schematics/wiring_diagram.png`.
4. Upload the code to your Arduino board.

## Usage

1. Power on the system.
2. Enroll fingerprints as described in the `docs/Enrollment.md`.
3. Use the enrolled fingerprints to lock/unlock the system.

## Code Explanation

### enroll.ino
The `enroll.ino` file handles the fingerprint enrollment process. It captures fingerprint images, converts them, and stores them in the fingerprint sensor's memory.

### fingerprint_locker_arduino.ino
The `fingerprint_locker_arduino.ino` file is the main code that handles the fingerprint authentication process. It checks the fingerprint against the stored data and controls the solenoid lock.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

