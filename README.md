# MISK-23L
## Setup
Clone this repo into your [CoppeliaSim](https://www.coppeliarobotics.com/coppeliaSim) directory.
The easiest way:
1. clone this repo
```bash
git clone git@github.com:TauTheLepton/MISK-23L.git
```
2. Moge `.git` directory into your CoppeliaSim directory
```bash
mv MISK-23L/.git <your CippeliaSim directory path>/
```

## How to use
In the Leader script you can change the following parameters
- `maxRescueDistance` - the greatest distance within which the soldiers will start the rescue operation  (the ones within this range will start rescue mission and others will continue the mission)

In the Soldier script you can change the following parameters
- `maxDist` simulated signal strength (how far the signal can travel)
- `alarmOnResume` control which soldier will send an Alarm signal upon resuming the simulation, set to `true` for the soldier you want to send the signal
