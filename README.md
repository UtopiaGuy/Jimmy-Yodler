# Jimmy Yodeler: Military Voice Procedure Trainer

## Overview

**Jimmy Yodeler** is a web-based training application designed to teach military voice procedures to signal operator trainees. Inspired by interactive language learning platforms, this tool uses **call-and-response training**, **voice recognition**, and **audio feedback** to enhance communication skills in simulated military environments.

## Features

- **Voice Interaction Modules**
  - Whisper API for **voice-to-text transcription**.
  - Text-to-Speech (TTS) with **audio band filtering** for realism.
- **Training Scenarios**
  - Library of **pre-scripted** military communication drills.
  - Real-time **response evaluation** and scoring (out of 100).
- **Feedback System**
  - Immediate **corrective feedback**.
  - Performance tracking with **visual graphing and analytics**.
- **User Authentication**
  - Secure login for **trainees** and **administrators**.
- **Admin Dashboard**
  - View trainee progress and **analyze training effectiveness**.

## System Architecture

### **Frontend**
- **Web UI:** Built with **HTML, CSS, and JavaScript** for a responsive interface.
- **Client-Side Logic:** Handles **user interactions and API communication**.

### **Backend**
- **Server:** **Node.js/Express** for API handling.
- **Performance-Critical Modules:** Developed in **C++** for real-time processing.

### **Core Integrations**
- **Whisper API** → Converts trainee voice input into text.
- **Text-to-Speech (TTS)** → Generates **filtered** military-style radio communications.
- **MySQL Database** → Stores:
  - User credentials.
  - Training scripts.
  - Accuracy scores and feedback.

## Workflow

1. **Trainee logs in** and selects a training scenario.
2. The system **plays a pre-recorded message** using TTS.
3. The trainee **responds using their voice**.
4. The system:
   - Converts speech to text via **Whisper API**.
   - Compares the response to the **expected script**.
   - Scores the accuracy and provides **immediate feedback**.
5. If accuracy is low, the trainee is prompted to **repeat** the message.
6. Results are **stored and visualized** in the trainee's dashboard.

## User Roles

| Role                  | Responsibilities |
|-----------------------|----------------|
| **Trainee (User)** | Practices military voice procedures, receives feedback, and tracks progress. |
| **Administrator** | Manages training scripts, monitors performance, and analyzes training effectiveness. |

## System Requirements

- **Device:** Any modern PC/laptop with an internet connection.
- **Microphone:** Required for voice input.
- **Basic Training:** Familiarity with military voice procedure.

## Challenges & Considerations

- **Voice Recognition Accuracy:** Handling **accents, background noise, and distorted radio signals**.
- **Real-Time Processing:** Ensuring **low latency** during call-and-response interactions.
- **Engagement & Usability:** Keeping the UI **simple and effective** for trainees.

## Future Enhancements

- **Expanded Training Library:** More realistic military scenarios.
- **AI-Driven Feedback:** Adaptive learning based on trainee peformance.
- **Mobile Compatibility:** Support for training on-the-go.


## Contact

For questions or feedback, please contact **Ahmed Nosseir** at **any284@uregina.ca**.
