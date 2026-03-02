# LIFePO4-Battery-Charger-With-Protection-using-ALTIUM
LiFePO4 single cell battery charger with protection using CN3058E IC, featuring USB Type-C input, CC/CV charging, thermal protection, LED status indication, and safe 3.6V charging for 3.2V LiFePO4 batteries.


#  LiFePO4 Battery Charger With Protection (CN3058)

##  Project Overview

This project is a single cell LiFePO4 battery charger

Based on CN3058E charging IC

Designed for safe charging of 3.2V LiFePO4 batteries

Supports USB Type-C input

Includes charging & full indication LEDs

Compact and minimal component design

---

##  Why LiFePO4 ?

Safer than Li-ion batteries

Longer life cycle (3000 – 5000 cycles)

Stable chemistry

Nominal voltage: 3.2V

Full charge voltage: 3.6V

---

##  Why CN3058 ?

Specially designed for LiFePO4

Fixed 3.6V charging voltage

No external MOSFET required

No blocking diode required

Supports CC/CV charging

---

##  Input Details

USB Type-C 5V Input

Input range: 3.8V – 6V

Input capacitors used for stability

---

##  Charging Features

Constant Current (CC) Mode

Constant Voltage (CV) Mode

Pre-Charge Mode

Auto Charge Termination (C/10)

Auto Recharge

---

##  Charge Current Setting

Charge current set using RISET resistor

Formula:

ICH = 1218 / RISET

Example used:

RISET = 2KΩ

Charging current ≈ 600mA

(Safer & reduces IC heating)

---

##  LED Indicators

CHRG LED → Charging

DONE LED → Fully Charged

---

##  Protection Features

Thermal regulation

Overcharge protection

Auto sleep mode

Safe charging without external protection IC

---

##  Battery Used

LiFePO4 18650

2000mAh

3C rated

---

##  Components Used

CN3058E

RISET resistor

Input capacitors

Output capacitors

USB Type-C connector

LEDs + current limiting resistors

---

##  Applications

Toys

Medical devices

Portable electronics

Solar battery systems

DIY power packs

---

##  Files Included

Schematic

PCB Layout

BOM

Gerber Files

---

##  Key Advantages

Simple design

Low cost

Safe charging

No complex circuitry
