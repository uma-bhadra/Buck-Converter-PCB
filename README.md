# Buck-Converter-PCB
DC-DC buck converter schematic and multi-layer PCB layout (KiCad)

Please view the folder titled "Outputs" to view the Gerber files I made to send to PCBWay to get your PCB printed 

- Engineered a DC-DC buck converter from scratch
- Developed the full schematic and multi-layer PCB layout using KiCad
- Soldered and assembled the board, followed by oscilloscope testing to verify switching efficiency and output stability.

<br><br>
Layout of all of the components; finished soldered product
<br><br>
<img src="https://github.com/user-attachments/assets/4d92b94b-26a1-43e6-ae18-da107409420b" width="400" height="600"/>
 
<br><br>

HighDR and LowDR nodes on the oscilloscope
<br><br>
<img src="https://github.com/user-attachments/assets/6085e0a2-a52c-4228-8633-6cc2040b7822" width="400" height="600"/>

<br><br>
SW and Vout nodes with varied freqiencies of PWM between 50kHz and 100kHz. As the duty cycle increased, the amplitude of Vout decreased and vice versa. 
<br><br>
<img src="https://github.com/user-attachments/assets/e1d53f8a-d650-46db-92d6-4a2f6e2b2322" width="400" height="600"/>
<img src="https://github.com/user-attachments/assets/72b922cb-46f6-4850-a3f0-59c3f873f401" width="400" height="600"/>

<br><br>
The method on how connections to oscilloscope were made (testing phase, results below)
<br><br>
<img src="https://github.com/user-attachments/assets/c26758b4-e82e-4ef7-a30f-f7c47ceddfa9" width="500" height="700"/>

Here, I connected the OPAMP OUT to the 10 ohm resistor (connections shown in picture above.) This dissipated up to 10W of power. The current flowing through the current sense resistor was 0.31V/0.5 ohm = 0.62 A. When the Vin was scaled up to 16V, the current and voltage outputs both increased.
<br><br>
<img src="https://github.com/user-attachments/assets/d9f33e7f-fd9b-425f-9043-effe8fe4885b" width="400" height="500"/>





