# deepost
A Node.js app that collects RSSI input and processes it using machine learning and provides report data via GraphQL.

## Overview

Below is an overview of the complete setup. 

![System overview of deepost](static/overview.png?raw=true "System overview of deepost")

It continuously measures RSSI (signal strength) between a nRF52832-based Bluetoth embedded device and an Android phone. An Android app sends data to this repo's Node.js server and then sets an API for a React app that present results in real-time.
