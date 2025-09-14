# Pipeline-implementation-of-ALU
This is a Verilog implementation of a 4-stage pipelined Arithmetic Logic Unit (ALU). The design is notable for its use of a two-phase, non-overlapping clocking scheme to safely pass data between pipeline stages, effectively preventing race conditions.
<img width="1536" height="672" alt="Gemini_Generated_Image_2oy99b2oy99b2oy9" src="https://github.com/user-attachments/assets/d93aeb7f-d4a0-4618-9972-f8b6901f570e" />

### The following ALU Operation is performed:
<img width="1024" height="329" alt="image" src="https://github.com/user-attachments/assets/730ee48a-491d-4ccc-8ccf-d534ef6d7cf9" />

## Two Phase  Non-Overlaping Clock
<img width="1024" height="256" alt="image" src="https://github.com/user-attachments/assets/c66cc8d2-b929-4b37-942d-d63b84898ec8" />
This is Important to provide clocking like this because if we not do like that then it might corrupt the output of next stage because of race condition.



