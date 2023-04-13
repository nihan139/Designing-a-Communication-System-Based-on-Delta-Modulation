# Designing-a-Communication-System-Based-on-Delta-Modulation
Implemented in Proteus

This project can be divided into following modules
-   Modulation
-   Transmission through noisy channel
-   Demodulation
-   Noise Analysis

<br>

## **Circuit Diagram**
<br>

<p align="center">
   <img src="./full_ckt.png" width="600" height="300"/>
</p>

<br> <br>
## **Modulation**
It consists of 3 blocks
-   Comparator
-   D Flip-Flop
-   Feedback Integrator

<br>

<p align="center">
   <img src="./modulation.png" width="600" height="300"/>
</p>

<br> <br>

After passing these 3 blocks, the output signal looks like following
<br>

<p align="center">
   <img src="./mod_out.png" width="600" height="300"/>
</p>

<br> <br>

## **Noise & Summing Block**
-   Noise is added to make realistic.
-   5 random sinusoid(500,800,1700,2300,3500 Hz)
-   Summing amplifier

<br>

<p align="center">
   <img src="./Noise_and_sum_amplifier.png" width="600" height="300"/>
</p>

<br> <br>

After adding random noise, the output signal looks like following
<br>

<p align="center">
   <img src="./sum_amp_out.png" width="600" height="300"/>
</p>

<br> <br>

## **Demodulation**
It consists of 2 blocks
-   Integrator
-   2 Low Pass Filter

<br>

<p align="center">
   <img src="./demodulation.png" width="600" height="300"/>
</p>

<br> <br>
After passing these 2 blocks the output signal looks like following.

<br>

<p align="center">
   <img src="./demod_out.png" width="600" height="300"/>
</p>

<br> <br>
So we can get the attenuated version of the original message signal.

<br>

## **Contributors**
1. Md. Tasnim Azad
2. Md. Ahsanul Haque
3. Mahadi Hassan
4. Kazi Moheuddin Alamgir
