https://github.com/user-attachments/assets/9cb116fe-cfa0-49a3-8c16-66a33fe62e30


https://github.com/user-attachments/assets/8d7c22b4-77f3-4cf6-b881-012497906da7


It was about Button Debouncing (Monostable Pulse)

## Objective
Convert the noisy bouncing signal from a pushbutton into a single pulse with a fixed width.  
This can be used as a manual clock signal.

## Description
Mechanical pushbuttons often produce bouncing.
One press may generate several short pulses instead of one clean signal. 
This can cause counters to advance multiple steps by mistake.

The 74LS123 is a dual one-shot multivibrator that can generate a pulse with a fixed width determined by an RC timing network.  
It is used to convert an unstable button signal into a clean single pulse.

An LED can be connected to the output so the pulse can be observed visually. 
When the output is connected to the clock input of a CD4017 or CD4026, 
each button press advances the counter by only one step, creating a reliable “single-step” effect.

No matter how many time you press in one second or while the LED is blinking,
The LED will only blink once.



<img width="912" height="950" alt="image" src="https://github.com/user-attachments/assets/9ed832dd-a661-40af-a5f9-fee6071f4e75" />
