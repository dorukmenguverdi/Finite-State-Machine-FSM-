# Finite-State-Machine-FSM-

This project simulates a pedestrian crossing traffic light system using a Finite State Machine (FSM). The system has three states: Red, Yellow, and Green, and it changes between these states in a set order.

States:
Red: Vehicles can go, and pedestrians must wait.
Yellow: Vehicles are getting ready to stop.
Green: Pedestrians can cross, and vehicles must wait.

How It Works:
The traffic light starts in the Red state.
After 3 seconds, it changes to Yellow, showing vehicles are stopping.
After 3 more seconds, it changes to Green, allowing pedestrians to cross.
After another 3 seconds, it changes back to Red.
This cycle repeats for 5 rounds (or more, if you change the loop number).


How to Use:
Run the script.
Watch the traffic light change states every 3 seconds.
The program shows each state and explains what happens at that moment.

Technologies Used:
Python
Time module for timing the transitions
