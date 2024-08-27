# Medical Image Analysis App

![Platform](https://img.shields.io/badge/platform-Android-brightgreen.svg)
![Language](https://img.shields.io/badge/language-Kotlin-orange.svg)
![Deep Learning](https://img.shields.io/badge/deep--learning-TensorFlow-yellow.svg)

## Overview

The **Medical Image Analysis App** is an Android application developed in Kotlin that uses deep learning to detect brain tumors from MRI images. In addition to image analysis, the app provides detailed information about brain tumor symptoms and recommended treatments.

## Features

- **User Input:** Allows users to input patient details before uploading MRI images.
- **Image Upload:** Supports the uploading of MRI images for analysis.
- **Deep Learning Model Integration:** Utilizes a deep learning model for brain tumor detection.
- **Result Display:** Provides a detailed result of the analysis, indicating the presence or absence of a tumor.
- **Symptoms of Brain Tumor:** Displays information about the common symptoms of brain tumors.
- **About Brain Tumor:** Offers detailed information on brain tumors and recommended treatments.
- **Dark Mode:** The app is designed to be user-friendly with dark mode compatibility.

## Snapshots

Here are some screenshots of the app in action:

| Feature               | Screenshot |
|-----------------------|------------|
| **Home Screen**       | ![image](https://github.com/user-attachments/assets/792e7c2f-a6ce-4e92-9103-53eb3d43a10e)|
| **Image Upload**      | ![image](https://github.com/user-attachments/assets/4391ff15-edb9-4db3-9776-f9de6f02c11b)|
| **Scan Results**      | ![image](https://github.com/user-attachments/assets/5f7f9918-3c3b-4514-9eff-e755acd24774)|
| **Symptoms Section**  | ![image](https://github.com/user-attachments/assets/785246ef-e9d1-4d22-b4f0-d77029963ced)|
| **About Tumor Section** | ![image](https://github.com/user-attachments/assets/cbd05afb-837e-4457-b575-ac0934f7867b)|


## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Mohammedazif/medical_image_analysis-app.git
   ```
2. **Open the project in Android Studio.**
3. **Sync Gradle:** Ensure that all dependencies are correctly set up by syncing Gradle.
4. **Run the app** on an emulator or a physical device.

## Project Structure

- **UserDetailsActivity:** Handles the input of user details.
- **AddTumorImageActivity:** Allows users to upload MRI images for analysis.
- **TumorScanResultActivity:** Displays the result of the tumor scan.
- **MainActivity:** Serves as the primary entry point of the application with navigation to other activities.
- **Fragments:**
  - `AddTumorImageFragment`: Handles image handling and scanning.
  - `SymptomsFragment`: Displays tumor symptoms in a point-wise format with accompanying images.
  - `AboutFragment`: Provides information about brain tumors, their types, and recommended treatments with visual aids.

## Dependencies

- **Kotlin:** The app is entirely developed using Kotlin.
- **TensorFlow Lite:** Used for running the deep learning model on the device.
- **MediaPipe:** Utilized for advanced image processing (if integrated).
- **Glide:** For efficient image loading.

## Usage

1. **Launch the app** and enter the required user details.
2. **Navigate** to the image upload section.
3. **Upload an MRI image** and wait for the analysis result.
4. **View the results** and explore other features like tumor symptoms and treatments in the respective sections.

## Known Issues

- **Compatibility:** The app currently works on API level 33. It may encounter crashes on API level 35.
