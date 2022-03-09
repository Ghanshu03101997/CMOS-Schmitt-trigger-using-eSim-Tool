# CMOS Schmitt-Trigger using eSim-Tool
### Abstract:- 
CMOS Schmitt trigger design with given circuit thresholds is described. The approach is based on studying the transient from one stable state to another when the trigger is in linear operation. 
### Introduction:-
The simple signal inverter circuit gives the opposite output signal from the input signal. For example, if the input signal is high, the output signal is low for a simple inverter circuit. But if the input signal has spikes (noise), the output signal will react change on a spike. That we don’t want. Therefore, the CMOS Schmitt trigger is used.
![DocScanner 04-Mar-2022 2-51 pm](https://user-images.githubusercontent.com/98162318/157423313-57e732e1-3be8-427c-b447-0d34a469913a.jpg)
In the first waveform, the input signal has no noise. So, the output is perfect. But in the second figure, the input signal has some noise. The output is also reacting to this noise. To avoid, this condition, CMOS Schmitt trigger is used.
![DocScanner 09-Mar-2022 11-40 am](https://user-images.githubusercontent.com/98162318/157423423-2ed58027-6dcc-439a-b663-9139a16fc844.jpg)

This circuit Act as a Inverter there is a No change in the property but the Question is what is the advantage or what kind of differences we will observe if we have provided two pull up transistor in the series and pull down transistor in the series. so the advantages will be effectively the width of the complete pull-up network will increase by double there is no change in the lenght but the width is going to be double like if I am considering the M3 and M2 and M4 and M5 are same size so the effective width of this pull up network.  
