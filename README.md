# AR_Humanoid_App
AR Humanoid Dataset Generator
This repository hosts the Android application package (APK) for an AR application designed to explore and capture 3D humanoid models in various angles and distances.

## App Overview:

- Purpose: 
Visualize and capture 3D humanoid models for generating diverse datasets applicable to various fields.
- Features:
Pre-defined humanoid models: Diverse appearances and postures for versatile data creation.
- 3D Visualization: 
Interact with and explore models in augmented reality.
- Image Capture: Capture images of models at various angles and distances from a user-defined path.
- AR Video Recording: Record AR video for later data extraction, enabling analysis without being physically present in the environment.
- Offline Use: Capture the physical space beforehand for offline use, expanding data collection flexibility.
- Benefits:
  - Efficient data collection: Seamless model transitions and diverse scene customization enable efficient data collection.
  - Versatility: Applicable to various fields requiring data on 3D object interaction, movement, and appearance under different conditions.
  
Note: Users cannot introduce their own models due to limitations in the chosen framework.

## Screenshots:

Here are some screenshots showcasing the app's interface and functionalities:

![App Main Scene](https://github.com/vasalpa/AR_Humanoid_App/assets/54214302/6a226e87-af7a-4b6d-8faf-4d001766dcbc)
![12_2 65_225](https://github.com/vasalpa/AR_Humanoid_App/assets/54214302/da85c8ef-173f-44d6-9d5c-16f95036d094)

![Settings Menu](https://github.com/vasalpa/AR_Humanoid_App/assets/54214302/ac9ff553-a2bd-4f5c-9de8-aeef133e7a35)
![Recording Selection](https://github.com/vasalpa/AR_Humanoid_App/assets/54214302/7ca9c27b-6a72-47b0-a720-d4cbeab1bcf6)

## Installation:

Download the APK file from the "Releases" tab of this repository.
Transfer the APK file to your Android device.
Enable installation from unknown sources if necessary (refer to your device's instructions).
Install the APK file on your device.
Usage:

1. Launch the app.
2. Select the desired function.
3. Choose between a pre-recorded AR video or the camera's live feed.
4. Define the rotation angle increment, total number of rotations, etc.
5. Collected data will be stored on your device for further processing or export.
   
This application is designed for various purposes and should not be used for commercial or unauthorized activities.

## 📂 Dataset for Human Detection & Recognition  

🚨 **Note:** The dataset is **not included in this repository**. It is available for download in the **[Releases](https://github.com/Alexandros-Vas/AR_Humanoid_App/releases)** section.  

### 📜 Dataset Contents  
The dataset consists of:  
- Multiple **room folders** (e.g., `Bedroom/`, `Kitchen/`, `Office_A/`, etc.)  
- Each folder contains:  
  - **Images:** Captured under different lighting conditions, distances, and rotations.  
  - **CSV Metadata File:** Includes structured annotations such as:  
    - `Humanoid ID`  
    - `Distance from Camera`  
    - `Rotation Angle`  
    - `Bounding Box Coordinates (Body & Head)`  
    - `Screenshot Filename`  

### 📥 Download the Dataset  
The dataset is available as a **ZIP file** in the **[Releases](https://github.com/Alexandros-Vas/AR_Humanoid_App/releases)** section.  

### 🎯 Usage  
This dataset is designed for training and evaluating models in:  
- **Human body detection**  
- **Head detection**  
- **Face recognition**  

The metadata file provides structured information for supervised learning tasks.

Disclaimer: The information provided here is for educational purposes only. The developer is not responsible for any misuse of the application.


## Acknowledgments

The work presented here was funded in part from the European Union’s research and innovation projects OpenDR (grant agreement no 871449, Horizon 2020) and RoboSAPIENS (grant agreement no 101133807, Horizon Europe).
This publication reflects the authors’ views only. The European Commission is not responsible for any use that may be made of the information it contains.

