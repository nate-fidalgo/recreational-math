# recreational-math
This program is used to search for solutions to any types of diophaintine equation in any number of variables.
The search pattern can be a brute force run thru a given start range to ending range.
Or one can set a custom search pattern where one searches a special pattern of numbers for solutions to the diophaintine equation.
Another really neat feature is that because pythonV3 has bignum libraries builtin to there interperter this program is not restricted to any size ranges to check.
<br>
Very neat program for people that have many computers , cpu/cores or has abilities to setup distributive computation 
This program can act as a way to quickly compute distributively diophaintine equations or explore new patterns of search to find solutions!!!
<br>
Python is a great language and usually comes installed by default on linux/unix systems 
<br>All that is required is diopy.py file and to run it type `python diopy.py` at the terminal then enter the information in the format below
<br>
<pre>
<code>
x^2+z+y = 14  # diophaintine equation to solve
x z y         # variables in the order they first appear left to right in above equation
0 1 2         # start range of the x z y variables
30 400 5000   # end range of the x z y variables
1  10  100    # incremental jumps for the x z y variables
</code>
</pre>
<br>
<code>The incremental jumps mean variables will increment like i+=1 , z+=10 , y+=100 one can make more complex type of jump patterns/searches </code>
<br>

Please note you must write the diophantine equation with all variables on left hand side of equal sign for this program to work!!!
<br>
For example finding all Pythagorean quadruple with each entry under 40 would be inputed as
<br>
<pre>
<code>
a^2+b^2+c^2-d^2 = 0  #not as a^2+b^2+c^2 = d^2
a b c d
1 1 1 1
40 40 40 40
1 1 1 1


</pre>
</code>

<pre>
<code>
List of all Pythagorean quadruples with each entry between 1 and 40

(1, 2, 2, 3)
(1, 4, 8, 9)
(1, 6, 18, 19)
(1, 8, 4, 9)
(1, 8, 32, 33)
(1, 12, 12, 17)
(1, 18, 6, 19)
(1, 18, 30, 35)
(1, 30, 18, 35)
(1, 32, 8, 33)
(2, 1, 2, 3)
(2, 2, 1, 3)
(2, 3, 6, 7)
(2, 4, 4, 6)
(2, 5, 14, 15)
(2, 6, 3, 7)
(2, 6, 9, 11)
(2, 7, 26, 27)
(2, 8, 16, 18)
(2, 9, 6, 11)
(2, 10, 11, 15)
(2, 10, 25, 27)
(2, 11, 10, 15)
(2, 12, 36, 38)
(2, 14, 5, 15)
(2, 14, 23, 27)
(2, 16, 8, 18)
(2, 19, 34, 39)
(2, 23, 14, 27)
(2, 24, 24, 34)
(2, 25, 10, 27)
(2, 26, 7, 27)
(2, 26, 29, 39)
(2, 29, 26, 39)
(2, 34, 19, 39)
(2, 36, 12, 38)
(3, 2, 6, 7)
(3, 4, 12, 13)
(3, 6, 2, 7)
(3, 6, 6, 9)
(3, 6, 22, 23)
(3, 8, 36, 37)
(3, 12, 4, 13)
(3, 12, 24, 27)
(3, 14, 18, 23)
(3, 16, 24, 29)
(3, 18, 14, 23)
(3, 22, 6, 23)
(3, 24, 12, 27)
(3, 24, 16, 29)
(3, 24, 28, 37)
(3, 28, 24, 37)
(3, 36, 8, 37)
(4, 1, 8, 9)
(4, 2, 4, 6)
(4, 3, 12, 13)
(4, 4, 2, 6)
(4, 4, 7, 9)
(4, 5, 20, 21)
(4, 6, 12, 14)
(4, 7, 4, 9)
(4, 7, 32, 33)
(4, 8, 1, 9)
(4, 8, 8, 12)
(4, 8, 19, 21)
(4, 10, 28, 30)
(4, 12, 3, 13)
(4, 12, 6, 14)
(4, 12, 18, 22)
(4, 13, 16, 21)
(4, 16, 13, 21)
(4, 16, 32, 36)
(4, 17, 28, 33)
(4, 18, 12, 22)
(4, 19, 8, 21)
(4, 20, 5, 21)
(4, 20, 22, 30)
(4, 22, 20, 30)
(4, 28, 10, 30)
(4, 28, 17, 33)
(4, 32, 7, 33)
(4, 32, 16, 36)
(5, 2, 14, 15)
(5, 4, 20, 21)
(5, 6, 30, 31)
(5, 10, 10, 15)
(5, 14, 2, 15)
(5, 20, 4, 21)
(5, 30, 6, 31)
(6, 1, 18, 19)
(6, 2, 3, 7)
(6, 2, 9, 11)
(6, 3, 2, 7)
(6, 3, 6, 9)
(6, 3, 22, 23)
(6, 4, 12, 14)
(6, 5, 30, 31)
(6, 6, 3, 9)
(6, 6, 7, 11)
(6, 6, 17, 19)
(6, 7, 6, 11)
(6, 8, 24, 26)
(6, 9, 2, 11)
(6, 9, 18, 21)
(6, 10, 15, 19)
(6, 10, 33, 35)
(6, 12, 4, 14)
(6, 12, 12, 18)
(6, 13, 18, 23)
(6, 14, 27, 31)
(6, 15, 10, 19)
(6, 17, 6, 19)
(6, 17, 30, 35)
(6, 18, 1, 19)
(6, 18, 9, 21)
(6, 18, 13, 23)
(6, 18, 27, 33)
(6, 21, 22, 31)
(6, 22, 3, 23)
(6, 22, 21, 31)
(6, 24, 8, 26)
(6, 27, 14, 31)
(6, 27, 18, 33)
(6, 30, 5, 31)
(6, 30, 17, 35)
(6, 33, 10, 35)
(7, 2, 26, 27)
(7, 4, 4, 9)
(7, 4, 32, 33)
(7, 6, 6, 11)
(7, 14, 14, 21)
(7, 14, 22, 27)
(7, 16, 28, 33)
(7, 22, 14, 27)
(7, 26, 2, 27)
(7, 28, 16, 33)
(7, 32, 4, 33)
(8, 1, 4, 9)
(8, 1, 32, 33)
(8, 2, 16, 18)
(8, 3, 36, 37)
(8, 4, 1, 9)
(8, 4, 8, 12)
(8, 4, 19, 21)
(8, 6, 24, 26)
(8, 8, 4, 12)
(8, 8, 14, 18)
(8, 8, 31, 33)
(8, 9, 12, 17)
(8, 11, 16, 21)
(8, 12, 9, 17)
(8, 12, 24, 28)
(8, 14, 8, 18)
(8, 16, 2, 18)
(8, 16, 11, 21)
(8, 16, 16, 24)
(8, 19, 4, 21)
(8, 20, 25, 33)
(8, 24, 6, 26)
(8, 24, 12, 28)
(8, 24, 27, 37)
(8, 25, 20, 33)
(8, 27, 24, 37)
(8, 31, 8, 33)
(8, 32, 1, 33)
(8, 36, 3, 37)
(9, 2, 6, 11)
(9, 6, 2, 11)
(9, 6, 18, 21)
(9, 8, 12, 17)
(9, 12, 8, 17)
(9, 12, 20, 25)
(9, 12, 36, 39)
(9, 18, 6, 21)
(9, 18, 18, 27)
(9, 20, 12, 25)
(9, 36, 12, 39)
(10, 2, 11, 15)
(10, 2, 25, 27)
(10, 4, 28, 30)
(10, 5, 10, 15)
(10, 6, 15, 19)
(10, 6, 33, 35)
(10, 10, 5, 15)
(10, 10, 23, 27)
(10, 11, 2, 15)
(10, 14, 35, 39)
(10, 15, 6, 19)
(10, 15, 30, 35)
(10, 20, 20, 30)
(10, 23, 10, 27)
(10, 25, 2, 27)
(10, 28, 4, 30)
(10, 30, 15, 35)
(10, 33, 6, 35)
(10, 35, 14, 39)
(11, 2, 10, 15)
(11, 8, 16, 21)
(11, 10, 2, 15)
(11, 12, 24, 29)
(11, 16, 8, 21)
(11, 22, 22, 33)
(11, 24, 12, 29)
(12, 1, 12, 17)
(12, 2, 36, 38)
(12, 3, 4, 13)
(12, 3, 24, 27)
(12, 4, 3, 13)
(12, 4, 6, 14)
(12, 4, 18, 22)
(12, 6, 4, 14)
(12, 6, 12, 18)
(12, 8, 9, 17)
(12, 8, 24, 28)
(12, 9, 8, 17)
(12, 9, 20, 25)
(12, 9, 36, 39)
(12, 11, 24, 29)
(12, 12, 1, 17)
(12, 12, 6, 18)
(12, 12, 14, 22)
(12, 12, 21, 27)
(12, 12, 34, 38)
(12, 14, 12, 22)
(12, 15, 16, 25)
(12, 16, 15, 25)
(12, 16, 21, 29)
(12, 18, 4, 22)
(12, 20, 9, 25)
(12, 20, 30, 38)
(12, 21, 12, 27)
(12, 21, 16, 29)
(12, 21, 28, 37)
(12, 24, 3, 27)
(12, 24, 8, 28)
(12, 24, 11, 29)
(12, 24, 24, 36)
(12, 28, 21, 37)
(12, 30, 20, 38)
(12, 34, 12, 38)
(12, 36, 2, 38)
(12, 36, 9, 39)
(13, 4, 16, 21)
(13, 6, 18, 23)
(13, 14, 34, 39)
(13, 16, 4, 21)
(13, 18, 6, 23)
(13, 26, 26, 39)
(13, 34, 14, 39)
(14, 2, 5, 15)
(14, 2, 23, 27)
(14, 3, 18, 23)
(14, 5, 2, 15)
(14, 6, 27, 31)
(14, 7, 14, 21)
(14, 7, 22, 27)
(14, 8, 8, 18)
(14, 10, 35, 39)
(14, 12, 12, 22)
(14, 13, 34, 39)
(14, 14, 7, 21)
(14, 18, 3, 23)
(14, 18, 21, 31)
(14, 21, 18, 31)
(14, 22, 7, 27)
(14, 22, 29, 39)
(14, 23, 2, 27)
(14, 27, 6, 31)
(14, 29, 22, 39)
(14, 34, 13, 39)
(14, 35, 10, 39)
(15, 6, 10, 19)
(15, 10, 6, 19)
(15, 10, 30, 35)
(15, 12, 16, 25)
(15, 16, 12, 25)
(15, 18, 26, 35)
(15, 26, 18, 35)
(15, 30, 10, 35)
(16, 2, 8, 18)
(16, 3, 24, 29)
(16, 4, 13, 21)
(16, 4, 32, 36)
(16, 7, 28, 33)
(16, 8, 2, 18)
(16, 8, 11, 21)
(16, 8, 16, 24)
(16, 11, 8, 21)
(16, 12, 15, 25)
(16, 12, 21, 29)
(16, 13, 4, 21)
(16, 15, 12, 25)
(16, 16, 8, 24)
(16, 16, 28, 36)
(16, 18, 24, 34)
(16, 21, 12, 29)
(16, 24, 3, 29)
(16, 24, 18, 34)
(16, 28, 7, 33)
(16, 28, 16, 36)
(16, 32, 4, 36)
(17, 4, 28, 33)
(17, 6, 6, 19)
(17, 6, 30, 35)
(17, 20, 20, 33)
(17, 28, 4, 33)
(17, 30, 6, 35)
(18, 1, 6, 19)
(18, 1, 30, 35)
(18, 3, 14, 23)
(18, 4, 12, 22)
(18, 6, 1, 19)
(18, 6, 9, 21)
(18, 6, 13, 23)
(18, 6, 27, 33)
(18, 9, 6, 21)
(18, 9, 18, 27)
(18, 12, 4, 22)
(18, 13, 6, 23)
(18, 14, 3, 23)
(18, 14, 21, 31)
(18, 15, 26, 35)
(18, 16, 24, 34)
(18, 18, 9, 27)
(18, 18, 21, 33)
(18, 21, 14, 31)
(18, 21, 18, 33)
(18, 24, 16, 34)
(18, 26, 15, 35)
(18, 27, 6, 33)
(18, 30, 1, 35)
(19, 2, 34, 39)
(19, 4, 8, 21)
(19, 8, 4, 21)
(19, 22, 26, 39)
(19, 26, 22, 39)
(19, 34, 2, 39)
(20, 4, 5, 21)
(20, 4, 22, 30)
(20, 5, 4, 21)
(20, 8, 25, 33)
(20, 9, 12, 25)
(20, 10, 20, 30)
(20, 12, 9, 25)
(20, 12, 30, 38)
(20, 17, 20, 33)
(20, 20, 10, 30)
(20, 20, 17, 33)
(20, 22, 4, 30)
(20, 25, 8, 33)
(20, 30, 12, 38)
(21, 6, 22, 31)
(21, 12, 12, 27)
(21, 12, 16, 29)
(21, 12, 28, 37)
(21, 14, 18, 31)
(21, 16, 12, 29)
(21, 18, 14, 31)
(21, 18, 18, 33)
(21, 22, 6, 31)
(21, 28, 12, 37)
(22, 3, 6, 23)
(22, 4, 20, 30)
(22, 6, 3, 23)
(22, 6, 21, 31)
(22, 7, 14, 27)
(22, 11, 22, 33)
(22, 14, 7, 27)
(22, 14, 29, 39)
(22, 19, 26, 39)
(22, 20, 4, 30)
(22, 21, 6, 31)
(22, 22, 11, 33)
(22, 26, 19, 39)
(22, 29, 14, 39)
(23, 2, 14, 27)
(23, 10, 10, 27)
(23, 14, 2, 27)
(24, 2, 24, 34)
(24, 3, 12, 27)
(24, 3, 16, 29)
(24, 3, 28, 37)
(24, 6, 8, 26)
(24, 8, 6, 26)
(24, 8, 12, 28)
(24, 8, 27, 37)
(24, 11, 12, 29)
(24, 12, 3, 27)
(24, 12, 8, 28)
(24, 12, 11, 29)
(24, 12, 24, 36)
(24, 16, 3, 29)
(24, 16, 18, 34)
(24, 18, 16, 34)
(24, 24, 2, 34)
(24, 24, 12, 36)
(24, 27, 8, 37)
(24, 28, 3, 37)
(25, 2, 10, 27)
(25, 8, 20, 33)
(25, 10, 2, 27)
(25, 20, 8, 33)
(26, 2, 7, 27)
(26, 2, 29, 39)
(26, 7, 2, 27)
(26, 13, 26, 39)
(26, 15, 18, 35)
(26, 18, 15, 35)
(26, 19, 22, 39)
(26, 22, 19, 39)
(26, 26, 13, 39)
(26, 29, 2, 39)
(27, 6, 14, 31)
(27, 6, 18, 33)
(27, 8, 24, 37)
(27, 14, 6, 31)
(27, 18, 6, 33)
(27, 24, 8, 37)
(28, 3, 24, 37)
(28, 4, 10, 30)
(28, 4, 17, 33)
(28, 7, 16, 33)
(28, 10, 4, 30)
(28, 12, 21, 37)
(28, 16, 7, 33)
(28, 16, 16, 36)
(28, 17, 4, 33)
(28, 21, 12, 37)
(28, 24, 3, 37)
(29, 2, 26, 39)
(29, 14, 22, 39)
(29, 22, 14, 39)
(29, 26, 2, 39)
(30, 1, 18, 35)
(30, 5, 6, 31)
(30, 6, 5, 31)
(30, 6, 17, 35)
(30, 10, 15, 35)
(30, 12, 20, 38)
(30, 15, 10, 35)
(30, 17, 6, 35)
(30, 18, 1, 35)
(30, 20, 12, 38)
(31, 8, 8, 33)
(32, 1, 8, 33)
(32, 4, 7, 33)
(32, 4, 16, 36)
(32, 7, 4, 33)
(32, 8, 1, 33)
(32, 16, 4, 36)
(33, 6, 10, 35)
(33, 10, 6, 35)
(34, 2, 19, 39)
(34, 12, 12, 38)
(34, 13, 14, 39)
(34, 14, 13, 39)
(34, 19, 2, 39)
(35, 10, 14, 39)
(35, 14, 10, 39)
(36, 2, 12, 38)
(36, 3, 8, 37)
(36, 8, 3, 37)
(36, 9, 12, 39)
(36, 12, 2, 38)
(36, 12, 9, 39)
</pre>
</code>

