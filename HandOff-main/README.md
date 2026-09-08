# HandOff

> Transfer files with a gesture.

## Overview

HandOff is a multiplatform SwiftUI application inspired by Huawei HarmonyOS and Apple's AirDrop.

The goal is to create a modern and intuitive way to transfer files between nearby devices. Instead of browsing folders or sending files through email, users can simply grab a file and hand it over to another device.

HandOff combines direct device discovery, peer-to-peer file transfer, drag-and-drop interactions, and optional gesture recognition using the device camera.

---

## Features

### Device Discovery

- Automatic detection of nearby devices
- No manual IP configuration
- Simple and intuitive pairing

### File Transfer

- Direct peer-to-peer transfer
- Fast local network communication
- No cloud required

### Drag & Drop

- Drag files onto another device
- Visual transfer animations
- Real-time progress tracking

### Gesture Transfer (Experimental)

Inspired by Huawei HarmonyOS.

1. Select a file.
2. Close your hand in front of the camera to "grab" the file.
3. Move to another device.
4. Open your hand to "drop" the file.
5. The file instantly appears on the target device.

### Security

- Local network only
- Encrypted communication
- No third-party servers

---

## Technology Stack

### Frontend

- SwiftUI
- Swift

### Networking

- Multipeer Connectivity
- Peer-to-peer communication

### Gesture Recognition

- Vision Framework
- Camera-based hand tracking

### Platforms

- macOS
- iOS
- iPadOS

Built as a SwiftUI Multiplatform App.

---

## Project Goals

### Version 0.1 (Developing)

- Device discovery
- Device list UI

### Version 0.2

- Device connection
- Text messaging

### Version 0.3

- File transfer

### Version 0.4

- Drag-and-drop interface
- Transfer animations

### Version 1.0

- Gesture-based file transfer
- HarmonyOS-inspired experience

---

## Use Cases

### School

Students can quickly exchange documents without USB sticks or email.

### Work

Transfer screenshots, PDFs, and files between nearby devices.

### Personal

Move photos and videos between your Apple devices with a simple gesture.

---

## Vision

HandOff aims to make file sharing feel natural.

Instead of clicking buttons and navigating folders, users interact with digital content as if it were a physical object—grab it, move it, and hand it to another device.

---

## Team

Developed as a student software engineering project using SwiftUI and Apple's modern frameworks.

## License

MIT License
