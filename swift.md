# Swift

## August 18, 2018

### 4:20 PM

Got to kick off Swift with the book Learning Swift, 3rd Edition from O'Reilly. Got to read up about the core language itself and it resembles Kotlin quite a bit. If there's one thing I especially found useful, it was the fact that you could make mutable or immutable collection simply by using `var` or `let`.

### 9:49 PM

Couldn't help but have another go at the language and learned about OOP in Swift. Something I found amazing was the fact that you could extend a class to conform to a protocol. That kinda blew my mind. It was also amusing to see that you could also declare your own operations on classes.

### 11:11 PM

Had a go all the way to the Swift Package Manager. I'll read up the rest of the chapter tomorrow since this looks rather long.

## August 19, 2018

### 10:42 AM

Finished up the third chapter and read about the Swift Package Manager. I did stumble on a few problems on my machine though. It might be that there have been some breaking changes made between the publication of the book.

### 11:01 AM

Got to setup the basic project and followed some of the modifications for Selfiegram. Time to build a very original app.

## August 21, 2018

### 1:56 PM

So today, I got to build up the model component of the Selfiegram app. In this I've pretty much created an image, saved it to disk, encoded and decoded JSON from local storage and had unit tests to boot.

## August 22, 2018

### 9:31 PM

Got to add the ability to view available selfies in a list. It displays how long ago a selfie has been taken and a preview. As of now, it's only showing the selfies that have been left out by running my tests.

## August 29, 2018

### 9:45 PM

After all the setbacks and traveling and settling down here in Sweden, I got back up again and started coding. This time, I added the ability to delete items in the list and add new selfies using the camera.

## August 30, 2018

### 7:28 AM

Added the ability to view individual selfies in Selfiegram. I'll work on editing a bit later.

### 11:09 AM

Finished up the basic functionality of the app. So I could now add new selfies, edit their titles, and then delete them. Up next will be adding metadata for location.

## August 31, 2018

### 9:41 AM

Today I got to work on the location library of iOS. This allowed me to add location data to Selfiegram's images and show a map. The map could be tapped and will open the Maps app to show you the general area where a selfie has been taken.

## September 1, 2018

### 10:33 PM

This time added a simple settings page to the Selfiegram app and added the ability to toggle on and off the ability to add location to selfies.

At this point, I think I've learned enough Swift to take on "Classic Computer Science Problems in Swift". And so with that, it time to close Learning Swift.

## September 2, 2018

### 9:13 PM

Today I shift my attention to "Classic Computer Science Problems in Swift". This book is the reason I started out Swift actually. So today I did the fibonacci sequence in a couple of ways. One that was absolutely broken (infinite recursion), one that worked through recursion, one with memoization, and one iteratively. Of course, this lead to some extra reading.

I also got to do compression for the first time. The example in the book takes a sequence of nucleotides that represent DNA in a String format and converted into a smaller binary form.

## September 3, 2018

### 9:50 AM

Today I got to work on creating encryption, solving pi, and solving the Towers of Hanoi. Though admittedly, I'm still confused by the Towers of Hanoi and will require some extra searching around.

## September 4, 2018

### 2:07 PM

Finally got to understand the Towers of Hanoi and it's actually quite amazing once you get it. I've also done the exercises listed for the first chapter including a version of fibonacci that does it iteratively and with memoization, a wrapper for the BitVector class, a Tower of Hanoi solver, and encrypting an image.

## September 6, 2018

### 2:24 PM

Did the DNA search section of Chapter 2, which is all about searching. I've known about linear search and binary search for a while now but writing them out makes for a good exercise.