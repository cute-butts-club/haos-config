# Home automation guide for my love <3

## Manual control
* Button on the door
    * Single click: turn off everything in the house because you are leaving and sets a low temperature
    * Double click: turn on cozy lights in the living room and your favourite playlist will start playing
* Button outside on the door (doorbell)
    * Single click: flash all lights in the house and display a notification on the TV and iPhones
* Button living room/bedroom
    * Single: click, increase the brightness between [10%, 50%, 100%]
    * Double click: change between bright lights and cozy lights
    * Shake: turn off the whole room (in the bedroom it will activate sleep mode)
* Dimmer switches on the wall living room/bedroom
    * Top button: increase the brightness between [10%, 50%, 100%]
    * Middle two buttons: turn on and off (or hold to dim)
    * Bottom button: change between bright lights and cozy lights
    * (Extra) If the lights are already on, clicking on the "turn on" button again, will turn on white lights at 100%
* Cube in living room
    * Throw up: start your favourite playlist on the speakers
    * Shake: shuffle song
    * Put label up and move it a bit on the table to put it in either [Volume, Brightness, Hue] (the TV will also display in which mode it is). Rotating the cube will change the volume, brightness, or hue.
* In Home Assistant app
    * *Going to sleep button*: turns everything off in the house and sets “sleep mode” (all the lights will automatically turn red when triggered)

## Automatic
* Lights in hall, toilet, bathroom, and kitchen automatically turn on
    * Its colours change depending on the time of the day
    * If in sleep mode (after clicking the button in the app) these lights will be 10% brightness and red
* An hour after we leave the house, everything turns off and temperature is set to low
* The TV and speakers
    * If Spotify is not playing on the speakers, the speakers will automatically switch to the TV
    * Speakers will turn on when turning on the TV
* Sleep mode automatically turns off if the alarm goes or if there is no alarm, it's at 06:00
* When sleep mode turns on, the temperature will be set to low
* We will get a notification on our phones when either the dishwasher or washing machine is done

Questions or suggestions? Ask Bas ❤️
