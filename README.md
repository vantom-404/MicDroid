🎙️ VocalTune Studio

Professional Android Auto-Tune & Vocal Recording Studio

VocalTune Studio is an Android vocal processing application designed to provide real-time pitch correction, professional vocal recording, and audio effects.

The project aims to modernize the original MicDroid pitch-correction technology into a modern Android music production experience.

✨ Features
🎤 Live Auto-Tune
Real-time microphone input.
Automatic pitch detection.
Musical key selection.
Major and Minor scales.
Adjustable pitch correction strength.
Retune speed control.
Original audio bypass.
Live audio level monitoring.
🎧 Recording Studio
Record vocals directly from the microphone.
Pause and resume recordings.
Playback recorded audio.
Apply pitch correction after recording.
Compare original and corrected vocals.
Save recordings locally.
Export WAV audio files.
🎛️ Vocal Effects

Planned audio effects:

Auto-Tune.
Reverb.
Echo and Delay.
Equalizer.
Compressor.
Noise Gate.
Vocal Gain.
🎨 Modern Interface
Dark professional music studio design.
Purple and violet visual theme.
Jetpack Compose interface.
Arabic and English language support.
Responsive Android layouts.
🛠️ Technology Stack
Technology	Purpose
Kotlin	Android development
Jetpack Compose	User interface
Material 3	Design system
Android AudioRecord	Microphone input
Android AudioTrack	Audio output
Android NDK / C++	Native audio processing
Oboe	Low-latency audio
JNI	Kotlin/C++ integration
DSP	Pitch detection and correction
🧠 Original Project

VocalTune Studio uses the following repositories as technical references:

MicDroid – vantom-404 — Primary candidate and modified fork.
MicDroid – intervigilium — Original upstream repository.

The original project's pitch-correction implementation will be evaluated for reuse and modernization.

All reused source code and dependencies must comply with their respective open-source licenses.

🏗️ Architecture

The planned architecture separates the application interface from audio processing.

text
VocalTune Studio
│
├── Android Application
│   ├── Jetpack Compose UI
│   ├── Home Screen
│   ├── Live Auto-Tune
│   ├── Recording Studio
│   ├── Effects
│   └── Recording Library
│
├── Audio Engine
│   ├── Microphone Input
│   ├── Pitch Detection
│   ├── Pitch Correction
│   ├── Audio Effects
│   └── Audio Output
│
├── Native DSP Engine
│   ├── C++ Processing
│   ├── Oboe Audio Stream
│   └── JNI Bridge
│
└── Local Storage
    ├── Recordings
    ├── Presets
    └── User Settings

🚀 Development Roadmap
Analyze the modified MicDroid fork.
Compare the fork with the original repository.
Verify source-code licenses.
Create the modern Android application.
Implement the Jetpack Compose interface.
Implement microphone recording.
Integrate the pitch detection engine.
Implement real-time pitch correction.
Add offline vocal correction.
Add Reverb and Echo.
Implement WAV export.
Test audio latency and performance.
Build and test the Android APK.
📱 Platform
Android smartphones and tablets.
Native Android application.
Local audio processing.
No cloud connection required for core audio processing.
🔒 Privacy

The intended architecture processes microphone audio locally on the device.

Microphone access requires explicit Android permission.

Recordings are stored locally unless the user chooses to export or share them.

⚙️ Build Requirements

The final development environment is expected to include:

Android Studio.
Android SDK.
Kotlin.
Android Gradle Plugin.
Android NDK.
CMake.
Oboe audio library.

Build instructions will be finalized after the native audio engine and project configuration are established.

⚠️ Development Status

Project Status: In Development

VocalTune Studio is under active development planning.

The interface, real-time audio engine, pitch correction, and recording workflow must be implemented and tested before being considered production-ready.

🎯 Project Goal

Create a modern Android Auto-Tune application that allows users to:

Sing into their microphone.
Hear their corrected voice in real time.
Record vocal performances.
Apply professional pitch correction.
Add vocal effects.
Export high-quality audio recordings.

VocalTune Studio — Your Voice, Perfectly Tuned.
