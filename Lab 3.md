<div align="justify">
  
# Lab 3: Synchronous Digital Counter
Date: 5 Jan 2026
## Handout
[Click here](https://drive.google.com/file/d/1JEXx8xaTuKBe6XTi_Xw3ZBZTcqS-q9uR/view?usp=sharing) to view the handout.
## Reflection
Completing Lab 3, Synchronous Digital Counter, provided significant practical insight into the behavior of sequential logic circuits and the fundamental role of flip-flops in memory-based systems. Through the construction and analysis of a physical circuit, I was able to bridge the gap between theoretical state tables and real-time hardware operation.

### Key Learning Outcomes
1. Practical Circuit Construction: I gained hands-on experience using the 7476 Dual J-K Flip-Flop alongside basic logic gates (7408 AND, 7404 Inverter, 7432 OR) on a breadboard. This highlighted the importance of proper hardware management, such as ensuring all ICs are connected to Vcc and GND for stable operation.

2. Understanding Synchronous Behavior: The lab reinforced the defining characteristic of a synchronous counter: all flip-flops are triggered by the same clock signal simultaneously. This contrasts with asynchronous circuits where the clock ripples through each stage.

3. Analyzing Sequential Logic: By completing the Next-State table and sketching a state diagram, I observed how the circuit transitions through four distinct states (00, 01, 10, 11) based on the current state and the external input, Switch 7 (X).

4. Triggering and Inputs: I learned to distinguish between synchronous inputs (J, K) that respond to clock edges and asynchronous inputs (PRESET and CLEAR) that affect the output immediately. Specifically, the 7476 IC was identified as a negative-edge triggered device.
### Personal Insights and Critical Thinking
The analysis of the state diagram revealed that the counter behaves as a saturated counter rather than a recycling one. This exercise promoted critical thinking by requiring me to interpret how the logic gates feeding into the J and K inputs controlled the specific sequence of the counter. Managing the asynchronous switches (Switch 0 and 1) further demonstrated how to initialize a digital system to a known state before starting a clock sequence.
### Conclusion
This lab exercise successfully demonstrated how complex behaviors can be built from simple memory cells. Understanding these synchronous properties is vital for designing more advanced digital systems, such as registers and timers, in future projects.
## Photos
![20260105_143941](https://github.com/user-attachments/assets/ba00b63f-38ad-40fa-bedc-b0159da45456)
</div>
