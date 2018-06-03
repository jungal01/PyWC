# PyWC

This program is designed to mimic the wc command in a bash terminal on linux. To run this program, ensure that python 3 is 
installed on your machine. There are four types of commands that this program accepts. <code>-l</code>, counts the
number of lines, and <code>-w</code>, counts the words. Both <code>-c</code> and <code>-m</code> count the characters of each file. This program will also
function without these commands, displaying the count of lines, words, and characters. The commands can also added together and run in tandem. To properly run this command, enter into the
terminal <br> <code>pywc -c filename</code> or <code>cat filename | pywc -l</code>.
