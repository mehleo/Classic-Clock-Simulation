Classic Clock Simulation – Analog clock using OPENGL AP

<h2>About Clock Simulation</h2>
A method for clock modeling in a simulation tool is described. An internal time (I) may be 
defined that governs the simulator tool's clock period. An external time (E) may be defined. 
The internal time may have a smaller resolution than the external time. A calibration period 
(C) may be defined for the clock. The calibration period may be smaller than 0.5E and greater
 than I. The largest inaccuracy of any clock edge may be monitored, and the clock may be 
calibrated if the largest inaccuracy is greater than (C−1)

<h3>Aim: </h3>
Computer Graphics Mini Projects in Opengl.
In this project, we have created a fully functional clock. Which minute hand changes after the 
second-hand travels the full 360-degree path. After each rotation the minute hand changes.

<h3>Behavior: </h3>
The clock toggles its output value on a regular schedule as long as ticks are enabled via
 the Simulate menu. (Ticks are disabled by default.) A "tick" is Logisim's unit of time; 
the speed at which ticks occur can be selected from the Simulate menu's Tick Frequency submenu.

The clock's cycle can be configured using its High Duration and Low Duration attributes.

Note that Logisim's simulation of clocks is quite unrealistic: In real circuits, multiple 
clocks will drift from one another and will never move in lockstep. But in Logisim, all 
clocks experience ticks at the same rate.

<h3>Pins: </h3>
A clock has only one pin, an output with a bit width of 1, whose value will represent the
current value of the clock. The location of this pin is specified in the Facing attribute.
The clock's value will toggle on its schedule whenever ticks are enabled, and it will toggle
whenever it is clicked using the Poke Tool.
