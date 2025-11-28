3. ##**EX.NO:
** 3  EXPERIMENTAL VERIFICATION OF INTEGRATOR AND DIFFERENTIATOR USING OP-AMP 
            
**DATE:**  
             3A INTEGRATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
INTEGRATOR
A circuit in which the output voltage waveform is the integral of the input voltage waveform is the integrator. Such a circuit is obtained by using a basic inverting amplifier configuration if the feedback resistor Rf is replaced by a capacitor Cf . The expression for the output voltage is given as,
Vo = - (1/Rf C1 ) ∫ Vi dt

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. Normally between fa and fb the circuit acts as an integrator. Generally, the value of fa < fb . The input signal will be integrated properly if the Time period T of the signal is larger than or equal to Rf Cf . That is,
T ≥ Rf Cf

The integrator is most commonly used in analog computers and ADC and signal-wave shaping circuits.
CIRCUIT DIAGRAM
## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 14 19 39_30830dd0](https://github.com/user-attachments/assets/40e0672f-7f24-41c3-aa07-a0f09fcfe4fe)



## MODEL GRAPH
![WhatsApp Image 2025-11-28 at 14 20 25_803c7efe](https://github.com/user-attachments/assets/c94522d6-c03a-4b84-af34-f1ccbe1f229e)

![WhatsApp Image 2025-11-28 at 14 20 56_c8e3428a](https://github.com/user-attachments/assets/42985988-12ad-441c-a352-d085134eab80)

---

## DESIGN
![WhatsApp Image 2025-11-28 at 14 25 21_078616a1](https://github.com/user-attachments/assets/f9870881-7b17-45f0-a058-c1505d29821b)

## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.


## TABULATION
![WhatsApp Image 2025-11-28 at 14 20 07_75e7f887](https://github.com/user-attachments/assets/01a3fe1c-8c95-48a0-b7ba-8ef644eae911)

		

---

## OUT PUT WAVEFORM AND DISCUSSION 

![WhatsApp Image 2025-11-27 at 19 05 05_b99596c2](https://github.com/user-attachments/assets/fc787bde-fd4e-47ef-8a20-76259b80c362)

---
**DATE:**  
             3 B DIFFERENTIATOR
---

## AIM
To design and test the performance of integrator and differentiator circuits using Op-amp

---

## APPARATUS REQUIRED

| S.No | Name of the Apparatus | Range | Quantity |
|------|------------------------|--------|-----------|
| 1 | Function Generator | 3 MHz | 1 |
| 2 | DSO | 30 MHz | 1 |
| 3 | Dual RPS | (0 – 30) V | 1 |
| 4 | Op-Amp | µA741 | 1 |
| 5 | Bread Board | — | 1 |
| 6 | Resistors | 1K,10K,100K  | 2 |
| 7 | capacitors | 0.1µF,0.01µF | 1 |
| 8 | Connecting wires and probes | As required | — |

---

## THEORY
DIFFEERENTIATOR:
The differentiator circuit performs the mathematical operation of differentiation; that is, the output waveform is the derivative of the input waveform. The differentiator may be constructed from a basic inverting amplifier if an input resistor R1 is replaced by a capacitor C1 . The expression for the output voltage is given as,
Vo = - Rf C1 ( dVi /dt )

Here the negative sign indicates that the output voltage is 180 0 out of phase with the input signal. A resistor Rcomp = Rf is normally connected to the non-inverting input terminal of the op-amp to compensate for the input bias current. A workable differentiator can be designed by implementing the following steps:
1.	Select fa equal to the highest frequency of the input signal to be differentiated. Then, assuming a value of C1 < 1 µF, calculate the value of Rf.
2.	Choose fb = 20 fa and calculate the values of R1 and Cf so that R1C1 = Rf Cf.

The differentiator is most commonly used in wave shaping circuits to detect high frequency components in an input signal and also as a rate–of–change detector in FM modulators.

## CIRCUIT DIAGRAM
![WhatsApp Image 2025-11-28 at 14 21 16_e6e428f8](https://github.com/user-attachments/assets/bcaade5f-6d3e-438a-b5d9-db51837a93cf)



## MODEL GRAPH

(i)	 SINE WAVE INPUT

![WhatsApp Image 2025-11-28 at 14 21 36_3add2551](https://github.com/user-attachments/assets/cc0e833d-f7c2-4f5c-9cf7-7bad9e351ac6)


AND

(ii) SQUARE WAVE INPUT

![WhatsApp Image 2025-11-28 at 14 22 16_8e110089](https://github.com/user-attachments/assets/438ee417-4630-4104-9785-5455040ba0e5)


---

## DESIGN

![WhatsApp Image 2025-11-28 at 14 29 08_d8a96f84](https://github.com/user-attachments/assets/bb4607c4-c3b0-4313-bee2-9f0064191b39)


## PROCEDURE

1.	Connections are given as per the circuit diagram
2. + Vcc and - Vcc supply is given to the power supply terminal of the Op-Amp IC.
3.	By adjusting the amplitude and frequency knobs of the function generator, appropriate input voltage is applied to the inverting input terminal of the Op- Amp.
4.	The output voltage is obtained in the CRO and the input and output voltage waveforms are plotted in a graph sheet.

 ## TABULATION
![WhatsApp Image 2025-11-28 at 14 23 02_16b6d77c](https://github.com/user-attachments/assets/d4f07b97-dc1a-4669-9062-589fdf34f2ad)

		

## OUT PUT WAVEFORM AND DISCUSSION 
![WhatsApp Image 2025-11-27 at 19 05 06_87617e3a](https://github.com/user-attachments/assets/9962935e-8310-447b-a0cc-30acf7faed30)

---

RESULT:
Thus an Integrator and Differentiator using op-amp are designed and their performance was successfully tested using op-amp IC 741.
---
![WhatsApp Image 2025-11-28 at 14 30 15_f70bcb18](https://github.com/user-attachments/assets/ded80cca-b909-441f-9700-a5ddceb6141f)



