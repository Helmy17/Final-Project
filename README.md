Steps to be followed :


Step 1: Set Up ESP32 for Sensor Data

    Write code to collect heart rate, temperature, and IMU sensor data using the ESP32.
    Set up the ESP32 to connect to the MQTT broker.
    Ensure the ESP32 publishes sensor readings to the broker.

Step 2: Set Up Raspberry Pi for Camera and Audio

    Write a Python script on the Raspberry Pi to capture images using the camera.
    Write another Python script to record audio in emergency situations.
    Make sure both the image and audio files are published to the MQTT broker.

Step 3: Configure Node-RED Dashboard

    Set up a Node-RED dashboard to visualize the sensor data, images, and audio from the Raspberry Pi.
    Add controls to manually take pictures using the camera.
    Test that the data from the sensors and images/audio are correctly displayed on the dashboard.

Step 4: Set Up MQTT Broker

    Install and start the MQTT broker on the Raspberry Pi or another device.
    Make sure the ESP32 and Raspberry Pi are connected and publishing data to the broker.

Step 5: Test the Entire System

    Start the MQTT broker.
    Run the ESP32 code to stream sensor data to the broker.
    Run the Raspberry Pi scripts to capture images and record audio during emergencies.
    Monitor everything in the Node-RED dashboard and check that manual controls work.

Step 6: Push Code to GitHub

    Create a GitHub repository for the project.
    Add all project files, including ESP32 code, Raspberry Pi scripts, and Node-RED flows.
    Push the code to GitHub for team members to access.
