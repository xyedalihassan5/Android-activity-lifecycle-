# Android Activity Lifecycle

This is a simple Android application created to demonstrate and understand the Android Activity Lifecycle.

## Description
The project contains two activities: `MainActivity` and `SecondActivity`. It uses `Log.d()` to print messages in the Logcat every time an activity transitions from one state to another. This helps in visually understanding how the Android system manages the lifecycle of an application.

## Lifecycle Methods Covered
The following lifecycle callbacks are implemented and logged in both activities:
* `onCreate()`
* `onStart()`
* `onResume()`
* `onPause()`
* `onStop()`
* `onDestroy()`

## How to Test
1. Clone or download this repository.
2. Open the project in **Android Studio**.
3. Run the app on an Emulator or a physical device.
4. Open the **Logcat** window at the bottom of Android Studio.
5. Type `Lifecycle` in the Logcat search bar to filter the messages.
6. Interact with the app (click the button to go to the second activity, press the back button, press the home button) and observe the logs to see the lifecycle methods triggering in real-time.
