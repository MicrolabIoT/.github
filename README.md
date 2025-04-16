# 🏢 MicrolabIoT – Project Overview

Welcome to the official code repository of **Atelier Eindhoven B.V.** This organization manages all code related to the **Microlab IoT infrastructure**, including smart building control, data collection, web interfaces, and experimental tooling.

---

## 🌐 Web-based applications & Dashboard Interfaces

These repositories power the user-facing web interfaces, including dashboards and configuration panels.
- [`Admin-panel`](https://github.com/MicrolabIoT/TabletAdminSPA) – Admin panel for tablet control, smart-building control (IoT side) - works with 
- [`Meeting room application`](https://github.com/MicrolabIoT/TabletSPA) - Meeting room tablet application for controlling lights, music, TV etc.
- [`factory-frontend`](https://github.com/MicrolabIoT/factory-provisiong-tool) – Fullstack application for factory flashing devices.
- [`Device-mapper`](https://github.com/MicrolabIoT/zigbee-helper-tool) - frontend for flashing esp devices with right settings and configuring zigbee devices.

- 
- [`dashboard_sensors`](https://github.com/MicrolabIoT/Dashboard_sensors) – Dash dashboard for all sensor data.

---

## 🔧 Backend Services & Architecture

More backend-oriented projects and service infrastructure.

- [`storing-script`](https://github.com/MicrolabIoT/storing-script) - Mass storing script of almost all MQTT messages in our broker.
- [`building-management-api`](https://github.com/MicrolabIoT/TabletAPI) - HTTP API for room/building specific settings, e.g. light-count, user-settings, room size, meeting-room tablet settings etc.
- [`Light-control-API`](https://github.com/MicrolabIoT/light_control_MQTT_API) - MQTT version of `building-management-api` for only the light-control settings, built on top of it.
- [`DPT-backend`](https://github.com/MicrolabIoT/microlab-dpt-PROD) - Backend service for flashing esp-devices, used by `device-mapper`, uses ESPHOME core to OTA devices.
- 
- [`general-service-architecture`](https://github.com/MicrolabIoT/general-service-architecture)
- [`docserver-mqtt-service`](https://github.com/MicrolabIoT/docserver-mqtt-service)
- [`event-monitoring`](https://github.com/MicrolabIoT/event-monitoring)
- [`mqtt-factory-db-projection`](https://github.com/MicrolabIoT/mqtt-factory-db-projection)
- [`dct-logger`](https://github.com/MicrolabIoT/dct-logger)
- [`db_24h`](https://github.com/MicrolabIoT/db_24h)
---

## 🏢 Smart Building Control

Automation and control logic for lights, doors, ventilation, and energy management.

- [`light_control`](https://github.com/MicrolabIoT/light_control)
- [`light_control_prod`](https://github.com/MicrolabIoT/Light_control_prod)
- [`light_hard_shutdown`](https://github.com/MicrolabIoT/Light_hard_shutdown)
- [`proto-light-control`](https://github.com/MicrolabIoT/proto-light-control)
- [`light_control_ui`](https://github.com/MicrolabIoT/light_control_ui)
- [`zigbee-helpers-tool`](https://github.com/MicrolabIoT/zigbee-helpers-tool) – Helper for managing Zigbee devices.
- [`motion-switch-controller`](https://github.com/MicrolabIoT/motion-switch-controller)
- [`doordevice-controller`](https://github.com/MicrolabIoT/doordevice-controller)
- [`trigger-light`](https://github.com/MicrolabIoT/trigger-light)
- [`lights-publisher`](https://github.com/MicrolabIoT/lights-publisher)

---

## 📡 MQTT / Messaging / Auth

All MQTT tools and messaging-related infrastructure (including auth and device messaging).

-
- [`mqtt-auth-script`](https://github.com/MicrolabIoT/mqtt-auth-script)
- [`mqtt-light-control`](https://github.com/MicrolabIoT/mqtt-light-control)
- [`auto-mapper`](https://github.com/MicrolabIoT/auto-mapper) – Automatically detects and maps controllable devices.
- [`mqtt-light-control-ui`](https://github.com/MicrolabIoT/mqtt-light-control-ui)
- [`mqtt-ota`](https://github.com/MicrolabIoT/mqtt-ota)
- [`mqtt_sensors`](https://github.com/MicrolabIoT/mqtt_sensors)
- [`zigbee2mqtt-extension-host`](https://github.com/MicrolabIoT/zigbee2mqtt-extension-host)

---

## 🧠 Experimental & Prototyping

Prototypes, scripts, and smaller test utilities that may be in development or R&D.

- [`MQTT-simulation`](https://github.com/MicrolabIoT/MQTT-Sim-Tool) - Simulates MQTT broker prod messages in development.
- [`SVG-building-dashboard`](https://github.com/MicrolabIoT/Floor-plan-dashboard) - Initial testing of an interactive SVG dashboard of a floor in a building - merged into `admin-panel
- [`testsvg`](https://github.com/MicrolabIoT/testsvg)
- [`tablet_lightshow`](https://github.com/MicrolabIoT/Tablet_lightshow) – Simple Python script to flicker the lights of a tablet's LED.
- [`observable-tutorial`](https://github.com/MicrolabIoT/observable-tutorial) – Angular tutorial in observables.
  
- [`weather-open-maps`](https://github.com/MicrolabIoT/weather-open-maps)
- [`device-control-service`](https://github.com/MicrolabIoT/device-control-service)
- [`sensor-monitoring-viewer`](https://github.com/MicrolabIoT/sensor-monitoring-viewer)
- [`statistics-service`](https://github.com/MicrolabIoT/statistics-service)
- [`temporary-keyboard-import`](https://github.com/MicrolabIoT/temporary-keyboard-import)
- [`factory-scripting-core`](https://github.com/MicrolabIoT/factory-scripting-core)
- [`calibration-service`](https://github.com/MicrolabIoT/calibration-service)
- [`registry-sensor-names`](https://github.com/MicrolabIoT/registry-sensor-names)

---

## 🧰 Utility Tools

Smaller helpers, tools, scripts, and miscellaneous utilities.

- [`zigbee-module-flasher`](https://github.com/MicrolabIoT/zigbee-module-flasher) - Flasher tool for the zigbee module on our sateraito/gateways for zigbee.
- [`auto-mapper`](https://github.com/MicrolabIoT/auto-mapper)
- [`scripting-scripts`](https://github.com/MicrolabIoT/scripting-scripts)
- [`trigger-light`](https://github.com/MicrolabIoT/trigger-light)
- [`zigbee2mqtt-extension-host`](https://github.com/MicrolabIoT/zigbee2mqtt-extension-host)
- [`Tablet_lightshow`](https://github.com/MicrolabIoT/Tablet_lightshow)

---
