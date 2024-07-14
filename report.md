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

