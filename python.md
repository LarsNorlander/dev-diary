# Python

## July 11, 2018

### 7:53 PM

I've decided today that after forever, I'd pick up and learn Python. Actually, I want to learn for a couple of things.
I want to use the language as my "Scripting Knife". Basically for quickly whipping up code for doing just about 
anything. That, and I'd like to use it as my language of choice for stuff like CodeSignal or LeetCode. I'm starting out
with the third edition of The Quick Python Book which released last May. I'm looking forward to this.

## July 12, 2018

### 7:56 AM

I've finished reading up on the first chapter of The Quick Python Book and now, I'm a lot more convinced and I look
forward to reading the rest of it. But for now, time for work.

## July 13, 2018

### 8:56 PM

Today I got to learn a whole bunch about Python's list data structure and the things you could do with it. I think today's biggest moment of amusement, is how you could take say, the last three elements of a list and put it at the beginning in one line.

```py
x = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
x[:-3],x[-3:] = x[-3:],x[:-3]
```