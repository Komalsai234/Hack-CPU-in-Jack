
# Implementation of Hack CPU in Jack

In this project of implementing the Hack CPU in jack, all the basic gates like And, Or, Not, Xor are build using the nand gate. Using these basic 
gates we build the remaining gates which are essential for building Hack CPU.

   

## Basic gates

- NAND gate
- AND gate
- Or gate
- NOT gate
- XOR hate


## Other gates

- Half Adder
- Full Adder
- 16-bit Adder
- 16-bit AND gate
- 16-bit MUX gate
- 16-bit NOT gate
- 16-bit Incrementor gate
## Important Implementation
- toBinary 
   
      This implementation allows us to convert a positive number to its respective
      16-bit binary representation. This conversion is done in the same way we do 
      generally that is dividing the given number with 2 and mention its remainders 
      until zero, by writing these remainder from down to up we get the 16-bit binary 
      representation of the given.)

- Binaryall

      This implementation of “toBinaryall” allows us to convert a both positive and negative 
      integers to its respective 16-bit binary representation.
    
      In the same way for positive numbers, we will use above implementation ‘toBinary. For 
      negative numbers, 2’s complement is used to find the binary representation. For that 
      we will take the number convert into 16-bit representation and negate all the bits 
      and add 1 to LSB.

- toBinary8  

      This implementation of “to Binary8” allows us to convert a positive integer to its 
      respective 8-bit binary representation. This conversion is done in the same way we 
      do generally that is dividing the given number with 2 and mention its remainders 
      until zero, by writing these remainder from down to up we give the 8-bit binary 
      representation of the given.

- toDecimal

      This implementation of “to Decimal” allows us to convert 16-bit binary representation to it 
      corresponding decimal value.This conversion can be done in a simple way by adding the product 
      of each binary digit with its weight (which is of form – binary digit × 2 raised to the power 
      of the position of the digit). Finally, the given 16-bit representation is converted into decimal.

- toDecimal8

      This implementation of “to Decimal8” allows us to convert an integer to its respective 8-bit binary
      representation.

      This conversion can be done in a simple way by adding the product of each binary digit with its weight 
      (which is of form – binary digit × 2 raised to the power of the position of the digit). Finally, the 
      given 8-bit representation is converted into decimal.





## Important Chips

- Data Flip-Flop(DFF)
- 16-bit Data Flip-Flop
- Register
- 16-bit Register
- Arithmetic Logic Unit (ALU)
- Pogram Counter (PC)
## Hack CPU

By combining all the above gates we implemented,the Hack CPU is build.

All files we implemented in jack is compiled into the vm files using the 
VM Translator. And then load this vm file 
into the VM Emulator and get the output.
## Screenshots

![App Screenshot](https://github.com/Komalsai234/Nand2tetris/blob/main/Screenshot%20(1810).png?raw=true)

![App Screenshot](https://github.com/Komalsai234/Nand2tetris/blob/main/Screenshot%20(1811).png?raw=true)



