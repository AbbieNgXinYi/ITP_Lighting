# ITP_Lighting

## Project Background
This project is a church project that involves installation of AV systems(Audio, Video, Lighting, Control).
The installation of AV systems is under Electronics & Engineering (E&E), an SI company that deals with Audio Visual Technology.

## What is this for?
This github is created for a more detailed and step by step manual for the lighting setup done in this project.

**Note:**
*Please note that this github is mainly created for a presentation. Please do not use it illegally. Thank you for your co-operation.*

---

## Table of Content :

- **[Design Phase](#design-phase)**
- **[Installation Phase](#installation-phase)**
- **[Testing Phase](#testing-phase)**
- **[Controls](#controls)**

---

## Design Phase
**[(Back To Top)](#table-of-content-)**

The design phase is the "planning stage". Together with the clients and consultants, the company comes out with the desired 
layout, the list of equipment to use, as well as the schematics for the equipment used.

**Below are examples a rack layout and schematics of one room in this project:**


**Theatrette 1 Lighting Rack Layout**
![Alt Text](Design_Img/lightingRackTH1.png)

<br>

**Theatrette 1 Lighting Schematics**

```mermaid
flowchart TD

   A[GrandMA 3] -- LAN --> B[Network Switch (1)]
   B -- LAN --> C[Network Switch (2)]
   C -- LAN --> D(Luminode 4(1))
   D -- LAN --> E(Sensor 3(Dimmer Rack))
   B -- LAN --> F(Luminode 4(2))
   B -- LAN --> G(Luminode 4(3))
   B -- LAN --> H(Luminode 4(4))
   B -- LAN --> I(Luminode 4(5))
   B -- LAN --> J(Luminode 4(6))
   B -- LAN --> K(Luminode 4(7))
   F -- DMX --> L(Lighting Fixtures)
   J -- DMX --> M(Lighting Fixtures)
   K -- DMX --> N(Lighting Fixtures)

```


**Note:** 
In case of company secrecy, not actual drawings or schematics will be posted.
Instead, above is a flow chart to roughly show the connection of the lighting setup done in this project.


## Installation Phase
**[(Back To Top)](#table-of-content-)**

The next stage is installation of equipment. 

**Here's a simple flow chart of what to take note when installing your equipment:**

![Alt Text](Installation_Img/flowchart.png)

<br>

**Note:**
Other than the required equipment, the electrcial side plays apart too. So knowing the appropriate power outlet and supply, where the incoming power is and so on is important too. However if it's on a small scale basis, it is not much of a problem.


## Testing Phase
**[(Back To Top)](#table-of-content-)**

After the equipment has been installed, we can now test our equipment.

### Dimmer Rack

1) Have your tools ready. Make sure that you at least have a working multimeter, torch light and screwdriver(both +ve & -ve).

2) Make sure that all incoming power is off. 

3) Now take out all modules if its still in the dimmer rack. Now you can start testing the rack with a working multimeter.


In the dimmer rack, there are 3 Phases, Live, Earth and Neutral Cables. To test for the dimmer rack, we have to test both open and close cicruit to ensure that there is no power leakage and the appropriate resistance when testing.

#### Open Circuit
When in an open cicruit, no power should be going through and resistance should be in the range of 0 - 10 Ohms.
OL(Open Line) will appear on the multimeter if its correct.

**What to test/check?**

To start off, we start by testing one phase to another. 
E.g. Phase A to Phase B

Phase to Phase
Phase to Live
Phase to Neutral 
Phase to Earth

The same goes for testing netural, live and earth.

Live to Live
Live to Neutral

.
.

Neutral to Neutral
Neutral to Earth

.
.

Earth to Earth
Earth to Live

.
.

## Controls
**[(Back To Top)](#table-of-content-)**