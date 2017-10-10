# Joule Thief

## Introduction

### What is a Joule Thief

A Joule thief is a low-cost self-oscillating voltage booster for driving small loads. It can use all the energy available in a battery, so it can be used even if the battery is almost "empty".

More info: 
*[Wikipedia page](https://en.wikipedia.org/wiki/Joule_thief)
*[Youtube video](https://www.youtube.com/watch?v=0GVLnyTdqkg)

### Our Joule Thief implementation

We utilized a simple circuit that permits to turn a LED on with a AA battery even when it is almost empty. We utilized 3mm DMF stock to build the battery case and the board to insert the components. They were cut using the laser cutter.
<img src="general_view(breadboard).jpg?raw=true" width="400">
<img src="general_view(top).jpg?raw=true" width="400">
<!--- ![Joule thief in a breadboard](general_view(breadboard).jpg?raw=true "Joule thief circuit")--->
<!--- ![Joule thief final version](general_view(top).jpg?raw=true "Joule thief circuit") --->

The ** components ** we used are the following:
 * AA battery
 * LED (any color)
 * Resistor (1K Ohm)
 * PNP transistor (BC337)
 * 2 X 1m of magnet wire (enabeled wired). Each wire should give at least 15 turns.

The circuit diagram is shown in the following picture:

<img src="diagram.png?raw=true" width="400">


### How to do it:
 1. Mount the battery case
     <img src="aa_battery_case.jpg?raw=true" width="400">
 1. Take the two pieces of wire together. Mark somehow the two ends of one of the wires. We used a color tape.
 2. Next we will built the coil. Roll the two pieces of wires forming a circle. We rolled the two wires on a battery to give adequate shape.
 3. Use tape to fix the coil so it does not disentangle itself.
 4. Now you have to swap the ends of the two wires. Each end of the marked wire should go with the oppossite end of the othe cable. TODO: Explain with picture how to bring the two opposite ends together. The goal is that the currents go in different directions for each cable.
 5. Build the circuit as it shown in the [following diagram](./diagram.pdf). The following picture might serve as a guide. 
    <img src="general_view(bottom).jpg?raw=true" width="400">

   
	
## Files:
 * Single_AA_Battery_Holder.svg -> File to laser-cut the battery case 
 * JouleThief_main_board.svg -> File to laser-cut the main board
 * diagram.pdf -> How the components should connect with each other
 * diagram.png -> Schematics
 * Image files: how it should look like.

## Author
Original idea and implementation: Antti Mäntyniemi -> antti.mantyniemi@oulu.fi
Instructions:  Iván Sánchez Milara -> ivan.sanchez@oulu.fi