#  Highway Illegal Stop Detection System

A desktop application for detecting illegal stopping events on highways using computer vision and Automatic License Plate Recognition (ALPR). The system analyzes recorded highway videos, detects and tracks vehicles, identifies illegal stopping behavior, extracts license plates, and displays the detected violations through an intuitive graphical interface.

> **Note:** This repository contains the compiled application only. The source code is not publicly available.

---

##  Features

*  Vehicle detection
*  Multi-object vehicle tracking
*  Illegal stopping detection based on configurable time thresholds
*  Automatic license plate detection
*  Optical Character Recognition (OCR) for license plate reading
*  Modern desktop interface built with PyQt6
*  Detection results displayed in an organized table
*  Video playback with real-time visualization
*  Exportable detection results

---

##  Technologies Used

* Python
* PyQt6
* OpenCV
* YOLO
* EasyOCR
* Bytetrack

---

##  Screenshots

Screenshots of the application are available in the `screenshots/` directory.

Example screenshots include:

* Dashboard
* Vehicle Detection
* Illegal Stop Detection
* Events
* Analytics
* Settings

---

##  Download

The latest Windows executable can be downloaded from the **Releases** section of this repository.

Download the latest version:

**Releases → hsids app v1.0**

---

##  How to Use

1. Download the latest release.
2. Extract the ZIP archive.
3. Run `dist\HSIDS\HSIDS.exe`(make suryou have internet while running this !).
4. Load a supported highway surveillance video.
5. Start the analysis.
6. Review detected illegal stopping events and recognized license plates.
7.For real-time inference i used Larix Broadcaster ios app
   .Install app from appstore
   . Enter Settings
   . Click connections and create a new connection
   . Put connection name
   . Create URL rtmp://<IP_ADDRESS>:1935/live/stream
     . <IP_ADDRESS> is your pc ip you can have it by running 'ipconfig' on cmd and search ex:'IPv4 Address . . . . . : 192.168.1.7'
     . Select mode Video only and save
   . You enter your final URL on the App->Live Stream (on top bar) ex: rtmp://192.168.1.7:1935/live/Stream
   
---

##  Requirements

* Windows 10 or Windows 11
* 64-bit operating system
* Recommended: Dedicated NVIDIA GPU for faster processing

---

##  Project Purpose

This project was developed as a computer vision application demonstrating how AI-assisted video analysis can improve highway traffic monitoring by automatically detecting illegal stopping events and identifying involved vehicles through license plate recognition.
