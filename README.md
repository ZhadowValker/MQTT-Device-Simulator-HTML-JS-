# MQTT-Device-Simulator-HTML-JS-
🛰️ MQTT Device Simulator — connect ⚡, publish 📡, and test 📊 IoT data instantly in your browser 🌐.

🛰️ MQTT Publisher Device Simulator
A lightweight, browser-based MQTT device simulator built using the Paho MQTT JavaScript client.
This single HTML file allows you to connect, publish, subscribe, and visualize simulated IoT device data — perfect for testing brokers, MQTT payloads, or IoT dashboards.

🚀 Features
No installation required — just open the .html file in any modern browser.
Connect to any MQTT broker using ws or wss (WebSocket) protocol.
Simulate device telemetry with customizable temperature and humidity data.
Auto-publish mode for periodic message simulation.
Subscribe and view messages live from any topic.
Visual-ready data — stores messages in localStorage for graphing on a graph.html page.
Responsive UI built with modern, clean styling (CSS only).

🧩 How to Use
Open the Mqtt Publisher Device Simulator.html file in your browser or upload it to CodePen.
Configure your broker:
Host (e.g. broker.hivemq.com)
Port (8883 for wss, or 8083 for ws)
Protocol (wss or ws)
Path (default /mqtt)
Credentials (if required)
Click 🔌 Connect to establish an MQTT connection.
Use 📡 Send to publish custom data or 🚀 Start Auto for automated simulation.
Subscribe to topics to view real-time MQTT messages in the log panel.

🧠 Example Configuration
Field	Example
Host	192.168.0.0
Port	8883
Protocol	wss
Path	/mqtt
Username	 iot
Password	 iot
Topic	devices/data

📊 Optional Graphing
The app stores all received data in your browser’s local storage (mqttDeviceData).
You can open a graph viewer (e.g., graph.html) to visualize device metrics over time.

🧱 Technologies Used
HTML5 + Vanilla JS
CSS3 (custom styling, no frameworks)
Paho MQTT JS client v1.1.0

🧪 Ideal For
MQTT Broker testing (Mosquitto, HiveMQ, EMQX, etc.)
IoT sensor data simulation
Educational demos
Quick debugging of MQTT topics and payloads

📝 License
This project is released under the MIT License.
Feel free to fork, modify, and experiment.
