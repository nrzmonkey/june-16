6/16/2018 Homework

/******** Car application **********/

This homework will serve the purpose of reviewing a variety of object
oriented java concepts that we have come across over the course
of this year's class, along with some new challenges.

Abstract:
Race Cars.

Building on what we have accomplished building our car class, we are
going to build an application that will race various cars across distances.

If you need to download eclipse for this project, this can be done here:
https://www.eclipse.org/downloads/


A car will be defined as:
1. name
3. Engine (another class)
4. Fuel capacity

An engine will need:
1. name
2. fuel efficiency (miles per gallon)
4. top speed

put both the "Car" and the "Engine" class in a new package that you
create called "cars"

Once you have your car and engine classes, we will need a new class
called "Race"

The race class will have a 'main' method (the special method we talked
about in class that is a "runnable" java method (meaning that you can run the class in eclipse)
The main method in the race-track will construct 3 cars, with 3 different engines. 

We will also need a "RaceTrack" class. This class will contain a public static method called "race"
that takes two cars and an integer (the length of the track in miles). The "race" method will determine
which car "wins" the race by calculating which car has a faster speed. if the length of the track is too long
for the car to finish with it's fuel capacity, that car will lose the race. 

the main method in "Race" will take the 3 cars you've constructed and race them against each other, while
using the static method "System.out.println" to let the user know the winner of each race.

Remember these concepts when creating your program:

<b>Main method</b>: a special type of method that the java virtual machine understands how to "run". This method
can be run directly from within eclipse by pressing the green play button.

<b>Composition</b>: The idea we talked about in class that denotes encapsulation of one type of data within 
another (i.e. a car has an engine). "Has A" relationships are almost always composition relationships.

<b>Static Methods</b>: Static methods were discussed in our spring class. Static methods do not require an 
instance of an class in order to call them. They can be invoked directly from the context of the class like this:
Class.method(arg1, arg2, arg3); An example of a static method would be something like Math.abs((2-3)); which 
would return the absolute value of 2-3 (which is 1). 
