## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
<img width="796" height="531" alt="image" src="https://github.com/user-attachments/assets/1b015ded-ad07-46e6-9c47-3125ceba163e" />

(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V
## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="832" height="523" alt="image" src="https://github.com/user-attachments/assets/465ccce8-9882-4428-8ce0-7c372b12168b" />

## Tabulation
<img width="941" height="331" alt="Screenshot 2026-02-23 090717" src="https://github.com/user-attachments/assets/8c71fc06-a416-4347-8a66-f0bb427a33ed" />

S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)
## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?
   A non-inverting amplifier is an op-amp configuration in which the input signal is applied to the non-inverting (+) terminal. The output signal is amplified without changing the phase of the input signal.
2.	What is the gain formula?
	The voltage gain of a non-inverting amplifier is

𝐴
𝑣
=
1
+
𝑅
𝑓
𝑅
1
A
v
	​

=1+
R
1
	​

R
f
	​

	​


where 
𝑅
𝑓
R
f
	​

 is the feedback resistor and 
𝑅
1
R
1
	​

 is the resistor connected to ground.
3.	Why is output in phase?
The input is applied to the non-inverting terminal, so the op-amp amplifies the signal without phase reversal. Hence, the output waveform remains in phase with the input.
4.	What happens if Rf increases?
If the feedback resistor 
𝑅
𝑓
R
f
	​

 increases, the voltage gain increases. Therefore, the output amplitude becomes larger.
5.	What is the input impedance of non-inverting amplifier?
The input impedance is very high because the signal is applied directly to the op-amp input terminal, resulting in very small input current.

