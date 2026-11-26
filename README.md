# EXP-8-SIMULATION-OF-REGULATED-POWER-SUPPLY
Aim
To design and simulate a complete AC to DC power supply using LTspice, consisting of a transformer, bridge rectifier, smoothing capacitor, Zener diode, voltage regulator and load, and to observe the output waveform at each stage. 
Software Required
LTspice
Components Required
•	AC source 
•	Transformer 
•	Diodes – 4 
•	Smoothing capacitor 
•	Zener diode 
•	Series resistor 
•	Load resistor 
________________________________________
Procedure
1.	Double-click on the LTspice icon and open a new schematic window. 
2.	Pick and place the required components from the library and draw the transformer circuit using AC source, L1L_1, L2L_2 and coupling. 
3.	Run the simulation and observe the transformer secondary output. 
4.	Pick and place four diodes and draw the bridge rectifier circuit. 
5.	Run the simulation to obtain the rectified waveform. 
6.	Place the smoothing capacitor across the rectifier output. 
7.	Run the simulation again to observe the filtered DC waveform. 
8.	Add the Zener diode regulator with a series resistor and connect the load resistor. 
9.	Right-click each component and set the required values. 
10.	Save the file with a suitable name. 
11.	Click Run → Advanced → Transient Analysis and set the stop time, for example 60 ms. 
12.	Click Run and place the probe at each stage to observe: 
•	Transformer output 
•	Rectifier output 
•	Filter output 
•	Regulated output 
•	Load voltage 
________________________________________
Observation
circuit diagram:
<img width="1280" height="307" alt="e8" src="https://github.com/user-attachments/assets/3b7cf27a-c3f2-4322-8542-069b5a98c2e5" />
Simulation Results:

<img width="1280" height="281" alt="r8" src="https://github.com/user-attachments/assets/83dd7c1a-13ec-42ef-90c4-8bd5174417c3" />




1. AC Input Waveform
The AC input waveform is observed in LTspice before applying it to the transformer.
2. Transformer Output
The transformer secondary output waveform is observed after running the simulation.
3. Signal Output – Without Filter
The output of the bridge rectifier is observed. The waveform is a pulsating DC waveform.
4. Signal Output – With Filter
The smoothing capacitor is connected across the rectifier output. The capacitor reduces the variations in the rectified waveform and produces a smoother DC output.
5. Stable Regulated DC Output
The Zener diode regulator and load are connected. A stable regulated DC output is obtained at the load.
________________________________________
Result


Thus, the regulated power supply was simulated using LTspice. The output waveform at each stage was observed and analysed, and a stable regulated DC output was obtained at the load. 
