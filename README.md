# LavendAid - ALERT

## Overview
LavendAid is dedicated to leveraging innovative technology and research to prevent sexual violence in communities. ALERT is their first product, a locket that triggers an emergency app on an iPhone when the user is in danger.

## Goals
- Introduce different technologies around campuses to create a safe space for everyone.
- Utilize scientific research to ensure effectiveness of projects.
- Provide a quick and discreet way for users to alert their emergency contacts, record evidence, and request help in dangerous situations.

## Specifications
- ALERT is a locket passive communication tag using 13.56 MHz frequency waves to communicate with iPhones.
- When tapped with an iPhone, it activates a shortcut that:
  - Sends messages and emails to emergency contacts with the user's location.
  - Records a video of the situation and sends it to emergency contacts.
  - Adjusts phone settings to conserve battery and minimize distractions.
  - Updates the user's location to emergency contacts every 90 seconds until stopped or battery runs out.

## Detailed Section
1. **Vibration Notification**: Alerts user that the process has started.
2. **Airplane Mode Off, Low Power Mode On**: Ensures phone can send/receive data and conserves battery.
3. **Battery Check and Connectivity**: Adjusts network settings based on battery level to conserve power.
4. **Music Paused, Brightness Reduced**: Minimizes distractions or alerts to the attacker.
5. **Initial Location Saved**: Stores user's initial location for reference.
6. **Photo Capture**: Takes a photo with the back camera for clarity.
7. **Alert Message and Email**: Informs emergency contacts of danger, includes location and photo.
8. **Wait 90 Seconds**: Allows time for user to move or escape.
9. **Distance Calculation**: Checks if user has moved from initial location.
10. **Location Update if Moved**: Notifies emergency contacts of user's new location if moved.
11. **Status Update if Not Moved**: Informs emergency contacts if user remains stationary.
12. **Repetition for 150 Minutes**: Continuously updates emergency contacts until stopped or battery depleted.

## Future Improvements
- Optimization for Android using NFC Tools or Trigger app for similar shortcut creation.
- Personalized setup tag for individuals preloaded with their contacts for automation when a "safe person" brings their phone in contact with the tag.

