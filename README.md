OBJECTIVES:
1.To construct a Bandpass filter.
2.To set lower cut-off frequency at 4kHz.
3.To set higher cut-off frequency at 8kHz.

Introduction 
An example of an analogue electronic band-pass filter is an RLC circuit (a resistor–inductor–capacitor circuit). These filters can also be created by combining a low-pass filter with a high-pass filter. 
Bandpass is an adjective that describes a type of filter or filtering process; it is to be distinguished from passband, which refers to the actual portion of affected spectrum. Hence, one might say "A dual bandpass filter has two passbands." A bandpass signal is a signal containing a band of frequencies not adjacent to zero frequency, such as a signal that comes out of a bandpass filter.
In this experiment,we are going to be acquainted with the bandpass filter and going to build a proper circuit that can operate as a bandpassfilter.Abandpass filter has two particular cut-off frequency.Any input frequency outside this band is attenuated.Here we are going to fix the cut-off frequencies at 4kHz to 10kHz using 2nd order high pass filter and 2nd order low pass filter.

THEORY:
A filter circuit is a circuit that removes unwanted frequency components from a signal. Filters are classified into active and passive filter. Active filters are constructed with transistors or OP-AMP in addition to resistor and capacitor. The most commonly used active filters are 5 types. Bandpass filter is one of them.A bandpass filter is an electronic device or circuit that allow signals between two specific frequencies to pass,but that discriminates against signals at other frequencies.If the lower cut-off frequency is f1 and higher cut-off frequency is f2,then the range between f1 and f2 is called the filter pass band.
F2= 1/(2π√R1R2C1C2)
If R1=R2 and C1=C2 then,
F2= 1/2πRC
Bandpass filter is of two types-wide bandpass filter and narrow bandpassfilter.Here the quality factor,Q=fc /(fH-fL).
fc=center frequency
If Q<10,its wide bandpass.If Q>10,its narrow bandpass.Bandpass filter is constructed with a high pass  filter and a low pass filter.We are going to use here the 2nd order version of them.So,we are going to use 2 capacitors and 2 resistors for each filter circuit.

APPARATUS REQUIRED:
1.Breadboard
2.OP-AMP(IC-741)
3.Resistors(1KΩ,2KΩ,10KΩ)
4.Capacitors(0.04 µF,0.01 µF)
5.Function Generator
6.DC Power Supply
7.Connecting wires

CIRCUIT DIAGRAM:



 



6.EXPERIMENTAL DATA:
FREQUENCY
(kHz)	INPUT VOLTAGE(VI)	OUTPUT VOLTAGE(V0)	              GAIN
1.0	        6.2 	           7.56                       	1.21
2.0	        4.0	             11.18	                        2.8
3.0	       3.2	             12.60                       	3.9
4.0	       2.6	             12.20	                        4.7
5.0	       2.5	             11.42	                        4.6
6.0	       2.52	             10.59                       	4.2
7.0	       2.57	             9.78                       	3.8
8.0	       3.08	             8.92	                        2.9
9.0	       5.2	             8.17	                        1.6
10.0	     5.3	             7.40                      	1.4
11.0	     5.1	             6.68                     	1.3
12.0	     4.9	             5.91                     	1.24
13.0	     4.6	             5.72	                        1.2

RF=10kΩ
R1=10kΩ
Calculated gain=(1+10/10)*10/10=2
Calculated cut-off frequency=3.98kHz to 10.61kHz
Measured cut-off frequency=4kHz to 9kHz



GRAPHICAL ANALYSIS:


 






COST ANALYSIS:
SL.NO	     Apparatus name      	Rating	    Quantity	    Price(Tk)
1	          Op-amp	             LM-741	        2	         30 Tk
2	          Resistors	           1K,2K,10K Ω	  9	         4.5 Tk
3	          Capacitors	     0.01 µF, 0.04 µF	  4	         8 Tk
4	          Others	             -	            -	         30 Tk
				                                                TOTAL: 72.5 Tk

DISCUSSION:
In this experiment,we acquired knowledge about bandpass filter and it’s frequency response.We set our calculated cut-off frequencies at 4kHz and 10kHz.But due to some instrumental error we got the frequencies at nearly 4kHz and 9kHz.We measured input and output voltages for several frequencies.We plotted a graph of Gain Vs Frequency. First the output voltage was increasing but at a particular level the output voltage was almost constant.After sometimes it was decreasing.Though there were some errors the experiment was overall successful.

Applications:
 	In wireless transmitters and receivers
 	In neuroscience, visual cortical simple cells
 	In the atmospheric sciences
 	Signal-to-noise ratio




CONCLUSION:
Through this experiment, we observe the frequency response of a 2nd order bandpassfilter.We measured the gainand plotted graph.We could build the circuit with less expenses.Our experiment was successful.


REFERENCES:
1.OP-AMPS and Linear Integrated Circuits(by RAMAKANT A.GAYAKWARD)




