Smart Electric Energy Management System (SEEMS)

Description:
            The Smart Electric Energy Management System (SEEMS) is an IoT-based solution designed to monitor household electrical parameters and control appliances in real time. The system uses ESP32 with voltage and current sensors to measure live energy data and communicates with a Flutter mobile application through MQTT. Firebase is used for storing user data, device states, and historical energy records, enabling users to track consumption, analyze trends, and manage appliances efficiently.

Key Features:
            SEEMS provides real-time monitoring of voltage, current, power, and energy cost while allowing users to control appliances room-wise from the mobile app. The system supports customization such as renaming, adding, and deleting switches. It includes a dashboard for instant monitoring, an analysis section for viewing daily, weekly, and yearly usage, and an alert mechanism that notifies users about overload or abnormal consumption. The interface is designed to be simple, fast, and responsive for everyday use.

Technologies Used:
                 The project is built using ESP32 for hardware control, ZMPT101B and ACS712 sensors for electrical measurements, and MQTT (HiveMQ) for real-time data communication. The mobile application is developed in Flutter and integrated with Firebase Authentication and Realtime Database for cloud storage and device management. Wi-Fi is used as the primary communication medium between the hardware and the app.

Installation and Usage:
                      To begin, the ESP32 is connected with the voltage and current sensors and flashed with the firmware containing MQTT and Wi-Fi configurations. The Flutter application is then downloaded, configured with Firebase and MQTT broker details, and installed on the mobile device. After launching the app, the user can monitor live electrical readings, operate appliances, view consumption analytics, and receive alerts directly on the dashboard. The system works seamlessly over the local Wi-Fi network and updates data instantly.

Future Enhancements:
                   The system can be further improved by adding AI-based energy prediction, appliance-wise fault detection, and automated scheduling to reduce electricity bills. Additional integration with solar power systems, smart meters, and voice assistants such as Alexa or Google Home can make the system more scalable and user-friendly. Offline data caching and multi-device synchronization are also planned for future versions.

Acknowledgement:
               This project was completed with the support and guidance of mentors, faculty members, and peers who provided valuable insights during development. Appreciation is also extended to the open-source communities of Flutter, Firebase, and MQTT for providing tools and resources that enabled the creation of this system.
               
Contact:  
          For any inquiries or questions, please contact me at davalajanakiram936@gmail.com
