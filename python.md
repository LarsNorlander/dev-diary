# Python

## July 11, 2018

### 7:53 PM

I've decided today that after forever, I'd pick up and learn Python. Actually, I want to learn for a couple of things. I want to use the language as my "Scripting Knife". Basically for quickly whipping up code for doing just about anything. That, and I'd like to use it as my language of choice for stuff like CodeSignal or LeetCode. I'm starting out with the third edition of The Quick Python Book which released last May. I'm looking forward to this.

## July 12, 2018

### 7:56 AM

I've finished reading up on the first chapter of The Quick Python Book and now, I'm a lot more convinced and I look forward to reading the rest of it. But for now, time for work.

## July 13, 2018

### 8:56 PM

Today I got to learn a whole bunch about Python's list data structure and the things you could do with it. I think today's biggest moment of amusement, is how you could take say, the last three elements of a list and put it at the beginning in one line.

```py
x = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
x[:-3],x[-3:] = x[-3:],x[:-3]
```

## July 14, 2018

### 8:34 AM

Finished reading about tuples and sets! So tuples are basically immutable lists and sets are basically the mathematical set. One important difference I guess between a set and a list are their lookup times. If I remember correctly, a list's lookup time is linear while a set's is constant. This makes a difference if all you care about is membership in a collection. I also found it amusing that the bitwise operators like `|`, `&`, and `^` work for doing set operations; it feels like it's intuitive too.

### 11:29 AM

This time, I got to read the chapters on strings and dictionaries. The more I read about Python, the more I get excited to try it out and code a bunch of stuff. I've already tried a few problems on hacker rank and it feels so nice being able to use the language to solve problems. It's nice that I could solve them pretty quickly too!

### 4:20 PM

Control flow, functions, generators, and decorators. There's a bunch of stuff in Python for doing a bunch of things huh? It's surprising how many shortcuts the language has for doing different things and now I'm seeing how I may want to use the language. I intend on using it for programming challenges but I'll just read the rest of the book and see what else I could learn. I might use Python for other things too.

## July 15, 2018

### 8:41 AM

So at this point, I've read the chapters "Modules and scoping rules" and "Python programs". This is gonna come in handy I suppose when I want to write some scripts to do stuff. What that stuff is gonna be I have no idea at the moment. But today I also decided to try using PyCharm Edu and it was a little too fun. After importing my custom IntelliJ IDEA settings, Python just got a little more fun again.

### 6:49 PM

I decided I know enough Python to go ahead and solve some problems. So I first go to CodeSignal and get my hopes crushed as I struggle to solve some problems. Luckily, it seems HackerRank has a few problems that are more fitting for my level. I pretty much ended up doing 29 practice challenges under Problem Solving and Python. It was honestly really hard to tear myself away from solving these problems and I constantly found myself saying, "Just one more and I'll log this." I guess that's not such a bad thing.

## July 16, 2018

### 6:16 PM

Continued studying up a bit this time on using the file system in Python. I also tried scanning a few books to see where my level is at and where I could move next. It seems I still need to learn a bunch. But, there is one book that seems interesting. Automate the Boring Stuff with Python might be an interesting next step and provide a few practice projects.

## July 17, 2018

### 7:55 AM

Even more on Python and file systems. This time around, how you could manipulate paths like joining them, splitting, getting the name or base and what not.

### 5:59 PM

Finally got to finish the chapter on "Using the filesystem" and have a good idea of what Python could do with regards to manipulating paths, editing filenames, removing them, the standard filesystem stuff. Tomorrow I'll read up about "Reading and writing files". Everyday, I get a little more comfortable with Python and a little more productive.

## July 18, 2018

### 7:57 AM

Read about reading and writing to files and the different modes and functions available to me. I'm a little surprised though at how you could easily override standard in and out to write or read to a file instead. 

### 7:54 PM

Finished studying up "Reading and writing files" from the book. The features here that really surprised me was the ability to pickle objects and the shelf module. I feel like these would be some rather ridiculously useful things for a bunch of simple things. Pickling though has it's drawbacks and shelves don't exactly work well with concurrency. But aside from that, their pretty awesome!

## July 19, 2018

### 7:53 AM

Read the entire chapter on "Exceptions" and now I've got a good idea of how it works in Python. I've encountered exceptions before in other languages like Java but it seems the way it's done in Python is a little different. Context managers are also a nice feature to make stuff concise. 

### 6:12 PM

Got to read about the starting of OOP in Python, how to declare classes, instance fields and the `__init__` method. I'll continue studying this tomorrow.

## July 20, 2018

### 7:55 AM

Read about class variables, static and class methods and some basic inheritance. Something I never thought of though while learning OOP in other languages was that the instance is always passed into instance methods. It's just that in Python it's explicit and in languages like Java, it's implicit and uses the keyword `this`.

## July 21, 2018

### 7:23 AM

Properties, private class members, and multiple inheritance.  Truthfully, I find the double underscores to mark things as private a little strange. Sure, you'll know right away what's private but... well, I guess I'm just not used to it. The way multiple inheritance works seems to be simple enough, though personally, coming from a Java background, I prefer to build up my objects with composition. In terms of experience, I don't remember the last time I did inheritance. Sure, Interfaces, but I could probably count the number of times I've inherited from a concrete class.

### 2:03 PM

Finished the chapter on Regular Expressions. I've used regular expressions a few times in Java and knowing how to use it and how not to trip may be useful in the future. I'm yet to see how I'll apply it.

## July 22, 2018

### 3:04 PM

Finished reading the chapter "Data types as objects" and got to learn about special methods and how Python handles types. 🦆 Honestly, Duck Typing feels really strange if you come from something like Java where everything is defined. The idea of creating your own list without implementing a list interface feels weird. I mean, I guess you could prevent making mistakes by doing TDD and doing it right, but I think I prefer Java's style for now. We'll see. 😂

## July 23, 2018

### 7:56 AM

Got to finish the chapter "Packages" in The Quick Python Book and got to understand how packages work and what constitutes to a Python package. Also, apparently in Python, a flat structure is better than a nested one.

### 6:40 PM

Finished the chapter on "Using Python libraries" and finally got to understand how Python handles external libraries and how to install them. Something useful I also learned was the virtual environment. I've been seeing it in PyCharm but never new what it was supposed to be. Now I've figured it out.

## October 21, 2018

### 8:59 PM

Well, now that I work with Python in my work, I might as well start learning the best practices. For this, I've started with the quite awesome book, [The Hitchhiker's Guide to Python](https://www.safaribooksonline.com/library/view/the-hitchhikers-guide/9781491933213/). So far I've gotten to the section talking about code conventions in Python and how to write proper Python code.

## October 22, 2018

### 8:08 PM

Today I continued on reading The Hitchhiker's Guide to Python. Got to read about some of the "gatchas" of the language for new comers. Turns out there's a tiny section on TDD, which is nice. That way I could finally be confident on my Python code. Next up would be learning some Django since I need to learn about it for work.