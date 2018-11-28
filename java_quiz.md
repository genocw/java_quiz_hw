Polymorphism & Composition Homework - Quiz

Polymorphism
What does the word 'polymorphism' mean?
THE ABILITY OF AN OBJECT TO TAKE ON MANY FORMS (AN INSTANCE OF MULTIPLE TYPES).

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
IF WE HAVE A CLASS Athlete, WHICH HAS CHILD CLASSES Swimmer AND Runner. Runner IMPLEMENTS THE IRun INTERFACE, ALONG WITH OTHER NON-ATHLETE CLASSES THAT HAVE THE ABILITY TO RUN. A Runner THEREFOR CAN BE AN INSTANCE OF Athlete, Runner OR IRun.

What can we use to implement polymorphism in Java?
INHERITANCE AND INTERFACES

How many 'forms' can an object take when using polymorphism?
INFINITE

Give an example of when you could use polymorphism.
PARENT CLASS Animal.
CHILD CLASSES Bird, Mammal, Reptile.
SEPERATE CLASS Plane.
INTERFACE IFly.
IN A LIST OF THINGS THAT CAN FLY, eg. AN ARRAYLIST EXPECTING IFly OBJECTS, BOTH A PLANE AND A BIRD COULD EXISIT IN THE SAME LIST, DESPITE BEING FROM UNRELATED CLASSES, BECAUSE THEY CAN BOTH BE AN INSTANCE OF IFly.

Composition
What do we mean by 'composition' in reference to object-oriented programming?


When would you use composition? Provide a simple example in Java.


What is/are the advantage(s) of using composition?


What happens to the behaviours when the object composed of them is destroyed?
