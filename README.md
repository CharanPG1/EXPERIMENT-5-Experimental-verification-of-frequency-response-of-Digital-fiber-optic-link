Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM

<img width="890" height="529" alt="Screenshot 2025-11-11 192121" src="https://github.com/user-attachments/assets/435b8e26-0b42-493e-9d58-2459aba62701" />

---

## CONNECTION DIAGRAM  
**Setting up a Digital Link**

*(Insert connection diagram here)*

---

## TABULATION  
**Transmission through Digital Link**

| Frequency (Hz) | Output Signal Amplitude (Vo) | Gain = Vo/Vi | Gain in dB |
| -------------- | ---------------------------- | ------------ | ---------- |
| 800 Hz         | 2.5 V                        | 0.5          | -8         |
| 1 kHz          | 8 V                          | 6.4          | 16.12      |
| 2 kHz          | 8.4 V                        | 6.8          | 16.66      |
| 5 kHz          | 9.6 V                        | 7.2          | 17.14      |
| 10 kHz         | 9.7 V                        | 7.4          | 17.38      |
| 20 kHz         | 9.7 V                        | 7.4          | 17.38      |
| 50 kHz         | 9.7 V                        | 7.4          | 17.38      |
| 100 kHz        | 7.7 V                        | 5.4          | 14.64      |
| 250 kHz        | 2.7 V                        | 2.84         | 8.09       |

---

## MODEL GRAPH

<img width="880" height="538" alt="Screenshot 2025-11-11 190804" src="https://github.com/user-attachments/assets/25ece563-cf37-448d-8b86-19078ca43f90" />

---

## GRAPH

![WhatsApp Image 2025-11-17 at 11 00 29_38ae26e7](https://github.com/user-attachments/assets/a03e6750-8830-437e-b058-79ded44062f1)

---

## RESULT

Thus, the experiment confirms that the 600 nm fiber optic link exhibits a stable frequency response within its mid-range and shows attenuation at higher frequencies, validating the theoretical characteristics of digital fiber transmission.
