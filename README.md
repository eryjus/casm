# Century Assembler (2-pass version)

I am working from the Assemblers and Loaders manual available on the internet (copy available [here](http://www.davidsalomon.name/assem.advertis/asl.pdf)).  In this there are several exercises that work toward building a functioning assembler (well, actually 2 functioning assemblers -- a 1-pass assembler and a 2-pass assembler),

This project focuses in on the 2-pass assembler.

There will be several iterations of this project as we develop it out following this guide.  This version will be extended to be used as a full-fledged assembler for at least x86 and likely for arm as well.

As a result (based on the book's assignment) I will be starting with M (Memory size) of 256 (requiring 8 bits to address) and N (Word size) of 8 (or a 8-bit word).  This, then, will leave 8 bits for the opcode, which is more than enough, and 8 bits for an optional operand.  As a result, instructions are variable in length.

