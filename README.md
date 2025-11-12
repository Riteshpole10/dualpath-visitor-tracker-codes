# dualpath-visitor-tracker-codes
 click on this link to see the working  of the system -(https://www.kapwing.com/videos/6676ffc4ace67005abb45cb8)

Description:-

The **DualPath Visitor Tracker** is an IoT-based system designed to **count and monitor visitors** moving through a specific area. Using **two sensor paths**, it can detect the **direction of movement** (entry or exit) and maintain a real-time visitor count.

The system uses **Bolt IoT sensors** (like IR or ultrasonic sensors) connected to the Bolt Cloud platform to:

* Track when a person crosses **Path A → Path B** (entry)
* Track when a person crosses **Path B → Path A** (exit)
* Update the **visitor count live** on the cloud dashboard

This setup is ideal for:

* Offices and buildings for **occupancy monitoring**
* Events or shops to track **customer flow**
* Any application needing **real-time visitor statistics**

Key Features:-

* **Dual-path detection** for accurate direction tracking
* **Real-time visitor count** on the cloud
* **Easy integration** with Bolt IoT platform
* Can be expanded to **send notifications or logs** when thresholds are reached

Technology Used:-

* **Bolt IoT WiFi Module**
* **Infrared / Ultrasonic Sensors**
* **Python / Bolt Cloud API** for programming and dashboard
* Optional: **Web dashboard / Mobile App** for monitoring



How It Works:-

1. **Sensors placed on two paths** detect movement.
2. **Microcontroller reads sensor input** and sends data to Bolt Cloud.
3. **Logic determines direction**:

   * Path A → Path B = Entry
   * Path B → Path A = Exit
4. Visitor count updated on the cloud in real-time.



Applications:-

* Provides **accurate visitor tracking**
* Supports **real-time monitoring** for safety and capacity
* Useful for **IoT-based smart buildings** and analytics



