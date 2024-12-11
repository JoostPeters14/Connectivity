# Process Overview
```
@startuml
title Factory Line: Process Overview with SCADA Integration

' Stations in the production line
[Distributing Station] --> [Measuring Station 2.0] : Processed Materials
[Measuring Station 2.0] --> [Sorting Station] : Measured Data
[Sorting Station] --> [Packaging Station (LFT Handling Mechanism)] : Sorted Products
[Packaging Station (LFT Handling Mechanism)] --> [Storage Station] : Packaged Units

' Notes for each station
note right of [Distributing Station]
- Distributes raw materials.
- Components: Conveyors, sensors, actuators.
- Interfaces: SCADA, Modbus, EtherCAT.
end note

note right of [Measuring Station 2.0]
- Measures size, weight, etc.
- Components: Measurement tools, PLCs.
- Interfaces: SCADA, IO-Link, Modbus.
end note

note right of [Sorting Station]
- Sorts products by type/quality.
- Components: Sorting mechanisms, classification sensors.
- Interfaces: SCADA, IO-Link, Modbus.
end note

note right of [Packaging Station (LFT Handling Mechanism)]
- Packages sorted products.
- Inputs: Sorted Products, Packaging Materials.
- Outputs: Packaged Units.
- Interfaces: SCADA, IO-Link.
end note

note right of [Storage Station]
- Stores finished packaged products.
- Components: Shelving, conveyor belts.
- Interfaces: SCADA, Modbus, EtherCAT.
end note

@enduml
```