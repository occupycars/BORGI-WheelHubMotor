# BORGI

Disclaimer:

*All components published here are in a development stage and are published for research purposes only. Everything you do with these files is on your own risk. We take no liability for what you do with these files or for the things you build with it.*

*Make sure to run the motor in a security housing only, to prevent any injury or damage to your property!*

*You should not run the motor higher than 10000 rpm!!! Letting it spin faster is very dangerous and can result in severe injury!*

## What is the BORGI Hubmotor?

The BORGI Hubmotor is an open source, axial-flux, pancake style wheel-hub motor which you can drop in between your cars rims and wheelaxle.

In theory you can convert your car from gasoline or diesel to electric hybrid or 100% electric with it.

![Motor Details](https://s3.eu-central-1.amazonaws.com/newforest-website/OC-Borgi-Exp-v2.gif)

## What are the specs?

The construction is quite simple so that you can build it yourself with common fabrication tools which you can find in any fablab.

It consists of a 3D-Printed polymer stator which houses the electromagnetic coils, two aluminum rotor discs with neodymium magnets and some nuts and bolts.

It incorporates a VAG OE-1T0598611 Wheelhub-bearing which is present in quite some VW, AUDI, SKODA & SEAT cars. It's probably easy to adapt it to other kind of wheelhubs/wheelbearings.

![Motor Mounting](https://s3.eu-central-1.amazonaws.com/newforest-website/OC-Bordi-Mount.gif)

The outer diameter of the motor should be compatible with 18" rims. The design is adaptable to other rim diameters.

It weighs approx. 15kg.

It's not fully tested yet but we have run it with 20KW (300A, 72V with no load) of power and did not notice any significant heat buildup. Our guesstimate is that you can probably run it upto 60KW. When you run it with no load, with 20kw it reaches 10000rpm quick. You should not run it higher than 10000 rpm!!! Letting it spin faster is very dangerous and can result in severe injury in case it breaks apart! Make sure to run the motor in a security housing only to prevent any injury or damage to your property! If you pump more energy through it make sure there is an appropriate counter force to keep the rpm below 10000 rpm!

## What kind of motor controller does it work with

In theory any kind of brushless, 3phase dc-motorcontroller should be able to drive it, yet because of its axial flux topology we are still investigating the best way to drive the motor.
For testing you can also wire it as a sensorless, split-stator version and drive it with 7 simple ESC's.

We will update this readme with more infos on the controller soon.


## Material to buy to build the BORGI:

28x Nd N45 30x10mm Magnets

21 electromagnets, 7mm thick, 210* 4,6m 0.1mm copperwire

3x Hall Sensor Honeywell SS411A bipolar halleffect switch(latching) sensor

## Building materials

Stator:
- Hightemp 3D-Printer Co-Polymer (PLA-Lignin mix) should be rated min 120 heat resistant.
- PUR Resin (heat resistant up to 120 degC)

Rotor: Any kind of cnc millable aluminuium alloy should work like AlMgSi1

## Build instructions

coming soon

## BOM

coming soon

## About the files

We are working with Autodesk Fusion360 for all the CAD and CAM work. It's free for small startups, educators and students and has all the functionality we need. We know, it's not exactly OpenSource but it is very convenient and not overpriced for what it delivers.

The assembly is available as Fusion360 .f3d file as well as .iges

Download fusion360 here: https://www.autodesk.de/products/fusion-360/students-teachers-educators
