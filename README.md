# PharmAssist: Medicine Assistance for the Elderly and Differently Abled

PharmAssist is an innovative solution designed to assist elderly, blind, and deaf individuals in managing their medication intake. The system ensures timely and accurate medication identification and reminders, leveraging unique conductive copper label patterns, voice assistance, and text-to-speech technology.

## Problem Statement

Elderly, blind, and deaf individuals often face challenges with medication due to confusion regarding:
- Intake timing
- Medicine names
- Dosage information

They frequently rely on external assistance, which can be inconvenient and unreliable.

## Solution

PharmAssist addresses these challenges with the following features:
- **Unique Copper Labels**: Each medicine bottle is labeled with a unique pattern made of conductive copper pieces.
- **App-Based Recognition**: The app detects the label's unique pattern when the bottle is placed on a mobile screen and provides details about the medicine based on the prescription stored in a database.
- **Voice and Text Assistance**:
  - Voice assistance for elderly and blind users.
  - Text display for deaf users, with text-to-speech and speech-to-text capabilities.
- **Reminders**: Generates reminder calls or messages to alert patients to take their medication.

## Key Features

- Scalable label design for up to 720 unique patterns (based on factorial combinations).
- Integration with Google APIs for multilingual support, text-to-speech, and speech-to-text functionalities.
- Firebase integration for real-time data storage, authentication, and messaging.

## Prototype Overview

1. **Label Design**: Labels with unique copper patterns are attached to medicine bottles by pharmacists.
2. **App Detection**: The app identifies the label when the bottle is placed on a mobile screen.
3. **Medication Details**: Provides medicine information based on the stored prescription.
4. **Reminders**: Alerts the user with calls or messages at scheduled times.

## Technology Stack

- **Android Studio** (Flutter Extension) for app development.
- **Firebase**:
  - Firestore for database management.
  - Firebase Authentication for user login.
  - Firebase Messaging for reminders.
- **Google APIs**:
  - Language support.
  - Text-to-speech and speech-to-text functionalities.
  - Time zone support.
- **Web Technologies**: HTML, CSS, and JavaScript for supporting frontend components.

## Dependencies

1. **Google API**:
   - Language Support
   - Text-to-Speech
   - Speech-to-Text
   - Time Zone Management
2. **Firebase**:
   - Firestore
   - Firebase Authentication
   - Firebase Messaging for automated call and message generation

## Challenges

- **Damaged Labels**: Broken or damaged labels may lead to incorrect results.
- **Mobile Screen Issues**: Devices with broken or unresponsive screens may fail to detect label patterns.

## Future Scope

- Expand scalability by increasing the number of copper pieces in label patterns.
- Enhance robustness to handle damaged labels effectively.
- Explore alternative label recognition technologies to minimize dependency on screen quality.

## Acknowledgments

PharmAssist was developed as part of the Student Innovation Program to address the critical needs of the differently-abled and elderly population.

## License

This project is licensed under the MIT License.
