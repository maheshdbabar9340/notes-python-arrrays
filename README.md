** Python **

1.How to print a list without brackets in Python
      
https://www.kite.com/python/answers/how-to-print-a-list-without-brackets-in-python#:~:text=Use%20*%20to%20print%20a%20list,set%20sep%20to%20%22%2C%20%22%20.


2.Handling EOFError Exception in Python

https://www.geeksforgeeks.org/handling-eoferror-exception-in-python/

3.Python List reverse()

https://www.programiz.com/python-programming/methods/list/reverse

** Java **

Java Type Casting
Type casting is when you assign a value of one primitive data type to another type.

In Java, there are two types of casting:

Widening Casting (automatically) - converting a smaller type to a larger type size
byte -> short -> char -> int -> long -> float -> double

    int myInt = 9;
    double myDouble = myInt; // Automatic casting: int to double

Narrowing Casting (manually) - converting a larger type to a smaller size type
double -> float -> long -> int -> char -> short -> byte

    double myDouble = 9.78;
    int myInt = (int) myDouble; // Manual casting: double to int
    
https://www.w3schools.com/java/java_type_casting.asp


In the example above, we created a static method, which means that it can be accessed without creating an object of the class, unlike public, which can only be accessed by objects:

      public class Main {
        // Static method
        static void myStaticMethod() {
          System.out.println("Static methods can be called without creating objects");
        }

        // Public method
        public void myPublicMethod() {
          System.out.println("Public methods must be called by creating objects");
        }

        // Main method
        public static void main(String[] args) {
          myStaticMethod(); // Call the static method
          // myPublicMethod(); This would compile an error

          Main myObj = new Main(); // Create an object of Main
          myObj.myPublicMethod(); // Call the public method on the object
        }
      }


Access Modifiers - controls the access level

For classes, you can use either public or default:

      public	The class is accessible by any other class	
      default	The class is only accessible by classes in the same package. This is used when you don't specify a modifier.

For attributes, methods and constructors,

      public	The code is accessible for all classes	
      private	The code is only accessible within the declared class	
      default	The code is only accessible in the same package. This is used when you don't specify a modifier. 
      protected	The code is accessible in the same package and subclasses.

Non-Access Modifiers - do not control access level, but provides other functionality
For classes, you can use either final or abstract:

      final       The class cannot be inherited by other classes 
      abstract	The class cannot be used to create objects (To access an abstract class, it must be inherited from another class.)

      For attributes and methods, you can use the one of the following:

      final	Attributes and methods cannot be overridden/modified
      static	      Attributes and methods belongs to the class, rather than an object
      abstract	      Can only be used in an abstract class, and can only be used on methods. The method does not have a body, for example abstract void run();. The body is provided                     by the subclass (inherited from). You will learn more about inheritance and abstraction in the Inheritance and Abstraction chapters
      transient	      Attributes and methods are skipped when serializing the object containing them
      synchronized	Methods can only be accessed by one thread at a time
      volatile	      The value of an attribute is not cached thread-locally, and is always read from the "main memory"

An abstract method belongs to an abstract class, and it does not have a body. The body is provided by the subclass

https://www.w3schools.com/java/java_modifiers.asp



