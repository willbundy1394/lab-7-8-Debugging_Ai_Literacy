# debug_log.md
# Author: Will  Bundy

## Bug 1
Error type: Key Error 'amount'
File + line: week8_buggy.py, line 21 (calling get_total() on line 12)
What the error means: Python attempted to look up a dictionary key that doesn't exist
What I told the duck: I read through the loop and saw it was looking for 'amount' in each record but there seems to be a typo
What I tried: I tried to use the debug print found in part 2
How I fixed it: I found that there was a typo in line 4 ("'amout'" , instead of "'amount'") then I fixed the spelling and deleted the DEBUG print

## Bug 2
Error type: TypeError '>' not supported betwen instances of 'int' and 'str'
File + line: week8_buggy.py, line 23 (calling is_over_limit on line 16 return amount > '1000')
What the error means: Python cannot compare an integer and a string using the greater than symbol.
How I fixed it: I removed the '' from 1000 and ran it again. the string needed to become an integer to run correctly.

## After Fixing Both Bugs
Final output: 5150.00 across 3 records True
Did pytest pass? Yes

## AI Literacy Reflection
Did I use AI? No
If yes -- exact prompt I used: N/A
What AI explained: I did not use Ai this week to help me because I felt as if trial and error would have helped me understand the concepts better. I also had help from my team and we figured out the issues fairly quickly. The Lab also laid out step by step instructions that were very easy to follow. 
What I changed myself: What I changed myself was really just a trial an error of running the code and seeing what was actually happening. What I fixed today was 2 bugs which were a TypeError and KeyError. I corrected a typo, changed a string into an integer and deleted the DEBUG print
Can I explain every fixed line? Yes

## What I learned
What I leanred this week was that a DEBUG print helps indicate errors I often times would overlook. This assignment I spent a lot of time using trial and error and kind of staring at the code not know what was wrong and running it to see whats actually wrong. Instead of playing detective the DEBUG print helped me find the issue and understand the error that kept popping up. 
