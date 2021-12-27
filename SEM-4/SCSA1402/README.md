# UNIT-1 `CENTRAL PROCESSING UNIT`

#### **Architecture** :
Specification dealing how a set of software and hardware technology standards interact to form a computer system.
- It can also be termed as "how a computer is designed to satisfy the needs of user".
- Computer architecture is a "set of rules and methods that describe the functionality, organization, and implementation of computer systems".
<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/d/d8/ABasicComputer.gif"/>
</p>

### **`VON NEUMANN MODEL`** : 
Von-Neumann proposed his computer architecture design in 1945 which was later known as **Von-Neumann Architecture**. It consisted of a `Control Unit`, `Arithmetic`, and `Logical Memory Unit` (ALU), `Registers` and `Inputs/Outputs`.

Von Neumann architecture is based on the stored-program computer concept, where instruction data and program data are stored in the same memory. This design is still used in most computers produced today.


![VON NEUMANN MODEL](https://static.javatpoint.com/tutorial/coa/images/von-neumann-model.png)

**Components of Von-Neumann Model** : 

- `Central Processing Unit` 
- `Buses` 
- `Memory Unit`   


###  **Central Processing Unit (CPU)** : 
The part of the Computer that performs the bulk of data processing operations is called the Central Processing Unit and is referred to as the `CPU` 

- The CPU performs a variety of functions dictated by the type of instructions that are incorporated in the computer.

- It is sometimes referred to as the `microprocessor` or `processor`.

- The major components of CPU are `Arithmetic and Logic Unit` (ALU), `Control Unit` (CU) and a variety of registers.


### **Arithmetic and Logic Unit (ALU)** : 

The Arithmetic and Logic Unit (ALU) performs the required micro-operations for executing the instructions. In simple words, ALU allows arithmetic (add, subtract, etc.) and logic (AND, OR, NOT, etc.) operations to be carried out.

-  It is a digital circuit used to perform arithmetic and logic operations. 

-  In some microprocessor architectures, the ALU is divided into the arithmetic and the logic units.

![ALU](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTqETcmGHdkc3V-N1NciFZQbG21TqAXyiSERA&usqp=CAU) 

### **Control Unit (CU)** : 
The Control Unit of a computer system `controls the operations of components` like ALU, memory and input/output devices.

The Control Unit consists of a program counter that contains the address of the instructions to be fetched and an instruction register into which instructions are fetched from memory for execution.

- The Control Unit of CPU `regulates and integrates` the operations of the computer. 

- The control unit also provides the timing and control signals required by other computer components. 
- It directs the `flow of data` between the CPU and the other devices. 
- It selects and retrieves instructions from the main memory in proper sequence and interprets them so as to activate the other functional elements of the system at the appropriate moment to perform their respective operations

<p>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/controlunit.png" width="400"/>
</p> 

### **Registers** : 

Registers are a type of computer memory used to quickly accept, store, and transfer data and instructions that are being used immediately by the CPU

Registers refer to high-speed storage areas in the CPU. The data processed by the CPU are fetched from the registers. 

 - Registers are also referred as `temporary storage locations` inside the CPU that hold data and addresses.

- All data must be stored in a register before it can be processed.

- Registers provides storage internal to the CPU. 

Following is the list of registers that plays a crucial role in data processing

![Types](https://imgur.com/xDieCk7.jpg)    

### **Buses** : 
Buses are the means by which data is transmitted from one part of a computer to another, connecting all major internal components to the CPU and memory.

- Buses are used to send control signals and data between the processor and other components 