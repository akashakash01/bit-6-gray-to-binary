# bit-6-gray-to-binary
Aim: To convert a 6-bit Gray code to a binary code using Verilog.

Equipment required:

1. A computer with a Verilog compiler.
2. A text editor or IDE (Integrated Development Environment) for writing and editing the Verilog code.

Procedure:

1. Open a text editor or IDE and create a new file.

2. Write the Verilog code for the 6-bit Gray to binary converter.

3. The code should include a module declaration, input and output ports for the Gray code and binary code, and the logic for converting the Gray code to binary.

4. Compile the code using a Verilog compiler.
5. Simulate the code to ensure it is functioning as expected.
6. Synthesize the code if it is functional and implement it on a device (FPGA or ASIC) if needed.
7. Note: The actual code implementation is not provided as it can be complex and depend on the design and requirement. 1
    
PROGRAM:
   Design and simulate 6 bit gray to binary converter using Verilog. It has 5 binary because of 6 bit converter input [5:0] gray
      output [5:0] binary
      
      DEVELOPED BY : AKASH R.
      
      REGISTER NUMBER : 22008463.
      
      
      module bit5 (gray, binary);
    input [5:0] gray;
    output [5:0] binary;

    assign binary = gray ^ (gray>>1);

endmodule
      
      
      
      
TIMING DIAGRAM :
   ![WhatsApp Image 2023-01-28 at 20 45 45](https://user-images.githubusercontent.com/123085535/215276180-4707f6e7-5838-4438-8734-977646eb260c.jpg)


TRUTH TABLE:


![WhatsApp Image 2023-01-28 at 21 21 25](https://user-images.githubusercontent.com/123085535/215276260-79d2eac2-a04a-46a4-ac52-03ec5cd2472f.jpg)


RTL realization:

![WhatsApp Image 2023-01-28 at 21 32 52](https://user-images.githubusercontent.com/123085535/215276566-2f52e492-91fc-436b-a600-d12846e94510.jpg)





RESULT:
   Thus the bit 6 gray to binary converter using verilog are designed and truth tables is verified using quatrus software.

    
