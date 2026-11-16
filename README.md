# Smart Dustbin – Wet and Dry Waste Segregation (Dummy Model)

A college project demonstrating the **concept** of separating wet and dry waste into two labelled compartments.

> **Project status:** Physical demonstration / dummy model. This repository documents the model, its intended working concept, and the components shown in the project poster. It does not claim that the prototype is a fully tested, automatically functioning waste-segregation product.

## Project overview

The model has two compartments labelled **WET** and **DRY**. The idea is that waste placed at the top is identified as wet or dry and directed to the corresponding compartment. The project poster describes a proposed sensor-and-controller arrangement for demonstrating this idea.

## Objectives

- Demonstrate the idea of wet and dry waste segregation.
- Encourage waste separation at the point of disposal.
- Present a simple college-level prototype and its proposed electronic arrangement.
- Explain how sensors, a controller, indicators and a servo mechanism could support an automated bin.

## Components listed in the project poster

1. Arduino Uno
2. Ultrasonic Sensor (HC-SR04)
3. IR Sensor / Limit Switch
4. Servo Motor
5. Buzzer
6. LED Indicator
7. 5V Power Supply (Adapter / Battery)
8. Connecting Wires
9. Dustbin with lid / two-compartment model
10. Moisture sensor (confirmed by the project team)

**Note:** The poster lists the first nine items. The project team has also confirmed that a moisture sensor is included. Exact model numbers, wiring, pin assignments and tested program details were not provided, so they are intentionally not guessed here.

## Proposed working concept

1. Waste is placed at the input area on top of the model.
2. A moisture sensor is intended to help identify whether the waste is wet or dry.
3. The controller concept uses the sensor information to select the appropriate compartment.
4. A servo mechanism is proposed to guide or open the route toward the selected compartment.
5. The ultrasonic sensor and IR sensor / limit switch are listed for detection or bin-status functions.
6. LEDs and a buzzer are listed as visual and audio indicators.

The above describes the **intended concept** shown in the project material. Actual automatic detection, sorting accuracy and full-bin alerts have not been verified for this dummy model.

## Repository contents

## Repository Content

```text
Smart-Dustbin/
│
├── README.md
├── project_report.md
├── project_report.pdf
└── smart_dustbin_project_photo.jpg
```

## Project scope and limitations

- This is a demonstration / dummy model, not a certified waste-management device.
- No claim is made about real-world sorting accuracy or continuous operation.
- Sensor calibration, wiring diagram, Arduino pin mapping and verified firmware are not included because those implementation details were not supplied.
- The project should be treated as an educational concept model.

## Applications (potential)

- Homes and living areas
- Offices and educational institutions
- Hospitals and public places
- Smart-city and environmental-awareness demonstrations

These are potential application areas for the concept, not confirmed deployments.

## How to view the documentation

Open `docs/project_report.pdf` in any PDF reader. The project photograph is available in the `assets` folder.

## Team details

- Project title: Smart Dustbin
- Project leader name shown on poster: Abarajitha K.R
- Guide name shown on poster: Dr. Gayathri V
- Department: Computer Science and Engineering
- Institution logo/name shown on poster: PRIET

## License

For academic demonstration and learning. Add a formal license only if your team has agreed on one.
