Polymorphism & Composition Homework - Quiz

Polymorphism

What does the word 'polymorphism' mean?

A: Multiple forms

What does it mean when we apply polymorphism to OO design? Give a simple Java example.

A: An object could take the form or behaviours of another class. Example, an object from a child class could inherit the behaviours of the parent class and also be used in its place. 

What can we use to implement polymorphism in Java?

A: Inheritance - Abstract Classes - and interfaces.

How many 'forms' can an object take when using polymorphism?

A: As many as it can by using inheritance or X number of interfaces. 

Give an example of when you could use polymorphism.

A: Car dealership example, it would contain a Stock of cars of diferent types. These car objects could be from child classes of a vehicle super class, so the stock could be an ArrayList<Vehicle> in that way any car object could be passed.

Composition and Aggregation

What do we mean by 'composition' in reference to object-oriented programming?

A: When an object is passed as an instance variable of another class. the contained object cannot exist without the existence of that class object.

When would you use composition? Provide a simple example in Java.

A:

Give a difference between composition and aggregation?

A:In Composition, composed objects cannot exist without the other object. This type of restriction does not exist in Aggregations. In Aggregation, the existence of a composed object is optional. In Aggregation, the child object can exist beyond the life cycle of its parent whereas in Composition the child object cannot exist beyond the life cycle of its parent.

What is/are the advantage(s) of using composition/aggregation?

A:In most cases "HAS-A" relationship is more semantically correct than "IS-A" relationship between classes.

Composition is more flexible and robust than inheritance.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?

A: They are also destroyed.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

A: Nothing