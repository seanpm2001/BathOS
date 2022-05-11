
***

# BathHouseOS

## BathOS

### About

BathOS is a subsystem of BathHouseOS, designed for fixing some of the problems with managing a bathtub, and improving the experience. This subsystem is what inspired this project. 2 times throughout my lifetime, I have seen houses get flooded, since either a cat turns the faucet on while your sleeping, or you just simply forget you have water running. The drain on most bathtubs isn't large enough to keep up with the flow of water, and sometimes, it is hard to just get the water a certain depth. I also can't determine the temperature of the bath.

All these issues can be fixed with BathOS. 

### Features

#### Flood protection

The typical drain in a bathtub normally can't keep up with the speed that water pours in. Sometimes, people forget, and then you come back to your floor being drowned in 1 inch of water. It is the reason why I made this operating system, I never thought I would gain approval for it, or make the system. Drain protection involves various sensors, which will automatically shut the water off when it reaches a threshold.

To prevent the water from getting turned off too early, 10 threshold levels have been implemented, and to trigger any of them, water must be touching ALL sensors at once, as sometimes splashing will do otherwise.

##### Thresholds

###### Threshold 1

The first flood protection threshold has sensors 10 centimeters (3.93 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 2

The second flood protection threshold has sensors 20 centimeters (7.8 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 3

The third flood protection threshold has sensors 30 centimeters (11.8 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 4

The fourth flood protection threshold has sensors 40 centimeters (15.74 inches, or 1 foot 3.74 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 5

The fifth flood protection threshold has sensors 50 centimeters (19.68 inches, or 1 foot 7.68 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 6

The sixth flood protection threshold has sensors 60 centimeters (23.62 inches, or 1 foot 11.62 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 7

The seventh flood protection threshold has sensors 70 centimeters (27.55 inches, or 2 foot 4.55 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 8

The eighth flood protection threshold has sensors 80 centimeters (31.94 inches, or 2 foot 7.94 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 9

The ninth flood protection threshold has sensors 90 centimeters (35.43 inches, or 2 foot 11.43 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically.

###### Threshold 10

The tenth flood protection threshold has sensors 100 centimeters (39.37 inches, or 3 foot 7.37 inches deep, or 1 meter) deep, and once the water touches all sensors at once, the water will be shut off automatically. |

###### Threshold Notes

Not all bathtubs are 1 meter deep. Most bathtubs may only be able to fill up to threshold 3 or 4, while some can be filled deeper. I am also considering adding additional thresholds, so that the system can also be used for swimming pools.

#### Temperature gauge

With the temperature gauge, you can separately see the temperature of cold water and hot water, along with the combined temperature (The default setting is Celsius, but it can be switched to Fahrenheit, Rankine, or Kelvin) and a separate meter for the average bath temperature by threshold

#### Hot water gauge

With the hot water gauge, you can see how much hot water is left in the hot water tank, limit how much hot water you use, and or schedule to complete the filling another time

#### Automatic draining

With automatic draining, you can automatically drain the water after a certain amount of time (max: 12 hours, or never)

## Home repositories

[Guesthouse repository](https://github.com/seanpm2001/BathOS/)

This is a guesthouse repository, and not a home repository, as development mainly stays on the main BathHouseOS side. This is just the guesthouse that the project retreats to at times. If you are already in this repository, the link is likely recursive, and will reload the page.

[Home repository](https://github.com/seanpm2001/BathHouseOS/tree/BathHouseOS_Main-dev/BathOS/)

This is the home repository. If you are already in this repository, the link is likely recursive, and will reload the page.

***

**File version:** `1 (2022, Tuesday, May 10th at 7:52 pm PST)`

***
