- main points {doesn't need to be explained "From my POV" }
1. hardware 
	- the difference between the RAM and the ROM that ==the ram stores data temporary==, but on the other hand ==the ROM stores the data permanently,== but the data that ROM  stores is just the ==OS programs and the main program "i really mean the main programs " , like the program that deals with the keyboard and that one deals with the mouse and so on== , but the other software you can find it on the HDD or the SSD cards or  flash memory and so on . 
1. software 


- watch this video that explains (input ,processing and output) from scratch . [ click the flipping button ](https://youtu.be/CBf-jIn44X0?si=uF7ZmGgoO4uHT-OY)
- ==Data items== encompass a wide range of information types (text, numbers, images, sounds and mouse movements ) that are input into a computer for processing.

#### what is the difference between the data type and the data items ?

##### Data type 
: Data types help the ***compiler or interpreter*** understand
how to treat data, including memory allocation, operations
and method invocations.

| Data Type | Example                                                                                                               |
| --------- | --------------------------------------------------------------------------------------------------------------------- |
| Integer   | Whole numbers (e.g., 1, 42, -5)                                                                                       |
| Float     | Decimal numbers (e.g., 3.14, 0.001)                                                                                   |
| String    | Sequences of characters (e.g., "Hello, World!")                                                                       |
| Boolean   | Represents truth values (true or false)                                                                               |
| Array     | A collection of items of the same type (e.g., [1, 2, 3])                                                              |
| Object    | A complex data structure that can hold multiple values and functions (e.g., a user profile with name, age, and email) |

##### Data items 
: they are the actual value of the data type , here is a table that breaks down what we've said .

| Data Item                            | Data Type |
| ------------------------------------ | --------- |
| A single integer value like ==42==   | Integer   |
| A text string such as =="John Doe"== | String    |

- ==So== we can say that *Data types are  "Classification of data values."* and on the other hand *Data items are "Individual pieces of data."*


=============================================

- now we'll explain that CPU units and parts and crack it down 

# CPU components 


### check that out [[CPU_components]]


 1. ALU (arithmetic logic unit)
	 - it make the arithmetic and logic ==according to the control unit instructions .==
    1. ==AL (arithmetic unit )==
	    - perform the sub and div and mul ==> all the *(+,-,/,* )* according to the CU 
    2. ==LU (logic units )== 
		- perform the *OR , AND , XOR , NOT* operations according to CU

2. CU (control unit )
	- it give the instructions and the orders to all other components in the CPU .
3. registers 
	-  save the data temporary until the ALU do its operations
	-  registers can only store data (that have a small size) ,but what if the data is large ? , well here it come the second CPU components { Cache memory}
4. cache memory 
	- The fastest "==faster than the main memory (the main memo if you don't know it is the RAM== ) " and very expensive so 
	- known as ==CPU memory== 
	- ==volatile memory== that temporarily stores frequently (when you shuts the PC off all data will be deleted  ) , and the vice versa of that is the ==RAM that have a non-volatile  memory== .
	- used for high-speed storage of frequently accessed data, while *main memory is used for larger amounts of data* that the CPU processes.
5. internal buses 
	- after the data has been processed the buses can  ==make the data walk through it to for example display it on the screen or send the data to HDD or SSD card too to store the data== ! . 


### check out that example that explains how the CPU can add 1 to 5 for example .



## Example of CPU Components Working  to ==add 1 to 5 for example== 

- **Control Unit (CU)**:
  - Fetches the instruction to add the numbers.
  - Understands that it needs to add 1 and 5 based on the instruction from memory.

- **Registers**:
  - CU places the number 1 into **Register A** and the number 5 into **Register B**.
  - Registers are small, fast storage locations in the CPU.

- **Arithmetic Logic Unit (ALU)**:
  - CU sends a command to the ALU to perform the addition operation.
  - ALU takes values from Register A (1) and Register B (5), adds them, and calculates the result (6).

- **Cache Memory (if needed)**:
  - In this example, cache memory may not be directly involved since the numbers are small.
  - If larger data sets were involved, cache would speed up the process by storing frequently used numbers.

- **Bus Interface**:
  - Once the ALU calculates the result (6), it sends the result back through the bus interface.
  - This result can be stored back into a register, sent to main memory, or displayed on a screen.
=============================================
# POINT 
- Web-browsing laptop needs about 2 GB of RAM, while an entertainment 
laptop can have anywhere from 4 to 8 GB.
- Laptop screens use thin liquid crystal display (LCD) screens
-  The laptop’s ==optical drive== is its DVD or CD drive. Most new laptops come 
with a DVD+/-RW drive, also called the burner
- laptop computer may also feature memory card slots for MMC and SD cards. 
-  Processor speeds for computers are measured in gigahertz (GHz). 
- the more cores the laptop processor has, the more tasks the laptop can do simultaneously. 
- Typical hard drives run at 5,400 rpm, but you can get a 
performance boost with a 7,200 or even 10,000 rpm hard drive.  
-  The higher the laptop screen’s ==native resolution==, the more detailed 
the picture quality will be.
- there is a  ==USB== ports to connect to a ==printer==
- and there is a  ==VGA== port if you want to connect to a separate 
==monitor or a projector==
- Internet Wireless connections, using a ==wireless-G or wireless-N signal==, are 
nearly universal in newer laptops.
- the ==GPUs==  or a video card, however, is an ==extra device== that takes the load off the processor.
- ==Speed: Main memory is relatively slower than registers but faster than secondary storage (like hard drives or SSDs).==

# Basics of Computers

### Quick notes

#### there's a 12 type of software but indeed we'll study 2

##### system software and the app software and integrated to the app software there is a utility software . 

- Anti-virus software are one of the utility software .
- word and power point are types of App software .
- and the OS and language processor and device driver are system software .