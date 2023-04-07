# PCB Design for ARM Cortex-M3

This project involves the schematic and PCB design of an Arduino like PCB for ARM Cortex-M3 MCU. 

A 9V Battery connector and a Voltage Regulator were used from the side of the Power Supply.

For the MCU, several circuits were designed, such as Bypass Capacitors for the Analog and Digital Power, Crystal Oscillators, Reset Button, Serial Wire Debug Interface, Boot Options and the routing of 30 GPIO pins.



### Schematic MCU

<img src="/Smart_MCU/Images/Schematic_MCU.png" >



### Schematic Power Supply

<img src="/Smart_MCU/Images/Schematic_PS.png" >





### PCB before Polygons

<img src="/Smart_MCU/Images/PCB_2D_before_poly.png">





<img src="/Smart_MCU/Images/PCB_3D_before_poly.png">



<img src="/Smart_MCU/Images/PCB_3D_before_poly_back.png">



### PCB after Polygons

<img src="/Smart_MCU/Images/PCB_2D_after_poly.png">



<img src="/Smart_MCU/Images/PCB_3D_after_poly.png">



<img src="/Smart_MCU/Images/PCB_3D_after_poly_back.png">



### Bill of Materials

<img src="/Smart_MCU/Images/bill_of_mat.png">



---



# Altium 5V Regulator PCB design

This project involves the schematic and PCB design of a 5V Voltage Regulator using commercial components and the add-on Altium Library Loader.

For the design I used capacitors, LM7805 regulator and a Schottky diode.



### Schematic

<img src="/Altium_5V_Regulator/Images/Schematic.png" >



### PCB

<img src="Altium_5V_Regulator/Images/2D_PCB.png">





<img src="Altium_5V_Regulator/Images/3D_PCB.png">



----





# Buck Converter with Altium

This project involves the schematic design and Simulation of a Buck converter of a Buck Converter with Altium, as it was assigned for my Power Electronic courses. 



### Requirements

Vin = 12V

Vout = 5V

I_load= 2A

f = 400KHz

Duty cycle = Vin/Vout = 5/12 = 0.416



### Schematic

<img src="Buck_Converter/Images/schematic.png" >



### PWD simulation with V2

<img src="Buck_Converter/Images/pwm.png" >



### Simulation

<img src="Buck_Converter/Images/simulation.png">



---





# USB to UART PCB

The Silicon Labs' CP2102 is a small module designed to convert interfaces between USB and UART, serving as a convenient interface converter.



### CP2102-GM

<img src="USB_to_UART_Altium/Images/cp21029.png" >



### Schematic

The PCB design will consist of a two-layer configuration where all the components will be placed on the top layer.



<img src="USB_to_UART_Altium/Images/schematic.png" >



### PCB 2D

<img src="USB_to_UART_Altium/Images/pcb2d.png">



