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

![CU](data:image/png;base64,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)

