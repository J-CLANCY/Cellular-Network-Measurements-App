# Cellular Network Measurements App

This repository contains the Android Studio project for cellular network measurement app that I attempted to develop for my PhD programme, as a way to collect data during the COVID-19 pandemic lockdowns. During the pandemic, I was unable to purchase/procure cellular network testing equipment, so I spent some time seeing how much information I could reasonable capture from my Android phone's cellular modem. The goals for the app were to collect cellular network measurement data at certain GPS locations and to provide a map view of existing collected data, similar to [this website](https://www.nperf.com/en/map/ww/-/-/signal/). This project was intended to be paired with my [Vehicular Networking Simulation Framework](https://github.com/J-CLANCY/Vehicular-Networking-Simulation-Platform) in order to provide more realistic channel models to the regions of interest in automotive scenarios i.e. specific junctions, commuter routes etc. It turns out that while the Android API is extensive, it was taking too long to develop the map aspect of it, so I scrapped the project in favour of using channel models created by others.

The goals for the app were:
- To collect cellular network measurement data at certain GPS locations
- To provide a map view of existing collected data, similar to [this website](https://www.nperf.com/en/map/ww/-/-/signal/).

<TO-DO - Insert screenshots of app >

## Project Structure

```
├── ""app"" => Contains the source code for the app.
├── ""gradle"" => Contains the gradle wrapper for the app.
├── ""build.gradle"" => Top level build configuration file for the gradle.
├── ""gradle.properties"" => Project-wide gradle configuration.
├── ""gradlew"" => Gradle start up script for UniX.
├── ""gradew.bat"" => Gradle startup script for Windows.
├── ""local.properties" => Automatically generated file.
├── ""settings.gradle" => User-defined global variables for gradle.
```
