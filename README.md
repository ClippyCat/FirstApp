# Create an App Using React Native CLI.

## 1. System Requirements:
* **CPU:** Any modern multi-core processor
* **RAM:** At least 8 GB
* **Operating System:** Windows 10 or higher
* **Node.js:** Latest LTS version
* **Java Development Kit (JDK):** Version 11
* **Android Studio:** Install Android Studio with the Android 13 (Tiramisu) SDK
* **Python:** Version 2.7 or 3.x

## 2. Installation Instructions:
1. Install Node.js, JDK and Python as mentioned above.
2. Install Android Studio. Make sure to include the following components:
	* Android SDK
	* Android SDK Platform
	* Android Virtual Device.
3. Open a command prompt or terminal and install the React Native CLI globally by running the following command:
	```bash
	npm install -g react-native-cli
	```

## 3. Environment
React Native require additional configuration for Android development. Add the path to the Android SDK tools and platform-tools to system's PATH environment variable.

## 4. Project Creation:

1. Open terminal and navigate to the directory where you want to create your project.
2. Run the following command to create a new project:
	```bash
	react-native init ProjectName
	```

## 5. Running the Project:
1. Navigate to your project directory:
2. Start the development server:
	```bash
	npx react-native start
	```
3. Build and run the project on an Android emulator or device:
	```bash
	npx react-native run-android
	```

## 6. Troubleshooting:
* Gradle build errors: Ensure that Android SDK and Java versions are compatible. Check the project's `android/build.gradle` file for the correct `buildToolsVersion` and `compileSdkVersion`.
* Emulator issues: Double-check Android emulator settings and configurations.
* Dependency problems: If encounter issues with dependencies. Use `npm` or `yarn` to update or install missing packages.

## Resources:
* [Setting up the development environment](https://reactnative.dev/docs/environment-setup?guide=native).)
* [Node's Downloads page](https://nodejs.org/en/download/)
* [Introduction to React Native](https://reactnative.dev/docs/getting-started)
* [Troubleshooting](https://reactnative.dev/docs/troubleshooting)
