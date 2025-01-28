# React Native Unhandled Network Error

This repository demonstrates a common issue in React Native applications: intermittent crashes caused by unhandled network errors.  The provided code simulates a network request that may fail randomly.  The original code crashes when the request fails. The solution demonstrates how to properly handle network errors and display informative error messages to the user instead of crashing the app.

## How to Reproduce

1. Clone this repository.
2. Run the app using `react-native run-android` or `react-native run-ios`.
3. The app will simulate a network request and may fail randomly, leading to a crash in the original code. The improved version will display an error message instead.

## Solution

The solution uses a `try...catch` block to handle potential errors during the network request.  If an error occurs, an error message is displayed to the user, preventing the app from crashing.