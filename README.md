## 0x11. C - printf

 

### printf
 is the C language function to do format-ted printing. The same function is also available inPERL. This paper explains how
 printf
 works, andhow to design the proper formatting speciﬁcation forany occasion.
In the most simple case,
 printf takes one argument:a string of characters to be printed. This string iscomposed of characters, each of which is printed ex-actly as it appears. 
 So printf("xyz");
 would sim-ply print an x, then a y, and ﬁnally a z. This is notexactly “formatted” printing, but it is still the basisof what printf does.
