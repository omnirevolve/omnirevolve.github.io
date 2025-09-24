# OmniRevolve

XY plotter (4 colors) · STM32F446 + ESP32 (microROS) · ROS 2 UI

- GitHub org: https://github.com/omnirevolve
- Umbrella repo: https://github.com/omnirevolve/omnirevolve

```mermaid
flowchart LR
UI -- byte_stream/cmds --> ESP32
ESP32 -- SPI DMA:512B --> STM32
STM32 -- telemetry via UART --> ESP32 --> UI
