# Designing-a-PCB-that-is-hacker-free
Designing a hacker-resistant Printed Circuit Board (PCB) helps to  prevent unauthorized access or manipulation/ tampering.
Still, a single step won't be enough to stop a determined hacker from breaking into a PCB design.
From PCB design to assembly, there are several strategies that designers can implement to create secure  PCBs that are resistant to PCB hacking.

## Verify that descriptive silkscreens are removed from PCBs
The descriptive silkscreen that displays information relating to debugging are present in the  majority of production PCBs.
Remove debuggable header from production PCBs. 
Removing extraneous information from the PCB assembly and designing process will prevents hackers from getting the information they need.
## Verify that debug paths and traces are depopulated from production PCBs
You can hide the debug paths and traces with the help of a through-hole PCB assembly. 
It will be hard for an attacker to track these debug paths, which are placed between the two layers. 
As it is invisible from the outside, reverse engineering becomes harder. It decreases the potential probing threshold for the hacker.
## Use compotents without leads
Use BGA-packaged MCUs in your circuit design. Use of the BGA package prevents attackers from connecting to the MCUs.
## Remove test points
Test points on a PCB (Printed Circuit Board) are specific locations designated for testing, debugging, and troubleshooting during the manufacturing and assembly process. 
If you cut down the unnecessary test point, it will be harder for the attacker to clone the design. Some test points give direct access to the debug peripherals of the microcontroller.
## Minimize the risk of side channel attack
A side-channel attack (SCA) is a security exploit that attempts to extract secrets from a chip or a system. 
This can be achieved by measuring or analyzing various physical parameters. 
Examples include supply current, execution time, and electromagnetic emission.
Use a microcontroller that emits less electromagnetic radiation.
Seperate the sesitive traces away from the noisey signal lines.
