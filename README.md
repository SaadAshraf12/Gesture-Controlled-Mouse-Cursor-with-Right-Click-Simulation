# Gesture-Controlled-Mouse-Cursor-with-Right-Click-Simulation
Transform your computer interaction with a gesture-controlled mouse cursor: move with your index finger and effortlessly right-click by touching your index finger and thumb. Experience intuitive computing through advanced computer vision and gesture recognition.


Mouse Control Integration:

Added pyautogui library to control the mouse cursor. Adjusted cursor_x and cursor_y based on the index finger's position relative to the screen size (screen_width and screen_height).
Right-Click Simulation:

If the distance between the thumb and index finger tips (distance) is less than 0.04 (adjust as needed), it simulates a right-click using pyautogui.rightClick().
Adjustments:

Screen resolution (screen_width and screen_height) should be set according to your actual screen size to accurately control the mouse cursor.
Execution:

The loop continuously captures webcam frames, processes hand landmarks, updates the mouse cursor position with the index finger, and triggers a right-click when the thumb and index finger are close enough.
This script should now allow you to control your mouse cursor with your index finger and perform a right-click gesture by touching your index finger and thumb together. Adjust the distance threshold and cursor movement speed (duration) as per your preference and setup.


![Screenshot 2024-07-08 171943](https://github.com/SaadAshraf12/Gesture-Controlled-Mouse-Cursor-with-Right-Click-Simulation/assets/95135917/5d8bd32c-b044-4501-b715-a06b7db77059)
