## Week 12, Day 2 homework - Polymorphism &amp; Composition Homework - Quiz

### Polymorphism

#### 1. What does the ___word___ 'polymorphism' mean?
* It means "many forms".

#### 2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
* This is when class objects have their own class type but can also inherite another type from a super class (if they are a child of that class) or they can use the class type of an interface which they implement.
* e.g. public class Student extends Person implements IWalk (This example shows a 'Student' class which could also be used as a 'Person' class and an 'IWalk' class).

#### 3. What can we use to implement polymorphism in Java?
* We can use inheritance and interfaces to implement polymorphism in Java

#### 4. How many 'forms' can an object take when using polymorphism?
* It can have numerous forms, depending on how many interfaces it implements, and if it inherits from a super class.

#### 5. Give an example of when you could use polymorphism.
* This could be used in the instance of a hotel, where say a Bedroom inherits from a super class of Room but also implements an interface of IMakeBooking. So Bedroom object could have a type of 'Bedroom', 'Room' or 'IMakeBooking'.


### Composition and Aggregation

#### 6. What do we mean by 'composition' in reference to object-oriented programming?
* This is where an object 'HAS' another object as part of its make-up. So, an object can comprise of other objects.

#### 7. When would you use composition? Provide a simple example in Java.
* e.g. public class Car {
    public Car(Engine engine, Tyre tyre, Battery battery)
    this.engine = engine;
    this.tyre = tyre;
    this.battery = battery;
}
* In this example a Car comprises of an Engine, Tyres and a battery, all of which are their own classes.

#### 8. Give a difference between composition and aggregation?
* Composition creates a new instance of an object within a class, where as aggregation passes in an object, as an arguement, created elsewhere to make up the composition of an object.

#### 9. What is/are the advantage(s) of using composition/aggregation?
* Composition/aggregation means an object is only composed of the thinbgs it really needs and doesn't inherit things it doesn't need or won't use. 

#### 10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
* The other objects are destroyed along with the object inwhich they make-up.

#### 11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
* The other objects remain available elsewhere, even when the object that is composed of them is destroyed.
