# CSN-221-SimpleRISC
Designed a SimpleRISC processor on Logisim. (Individual Contribution: designed the Arithmetic Logical Unit for the processor.)

• All the SimpleRISC instructions which have been discussed in lectures are used.
• It contains 21 instructions.
• The complete processor is divided into 5 stages.
• The processor is made using Logisim.
• We can run any program using this processor having SimpleRISC instructions to give us the correct outputs.
• We have added a display feature, which displays the contents of any register.

  We used a basic approach of dividing the processing into various stages and then design each stage. We use multiplexers where alternate data sources are used for different instructions
The instructions are executed systematically going through each stage. Every stage performs its pre-determined tasks and thus the whole task is completed separately.
Various Stages are : 
1. CONTROL UNIT
2. MEMORY UNIT
3. BRANCH UNIT
4. ARITHMETIC LOGICAL UNIT
5. FLAGS UNIT
6. IMMEDIATE VALUE
7. REGISTER FILES
