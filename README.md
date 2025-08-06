# soil-compaction-sensor
Low-cost soil compaction estimation using moisture readings as proxy. Built on ESP32 with auto-network discovery and modular communication logic. Ideal for smart agriculture and irrigation planning.


This project simulates a low-cost sensor system designed to estimate soil compaction based on water retention patterns. The more compacted the soil, the slower the infiltration rate—detected via soil moisture sensors.

## Features

- ESP32-based wireless sensor
- Soil moisture measurement as a compaction proxy
- Automatic WiFi network connection
- Periodic UDP broadcast for detection and pairing
- Built with scalability and modularity in mind

## Technical Overview

- Uses an ESP32 microcontroller
- Measures soil moisture (simulated in Wokwi)
- Broadcasts its presence via UDP
- Can be integrated into a larger irrigation or data collection system

## Use Cases

- Pre-irrigation soil diagnosis
- Identifying areas with poor infiltration
- Optimizing water usage based on compaction patterns

## Next Steps

- Add battery + solar support
- Build companion node for data aggregation
- Simulate behavior under different soil types
