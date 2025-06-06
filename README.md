# Calculator
vim bas.y   
vim bas.l  
yacc –d bas.y                   # create y.tab.h, y.tab.c 
lex bas.l                       # create lex.yy.c 
cc lex.yy.c y.tab.c –o bas.exe  # compile/link   
./bas.exe  

![image](https://github.com/user-attachments/assets/fd1ed342-4323-45e1-a137-e15d4e185c2e)
