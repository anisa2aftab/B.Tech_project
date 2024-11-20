
# AUTOMATIC LOW POWER EMERGENCY LIGHT

Today, in industries and as well as in household applications an emergency light is employed where there is frequent non uniform voltage distribution occurs. Many types of emergency lights from rechargeable torches to systems like generators are available in market. All of them require a switch to operate them when frequent power failure occurs. The present one deals with a model which senses the mains as well as daylight to switch on the emergency light. This emergency light holds requirements of domestic purposes also. There is no need to search the switch in the dark as it switches on /off automatically.
## Features

- A model which senses the mains as well as daylight to switch on the emergency light.

- Low power consuming system.



## Components

- STEP DOWN TRANSFORMER
- BRIDGE RECTIFIER
- FILTER CAPACITOR
- HIGH INTENSITY WHITE LED
- ZENER DIODE
- IC LM-317
- TRANSISTOR BD-140,BC-548
- DIODE 
- RESISTOR   

## Operation of the circuit

The circuit comprises two sections:

i) Charger power supply

ii) LED driver
  
- The charger power supply section is built around 3-terminal adjustable regulator IC LM317 (IC1), while the LED driver section is built around transistor BD140 (T2).
            
- In the charger power supply section, input AC mains is stepped down by transformer X1 to deliver 9V, 500 mA to the bridge rectifier, which comprises diode D1through D4.
  
- Filter capacitor C1 eliminates ripples.

- Unregulated DC voltage is fed to input pin 3 of IC1 and provides charging current through diode D5 and limiting resistor R16.

- By adjusting preset VR1, the output voltage can be adjusted to deliver the required charging current

- When the battery gets charged to 6.8V, zener diode ZD1 conducts and charging current from regulator IC1 finds a path through transistor T1 to ground and it stops charging of the battery.

- The LED driver section uses a total of twelve 10mm white LEDs. All the LEDs are connected in parallel with a 100-ohm resistor in series with each.     

- The common-anode junction of all the twelve LEDs is connected to
the collector of pnp transistor T2 and the emitter of transistor T2 is directly connected to the positive terminal of 6V battery.

- The unregulated DC voltage, produced at the cathode junction of diodes D1 and D3, is fed to the base of transistor T2 through a 1-kilo-ohm resistor.

- When mains power is available, the base of transistor T2 remains high and T2 does not conduct. Thus LEDs are off.

- On the other hand, when mains fails, the base of transistor T2 becomes low and it conducts. 

- This makes all the LEDs (LED1 through LED12) glow.

- The mains power supply, when a v a i l a b l e ,charges the battery and keeps the LEDs off as transistor T2 remains cut-off.


- During mains failure the charging section stops working and the battery supply makes the LEDs glow.

- Assemble the circuit on a general purpose PCB and enclose in a cabinet with enough space for battery and switches.


- Mount the LEDs on the cabinet such that they light up the room.

- A hole in the cabinet should be drilled to connect 230V AC input for the primary of the transformer.

![B Tech_project_ckt_diagram](https://github.com/user-attachments/assets/e8b5a590-599c-4807-a723-987ae2bb9b54)

## Advantages 

Here is a white-LED-based emergency light that offers the following advantages:

1.   It is highly bright due to the use of white LEDs.

2.  The light turns on automatically when mains supply fails, and turns off
     when mains power resumes.

3.  It has its own battery charger. When the battery is fully charged charging stops automatically