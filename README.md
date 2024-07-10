# Automated Attendance Monitoring System

## Overview
The proposed solution is an automated attendance monitoring system that utilizes facial recognition technology to identify students as they enter a classroom or lecture hall. This system aims to eliminate the need for manual attendance tracking, reduce errors, and streamline the process of recording student attendance.

## Videos and Outputs
- **Original Video:** [Original Video](VID_20240228_112302.mp4)
- **Output Video:** [Output Video](out.mp4)

## System Components
- **Face Recognition:** Uses pre-trained models to detect and recognize faces in real-time video streams.
- **Attendance Marking:** Automatically marks attendance in a CSV file (`out Attendance.csv`) when a recognized face is detected.
- **Video Processing:** Capable of processing videos to detect faces and mark attendance retrospectively.

## How to Use
1. **Requirements:**
   - Libraries: `cmake`, `dlib`, `face_recognition`, `numpy`, `opencv-python`

2. **Setup:**
   - Clone the repository.
   - Install required libraries .

3. **Running the System:**
   - Execute `python main.py` to start the system.
   - Choose between real-time video streaming or processing a recorded video.

4. **Output:**
   - The system outputs an attendance CSV file as (`out Attendance.csv`) with timestamps for each recognized student.
   - An output video as (`out.mp4`) demonstrates the detection and recognition process.

