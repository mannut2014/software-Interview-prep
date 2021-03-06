1. What happens when a duplicate is added to the HashMap or HashSet?
=> HashMap: Item is replaced by the new.
   HashSet: Item is not added.


2. Explain static function.
=> A static function is a member function of a class that can be called even when an object of the class is not initialized.
   A static function cannot access any variable of its class except for static variables.


3. Explain oops concept.
=> Abstraction: Hiding implementation details and exposing only the functionality. Ex : .apk files on app store.
   Encapsulation: Binding of data and the functions acting on them together. Ex: Student, grades and cgpa calculation.
   Inheritence : The process of inheriting the properties from parents to child in inheritance. Ex: vehicle -> car  // single, multilevel, heirarchial //multiple not supported
   Polymorphism: Multiple methods with same name and different signatures. Ex : Method overloading(compile time) and Overriding (inheritence-> run time).


4. Difference between jdk,jre and jvm?
=> JVM(Java virtual machine) : Abstract machine, it provides the runtime environment in which java bytecode can be executed. Java source is compiled to byte code.
   JRE(Java runtime environment):  provides all class libraries and other files that JVM uses in run time.
   JDK(Java development kit): is the tool necessary to compile, document, and package java programs. (has java.io and other packages, javac)
   JDK->JRE->JVM

5. What is synchronization?
=> it keeps all concurrent threads in execution to be in sync. It avoids memory inconsistency. (Example : booking one seat by multiple people(threads) over web,
   allows the person locked continue, restricting the rest). Synchronization provides lock on the object.

6. Process and Thread.
=> Process is a running instance of a program executing on an operating system.
   Thread: Thread is running with in the proccess. (Ex: main thread (main method)).

7. Concurrency
=> The process of offloading heavier task to new threads is called concurrent programming.

8. What is a wrapper class?
=>  Ex: int has wrapper class Integer.

9. Data types in Java?
=> int, char , boolean, byte, short, long, float, double.

10. Boxing vs Unboxing? Give Example.
=>  boxed : int i =10 ,  Integer ref = new Integer(i);  //converting integer to references
    unboxing: int i = ref.intValue();  // converting reference to premitive

11. AutoBoxing vs AutoUnBoxing?
=>  AutoBoxing -> int i = 10 , Integer k = i;  (autoboxing) implicit conversion to references
    AutounBoxing-> int j = k     (autounBoxing) implicit conversion to premitive type.


12. Pass by reference and pass by value?
=>  reference to the object is passed.
    Value is passed.

13. What is final, finally and finalize fulfill?
=>  Final-> classes cannot be extended, methods cannot be overridden, variable cannot be reassigned.
    Finally-> block of code which is executed no matter what happens in try catch block. Usually used to release the resources.
    Finalize-> Finalize is used to perform clean up processing just before object is garbage collected.

14. What is difference between StringBuffer and StringBuilder?
=>  StringBuffer is thread safe. Not fast.
    StringBuilder is not thread safe. Faster.

15. Mutability in String, stringbuffer and stringbuilder?
=>  String in immutable. StringBuffer and stringbuilder are mutable.


16. Differences between Stack and heap memory?
=>  Stack => stack memory used by one thread execution and not available for other threads.
              Follows LIFO.
    heap => is used by all parts of the application.
              Memory management is based on generation asscciated with each object.


17. ArrayList and Vector?
=>  ArrayList is not synchronized. Vector is synchronized.
    ArrayList is not thread safe.  Vector is thread safe.
    Upon insertion, arraylist increase by 50% whereas vector doubles its size.  

18. HashMap and HashTable?
=>  HashMap is not synchronized and not thread safe.
    HashTable is synchronized and thread safe.
    HashMap allows one null key and multiple null values.
    HashTable throws null pointer exception.


19. Equals() and  == operator?
=>  For references, == compares reference value whereas equals method written inside that object.
    For primitive types, = both does same job.


20. Difference between Abstract classes and Interfaces? with example.
=> A class can extend one abstract class but can implement many interfaces.



21. Are methods in interface abstract?
=>  Yes.


22. can abstract class have non abstract methods?
=> Yes.

23. Visibility of abstract class and interface?
=> Abstract class can have any visibility public, private and protected.
  interface can have only public or none.

24. Is instance of class created at runtime for abstract class?
=> Yes.  (implicitly). but we cannot create an instance.

25. Is instance of interface be created at run time or compile time?
=> No.

26. What is the difference between class extending the abstract class and a
    class implementing the interface.
=> A class can extend only one abstract class, inheritance.
    A class can implement many interfaces.    

27. What is polymorphism with example?
=>     Polymorphism: Multiple methods with same name and different signatures. Ex : Method overloading(COMPILE time) and Overriding (inheritence-> run time).

28. What is run time polymorphism or dynamic method dispatch?
=> Method overriding is run time polymorphism.

29. What is upcasting? Give an example?
=>  Assigning instace object of child to a parent class variable.
    ex: A is a parent and B is the child then,
        A a = new B();

30. Overloading and Overriding?
=>  Overloading: functions with same name but different signatures. ex : sum(a,b) & sum (a,b,c).
    Overriding : Overriding the methods of parent class by child classes.

31. Can you override a private or static method in java?
=> No


32. What is multiple inheritance, does java support it?
=>  Multiple inheritence is smae child having more than one parent. No, it is not supported directly but supported through interfaces.

33. What is static? Give example.
=>  In Java, a static member is a member of a class that isn't associated with an instance of a class.
    Instead, the member belongs to the class itself


34. When is static loaded into the memory?
=>  During compile time.

35. Compile time and run time?
=>  During compile time jvm takes the .java file and compiles it to .class file. (byte code)
    Runtime is normal execution phase.

#### Questions asked
  1. What is encapsulation.
  2. What is abstraction.
  3. What is final.
  4. What is final in class and methods.
  5. Explain SOLID principles.
  6. Difference between abstract class and interface.
