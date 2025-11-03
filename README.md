It was a hot and boring summer in Madrid. Since I studied in High School the basics of circuits, I had wanted to apply that knowledge to build something real.
Somehow, I found that it was the right moment to dust off my notes and start a project.
So I downloaded a software to simulate circuits. I choose one called 'Digital', developed by Helmut Neemann (you can download it at https://github.com/hneemann/Digital).

I designed memory of 64 'bytes', where this 'byte' was made out of 6 bits instead of 8 (I was bored but the summertime was finite). So each byte can store a number between 0 and 63.
This memory can be accessed to be read and written. To get the content of a byte, type its direction (in 'pointed direction'). And to modify it, type the new value in 'Input to write' and press the button C.

This was made using only: basic logic gates, demultiplexors and Flip-Flop RS.
The main file is memoriaW64.dig, while 2chooser64.dig and comparador64.dig are auxiliary functions/circuits that I implemented separatedly in order to make the desing simpler.

Please note that I have no degree in Computer Science or anything related to circuit design, so I expect my design to be highly ineficient. But I had a really fun time making this little approach to the world of circuit design.
