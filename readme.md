## Have you ever forgotten to press the "Record" button, and only realized after finishing a perfect take? 

The retro recorder is a digital "tape recorder"
that also happens to be able to time travel. 

As a result, it is possible to go back and hit record 
if you play something really cool but forgot to turn the 
recorder on. Up to 20 minutes. 

## Product 

The tape recorder is a small box with a large red button on top. When you press the button, TapeDeck begins recording 20 minutes in the past, and continues recording in the present, until you press the button again. Recordings are stored on a removable SD card. 

## Implementation Details 

### Hardware 

#### Computer 

Raspberry Pi 3 with stock Raspbian will do nicely 

#### Case 

I am thinking a guitar pedal case design may be easy. It will be familiar to musicians. Sturdy. [Can be had for less than $10 from StewMac](http://www.stewmac.com/Pickups_and_Electronics/Pedal_Kits_and_Parts/Pedal_Enclosure.html?utm_source=google&utm_medium=shopping&utm_campaign=2017-06-gp&gclid=Cj0KEQjw4cLKBRCZmNTvyovvj-4BEiQAl_sgQld-d9NHa9TFqlxt1PhDN1h00vBHIUc598PtPNkBI6EaAnAl8P8HAQ) big enough to fit Raspberry Pi 

#### Big Red Button 

For the button: very large and very red. Good feel and completely silent of course, don't want clicky buttons on the recording. For the switch, something simple like this [pushbutton switch from DigiKey](https://www.digikey.com/product-detail/en/e-switch/JN2UOANAGX/EG4368-ND/1144793). 

#### Power 

Rechargable battery inside. For charging, USB. 

#### IO 

Uses micro SD cards for storage of audio files. Possibly: exposes file system over USB. Certainly: charges over USB. 

### Software 

Build recording program in Python, Linux daemon to run program in production 
