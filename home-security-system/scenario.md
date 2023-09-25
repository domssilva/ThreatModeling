# Scenario: Smart Home Security System

## Imagine a basic e-commerce website with the following components:
* Mobile App: For remote monitoring and control
* Indoor Cameras: With facial recognition capabilities
* Outdoor Cameras: Motion-sensitive, night vision
* Door Sensors: For all external doors
* Glass Break Sensors: For windows
* Alarm System: Connected to a central monitoring service
* Smart Door Locks: Can be controlled via the mobile app
* WiFi Router: All devices connected via a home WiFi network

## Features:
* Real-time alerts for any security incidents
* Voice commands to control the system
* Integration with smart home devices like thermostats and lights
* Scheduled arm/disarm times
* Geofencing to auto-arm/disarm when you leave or arrive home
* Two-factor authentication for app and web portal access

## Additional Questions:
how does the remote connection works between the mobile and that system? is there a server where our wifi sends the data to?
In this hypothetical scenario, let's assume there's a cloud-based server that acts as an intermediary between the mobile app and the home security system. This server is responsible for:

1. Storing user profiles and configuration settings.
1. Handling real-time alerts and notifications.
1. Processing and forwarding commands from the mobile app to the home security system.
1.Storing video footage and sensor data for a limited time (e.g., 30 days). 

Your home WiFi network would connect to this cloud-based server to sync data and receive commands. The mobile app communicates with the same server to get updates and send commands.

* is it possible to connect to each component (camera, alarm system, smart lock, sensors) individually? within the local network?
In a typical smart home security system, individual components like cameras, alarm systems, smart locks, and sensors are usually not directly accessible from a computer over the internet. They're generally designed to communicate through a centralized hub or controller, which in turn connects to the cloud-based server.

However, within the local network, it's sometimes possible to access these devices directly, depending on the device and its settings. This is often how initial setup and troubleshooting are done.

For the sake of this exercise, let's assume two scenarios:

1. Standard Setup: All devices communicate via the centralized cloud-based server, and direct access is not allowed from outside the home network.
1. Advanced Setup: Within the local network, direct access to individual components is possible.