# **`INTERFACING`**

## **`PROGRAMMABLE PERIPHERAL INTERFACE 8255`**

PPI 8255 is a general purpose programmable I/O device designed to interface the CPU with its outside world such as ADC, DAC, keyboard etc. We can program it according to the given condition. It can be used with almost any microprocessor.
- It is a `40-pin` IC and operates in `+5V` regulated power supply(DC).
- It is a `dual in-line package` that means it will have the equal number of pins on either sides(20 each).
- IC8255 acts as an `interface` between the MP(microprocessor) and the I/O(input/output) device.
- I/O ports are further divided into three `bi-directional` ports i.e. **PORT A, PORT B and PORT C** (8 pins each). 
- The most important feature of 8255 is that it is `‘programmable’`. This means that the operation of 8255 can be controlled by programming the microprocessor appropriately.

### **`PIN DIAGRAM OF 8255 PPI`** 
<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/PPI8255.png" width="180"/>
</p> 

#### **`Description of pins in 8255 PPI`** :

- `PA0 to PA7` - Pins of port-A, they are equally distributed on either sides at the top of 8255IC. The keys 1 to 4 and 37 to 40 are the pins devoted for port A.

- `PB0 to PB7` - Pins of port-B, keys 18 to 25 are the pins that carry the data of port B. 

- `PC0 to PC7` -  Pins of port-C, they are further classified into Port C lower pins(PC0-PC3) and upper pins(PC4-PC7). 

- `D0 to D7` – Data pins for the transfer of data.

- `RESET` - Reset input, This is an *active high signal*. It clears the control register and sets all ports in the input mode.

- `RD'` - Read input, this control signal enables the Read operation. When the signal is low, the microprocessor reads the data from the selected I/O port of the 8255.

- `WR'` - Write input, this control signal enables the write operation. When this signal goes low, the microprocessor writes into a selected I/O port or control register.

- `VCC` - *Voltage Common Collector*, it is the power input of a device.(+5V for 8255 PPI). 

- `GND` - *Ground*, it is like a reference point for all signals. Can also be termed as commnon drain or sink. It is connected to the common ground of the circuit.  

- `CS` - *Chip Select*,
This is an `active low` input pin. When the input is `LOW(0)`, it selects the chip and operation of ports, that results in enabling the communication between the 8255A and the CPU. It will not select the ports if the input is high(1). 

![ppi](https://www.tutorialspoint.com/assets/questions/media/19061/functional_pin_diagram.jpg)

### **Block diagram and internal structure of 8255** 

![block_diagram](https://i1.wp.com/technobyte.org/wp-content/uploads/2020/05/8255-block-diagram.png?w=600&ssl=1)

