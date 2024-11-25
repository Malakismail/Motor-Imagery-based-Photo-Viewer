# Motor Imagery-based Photo Viewer
A unique application enabling photo browsing and viewing through EEG-based motor imagery signals. This project combines cutting-edge brain-computer interface (BCI) technology with an intuitive photo viewer application. Users can interact with the system hands-free by leveraging EEG signals captured during motor imagery tasks.



# Features
  •	**Brain-Controlled Interaction**: Navigate and view photos using EEG signals from motor imagery.
  •	**Customizable EEG Signal Processing**: Built-in support for processing raw EEG data, including filtering, feature extraction, and classification.
  •	**User-Friendly Interface**: A clean and interactive UI for smooth photo viewing.
  •	**Real-Time EEG Analysis**: The system processes and responds to motor imagery signals in real-time.
  •	**Extensible Framework**: Modular design allows integration with different EEG devices and classification algorithms.



# How It Works
  1. EEG Signal Collection: Motor imagery tasks are performed, and corresponding EEG signals are collected.
  2. Signal Processing: The signals undergo pre-processing (e.g., noise filtering, feature extraction).
  3. Classification: A machine learning model identifies specific motor imagery patterns.
  4. Photo Viewer Control: Identified patterns are mapped to photo viewer commands, such as "next photo," "previous photo," or "select photo."



# Installation
  **1. Clone the repository:**

         git clone https://github.com/Malakismail/Motor-Imagery-based-Photo-Viewer.git
         cd Motor-Imagery-based-Photo-Viewer
  **2. Install the required dependencies:**

         pip install -r requirements.txt
  **3. Connect your EEG device** and configure the settings as needed in the config file



# Usage
  1. Launch the application:

         python main.py
  2. Follow the on-screen instructions to calibrate the system with your motor imagery patterns.
  3. Start navigating your photo collection using brain signals.



# Requirements

  •	Python 3.8 or later

  •	Required libraries listed in requirements.txt

  •	EEG device (e.g., OpenBCI, Muse)



# Contributing
Contributions are welcome! Fork the repository, create a feature branch, and submit a pull request. 



# Contact
For any inquiries or support, please contact malakismail706@gmail.com
