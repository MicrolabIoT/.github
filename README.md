# 🏢 MicrolabIoT – Project Overview

Welcome to the official code repository of **Atelier Eindhoven B.V.** This organization manages all code related to the **Microlab IoT infrastructure**, including smart building control, data collection, web interfaces, and experimental tooling.

---

## 🌐 Web-based applications & Dashboard Interfaces

These repositories power the user-facing web interfaces, including dashboards and configuration panels.
- [`Admin-panel`](https://github.com/MicrolabIoT/TabletAdminSPA) – Admin panel for tablet control, smart-building control (IoT side) - works with 
- [`Meeting room application`](https://github.com/MicrolabIoT/TabletSPA) - Meeting room tablet application for controlling lights, music, TV etc.
- [`factory-provisioning-tool`](https://github.com/MicrolabIoT/factory-provisiong-tool) – Fullstack application for factory flashing devices and generating QR.
- [`factory-testing-tool`](https://github.com/MicrolabIoT/factory-testing-tool) - Factory **testing tool** for sensors of a device straight out of the factory using a broker (hivemq) as the response.
- [`Device-mapper`](https://github.com/MicrolabIoT/zigbee-helper-tool) - frontend for flashing esp devices with right settings and configuring zigbee devices.
- ~['Floor-plan-dashboard](https://github.com/MicrolabIoT/Floor-plan-dashboard) - Interactive SVG dashboard for floor plans, merged into `Admin-panel`~
- 

---

## 🔧 Backend Services & Architecture

More backend-oriented projects and service infrastructure.

- [`storing-script`](https://github.com/MicrolabIoT/storing-script) - Mass storing script of specific MQTT messages in our broker.
- [`storing_script`](https://github.com/MicrolabIoT/storing_script) - Mass storing **dynamic** script of specific MQTT messages in our broker.
- [`broker-logger`](https://github.com/MicrolabIoT/broker-logger) - Latest broker storer of ALL mqtt messages, which is in use right now.
- [`db_24h`](https://github.com/MicrolabIoT/db_24h) - Last 24 hour MQTT broker storer, for data analysis.
- [`building-management-api`](https://github.com/MicrolabIoT/TabletAPI) - HTTP API for room/building specific settings, e.g. light-count, user-settings, room size, meeting-room tablet settings etc.
- [`Light-control-API`](https://github.com/MicrolabIoT/light_control_MQTT_API) - MQTT version of `building-management-api` for only the light-control settings, built on top of it.
- [`DPT-backend`](https://github.com/MicrolabIoT/microlab-dpt-PROD) - Backend service for flashing esp-devices, used by `device-mapper`, uses ESPHOME core to OTA devices.
- [`exact2postgres`](https://github.com/MicrolabIoT/exact_to_postgres) - Exact to postgres CRON storage.
- [`samsung-serial-controller`](https://github.com/MicrolabIoT/samsung-tv-serial-controller) - backend system to be able to control samsung tvs, with custom commands.
- [`dpt-logger`](https://github.com/MicrolabIoT/dpt-logger) - logger related to `Device-mapper` and `DPT-backend`, every interaction in the frontend is logged whilst all backend events are logged.
- [`Calibration`](https://github.com/MicrolabIoT/Calibration) - Calibration backend service for calculating coefficients for a simple linear regression where eos sensor and seperate lux sensor are variables.
- [`blinds-controller`](https://github.com/MicrolabIoT/blinds-controller) - Backend mapper for blind control commands.
- [`auto-mapper`](https://github.com/MicrolabIoT/auto-mapper) - Main mapper for things such as lights to sateraito and sateraito status to rooms.
- 
- ~[`mqtt-light-mapper`](https://github.com/MicrolabIoT/mqtt-light-mapper) - Predecessor of `auto-mapper~  
---

## 🏢 Smart Building Control

Automation and control logic for lights, doors, ventilation, and energy management.

- [`light_control`](https://github.com/MicrolabIoT/light_control_4) - Smart lighting service based on MQTT
- [`rayonics-locks-backend`](https://github.com/MicrolabIoT/rayonics-locks-backend`) - Nest backend for our proprietary lock system based on RAYONICS.
- [`Rayonics-android-app`](https://github.com/MicrolabIoT/rayonics-android-app) - Java based android app for rayonics.


- [`light_hard_shutdown`](https://github.com/MicrolabIoT/Light_hard_shutdown)
- [`proto-light-control`](https://github.com/MicrolabIoT/proto-light-control)
- [`light_control_ui`](https://github.com/MicrolabIoT/light_control_ui)
- [`motion-switch-controller`](https://github.com/MicrolabIoT/motion-switch-controller)
- [`doordevice-controller`](https://github.com/MicrolabIoT/doordevice-controller)
- [`trigger-light`](https://github.com/MicrolabIoT/trigger-light)
- [`lights-publisher`](https://github.com/MicrolabIoT/lights-publisher)

---

## 📡 MQTT / Messaging / Auth

All MQTT tools and messaging-related infrastructure (including auth and device messaging).

- [`zkteco-scrapper-ws`](https://github.com/MicrolabIoT/zkteco-scrapper-ws) - Connects to websockets and forwards door events to MQTT.
- [`mqtt-auth-script`](https://github.com/MicrolabIoT/mqtt-auth-script) - Auth add-on for MQTT broker.
- [`mqtt-light-control`](https://github.com/MicrolabIoT/mqtt-light-control)
- [`auto-mapper`](https://github.com/MicrolabIoT/auto-mapper) – Automatically detects and maps controllable devices.
- [`server-monitoring`](https://github.com/MicrolabIoT/server-monitoring) - MQTT publisher of server physical stats, RAM, cpu etc.


- [`mqtt-ota`](https://github.com/MicrolabIoT/mqtt-ota)
- [`mqtt_sensors`](https://github.com/MicrolabIoT/mqtt_sensors)
- [`zigbee2mqtt-extension-host`](https://github.com/MicrolabIoT/zigbee2mqtt-extension-host)

---

## 🧠 Experimental, prototyping & visualizations

Prototypes, scripts, and smaller test utilities that may be in development or R&D.

- [`MQTT-simulation`](https://github.com/MicrolabIoT/MQTT-Sim-Tool) - Simulates MQTT broker prod messages in development.
- [`SVG-building-dashboard`](https://github.com/MicrolabIoT/Floor-plan-dashboard) - Initial testing of an interactive SVG dashboard of a floor in a building - merged into `admin-panel`.
- [`trv publisher`](https://github.com/MicrolabIoT/trv-publisher) - jupyter notebook to manually send commands to TRV's in a building, not automated or in prod yet.
- [`web-easy-mapper`](https://github.com/MicrolabIoT/webeasy-mapper) - Temperature mappers from EOS to Webeasy listener topics.
- [`lux-pir-analysis`](https://github.com/MicrolabIoT/rb-lux-and-pir-analysis) - Lux and pir analysis in jupyter notebook
- [`Sensor-dashboard`](https://github.com/MicrolabIoT/Dashboard_sensors) - Initial sensor-dashboard in python DASH.
- [`testsvg`](https://github.com/MicrolabIoT/testsvg) - Test interactive SVG dashboard of a floor plan, predecessor of `floor-plan-dashboard`.
- [`tablet_lightshow`](https://github.com/MicrolabIoT/Tablet_lightshow) – Simple Python script to flicker the lights of a tablet's LED.
- [`observable-tutorial`](https://github.com/MicrolabIoT/observable-tutorial) – Angular tutorial in observables.
- [`people-counter`](https://github.com/MicrolabIoT/peopleCounter) - People counter using ML and camera streams. Never went into production due to buggy frontend + manual tagging.
- [`proto-light-control`](https://github.com/MicrolabIoT/proto-light-control) - JS test version for light control, stopped quite quickly.
- [`light-calibration-logger`](https://github.com/MicrolabIoT/light-calibration-logger) - Small NESTJS logger for specific topics, used for data analysis
  

---

## 🧰 Utility Tools

Smaller helpers, tools, scripts, and miscellaneous utilities.

- [`zigbee-module-flasher`](https://github.com/MicrolabIoT/zigbee-module-flasher) - Flasher tool for the zigbee module on our sateraito/gateways for zigbee.
- [`factory-testing-tool`](https://github.com/MicrolabIoT/factory-testing-tool) - Factory testing tool for sensors of a device straight out of the factory.
- [`light-publisher`](https://github.com/MicrolabIoT/lights-publisher) - Mass on/off tool for lights in a building
- [`light-hard-shutdown](https://github.com/MicrolabIoT/Light_hard_shutdown) - Mass shutdown of a buildings light.


---
