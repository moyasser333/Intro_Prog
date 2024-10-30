

- the *source code* is the high-level language that you'r programming with , and *object code* is a specific part in the source code "that do specific thing" and it can be executed partly "as in some objects they need an input from the user to complete the execution process " , *machine lang or binary lang* 0s and 1s and it is the executed version of the high-level language  , then we have an *app software* like "*compiler and interpreter*" that translate the source code into the machine language . that's it in short 




# compiler and interpreter 


| Aspect                  | Compiler                                                                                                                                                               | Interpreter                                                                          |
| ----------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| **Translation Process** | Translates ==entire code at once== into machine code (executable)                                                                                                      | Translates code ==line-by-line at runtime==                                          |
| **Execution Speed**     | ==Faster== during execution after compilation                                                                                                                          | ==Slower== due to line-by-line interpretation                                        |
| **Startup Time**        | ==Slower== (requires compilation before execution)                                                                                                                     | ==Faster== (immediate execution without compilation)                                 |
| **Error Detection**     | Detects errors ==after compiling the whole code==                                                                                                                      | ==Stops at the first error== and reports it immediately                              |
| **Memory Usage**        | Generally requires ==more memory for the compiled executable file==                                                                                                    | Requires ==less memory since it processes code at runtime==                          |
| **Use Cases**           | Suitable for larger applications ==requiring high performance==                                                                                                        | Ideal for scripting, rapid prototyping, and interactive environments                 |
| **Output**              | Produces an executable file (e.g., .exe)                                                                                                                               | ==No executable file, runs code directly==                                           |
| **Portability**         | Platform-dependent (compiled for specific OS) , "==For that reason there is a specific version for each OS ! as they depend on the OS software ,which is different== " | More portable; the same source code can run on any ==platform== with the interpreter |
| **Examples**            | C, C++, Rust,Python                                                                                                                                                    | Python, JavaScript, Ruby                                                             |


# The Machine Cycle

#### main concepts 
 - The cycle consists of three standard steps: fetch, decode and execute (store "optionally ").
 - There are steps in machine cycle: 
	 a) Instruction Phase: 
		• Fetch - get an instruction from **Main Memory** {the compiled code }
		• Decode - translate it into computer commands in the **CU** { decode means tern the 0s and 1s to instructions of electric signals 0 = 0 volt , 1 = 5 volt  } and send it to ALU
	b) Execution Phase 
		• Execute - actually process the command in ALU { make the electric signals applied}
		• Store - write the result to Main Memory {if needed !}
All programs could be structured in the following four ways: 
(1) Sequences of instructions 
(2) Branches 
(3) Loops    
(4) Modules 


## here is an explained blocked
[[Machine-Cycle]]


# Basic Operations of a Programming Environment

1. **Input**: 
   - Users enter data through various means (keyboard, touch screen, etc.), such as entering flight details (login, dates, seats, destinations) to book a ticket.

2. **Output**: 
   - After processing the input, the system displays a confirmation of the booking on the screen and sends a copy of the tickets and invoice to the user's email and mobile.

3. **Arithmetic**: 
   - The program performs mathematical calculations to update the number of seats booked and records passenger details in the airline's database.

4. **Conditional**: 
   - The program checks specific conditions to determine if a function should be executed based on those conditions.

5. **Looping**: 
   - Tasks are repeated until a certain condition is met, utilizing structures like ==while loops, do-while loops, and for loops.==

