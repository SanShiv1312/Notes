# **`INTERFACING`**

### **`PROGRAMMABLE PERIPHERAL INTERFACE 8255`**

PPI 8255 is a general purpose programmable I/O device designed to interface the CPU with its outside world such as ADC, DAC, keyboard etc. We can program it according to the given condition. It can be used with almost any microprocessor.
- It is a `40-pin` IC and operates in `+5V` regulated power supply(DC).
- It is a `dual in-line package` that means it will have the equal number of pins on either sides(20 each).
- IC8255 acts as an `interface` between the MP(microprocessor) and the I/O(input/output) device.
- I/O ports are further divided into three `bi-directional` ports i.e. **PORT A, PORT B and PORT C** (8 pins each).  

#### **PIN DIAGRAM OF 8255 PPI** 
<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/PPI8255.png" width="180"/>
</p> 

#### `Description of pins in 8255 PPI`

- ***PA0 to PA7*** - Pins of port-A, they are equally distributed on either sides at the top of 8255IC. The keys 1 to 4 and 37 to 40 are the pins devoted for port A.

- ***PB0 to PB7*** - Pins of port-B, keys 18 to 25 are the pins that carry the data of port B. 

- ***PC0 to PC7*** -  Pins of port-C, they are further classified into Port C upper pins and lower pins 










![ppi](https://www.tutorialspoint.com/assets/questions/media/19061/functional_pin_diagram.jpg)
