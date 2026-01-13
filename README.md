# Image Tracer Android App

A mobile Android app that allows users to overlay an image on the camera view and adjust its transparency for tracing purposes. Designed for artists, students, and creative workflows, this app uses modern **Material Design** and real-time camera input to create an intuitive and functional tracing experience.

---

## Features
- **Live Camera Background**: Full-screen camera preview as the background.
- **Image Overlay**: Load any image and place it over the camera view.
- **Opacity Slider**: Adjust transparency in real-time for precise tracing.
- **Material Design UI**: Modern, clean, and user-friendly interface with a floating control panel.
- **Light & Dark Mode Support**: Adapts to system theme automatically.

---

## Technologies Used
- **Language**: Kotlin
- **Platform**: Android Studio
- **Libraries/Tools**:
  - [CameraX](https://developer.android.com/training/camerax) for camera integration
  - [Material Design Components](https://material.io/develop/android) for modern UI
  - Android SDK and Jetpack libraries

---

## Getting Started
1. Clone the repository:
```bash
git clone https://github.com/yourusername/ImageTracer.git
```
2. Open the project in Android Studio.
3. Sync Gradle and build the project.
4. Run the app on a device or emulator with camera support.
5. Tap Choose Image to load an image and adjust the opacity slider to begin tracing.

---

## How It Works

The camera preview is rendered full-screen using PreviewView (CameraX).
Users load an image which is displayed as a semi-transparent overlay (ImageView) on top of the camera.
The opacity slider modifies the alpha property of the overlay in real-time, allowing the user to see the camera underneath.
The control panel is a MaterialCardView floating at the bottom for a clean and unobtrusive interface.
