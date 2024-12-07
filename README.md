# CSCI441 Electronic Project Archive

This is the electronic project archive for Judson Hartley's CSCI441 Project. This document describes how to use the software included.

## Folder Structure
- Docker: This folder contains a basic docker compose yaml file, and the configuration files needed to self host MQTT and Home Assistant. I have used this file and corresponding configuration to setup this stack on a Raspberry Pi. There are many possible configurations, and future versions of this project will include documentation on the basics.

- Docs: This folder contains the project reports.

- PsyCalcJS: This folder contains the psychrometric calculator JavaScript to be run on Node.js. Use npm install to install the dependencies and npm start to start the calculator.

- SensorBoard: This folder contains the code to program a sensor board micro controller, using VS Code, and the PlatformIO plugin.
