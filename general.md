# Random Stuff That I Couldn't Figure Out Where To Put

## July 21, 2018

### 5:47 AM

For some reason, I decided to do a quick stint on the book Seven Languages in Seven Weeks. I think I'll do this book once I'm done with The Quick Python Book.

### 12:11 PM

I was working on Brilliant.org's Mathematical Fundamentals and got to the section on Patterns & Variables. The last thing I expected was to suddenly learn something that could be tied to Computer Science. For the most part, describing patterns. There are two ways of doing it, recursive – where you describe a pattern going forward, and explicit – where given the figure number, you could generate the answer right away. A horribly simple example would be an alternating pattern of `X` and `O` like this:

```
X O X O X O
```

You could of course, describe this in two ways.

A. It starts with `X`, and then alternates between `O` and `X`. (Recursive)

B. If `n` is the position being asked, if `n` is odd the value is `X` else, it's `O`. (Exact)

You could imagine that there are two ways of implementing this in a code. Recursively, you'll have to hold the previous value to generate the next. You'll then have an algorithm that's `O(n)`. But if you do it by computing the value for `n % 2 == 0`, you'll have a `O(1)` algorithm. Though for the given example, solving it recursively probably never crossed your mind when you code but you get the idea.