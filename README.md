# CMOS Schmitt-Trigger using eSim-Tool

- [Abstract](#abstract)
- [Reference Circuit Diagram](#reference-circuit-diagram)
- [Circuit Details](#circuit-details)
- [Software Used](#software-used)
    * [eSim](#esim)
    * [NgSpice](#ngspice)
    * [Makerchip](#makerchip)
- [Circuit Diagram in eSim](#circuit-diagram-in-esim)
- [Waveforms](#waveforms)
     * [Dc Response](#Dc-Response)
  
   
  
- [Acknowlegdements](#acknowlegdements)
- [References](#references)
 
## Abstract:- 
CMOS Schmitt trigger design with given circuit thresholds is described. The approach is based on studying the transient from one stable state to another when the trigger is in linear operation. 
## Introduction:-
The simple signal inverter circuit gives the opposite output signal from the input signal. For example, if the input signal is high, the output signal is low for a simple inverter circuit. But if the input signal has spikes (noise), the output signal will react change on a spike. That we don’t want. Therefore, the CMOS Schmitt trigger is used.
![DocScanner 04-Mar-2022 2-51 pm](https://user-images.githubusercontent.com/98162318/157423313-57e732e1-3be8-427c-b447-0d34a469913a.jpg)
In the first waveform, the input signal has no noise. So, the output is perfect. But in the second figure, the input signal has some noise. The output is also reacting to this noise. To avoid, this condition, CMOS Schmitt trigger is used.
## Reference Circuit Diagram:

![DocScanner 09-Mar-2022 11-40 am](https://user-images.githubusercontent.com/98162318/157423423-2ed58027-6dcc-439a-b663-9139a16fc844.jpg)

## Circuit Details:

This circuit Act as a Inverter there is a No change in the property but the Question is what is the advantage or what kind of differences we will observe if we have provided two pull up transistor in the series and pull down transistor in the series. so the advantages will be effectively the width of the complete pull-up network will increase by double there is no change in the lenght but the width is going to be double like if I am considering the M3 and M2 and M4 and M5 are same size so the effective width of this pull up network.  
From the circuit diagram M4 and M5 are PMOS transistor are connected in series. And M1 and M2 Nmos transistor connected in series.
If we will give O logic in input side the M4 and M5 transistor are activated and M1 and M2 transistor are dectivated. 
If will give logic 1 in input side the M1 and M2 are activated and M4 and M5 are deactivated .

## Software Used:
### eSim
It is an Open Source EDA developed by FOSSEE, IIT Bombay. It is used for electronic circuit simulation. It is made by the combination of two software namely NgSpice and KiCAD.
For more details refer:

https://esim.fossee.in/home

### NgSpice
It is an Open Source Software for Spice Simulations. For more details refer:

http://ngspice.sourceforge.net/docs.html

### Makerchip
It is an Online Web Browser IDE for Verilog/System-verilog/TL-Verilog Simulation. Refer

https://www.makerchip.com/

### Verilator
It is a tool which converts Verilog code to C++ objects. Refer:

https://www.veripool.org/verilator/

### Circuit Diagram in eSim:

![image](https://user-images.githubusercontent.com/98162318/157478144-5b814285-6bec-4848-8497-aee9acf56db0.png)



## Waveforms
![new schmitt trigger1](https://user-images.githubusercontent.com/98162318/157637097-dde9f98d-50bb-4296-8b8d-d6c7af7f9b61.png)



## Acknowlegdements:
1. FOSSEE, IIT Bombay
2. Steve Hoover, Founder, Redwood EDA
3. Kunal Ghosh, Co-founder, VSD Corp. Pvt. Ltd. - kunalpghosh@gmail.com
4. Sumanto Kar, eSim Team, FOSSEE

## References
[1] Filanovsky, I. M., and H. Baltes. "CMOS Schmitt trigger design." IEEE Transactions on Circuits and Systems I: Fundamental Theory and Applications 41.1 (1994): 46-49.


