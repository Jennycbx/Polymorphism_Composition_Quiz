# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
Many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
We can change a method depending on the type of object that is using it. E.g:
   public class Football extends Sport{
        @Override
        public void scorePoints() {
            System.out.println("Sam kicks the ball into the goal");
   
3. What can we use to implement polymorphism in Java?
Inheritance

4. How many 'forms' can an object take when using polymorphism?
As many as it wants

5. Give an example of when you could use polymorphism.
When you have a Parent class and child classes which need to use different versions of the same method.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
When an object is used by another object. E.g. objectA has an objectB. ObjectB cannot exist without ObjectA.

7. When would you use composition? Provide a simple example in Java.
If we have a Fridge class that contains a list of Food using the Food class. The fridge contains instances of food so food cannot exist without the fridge.

8. Give a difference between composition and aggregation?
Composition is 'part of' whereas aggregation 'has a'. E.g. a door is part of a house, and a house has a door.

9. What is/are the advantage(s) of using composition/aggregation?
You can reuse code, if you use composition you can achieve multiple inheritances.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
They are destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
They are still available