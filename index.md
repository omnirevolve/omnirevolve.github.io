# OmniRevolve

XY plotter (4 colors) · STM32F446 + ESP32 (microROS) · ROS 2 UI

- GitHub org: https://github.com/omnirevolve
- Umbrella repo: https://github.com/omnirevolve/omnirevolve

```mermaid
flowchart LR
UI -- byte_stream/cmds --> ESP32
ESP32 -- SPI DMA:512B --> STM32
STM32 -- telemetry via UART --> ESP32 --> UI



## Photos

<figure align="center">
  <img src="docs/media/plotter.jpg" alt="OmniRevolve plotter hardware" style="max-width:980px;width:100%;height:auto;border-radius:8px;">
  <figcaption>OmniRevolve plotter — 4-color carousel (mechanically scalable to ~15 colors)</figcaption>
</figure>

<p align="center">
  <figure style="display:inline-block; width:49%; min-width:320px; text-align:center;">
    <img src="docs/media/result.jpg" alt="Sample output #1" style="width:100%; height:auto; border-radius:8px;">
    <figcaption>Sample output #1</figcaption>
  </figure>
  <figure style="display:inline-block; width:49%; min-width:320px; text-align:center;">
    <img src="docs/media/result-2.jpg" alt="Sample output #2" style="width:100%; height:auto; border-radius:8px;">
    <figcaption>Sample output #2</figcaption>
  </figure>
</p>


## Videos

<p align="center">
  <a href="https://www.youtube.com/watch?v=epHM4n3US48">
    <img src="https://img.youtube.com/vi/epHM4n3US48/hqdefault.jpg" alt="Timelapse demo #1 (printing)" width="32%">
  </a>
  <a href="https://www.youtube.com/watch?v=NMgnAYHxDm4">
    <img src="https://img.youtube.com/vi/NMgnAYHxDm4/hqdefault.jpg" alt="Pen carousel change" width="32%">
  </a>
  <a href="https://www.youtube.com/watch?v=BMJWWeqkJn0">
    <img src="https://img.youtube.com/vi/BMJWWeqkJn0/hqdefault.jpg" alt="Full process: PC + hardware + plotting" width="32%">
  </a>
</p>

