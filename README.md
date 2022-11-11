# arduino-led-matrix-pattern-maker
google spreadsheet/excel file that help you make patterns on your arduino 8x8 led matrix. comes with source code and wiring diagram for the led matrix
In the excel file to make your pattern replace a 0 on the grid with a 1 and it will turn the square red. make whatever pattern you want chaning the zeros to ones
on the right, there is 3 collums. the collum collum, the decimal collum and the hex collum. for this next part i reccomend using the hex code
on the "smily" arduino ide file, locate lines 154-161. you will see something that looks like
maxSingle(1,0x8)
maxSingle etc.
now, to import your pattern from the excel sheet. in the col collum, there are numbers listed 1-8. you will also see on the maxSingle() lines of code inside the brackets they each start with a number from 1-8. these are your collums.
in the brackets/parenthesis replace the number furthest to the right with the number in the corresponding line (1-8) on the spreadsheet witht the number in the "hex" collum. keep the 1,0x the same.
do this for the rest of the line (1-8 ) and make ur pattern.
if you have any questions or have no idea what any of thsi means, email me demijohnlees@gmail.com
