### Introduction
<br>

In most of the cases we get the output of measuring devices in the form of voltage. It is not good to transmit this output voltage to the destination directly. Due to addition of noise and wire impedance the output voltage may get corrupted. So in such cases we have convert that voltage into current form. So let us see voltage to current converter.

Op-amp is implemented to simply convert the voltage signal to corresponding current signal.<br> The Op-amp used for this purpose is IC LM741. This Op-amp is designed to hold the precise amount of current by applying the voltage which is essential to sustain that current through out the circuit.<br>
The output current is given by<br>
<center><b>I<sub>o</sub> = V<sub>in</sub>/R</b></center>
<br>Following circuit shows the voltage to current converter using operational amplifier. It consist of simple resistance connected to the inverting and non inverting terminals of op amp.<br>

<center><img src="images/volt.png" style="margin-left: 0.9%;margin-top: 9%"></center><br>
<center><b>Figure 1. Voltage to current converter</b></center>
                    




