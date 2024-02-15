#### DiceCTF
started zshfuck, it's a bash file which runs a shell in a shell!
read the code and with gpt got some clue how it works
it will take only 6 characters in and some characters are banned
a senior got a lead that `find .` gives us some interesting files
we got a few files which may have contained the file (later found out that this is exactly where the flag was 👍 😃 👍)
had no clue how to access so decided to move on from this (big mistake, shouldn't have) 
thought of `/*/*/*/*` but `*` was banned (big mistake, should've thought more)
went around the whole around of making a nano file in shell and then storing binary in them to run them and some bulshit (didn't work)(didn't had permission)
grepped all files in bin to get some clue, didn't work!
thought of making a script to run all binary with 6 or less than 6 characters and what not!
and something more which i can't remember. long story short wasn't able to solve

looked up a japanese write up. which used something called glob which works like if this used `[^a]` then all file which don't have a will pop up!
easy!
