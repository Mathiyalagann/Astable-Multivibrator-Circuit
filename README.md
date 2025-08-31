Astable Multivibrator Circuit
📌 Overview
This project is a PCB design for an Astable Multivibrator circuit. The circuit uses an 


NE555 timer IC to create a continuous square wave output. The frequency of this output is determined by the values of the resistors and the capacitor in the circuit. An LED (LED1) is connected to the output, which flashes in sync with the square wave.





🛠 Tools Used

EasyEDA  - Used for the schematic and PCB design.

📄 Key Components

IC: U2, NE555 timer IC 

Resistors:

R1: 2KΩ 




R2: 146KΩ 




R3: 560Ω 



Capacitors:

C1: 10uF 




C2: 0.1uF 


LED: LED1 




Connectors: J1 and J2 (CON_TERMINAL_BLOCK_02) 



⚡ Circuit Operation
The NE555 timer is configured in astable mode. The timing components, R1, R2, and C1, determine the charging and discharging cycles of the capacitor, which in turn controls the frequency and duty cycle of the output signal at pin 3. The LED (LED1) is connected to the output pin (pin 3) through a current-limiting resistor (R3), causing it to blink.





📸 Project Images
🔹 PCB Layout
![Top latout](<LAYOUT/top layout.jpg>)

![Bottom layout](<LAYOUT/bottom layout.jpg>)

🔹 PCB 3D Model
![Top 3d](<3D MODEL/top 3D model.jpg>)

![Bottom 3D](<3D MODEL/bottom 3D model.jpg>)

📄 License
This project is shared for educational and learning purposes only.