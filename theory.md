<div style="font-family: 'Nunito Sans', sans-serif; font-size: 20px;text-align: justify;">
<h2>Introduction</h2>

A voltage to current converter (also known as a V to I converter) is an electronic circuit that takes current as the input and produces voltage as the output. Well for instrumentation cicuits when creating an analog representation of certain physical quantities (weight, pressure, motion etc), DC current is preferred. This is because DC current signals will be constant throughout the circuit in series from the source to the load. The current sensing instruments also have the advantage of less noise. So, sometimes it is essential to create current which is corresponding or proportional to a definite voltage. For this purpose Voltage to Current Converters (also known as V to I converters) are used. It can simply change the carrier of electrical data from voltage to current.<br>

### Voltage to Current Converter Using Op-Amp

An op-amp is implemented to simply convert the voltage signal to corresponding current signal. The Op-amp used for this purpose is IC LM741. This Op-amp is designed to hold the precise amount of current by applying the voltage which is essential to sustain that current through out the circuit. They are of two types that are explained in detail below.<br>

### Floating Load Voltage to Current Converter

As the name indicates, the load resistor is floating in this converter circuit. That is, the resistor R<sub>L</sub> is not linked to ground. The voltage V<sub>IN</sub> which is the input voltage is given to the non-inverting input terminal. The inverting input terminal is driven by the feedback voltage which is across the R<sub>L</sub> resistor.

This feedback voltage is determined by the load current and it is in series with the V<sub>D</sub> which is the input difference voltage. So this circuit is also known as current series negative feedback amplifier.

<center><img src="images/VC1.png" height="280" width="350"></center><center>Fig. 1 Floating Load Voltage to Current Converter</center>

For the input loop, the voltage equation is

<center><b>V<sub>IN</sub> = V<sub>D</sub> + V<sub>F</sub></b></center>

Since A is very large,

<center><b>V<sub>D</sub> = 0</b></center>

So,

<center><b>V<sub>IN</sub> = V<sub>F</sub></b></center>

Since, the input to the Op-amp,

<center><b>I'<sub>B</sub> = 0</b></center><br>

<center><b>V<sub>IN</sub> = I<sub>L</sub> x R</b></center><br>

<center><b>I<sub>I</sub> = I<sub>L</sub> x V<sub>IN</sub>/R</b></center><br>

From the above equation, it is clear that the load current depends on the input voltage and the input resistance. That is, the load current which is the input voltage. The load current is controlled by the resistor R. Here, the proportionality constant is 1/R. So, this converter circuit is also known as Trans-Conductance Amplifier. Other name of this circuit is Voltage Controlled Current Source.

The type of load may be resistive, capacitive or non-linear load. The type of load has no role in the above equation. When the load connected is capacitor then it will get charge or discharge at a steady rate. Due to this reason, the converter circuit is used for the production of saw tooth and triangular wave forms.

### Ground Load Voltage to Current Converter

This V to I converter is also known as Howland Current Converter. Here, one end of the load is always grounded. For the circuit analysis, we have to first determine the voltage V<sub>IN</sub> and then the relationship or the connection between the input voltage and load current can be achieved.

<center><img src="images/VC2.png" height="300" width="380"></center><center>Fig. 2 Ground Load Voltage to Current Converter</center><br>

For that, we apply Kirchhoff’s current law at the node V<sub>1</sub>

<center><b>I<sub>1</sub> + I<sub>2</sub> = I<sub>L</sub></b></center><br>

<center><b>(V<sub>IN</sub> - V<sub>1</sub>)/R  + (V<sub>0</sub> - V<sub>1</sub>)/R = I<sub>L</sub></b></center><br>

<center><b>V<sub>IN</sub> + V<sub>0</sub> - 2V<sub>1</sub> = I<sub>L</sub>R</b></center><br>

<center><b>V<sub>1</sub> = (V<sub>IN</sub>  + V<sub>0</sub> - I<sub>L</sub>)/2</b></center>

For a non-inverting amplifier, gain is

<center><b>A = 1 + R<sub>F</sub>/R<sub>1</sub></b></center>

Here, the resistor,

<center><b>R<sub>F</sub> = R = R<sub>1</sub></b></center>

So,

<center><b>A = 1 + R/R = 2</b></center>

Hence the voltage in the output will be

<center><b>V<sub>0</sub> = 2V<sub>1</sub> = V<sub>IN</sub> + V<sub>0</sub> - I<sub>L</sub>R</b></center><br>

<center><b>0 = V<sub>IN</sub> - I<sub>L</sub>R</b></center><br>

<center><b>V<sub>IN</sub> = I<sub>L</sub>R</b></center><br>

<center><b>I<sub>L</sub> = V<sub>IN</sub>/R</b></center><br>

Thus, We can conclude from the above equation that the current I<sub>L</sub> is related to the voltage V<sub>IN</sub> and the resistor R.
    
### Applications of Voltage to Current Converter

1.	Zener diode tester<br>
2.	Low AC and DC Voltmeters<br>
3.	Testing LED<br>
4.	Testing Diodes<br>
