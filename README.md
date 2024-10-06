# Smooth Moves

Smooth Moves is an innovative project that integrates Electroencephalography (EEG) technology to enable hands-free control of automation tasks. By leveraging brain activity, captured via the Emotiv EPOC X EEG headset, this system allows users to trigger automation workflows on iOS devices using mental commands and facial expressions. This project bridges the gap between neuroscience and automation, empowering users—especially those with physical disabilities—to control their digital environment using just their thoughts.

## Project Overview

Smooth Moves revolutionizes how automation tasks are executed by removing the need for physical interaction with devices. By using EEG technology, users can:
- **Trigger automation tasks** (e.g., opening apps, controlling smart devices).
- **Create personalized workflows** via the iOS Shortcuts app.
- **Control their digital environment** through mental commands and facial expressions.

This system provides a natural, intuitive interface for users with mobility challenges, enhancing both productivity and independence.

## Features

### EEG-Based Control
- **Mental Commands**: Users can map various mental commands (e.g., push, pull, lift, drop) to specific automation tasks.
- **Facial Expressions**: The system recognizes facial expressions (e.g., smile, frown, clench) to trigger actions.
  
### Seamless iOS Integration
- **iOS Shortcuts**: Users can create, map, and trigger automation workflows using Apple’s Shortcuts app.
- **Real-time Interaction**: The system provides real-time feedback and control through brain activity.

### Backend Architecture
- **Python Backend**: The backend interacts with the Emotiv WebSocket Secure (WSS) server to process brain signals and facial expressions.
- **Firebase Realtime Database**: Flags triggered by mental commands are stored in a cloud-based Firebase database, allowing real-time communication between the EEG headset and the iOS app.
- **Supabase Database**: Stores user preferences and shortcut mappings for future access and updates.

## Methodology

The system is designed in two phases:
1. **Phase I**: Establishes the basic architecture for controlling virtual devices through mental commands. The user maps actions in the iOS Shortcuts app, and the Python backend processes and translates brain signals into corresponding actions.
   
2. **Phase II**: Enhances the system by reducing latency and adding more mental command options. The system integrates a Realtime Cloud Database to improve responsiveness and data handling.

## Applications

Smooth Moves is designed to be versatile, with potential applications including:
- **Automation Control**: Control smart devices or perform automated tasks using mental commands.
- **Gaming**: Use mental commands to play games or control virtual environments.
- **Assistive Technology**: Help individuals with disabilities control devices without needing physical input.

## Future Work

The project opens up possibilities for further development, including:
- Expanding the system to other platforms such as Android.
- Generalizing the backend to support additional use cases (e.g., gaming, text writing).
- Enhancing brain signal detection accuracy to further reduce latency and false triggers.

## Acknowledgments

This project was developed as part of a minor project for the Department of Computer Science & Engineering at Jaypee Institute of Information Technology.
