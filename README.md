#Overview

This project is a simple temperature-controlled fan system built using an Arduino Uno and a TMP36 temperature sensor. The idea was to create a small system that can automatically respond to changes in room temperature and adjust cooling accordingly.

The TMP36 sensor measures the ambient temperature and outputs a voltage that is proportional to the temperature. The Arduino reads this analog signal, converts it into a temperature value, and uses it to control the speed of a DC motor that acts as the fan.

To make the system more interactive, a 16×2 LCD display is used to show the current temperature in real time. This allows the user to continuously monitor the environment.

When the temperature goes above 30 °C, the system triggers an alert using a piezo buzzer and an indicator LED to notify the user that the temperature has crossed the threshold.

A push button is also included as a manual override. Pressing the button disables the buzzer temporarily, allowing the user to silence the alert while the system continues monitoring the temperature.

#What I Learned

While building this project, I got hands-on experience with:

Reading analog sensor data using Arduino

Converting voltage signals into temperature values

Using PWM to control motor speed

Interfacing LCD displays with microcontrollers

Handling digital inputs like push buttons

Integrating multiple components into a working embedded system

Overall, this project helped me understand how sensing, processing, and actuation work together in a basic embedded system.
<img width="630" height="401" alt="image" src="https://github.com/user-attachments/assets/7119b229-eb16-467d-bf7c-baa4716f6f14" />
<img width="615" height="394" alt="image" src="https://github.com/user-attachments/assets/d09420fe-973b-4f80-8090-06f181b485bb" />

