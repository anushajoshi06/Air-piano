# Air-piano
Keyless piano using Atmega16, ir sensors
The push buttons have been replaced by IR sensor module in this project. This module is capable of sensing any obstruction caused in its IR beam path. This obstruction forces the module to change the output voltage level in output. In our case fingers will be obstructing the IR beam which in turn will produce a voltage level change. As a result it acts same way as a button press. This way we can simulate the key press by obstructing the beam path. 
Each notes in a piano will have certain frequency values. By creating those frequency signals using Atmega16 we can produce tones identical to the piano. 
**************************
