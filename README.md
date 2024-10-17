# Event Trigger Timer

**Event Trigger Timer (ETT)** is a LabVIEW-based application designed to manage and visualize the timing of various triggered events. It provides users with control over event triggers, managing durations, and visualizing results in real-time through a graphical interface.

## Features:
- **Event Triggering**: The program responds to various user button presses to start, stop, and reset timed events.
- **Time Tracking**: Keeps track of elapsed time for each event and offers feedback based on defined intervals.
- **Graphical Display**: Visualizes the current status of the event (running or stopped) using a 2D Picture control.
- **Multiple Timers**: The program can handle multiple timed events simultaneously, allowing different durations and conditions to be applied.
- **Customizable Intervals**: Users can input specific intervals for each event trigger.

## How It Works:
1. **Event Start**:
   - When the user presses the "Start" button, the corresponding event timer begins counting.
   - A value is set for the duration, and the event starts counting down or up depending on the setup.

2. **Event Stop**:
   - The "Stop" button halts the timer and stops further calculations for the specific event.
   - The 2D Picture control reflects the stop status of the event visually.

3. **Reset Event**:
   - The "Reset" button allows the user to reset the event timer, clearing the current time and restarting the process.

4. **Visual Feedback**:
   - Each event displays visual feedback in a picture box, showing the current state of the event.
   - If the event is running, the picture box will update accordingly; when stopped, it shows a different image or indication.

5. **Multiple Conditions**:
   - The program handles multiple conditions for different events, allowing complex setups with individual controls for each event.
   - Logic branches in the program ensure that only the correct event is processed based on user input.

6. **Adjustable Time Intervals**:
   - Users can set specific time intervals for each event (default is 1000 ms).
   - The program checks these intervals and updates the interface based on the elapsed time.

## Usage:
1. Connect the necessary hardware (if applicable).
2. Run the program in LabVIEW.
3. Use the interface buttons to trigger events:
   - `Start` to initiate a timed event.
   - `Stop` to halt the timer.
   - `Reset` to reset the event and start over.
4. Input specific time intervals in the control panel if desired.
5. Monitor the visual feedback through the 2D Picture control.

## Example:
- A user presses the "Start" button to begin an event, and the timer starts counting the elapsed time.
- Visual feedback shows the current state of the event.
- When the user presses "Stop," the timer halts, and the visual feedback changes to reflect the stop.
- Pressing "Reset" clears the event and allows it to be started again.

## Troubleshooting:
- Ensure that the correct buttons are being pressed for the desired actions (start, stop, reset).
- If timers do not behave as expected, verify that the time intervals are correctly set and the necessary event conditions are met.

## Code:
![image](https://github.com/user-attachments/assets/f3eea2bc-cdfc-43f2-bc34-b2cca41ff59d)
![image](https://github.com/user-attachments/assets/d6c7b083-2997-43c1-b47c-3dbc02055ed5)
![image](https://github.com/user-attachments/assets/2ad0247c-dbac-45b2-8a33-89d1910fe148)
![image](https://github.com/user-attachments/assets/e05d093d-2fb4-4170-a6fb-d5b386c64ffc)
![image](https://github.com/user-attachments/assets/88c94a98-8a10-4086-a558-5048fca6161a)
![image](https://github.com/user-attachments/assets/5ca04a75-308b-4496-ac7b-c62b49059b59)

## Program view:
![image](https://github.com/user-attachments/assets/2e22b099-9d41-4480-96e5-6f92df198ba8)
![image](https://github.com/user-attachments/assets/cb0ed240-6a61-4ce6-bbe2-becce95ba484)

