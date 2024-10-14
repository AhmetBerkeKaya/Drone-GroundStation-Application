## Drone-GroundStation-Application
We developed a ground station software for a drone capable of operating both as an aerial and ground vehicle to participate in TEKNOFEST. This software meets all operational requirements of the drone, providing efficient control and data tracking.

# Ground Station for Hybrid Drone (Aerial and Ground Vehicle)

![Ground Station Design]
![1727216863708](https://github.com/user-attachments/assets/bf44b385-aa44-4555-b25e-fd9b87edb070)


This project involves the development of a custom ground station for a drone capable of operating both as an aerial and ground vehicle. The entire design of the ground station was created using Canva, ensuring a unique and user-friendly interface.

## Features

### 1. **Custom Design**
The ground station interface was designed from scratch using Canva, offering a distinctive and intuitive user experience.

### 2. **Map Integration**
We integrated OpenStreetMap into the interface, allowing real-time tracking of the drone’s location. The map data is fetched and displayed via an embedded HTML solution, ensuring seamless updates during flight operations.

### 3. **Weather Information**
We utilized the OpenWeatherMap API to retrieve real-time weather data, including wind speed and temperature, to enhance flight safety and decision-making during operations.

### 4. **Mathematical Functions and Coordination**
By collaborating with my teammate, we developed mathematical functions and connection protocols to ensure accurate data transmission and real-time updates between the drone and the ground station.

### 5. **Data Verification**
All retrieved and processed data were tested for accuracy using Mission Planner, ensuring that the drone's flight information and weather conditions were reliable and precise.

## How to Add an Image to Your README

To add an image like the ground station screenshot, simply upload your image to the GitHub repository and link to it using the following markdown syntax:


[Ground Station Design](path_to_your_image.png)
## Tools & Technologies Used
-Python: For scripting, data management, and ground station functionalities.
-PyQt5: For creating the graphical user interface (GUI) of the ground station.
-HTML & JavaScript: To embed and interact with OpenStreetMap for real-time mapping.
-Canva: For custom ground station interface design.
-OpenStreetMap: For real-time mapping and location tracking.
-OpenWeatherMap API: To retrieve weather and wind data for enhanced flight safety.
-Mission Planner: To test and verify the accuracy of drone data and weather conditions.
