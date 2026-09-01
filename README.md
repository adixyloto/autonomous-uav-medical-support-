# Autonomous UAV for Medical Support

A fixed-wing UAV developed for autonomous transportation and delivery
of medical supplies to remote or difficult-to-access locations.

The project involved UAV fabrication and assembly, flight-control
integration, GPS-based waypoint navigation, telemetry, payload
delivery, and flight testing.

## Project Objective

To develop a lightweight fixed-wing UAV capable of carrying medical
supplies and supporting autonomous delivery missions in areas where
conventional transportation may be difficult or slow.

##  System Overview

The UAV combines:

- Fixed-wing airframe
- Pixhawk flight controller
- GPS navigation
- Telemetry communication
- Brushless motor + ESC
- RC manual control
- Autonomous waypoint navigation
- Medical payload compartment
- Servo-actuated payload release
- Return-to-base functionality

##  Hardware

| Component | Purpose |
|---|---|
| Pixhawk 2.4.8 | Flight control and autonomous navigation |
| GPS Module | Position and waypoint navigation |
| Power Module | Flight-controller power and battery monitoring |
| Telemetry Radio | UAV ↔ Ground Station communication |
| Brushless Motor | Propulsion |
| ESC | Motor control |
| RC Transceiver | Manual flight control |
| Safety Switch | Arming/disarming |
| Payload Mechanism | Medical supply delivery |

## Software

- ArduPilot / Pixhawk flight-control ecosystem
- Mission Planner
- GPS waypoint mission planning
- Telemetry monitoring

##  Autonomous Mission

1. Plan mission and GPS waypoints in Mission Planner
2. Upload mission to the flight controller
3. Launch the fixed-wing UAV
4. Navigate through predefined waypoints
5. Monitor flight data through telemetry
6. Deliver the medical payload
7. Return to base

## Payload Delivery

The UAV was designed with a dedicated payload compartment
for transporting medical supplies.

A servo-actuated release mechanism was used for payload deployment,
with a parachute-based delivery concept.

## Testing & Validation

Testing focused on:

- Flight stability
- Waypoint navigation
- GPS tracking
- Telemetry communication
- Payload delivery
- Return-to-base operation

## Airframe

- Wingspan: 2 m
- Fuselage length: 1.8 m
- V-tail configuration
- NACA 4415 airfoil
- Carbon-fibre structural reinforcement

## Team

**Adithi R**  
**K V Keerthan**  
**Manasa K S**  
**Hemanth Gowda S J**

Major Project — Robotics & Automation Engineering  
JSS Academy of Technical Education, Bengaluru

## What I Learned

- UAV system integration
- Flight-controller architecture
- GPS-based autonomous navigation
- Telemetry and ground-station communication
- ESC and motor integration
- UAV fabrication and assembly
- Payload delivery mechanisms
- Flight testing and validation

## Future Improvements

- Improved obstacle avoidance
- Extended communication range
- Improved payload capacity
- Better autonomous mission planning
- More extensive flight-data analysis
