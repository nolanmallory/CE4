CE4
===

###Simple Memory Manipulation

The objective was to write a program that stores the value $9 in location $B0, $8 in $C4 and $B in $CB. The Target program end was $11 which was met.

![alt text][logo1]

[logo1]: /mempic.JPG

This program was validated by running it step by step. As each step was ran, the accumulator held the values of 9, 8, and B in that order. As the loop was executed it would repeat the pattern over and over again.

###Mathematics

The objective was to write a program that retrieves a value from location $B0, doubles it, and subtracts 4.  The result was outputted to Port 2.  The Target program end was $0C which was met.

![alt text][logo2]

[logo2]: /mathpic.JPG

This program was validated by choosing a value to input. The value of 2 was choosen which was loaded into the accumulator. This value was then doubled by adding the value to itself. This number,4, was then loaded into the accumulator. After that, a value of 4 was subtracted from the existing 4 in the accumulator. In order to do this, the two's complement was used, C. The final value in the accumulator was 2 as expected.

###Loops

The objective was to write a program that starts by reading what is on Input Port 3 and then displaying that on Output Port 0.  One less than that is then displayed on Port 1 and one less than what is on Port 1 is displayed on Port 2.  The program then decremented what was on Port 0, then decremented what was on Port 1, then decremented what was on Port 2.  This process is continued in an infinite loop. The Target program end was $10 which was met.

![alt text][logo]

[logo]: /loopspic.JPG

This program was validated by giving the input port a value. In this case the Input Port 3 contained a ‘2’ , Ports 0-2 showed 2,1,0, respectively.  The 2, 1, 0  then changed to 1,0,F, then 0, F, E, and so on as stated in the computer excersise directions.
