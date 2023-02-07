<h1>Theory:</h1>
<h3>Introduction:</h3>
An Instrumentation amplifier is an integrated circuit (IC) that is used to Amplify a signal.<br>This type of amplifier is in the differential amplifier family because It amplifies the difference between two inputs.<br> The importance of an Instrumentation amplifier is that it can reduce unwanted noise that is picked up by The circuit. <br>The ability to reject noise or unwanted signals common to all IC pins is Called the common-mode rejection ratio (CMRR).<br> Instrumentation amplifiers are Very useful due to their high CMRR.<br> Other characteristics, such as high open loop Gain, low DC offset and low drift, make this IC very important in circuit design

![image](https://user-images.githubusercontent.com/99191853/217315960-675f70e8-e610-4653-9727-3ad4e885dc79.png)

The most commonly used instrumentation amplifier circuit is shown in Fig. 1. The gain of the circuit is

![image](https://user-images.githubusercontent.com/99191853/217316447-c19f08c2-8016-4b60-bdc2-f4f110976011.png)

An instrumentation amplifier is a differential op-amp Circuit providing high input impedance with ease of gain Adjustment through the variation of a single resistor.<br>It is A type of differential amplifier that has been outfitted With input buffer amplifiers, which eliminate the need For input impedance matching and thus make<br> the Amplifier particularly suitable for use in measurement And test equipment.<br> Additional characteristics include Very low DC offset, low drift, low noise, very High open-loop gain, very high common-mode rejection Ratio, <br>and very high input the input of Impedance Always the input of instrumentation amplifier is the output from the Transducers and will a small signal.<br>These are used where Great accuracy and stability of the circuit are required for Both short and long-term.<br>
The output voltage of the Instrumentation amplifier circuit can be calculated using the below formulae:<br>
Vout = (V2-V1)(1+(2R/Rg))<br>
Where, (V2-V1) = Voltage difference of the input voltages<br>
 R = Resistor value the circuit <br>
Rg  = Gain Resistor <br>
So the value of R and Rg decides the gain of the amplifier. The value of gain can be calculated by :<br>
Gain = (1+(2R/Rg))<br>
The amplifier’s gain is referred to as the factor by which the amplifier amplifies the input signal.<br> The resistance values represent the gain of an instrumentation amplifier.<br> The gain also depends on the type of feedbacks being used. The positive feedback provides higher gain, whereas negative feedback provides better stabilities of the system.
<h2>Understanding the Instrumentation Amplifier Circuit</h2>

<h3>Instrumentation Amplifier Design</h3>
An instrumentation amplifier is a combination of 3 typical amplifiers.<br> They are connected in a specific order to build an instrumentation amplifier. <br>We can segregate the instrument amplifier design into two-part.<br>
The first part is “Two input and two output”. <br>Two standard operational amplifiers are connected, as shown in the amplifier circuit figure.<br> Both of them are provided with negative feedback as it stabilizes the circuit more.<br> The output of both the amplifier is connected with three resistors.<br>
The second part is a basic “Differential Amplifier”.<br>  The output of both the previous amplifier acts as input for the last amplifier.<br> Outputs are connected with two identical valued resistors with the amplifier. 

