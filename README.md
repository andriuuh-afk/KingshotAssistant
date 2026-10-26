# Kingshot Assistant Android — starter prototype

This is an Android Studio source project (not a ready-to-install APK). It starts a minimal dark app, requests Android's official screen-capture consent, and shows a floating overlay bubble after the overlay permission is granted.

## Open it
1. Download and extract the ZIP on a computer.
2. Open the `KingshotAssistantAndroid` folder in Android Studio.
3. Allow Gradle sync and install the Android SDK platform 35 if prompted.
4. Run it on your Android phone.
5. Grant the overlay permission in Android Settings, then grant the system screen-capture prompt.

## Important current limitations
- This is a starter scaffold, not a finished app or APK.
- The current version does not yet process frames from MediaProjection and does not run OCR/vision. The bubble's text is only a UI placeholder.
- Android may require notification permission and foreground-service behavior depending on OS version and device.
- No game actions are automated. Screen sharing is user-authorized and can be stopped by Android.
- Never enter game credentials into this prototype.

## Planned next steps
1. Connect MediaProjection frames through ImageReader.
2. Add OCR and screenshot parsing for visible game UI.
3. Add a small overlay panel with confidence labels and user correction.
4. Add troop, rally, training, and event calculators.
