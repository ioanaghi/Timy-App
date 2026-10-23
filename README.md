# Timy

Flutter/FlutterFlow app designed to support autistic users; third place at the Polihack competition.

## Purpose

Timy explores supportive mobile experiences for autistic users through activity, communication, and game interfaces. The team project received third place at the Polihack competition.

## Implementation

The application lives in `Timy---Hackie-Chan-flutterflow/` and combines FlutterFlow-generated structure with the project implementation. It includes Flutter/Dart UI, Firebase dependencies, navigation, and bundled activity assets.

## Run locally

```sh
git clone https://github.com/ioanaghi/Timy-App.git
cd Timy-App/Timy---Hackie-Chan-flutterflow
flutter pub get
flutter run
```

Install Flutter with a compatible Dart 3 SDK; the manifest specifies Dart `>=3.0.0 <4.0.0`. The original dependency versions may require a compatible Flutter release. Configure your own Firebase development project for authentication/database features. Platform builds require the relevant Android or iOS toolchain.

## Responsible implementation

This is a competition prototype, not a clinically validated intervention. Its intended purpose does not establish a medical outcome. Use sample data for demos, enforce Firebase access rules, and avoid collecting sensitive user information without a defined need and appropriate controls.

## Project context and next steps

This is a team-built FlutterFlow/Flutter project; generated code and team work should be credited when presenting individual contributions. Priorities are documented demo flows, a verified toolchain, accessibility testing, and clearer separation of generated and custom components.
