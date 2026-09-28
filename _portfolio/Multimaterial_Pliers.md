---
title: "Multimaterial Pliers"
excerpt: "These mutlimaterial pliers were 3D printed with both PLA and TPU to create handles and jaws which can flexibly pinch back and forth."
header:
  image: assets/img/Plier_Render.jpg
  teaser: assets/img/Plier_Render.jpg.archive__item-teaser img 
  {object-position: center 20%}

toc: true
toc_label: "Table of Contents"
toc_sticky: true
toc_icon: bars

---
The intention of this project is to create a functional plier design on Fusion, and incorporate multimaterial 3D-printing methods to construct a physical product. These pliers are capable of presisely picking up a through hole resistor, whose diameter measures only about 2.5mm.

# CAD Model

<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH90d2dQT28d5b602811ea89f3aa026b5977?mode=embed" width="640" height="480" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>


# Design Description

To operate the pump, the syringe is first filled and positioned into the actuator by the user. After proper set-up, the Arduino code is set to the desired flow_rate and syringe_diameter values. The Arduino is disconnected, the power supply is plugged in, and a yellow LED confirms the system is idle and ready. Pressing the latching start/stop button turns the LED green and activates the motor, driving the carriage forward at the pre-set speed to empty the syringe. If the plunger reaches full displacement, a limit switch signals the system to stop the motor and turn the LED red, indicating the syringe is empty, and the device can be safely powered down.

# Print-in-Place Parts

[View the Arduino controller code on GitHub](/Arduino-Code.MD)

# Specifications

| # | Part Name | Quantity |
|---|-----------|----------|
| 1 | Power Cord Hole Plug | 1 |
| 2 | 91290A115 Alloy Steel Socket Head Screw | 8 |
| 3 | Plastic_Body | 1 |
| 4 | Button | 1 |
| 5 | Contact1 | 1 |
| 6 | Metal_Body | 1 |
| 7 | LED 10mm White | 1 |
| 8 | Contact2 | 1 |
| 9 | 91290A222 Alloy Steel Socket Head Screw | 14 |
| 10 | Nut-tr8x8-4 | 1 |
| 11 | Linear-Rod-8mmx200mm | 1 |
| 12 | Rubber Tampon 20ml | 1 |
| 13 | Syringe Cylinder 20ml | 1 |
| 14 | LM8UU Linear Bearing | 1 |
| 15 | Syringe Piston 20ml | 1 |
| 16 | V-Slot 20x40x350 | 1 |
| 17 | 91290A113 Alloy Steel Socket Head Screw | 2 |
| 18 | NEMA-17 Motor | 1 |
| 19 | Lead-Screw-TR8x8x250mm | 1 |
| 20 | M5-Tee-Nut | 13 |
| 21 | Default (1) | 2 |
| 22 | 91390A403 Alloy Steel Cup-Point Set Screw | 2 |
| 23 | 99461A941 Phillips Rounded Head Thread-Forming Screws | 6 |
| 24 | Housing Removable Panel | 1 |
| 25 | LED Hole Plug | 1 |
| 26 | Lead-Screw-SubAssembly | 1 |
| 27 | SWITCH_LIMITE | 1 |
| 28 | Housing | 1 |
| 29 | Housing Cover | 1 |

# 3D Printed Parts

| # | Part Name | Quantity |
|---|-----------|----------|
| 1 | Motor-Mounting-Plate | 1 |
| 2 | Flexible Coupler | 1 |
| 3 | End-Support-Regular | 1 |
| 4 | End-Support - Flange Slots | 1 |
| 5 | Carriage | 1 |
| 6 | End-Support - Holds Syringe Tip | 1 |


