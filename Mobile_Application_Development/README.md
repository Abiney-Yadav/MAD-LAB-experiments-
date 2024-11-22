MOBILE APPLICATION DEVELOPMENT LAB
Overview
This project contains multiple experiments focused on different aspects of mobile application development. These experiments include implementations of secure login systems, dynamic font change functionality, a basic calculator, credential verification methods, and advanced features like OCR for traffic signs, face recognition, and barcode scanning. Each experiment is designed to be modular, allowing seamless integration into your projects.

Features
1. Login System
Description: The login system is designed with security as a priority, providing a seamless and safe user experience.

Username and Password Validation: Ensures valid credentials are entered.
Error Handling: Provides feedback for incorrect login attempts.
Session Management: Maintains user sessions securely.
Usage:
Log in using your username and password.
Successful login redirects you to the main application screen.
Incorrect credentials display an error message.

2. Font Change Functionality
Description: Users can dynamically change the font style and size within the application.

Predefined Font Styles: Offers a selection of popular fonts.
Custom Font Sizes: Allows users to adjust font size.
Real-time Preview: Immediate visualization of changes.
Usage:
Navigate to the settings menu and select "Font Settings."
Choose a preferred font style and size.

3. Calculator
Description: A simple yet functional calculator built for basic arithmetic operations.
Basic Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
User-friendly Interface: Designed for ease of use.
Usage:
Access the calculator from the main menu.
Enter numbers and choose an operation for quick calculations.

4. Connection Establishment
Description: Establishing a connection to a database to enable application functionalities.
Usage:
Choose a Database Driver: Select the correct driver (e.g., MySQL, PostgreSQL, SQLite).
Configure Connection Parameters:
Database Type
Server Address
Database Name
Username and Password

5. Credential Verification
Description: Strengthens the login system with advanced credential verification.
Email Verification: Sends a verification link during registration.
Two-Factor Authentication (2FA): Optional for enhanced security.
Password Strength Checker: Encourages strong password creation.
Usage:
Users verify their email during registration.
Enable 2FA from the security settings for additional protection.

6. Text-to-Speech (TTS) and Speech-to-Text (STT)
Text-to-Speech (TTS)
Transforms written text into audible speech for improved accessibility.
Natural Voice Generation: Human-like voice output.
Wide Application: Used in virtual assistants and accessibility tools.
Speech-to-Text (STT)
Converts spoken words into text, facilitating transcription and voice commands.
Real-time Transcription: Quick and accurate.
Language Support: Supports multiple languages.
Usage:
TTS: Provides auditory feedback, reads notifications, and aids navigation.
STT: Enables voice-controlled features and audio transcription.

7. OCR for Traffic Sign Recognition
Description: Uses Optical Character Recognition (OCR) to identify and interpret traffic signs.
Traffic Sign Detection: Recognizes traffic signs in real-time using the device camera.
Text Extraction: Extracts text or symbols from detected signs.
Navigation Aid: Helps users understand and follow traffic rules.
Usage:
Activate the "Traffic Sign OCR" feature from the menu.
Point the camera at a traffic sign for instant recognition and feedback.

8. Face Recognition
Description: Implements face recognition technology for authentication and personalization.

Face Detection: Identifies and analyzes facial features.
Authentication: Enhances security with biometric login.
Personalization: Tailors user experience based on recognized profiles.
Usage:
Enable face recognition in the "Security Settings" menu.
Use your face for secure and convenient login.

9. Barcode Scanner
Description: A feature to scan and decode barcodes for various applications.

Barcode Detection: Supports standard barcode formats like QR codes and UPC.
Data Extraction: Extracts and displays relevant data from scanned barcodes.
Integration Options: Links to inventory systems or payment gateways.
Usage:

Access the "Barcode Scanner" from the main menu.
Scan a barcode to retrieve its data.
Installation
Clone the repository:
git clone https://github.com/Abiney-Yadav/MAD-LAB-experiments-
Navigate to the project directory:
cd mobile-app-experiments-lab
Install dependencies:
npm install
Run the application:
npm start
Usage
Once the application is running, navigate through the menu to explore the experiments. Each feature is intuitive, with user guides available in the help section.

Contributing
Contributions are welcome! Please refer to the CONTRIBUTING.md file for details on how to contribute.

License
This project is licensed under the MIT License. See the LICENSE file for more details.