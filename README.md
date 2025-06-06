# Calculator
vim bas.y
vim bas.l
yacc -d bas.y
lex bas.l
cc lex.yy.c y.tab.c -o bas.exe
./bas.exe
