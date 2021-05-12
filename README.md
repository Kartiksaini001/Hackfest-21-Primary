# Hackfest-21
This repo contains the primary project of Team Alpha_zero for Hackfest'21

### The Project
It is an app for helping drivers by suggesting appropriate speed limit by taking different things into consideration like traffic signs/signals, sensitive buildings like schools, hospitals, etc.

### Basic Idea
The idea is to create an app which suggests appropriate speed limit by recognizing traffic signs/signals on the road, and taking into account the amount of traffic and nearby sensitive areas/buildings. Beside this, the app will suggest to slow down if the speed of the vehicle is above the suggested speed limit and also suggest not to horn near sensitive areas.
* Traffic Sign Recognition: This is done using pre trained ML model
* Traffic on Road and Sensitive areas: For this, we used Google Maps API to check traffic and to find sensitive buildings near the vehicle.
* Suggest Speed: This was planned to do using an ML model to suggest the best possible speed. But due to some difficulties we decided to make our own algorithm, which may not be as good as the ML model.

### Current Progress
* We have the ML model for traffic sign recognition
* Google Maps API is configured with the app
