# ARM-SOC-BASIC
Offline English → Hindi Speech-to-Speech Translator  
Built for Bharat AI SoC Challenge

## Features
- Fully Offline
- English Speech Recognition (Vosk)
- English → Hindi Translation (ONNX Transformer)
- Hindi Text-to-Speech
- Optimized for ARM devices
- Low latency (~1 sec)

## Architecture
Speech → ASR → Text Correction → Transformer → Hindi → TTS

## Tech Stack
- Kotlin
- ONNX Runtime Android
- Vosk Offline ASR
- Android TTS

## Build Instructions

```bash
./gradlew assembleDebug

##Install:

adb install -r app/build/outputs/apk/debug/app-arm64-v8a-debug.apk

##Model Setup

Place Vosk model inside:

app/src/main/assets/model/

vosk-model-small-en-us-0.15Save and exit
.---# 🚀 STEP 6 —  First Commi

t```bashgit add .git commit -m "Initial commit - Offline ENG to HIN Speech Translator"
