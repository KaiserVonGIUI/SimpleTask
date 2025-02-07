# SimpleTask
A task management application with a user-friendly interface, task completion animations, and theme customization.

## 1. Development Environment Requirements
To build the project on a local machine, you need to install:

Flutter SDK (version 3.16.0 or newer) (use 3.27.4)
Dart SDK (included with Flutter) (use 3.6.2)
Android Studio (version 2022.1.1 or newer) (use 2022.1.1 Patch 1)
Android SDK (platform API 35)
Android SDK Build-Tools (version 33.0.1 or newer) (use 33.0.1)
Android SDK Command-line Tools (version 7.0 or newer) (use 7.0)
Android NDK (optional but recommended)
Java Development Kit (JDK 17) (use openjdk version "17.0.14" 2025-01-21 LTS)
Gradle (uses the built-in Gradle wrapper) (use 8.12.1)
Visual Studio Code (optional but recommended)

## 2. System Requirements for the Application
Operating System: Android 10 (API 29) or newer
Minimum API Level: 29
Target API Level: 35
Free Storage Space: At least 100 MB for installation, ~35 MB after installation
RAM: Minimum 2 GB (4 GB recommended)

## 3. Setting Up the Development Environment and Building the Project
3.1 Extracting the Project Archive
Download and extract the project archive to a convenient location.
Open a command prompt (cmd/Powershell/terminal) and navigate to the project directory:

`cd path/to/project/simpletask`

3.2 Installing Development Tools
3.2.1 Installing Flutter
3.2.2 Installing Android Studio and SDK
3.2.2.1 Install:
SDK Platform (API 35)
SDK Build-Tools (33.0.1)
Android Command-line tools (7.0 or newer)
3.2.3 Installing Java (JDK 17)
3.2.4 Configuring and Verifying the Environment
After installation, run:

`flutter doctor`

If there are any errors, follow the instructions to fix them.

3.3 Installing Dependencies
Navigate to the project folder and run:

`flutter pub get`

3.4 Building the APK
Build a debug APK for testing:

`flutter build apk --debug`

Build an optimized APK:

`flutter build apk --release`

The APK file will be located in build/app/outputs/flutter-apk/app-release.apk.

3.5 Running the Project on an Emulator or Device
Connect a device or launch an emulator and run:

`flutter run`

## 4. Application Features
Create, edit, and delete tasks
Add descriptions and deadlines to tasks
Categorize tasks (active, urgent, completed)
Task completion animation with a pop-up notification
Settings (theme switching, task list clearing, app info)
Localization (Russian, English)

## 5. Additional Information
If you encounter issues, try:

Clearing cache:

`flutter clean
flutter pub get`

Checking Gradle settings:

`gradlew wrapper --gradle-version 8.0`

Opening Android Studio and verifying the SDK configuration.

## 6. Download-link

`https://drive.google.com/file/d/1qcO6CisWQuuXGzRBcnDKnUh46Ahm0EmQ/view?usp=sharing`

The SimpleTask application is intended for personal use and will not be published on Google Play.
