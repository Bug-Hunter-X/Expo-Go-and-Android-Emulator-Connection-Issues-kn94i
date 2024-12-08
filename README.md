# Expo Go and Android Emulator Connection Issues

This repository demonstrates a bug encountered while using Expo Go with an Android emulator. The app builds successfully but inconsistently fails to run on the emulator, producing connection or resource-finding errors.

## Bug Description

The project builds correctly, but when attempting to run it on an Android emulator using Expo Go, it intermittently throws errors related to connectivity or resource availability.  No clear pattern exists for when the error occurs.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Attempt to start the project using `expo start`.
4. Select the Android emulator as the target device.
5. Observe the intermittent connection failures.

## Solution

The solution involved ensuring that both the emulator and development machine were connected to the same network, and that the emulator was properly configured with network access.  Additionally, restarting the emulator, computer, and sometimes even the Expo Go app itself provided temporary fixes.  However, a definitive permanent solution requires further investigation.