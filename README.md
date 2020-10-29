# Mini Heater Stage

## Summary

The miniature heater stage outlined here was created for the fabrication of two-dimensional semiconductor heterostructures. It features a 19 W heater and a thermistor for accurately tuning the temperature of the aluminum stage (up to 200 C) which sits on top of a ceramic base. The heater and thermistor can be operated by a voltage source and an Arduino or whatever similar instruments are available to the end user. 

## Components

| Component | Vendor | Part Number |
|---|---|---|
| Metal ceramic heater | Thorlabs | HT19R |
| Platinum thermistor | Thorlabs | TH100PT |
| Aluminum stage | Ted Pella | 16327 |
| Ceramic base | Thorlabs | RS05PC |
| Header pins | Digi-Key | WM4177-ND |
| Cable wiring header | Digi-Key | WM2902-ND |
| Heater stage belt PCB | OSH Park | 4WIJkWK7 |
| | | |
| Double-sided copper tape | Ted Pella | |
| Clamping fork | Thorlabs | CF125 or similar |

Other: Epoxy, single-sided Kapton tape, M4 screw, wiring (for 0.1 inch pitch), soldering equipment

Optional: Double-sided Kapton tape

## Assembly

Using epoxy, mount heater stage belt PCB on the ceramic base and allow to cure. Sandwich the ceramic heater between the aluminum stage and the ceramic base with the metal leads facing towards  the pair of through-holes in the stage belt PCB to the right of the large tab. Ideally use double-sided Kapton tape at each interface to prevent any possible crushing of the ceramic base in the next step. Using the M4 screw, tighten the stack by feeding it through the holes in the base and heater, into the threaded hole of the aluminum stage. Next, mount the thermistor on the side of the aluminum stage with single-sided Kapton tape with its leads facing the other pair of through-holes in the PCB. Trim the leads from the heater and thermistor and solder them to the PCB. Finally, attach and solder the header pins.

A cable can then be made using the wiring header part with whatever wiring is available.
