# Computer Vision Quiz with Hand Gesture Recognition

This project is a Computer Vision Quiz application that enables users to answer questions using hand gesture recognition. Developed with the cvzone library, it leverages hand-tracking technology to create an interactive, touch-free quiz experience where users can interact by making specific gestures.

## Project Overview

This innovative quiz application combines computer vision with gesture-based controls, making learning more engaging and interactive. Users respond to quiz questions by using hand gestures, which are recognized and processed by the application to determine answers.

## Dataset

The project uses a dataset of multiple-choice questions in CSV format (Mcqs.csv). The file includes:

- Questions
- Answer Choices
- Correct Answers

The questions are displayed one at a time, and users can answer by making specific hand gestures.

## Running the Application
- Camera Access: Ensure that your webcam is accessible, as the application relies on real-time hand tracking.
- Gestures: Each question presents multiple choices, and you answer by showing a specific hand gesture corresponding to your selected choice. Details of gestures and their corresponding actions are outlined in the notebook.

## Technical Details

- Hand Tracking: The application uses the cvzone library, which is built on top of mediapipe, to detect and track hand gestures in real-time.
- Gesture Recognition: Each gesture corresponds to a choice, allowing users to select answers without physical touch.
- Feedback: The application provides immediate feedback on whether the selected answer is correct.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
