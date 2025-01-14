# LumiCube

This repository will contain code and documentation for the LumiCube:
* https://www.kickstarter.com/projects/1202256831/lumicube-an-led-cube-kit-for-the-raspberry-pi
* https://www.indiegogo.com/projects/lumicube-an-led-cube-kit-for-the-raspberry-pi

At the moment there are just a few example projects, and a basic description of the API, to give a taste of how to program the cube. We will be adding more resources as we get closer to shipping.

## Example projects

The “examples” folder contains a number of example projects, some of which we used in our Kickstarter and Indiegogo video. The API might change a bit over the next few months, but hopefully not too much. We don’t have a simulator to run these examples without access to a physical cube at the moment (but if anyone is looking for a fun project)!

### Level 1 (easiest)

#### button
Use the button to switch the cube’s colour between red and blue

#### chiptune
Play a randomly generated tune

#### pi_status_screen
Display some Raspberry Pi stats on the screen (CPU temperature, disk usage...)

#### rainbow
Continually change the cube's colour

#### scrolling_clock
Every 10 seconds scroll the time across the LEDs

#### voice_recognition
Basic voice recognition and text-to-speech

### Level 2 (after you’ve learnt the basics)

#### autumn_scene
Autumn animation (leaves falling from a pixel-art tree)

#### binary_clock
A simple binary clock (see https://en.wikipedia.org/wiki/Binary_clock)

#### conways_game_of_life
Run Conway’s Game of Life on the LEDs (see https://en.wikipedia.org/wiki/Conway's_Game_of_Life)

#### equaliser
Colourful equaliser using the microphone

#### land_grab
Several computer players randomly walk the LED grid colouring squares until they get stuck

#### lava_lamp
Use Simplex noise to generate a lava lamp like effect (see https://en.wikipedia.org/wiki/Simplex_noise)

#### rain
Rain animation

#### ripples
Random circular ripple animation

#### tapping_ripples
Ripple animation which responds to tapping or moving the cube

#### water_level
Virtual water level effect responds to the cubes orientation

#### windmill
Blow at the back of the cube to make the windmill animation turn

## Documentation

### API

Basic outline of the LumiCube API.
