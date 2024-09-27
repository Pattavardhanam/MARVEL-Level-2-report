# Level 2 report
## CFD
My exploration of aerodynamics took a thrilling flight with Autodesk CFD. This powerful software allowed me to delve into the fascinating world of computational fluid dynamics (CFD), offering a visually stunning experience.  Autodesk CFD's strength lies in its meticulous detail, enabling the simulation of various fluids (compressible or incompressible) and even incorporating heat transfer.  In this project, I harnessed the DAT to Spline plugin to streamline the process.  After acquiring the coordinates for a NACA 2412 airfoil from an online database, I meticulously crafted a wing model in Fusion360, with the ability to precisely adjust its scale, camber, and offset.  The completed wing, assigned aluminum properties, was then seamlessly imported into the CFD environment.

To simulate real-world conditions, I meticulously constructed a virtual win m/s tunnel around the wing model. The surrounding fluid was designated as air, and a realistic wind velocity of 2 was set.  The simulation meticulously ran through 25 iterations, generating a wealth of data for various parameters.  This rich dataset allowed me to calculate the crucial aerodynamic forces acting on the wing: drag coefficient and lift. This project provided a deeper understanding of how air interacts with a wing, offering valuable insights into the science of flight.

![CFD 1](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-05-11%20183927.png?raw=true)
![CFD 2](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-05-11%20212616.png?raw=true)

## Sourcing and Materials Selection
Frame:
Material: High-tensile steel or aluminum alloy (lightweight and durable for rider weight)
Style: Step-through or traditional (depending on rider preference)
Size: Select frame size based on rider height for optimal comfort and control.

![Body](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(1).jpg?raw=true)

Fork:
Material: Rigid steel or suspension fork (suspension offers better comfort on rough terrain)
Compatibility: Ensure fork fits the chosen frame's head tube.

![Fork](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(5).jpg?raw=true)

Wheels:
Size: 700c (28-inch) wheels offer a good balance of speed and comfort.
Rims: Double-walled aluminum for strength.
Spokes: Stainless steel spokes for durability.
Tires: Puncture-resistant tires suitable for the intended terrain (e.g., road or off-road).

![Wheels](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(6).jpg?raw=true)

Brakes:
Hydraulic disc brakes: Provide strong, all-weather stopping power for rider and bike weight.

![Brakes](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(10).jpg?raw=true)

Drivetrain:
Shifter: 7-speed or higher cassette for gear range on hills.
Derailleur: Durable derailleur compatible with chosen shifter and cassette.
Chain: Rust-resistant chain.

![Drivetrain](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(12).jpg?raw=true)

Electric Motor:
Power: 250W - 500W (depending on local regulations and desired performance)
Mid-drive motor: Offers better weight distribution and climbing ability compared to a hub motor.

![Motor](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(15).jpg?raw=true)

Battery:
Capacity: 36V - 48V, 10Ah - 15Ah (higher capacity for longer range)
Lithium-ion battery: Lightweight and efficient battery technology.
Consider factors like weight, charging time, and desired range when selecting battery capacity.

Battery Management System (BMS):
Protects the battery from overcharging, over-discharging, and overheating.

![BMS](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(17).jpg?raw=true)

Motor Controller:
Regulates power delivery from the battery to the motor.
Choose a controller compatible with the chosen motor and battery voltage.

Display:
Shows battery level, speed, assist mode, and other riding data.

Crankset:
Single chainring with a guard for protection.

Handlebars and Grips:
Select handlebars that provide a comfortable riding position.
Ergonomic grips for comfort and control.

![Grips](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(18).jpg?raw=true)

Saddle:
A comfortable saddle is essential for longer rides.

![Saddle](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(19).jpg?raw=true)

Pedals:
Platform pedals with good grip.

![Pedals](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/images%20(21).jpg?raw=true)

## Band Pass Filter
In this task I attempt to build a 2nd order band pass filter using OpAmp OP747(LTSpice didn't have OP741).

I have designed the band pass filer based on the Butterworth filter. This filter is designed to band pass frequencies between 3kHz and 11kHz

![Band Pass](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-07-14%20152835.png?raw=true)
![Band Pass](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/WhatsApp%20Image%202024-07-14%20at%2011.00.31_d3b20e15.jpg?raw=true)

## Logic design:
I had learnt binary addition and binary number representation using 1's complement and 2's complement in 2nd PU. I learnt how full adders and 2x1 MUXs work. Using XOR gate, NOT gate(To give XNOR values), AND gate and OR Gate I designed a full adder circuit.
This is the full adder truth table:

![Full Adder TT](https://github.com/Pattavardhanam/MARVEL-Level-1-Report/blob/main/Pics/Full%20adder%20Truth%20table.png?raw=true)

This is the implementation of the same:

![FAI](https://github.com/Pattavardhanam/MARVEL-Level-1-Report/blob/main/Pics/Full%20Adder%20Implementation.png?raw=true)
![Full Adder](https://github.com/Pattavardhanam/MARVEL-Level-1-Report/blob/main/Pics/Full%20adder%20GIF.gif?raw=true)
This is the simulation of the adder circuit. [The link to the adder simuation](https://circuitverse.org/users/235959/projects/full-adder-using-mux-f6b940c1-7610-4385-b890-ccf287be4230)

I then made a 4-bit binary additon circuit using 4 full adders using 2x1 MUX(Read the numbers from right to left):
[The link to the 4-bit adder simuation](https://circuitverse.org/users/235959/projects/4-bit-binary-adder-using-mux)
The top row of numbers is the first number in the sum. The second row is the second number. This example illustrates the addition of 3 and 2. (Read from the right and written left to right) 0011+0010=0101. 0101 is 5
![4-bit Adder](https://github.com/Pattavardhanam/MARVEL-Level-1-Report/blob/main/Pics/4-bit%20adder.png?raw=true) 

## Voltage Multiplier
In this task I built a voltage multiplier circuit using a timer circuit using 555 IC and an inverter timer circuit using an N-Channel MOSFET and the multiplier circuit consisting of diodes and capacitor pumps. The input voltage of 9V gets tripled to 27V(Not considering diode drops).

This GIF shows the Oscilloscope graph in TinkerCad first in Timer/Inverted Timer, then doubled output, tripled output and then finally near stable tripled output. The oscilloscope on the left is always showing output across the 555 timer output. The oscilloscope on the right varies its output across the different points of the diode capacitor pump circuit to show the multiplied output. [The link to the TinkerCad simuation](https://www.tinkercad.com/things/dQi33wQKAI8-voltage-multiplier-?sharecode=YnaduRegVWhudP53628GcphST_o8Lzpk4tIcEBe1AvU) 

<iframe width="560" height="315" src="https://www.youtube.com/embed/QgBlGBeQMCM?si=C9ae9K8EbFPN05e7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


## MATLAB ONRAMP
This is a task from Level 1, but is a prerequistie for the Simulink and Stateflow Onaramps. This gave me a breif overview of how MATLAB works
The MATLAB Onramp course provides an introduction to the key features of MATLAB, offering a hands-on learning experience. It's structured into several modules that guide users through common tasks, such as performing calculations, writing scripts, and creating visualizations. Key topics include using MATLAB commands, manipulating arrays, creating plots, and importing data.

In the **Stellar Motion project** you analyze the motion of a star relative to Earth by examining the shift in its spectrum. The project focuses on determining the speed at which the star HD94028 is moving away from Earth using the hydrogen alpha line (`656.3 nm`). By comparing the observed wavelength in the star’s spectrum with the known wavelength, you can detect whether the spectrum has been redshifted (indicating motion away from Earth) or blueshifted (indicating motion toward Earth).

The project involves using MATLAB to process and visualize the star's spectrum data from a file (`spectrum_data.mat`) containing spectral information for various stars. The data is plotted and analyzed using the script `stellar_motion.m`, where you can adjust parameters to examine different stars in the dataset. This hands-on approach helps in understanding fundamental astronomical techniques like the Doppler effect and how they are used to study stellar motion.

![Matlab_Project_1](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-09-22%20211123.png?raw=true)

The **Stellar Spectra Comparison project** analyzes a star's light spectrum to determine its velocity relative to Earth by measuring the redshift or blueshift of specific absorption lines, such as the hydrogen alpha line. In this MATLAB-based project, the star HD94028, located in the Leo constellation, is examined by comparing its observed hydrogen alpha line with its known wavelength of 656.3 nanometers. This comparison allows for the calculation of the star's velocity using Doppler shift principles, where redshifts indicate a star moving away from Earth and blueshifts suggest it is approaching. The project demonstrates how astronomers utilize these techniques not only to study stellar motion but also to detect planets through subtle oscillations in a star’s motion.

![Matlab_Project_2](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-09-22%20211621.png?raw=true)
![Matlab_Certi_](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/certificate_page-0001.jpg?raw=true)


## Simulink Onramp
The Simulink Onramp course offers an engaging, hands-on introduction to Simulink's key features and functionality, guiding users through a series of modules that cover the basics of modeling dynamic systems using block diagrams, running simulations, and integrating with MATLAB. Topics include inspecting signals, building mathematical algorithms, and modeling both discrete and continuous systems. The course features two major projects: the Automotive Performance Modes project, which involves implementing math and logic operators to model vehicle dynamics, and the Thermostat Model project, simulating a basic heating system. Additionally, the Peregrine Falcon Dive project deepens understanding of continuous systems by simulating the falcon's high-speed dive, reinforcing concepts of dynamic systems and continuous-time modeling.

## Thermostat Model and Peregrine Falcon Dive Projects

### 1. Thermostat Model
In this project, you simulate how a thermostat controls the temperature of a system by turning heating or cooling elements on or off.

#### Energy Balance Equation
The temperature of a system changes based on the heat entering and leaving it. This can be modeled using the energy balance equation:

$$
Q_{in} - Q_{out} = C \frac{dT}{dt}
$$

Where:
- \( Q_{in} \) is the heat supplied to the system (e.g., from a heater).
- \( Q_{out} \) is the heat lost to the environment (depends on ambient temperature and insulation).
- \( C \) is the thermal capacitance (a measure of the system's ability to store heat).
- \( T \) is the temperature.
- \( \frac{dT}{dt} \) is the rate of change of temperature over time.

This equation governs how the temperature evolves over time. The thermostat uses a control logic where heating is activated if the temperature drops below a certain setpoint and deactivated once the setpoint is reached.

#### First-Order Differential Equation for Temperature Control
The system temperature \( T(t) \) is often modeled as a first-order differential equation:

$$
\tau \frac{dT}{dt} + T(t) = T_{setpoint}
$$

Where:
- \( \tau \) is the time constant of the system (related to how quickly the temperature changes).
- \( T_{setpoint} \) is the desired temperature to be maintained.

### 2. Peregrine Falcon Dive Model
In this project, you simulate the high-speed dive of a peregrine falcon by modeling its velocity and acceleration during the dive.

#### Kinematic Equations
The falcon's motion can be described using basic physics (kinematics) equations. If the falcon dives under constant acceleration (gravity), its velocity \( v(t) \) and position \( y(t) \) can be calculated as:

$$
v(t) = v_0 + at
$$

$$
y(t) = y_0 + v_0 t + \frac{1}{2} a t^2
$$

Where:
- \( v(t) \) is the velocity at time \( t \).
- \( v_0 \) is the initial velocity (before the dive).
- \( a \) is the acceleration due to gravity (approximately \( 9.81 \, \text{m/s}^2 \)).
- \( t \) is the time elapsed.
- \( y(t) \) is the position of the falcon as a function of time.
- \( y_0 \) is the initial height.

#### Drag Force
In real-world scenarios, drag (air resistance) affects the falcon's motion. The drag force \( F_d \) can be expressed as:

$$
F_d = \frac{1}{2} C_d \rho A v^2 - mg
$$

Where:
- \( C_d \) is the drag coefficient (depends on the shape of the falcon).
- \( \rho \) is the air density.
- \( A \) is the cross-sectional area of the falcon.
- \( v \) is the falcon's velocity.
- \( mg \) is the gravitational force

The presence of drag modifies the acceleration, leading to a terminal velocity when the forces of drag and gravity balance out.

These models form the basis of simulating the dynamic behavior in both projects.

![Ckt](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-09-16%20213731.png?raw=true)
![Out](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-09-16%20213752.png?raw=true)
![Certi](https://github.com/Pattavardhanam/MARVEL-Level-2-report/blob/main/Pics/Screenshot%202024-09-25%20194422.png?raw=true)

## Stateflow Onramp