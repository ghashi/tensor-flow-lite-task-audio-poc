# TensorFlow Lite Audio Classification Android Demo

This is a "fork" of https://www.tensorflow.org/lite/android/tutorials/audio_classification

### Overview

This sample will record audio on a physical Android device and attempt to
classify those recordings. The supported classification models include
[YAMNET](https://tfhub.dev/google/lite-model/yamnet/classification/tflite/1) and
a custom speech command model trained using
[TensorFlow's Model Maker](https://www.tensorflow.org/lite/models/modify/model_maker/speech_recognition).
These instructions walk you through building and running the demo on an Android
device.

This application should be run on a physical Android device.

## Build the demo using Android Studio

### Prerequisites

*   The **[Android Studio](https://developer.android.com/studio/index.html)**
    IDE. This sample has been tested on Android Studio Bumblebee.

*   A physical Android device with a minimum OS version of SDK 23 (Android 6.0)
    with developer mode enabled. The process of enabling developer mode may vary
    by device.

### Building

*   Open Android Studio. From the Welcome screen, select Open an existing
    Android Studio project.

*   From the Open File or Project window that appears, navigate to and select
    the tensorflow-lite/examples/audio_classification/android
    directory. Click OK.

*   If it asks you to do a Gradle Sync, click OK.

*   With your Android device connected to your computer and developer mode
    enabled, click on the green Run arrow in Android Studio.
