# IntelliQR Meal Scanner App

## Overview

IntelliQR Meal Scanner is an Android application designed to scan QR codes for meal distribution at events. It ensures each participant can only take a meal once and provides real-time status updates. The app also features a secondary screen for the "M2M Planner".

## Features

- QR code scanning for meal distribution.
- Real-time meal status updates.
- Ensures no participant can take more than one meal.
- "M2M Planner" section accessible from the home screen.
- Integration with Firebase for participant data management.
- Custom app icon and background images.
- Enabled/disabled state for scanning based on a switch control.

## Screenshots
![Home Screen](https://github.com/Kartikey03/Trikon/assets/77600935/5aad17f9-60a2-4acb-b6be-db73e76eae5d)
![Social Media Screen](https://github.com/Kartikey03/Trikon/assets/77600935/ead10fd9-35ad-468e-8a7c-66e53701e9b2)
![Scanning Screen](https://github.com/Kartikey03/Trikon/assets/77600935/d49b04ce-f32a-47d4-ae70-a7a707ca024a)

<img src="https://github.com/Kartikey03/Trikon/assets/77600935/d49b04ce-f32a-47d4-ae70-a7a707ca024a" alt="Home Screen" width="300">

## Setup and Installation

### Prerequisites

- Android Studio
- Firebase account
- Git

### Steps

1. **Clone the repository**

   ```sh
   git clone https://github.com/Kartikey03/Trikon.git
   cd Trikon
   ```

2. **Open in Android Studio**
   - Open Android Studio and select "Open an existing Android Studio project".
   - Navigate to the cloned repository folder and open it.

3. **Configure Firebase**
   - Go to the Firebase Console.
   - Create a new project or use an existing one.
   - Add an Android app to your project.
   - Download the `google-services.json` file and place it in the `app` directory of your project.
   - Follow the instructions to add Firebase to your Android project.

4. **Build and Run the Project**
   - Sync the project with Gradle files.
   - Run the project on an emulator or a physical device.

## Usage

1. **Home Screen**
   - You will see two buttons: "M2M Planner" and "Meal Scanner".
   - "M2M Planner" opens a scrollable view.
   - "Meal Scanner" opens the QR scanning activity.

2. **QR Scanning**
   - Enable the switch to activate the "Scan for Meals" button.
   - Click the "Scan for Meals" button to start scanning QR codes.
   - The app will display the meal status based on the scan.

## Contributing

We welcome contributions from the community. Please follow these steps to contribute:

1. **Fork the repository**

   Click the "Fork" button at the top right of the repository page.

2. **Clone your forked repository**

   ```sh
   git clone https://github.com/your-username/IntelliQR-Meal-Scanner.git
   cd IntelliQR-Meal-Scanner
   ```

3. **Create a new branch**

   ```sh
   git checkout -b feature/your-feature-name
   ```

4. **Make your changes**

   - Add new features or fix bugs.
   - Ensure your code follows the existing coding style.
   - Test your changes thoroughly.

5. **Commit and push your changes**

   ```sh
   git add .
   git commit -m "Description of your changes"
   git push origin feature/your-feature-name
   ```

6. **Create a pull request**

   - Go to the repository on GitHub.
   - Click the "New Pull Request" button.
   - Provide a description of your changes and submit the pull request.

## Contact
If you have any questions or suggestions, feel free to open an issue or contact us directly at info.kartik2003@gmail.com.

Thank you for using IntelliQR Meal Scanner! We hope this app helps in managing meal distribution effectively at your events.
