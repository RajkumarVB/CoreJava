![img.png](slides/img.png)
![img.png](slides/img1.png)
![img.png](slides/img2.png)
## Java - Platform Independent (WORA - Write Once Run Anywhere)
![img.png](slides/img_1.png)
![img.png](slides/img_2.png)
![img.png](slides/img_3.png)

## JDK vs JRE vs JVM
![img.png](slides/img_4.png)
![img.png](slides/img_5.png)
![img.png](slides/img_6.png)
![img.png](slides/img_7.png)

## Advantage of this model 
- WORA, once you got the byte code, you can run it on any machine where the JRE/JVM is installed.
- Security, JVM acts as a Sandbox. JVM will not let you run anything

## JIT - Just In Time Compiler
![img.png](slides/img_8.png)

## Five design goals of Java
![img.png](slides/img_9.png)

## Compiling & Running a Java program without an IDE 
![img.png](slides/img_10.png)

## JShell
![img.png](slides/img_11.png)

## Disecting a Java Program
![img.png](slides/img_12.png)
![img.png](slides/img_13.png)

## Variable declaration and assignment
![img.png](slides/img_14.png)
![img.png](slides/img_15.png)
![img.png](slides/img_16.png)

## Primitive types  
![img.png](slides/img_17.png)
![img.png](slides/img_18.png)

## Literals 
A way to specify value inline 
<br></br>
![img.png](slides/img_19.png)
![img.png](slides/img_20.png)
![img.png](slides/img_21.png)
![img.png](slides/img_22.png)
![img.png](slides/img_23.png)

## Strong static typing
- Java is a strongly typed language
![img.png](slides/img_24.png)
![img.png](slides/img_25.png)
- What is static typing?
![img.png](slides/img_26.png)
![img.png](slides/img_27.png)

## Type casting
- Conversion in number types
![img.png](slides/img_28.png)
![img.png](slides/img_29.png)
![img.png](slides/img_30.png)
![img.png](slides/img_31.png)
![img.png](slides/img_32.png)
![img.png](slides/img_33.png)

## Casting and lossy conversion
![img.png](slides/img_34.png)
- Casting object references(Covered later)

## Precision loss in numeric operations
![img.png](slides/img_35.png)

## Automatic Type Promotion
![img.png](slides/img_36.png)
 - What happens when one expression has multiple types?
 - Ans : Automatic type promotion
![img.png](slides/img_37.png)
 - In an expression, if one int is present, every value will be converted to int
 - In an expression, if one long is present, every value will be converted to long
 - In an expression, if one double is present, every value will be converted to double

## Arrays
![img.png](slides/img_38.png)
![img.png](slides/img_39.png)
![img.png](slides/img_40.png)
![img.png](slides/img_41.png)
![img.png](slides/img_42.png)

## Multidimensional Arrays
![img.png](slides/img_43.png)
![img.png](slides/img_44.png)

## Operators
![img.png](slides/img_45.png)
![img.png](slides/img_46.png)
![img.png](slides/img_47.png)
![img.png](slides/img_48.png)
![img.png](slides/img_49.png)
![img.png](slides/img_50.png)
![img.png](slides/img_51.png)
![img.png](slides/img_52.png)

## Blocks and Variable Scoping
- Curly braces forms a **Block**
- Local variables -> **Local** to scope  

![img.png](slides/img_53.png)
![img.png](slides/img_54.png)

## Flow/ Control Statements
![img.png](slides/img_55.png)
![img.png](slides/img_56.png)
![img.png](slides/img_57.png)
![img.png](slides/img_58.png)
![img.png](slides/img_59.png)
![img.png](slides/img_60.png)
![img.png](slides/img_61.png)
![img.png](slides/img_62.png)
![img.png](slides/img_63.png)
![img.png](slides/img_64.png)
![img.png](slides/img_65.png)
![img.png](slides/img_66.png)
![img.png](slides/img_67.png)
![img.png](slides/img_68.png)
![img.png](slides/img_69.png)
![img.png](slides/img_70.png)
![img.png](slides/img_71.png)
![img.png](slides/img_72.png)
![img.png](slides/img_73.png)

## Revisiting variable scoping 
![img.png](slides/img_74.png)
![img.png](slides/img_75.png)
![img.png](slides/img_76.png)

## Object Oriented Programming
 - Models **"things"** in the real or business world
 - State and Behavior
 - Objects - Referred to as instances or class instances
![img.png](slides/img_77.png)
![img.png](slides/img_78.png)
![img.png](slides/img_79.png)

## Class Syntax and Object creation
![img.png](slides/img_80.png)
![img.png](slides/img_81.png)
![img.png](slides/img_82.png)
![img.png](slides/img_83.png)
![img.png](slides/img_84.png)

## Object references
![img.png](slides/img_85.png)
 - myNewCar, neighborCar are **Reference variables**

![img.png](slides/img_86.png)
![img.png](slides/img_87.png)

## Things to remember
![img.png](slides/img_88.png)
![img.png](slides/img_89.png)

## Variable Shadowing and this reference
![img.png](slides/img_90.png)
- The **this** reference -> Refers to the instance the method will be run on.

![img.png](slides/img_91.png)

## Constructors
![img.png](slides/img_92.png)
![img.png](slides/img_93.png)
![img.png](slides/img_94.png)
![img.png](slides/img_95.png)

## Calling a Constructor from Constructor
![img.png](slides/img_96.png)

## Instance arguments and copy constructors
![img.png](slides/img_97.png)
 - Instance variable can be references too. 

![img.png](slides/img_98.png)
 - Method parameters/arguments can be reference variable too. 

## Constructor Object Argument
![img.png](slides/img_99.png)

## Copy Constructor Pattern
![img.png](slides/img_100.png)
 - Interview Question - What is a copy constructor?
 - Copy constructor is just one application of the constructor
 - For instance, you could pass the reference variable of different class and use one data member.

## Passing objects as method arguments
![img.png](slides/img_101.png)
- Java has only call by value

![img.png](slides/img_102.png)
![img.png](slides/img_103.png)
![img.png](slides/img_104.png)

## Packages
![img.png](slides/img_105.png)
![img.png](slides/img_106.png)
 - Let's say you have two packages, a.b and a.b.c, a.b.c doesn't belong to a.b. Both are two different packages.

![img.png](slides/img_107.png)

## The Import statement
 - Import required to use a class from a different package. 
 - Or else you have to use Fully Qualified Name(packagename.ClassName)
![img.png](slides/img_108.png)
![img.png](slides/img_109.png)

## Access Modifiers
 - Encapsulate and restrict access to member variables and methods in Classes
 - What are the access modifiers in Java?
![img.png](slides/img_110.png)
![img.png](slides/img_111.png)
![img.png](slides/img_112.png)
![img.png](slides/img_113.png)
![img.png](slides/img_114.png)
![img.png](slides/img_115.png)

## The Static keyword
 - When you need to define a class member as independent from any object instance
 - Make a class member associate with the class, not instance.

![img.png](slides/img_116.png)
![img.png](slides/img_117.png)
![img.png](slides/img_118.png)
![img.png](slides/img_119.png)
![img.png](slides/img_120.png)
![img.png](slides/img_121.png)
![img.png](slides/img_122.png)

## The final modifier

![Pasted image 20231221133543](slides/Pasted%20image%2020231221133543.png)

If we didn't initialize i variable, we can assign once. 

![Pasted image 20231221133632](slides/Pasted%20image%2020231221133632.png)

![Pasted image 20231221133650](slides/Pasted%20image%2020231221133650.png)

![Pasted image 20231221133701](slides/Pasted%20image%2020231221133701.png)

![Pasted image 20231221133714](slides/Pasted%20image%2020231221133714.png)

![Pasted image 20231221133721](slides/Pasted%20image%2020231221133721.png)

![Pasted image 20231221133727](slides/Pasted%20image%2020231221133727.png)


## Nested Classes 

### Static inner class

![Pasted image 20231221134345](slides/Pasted%20image%2020231221134345.png)

### Inner class 
![Pasted image 20231221134417](slides/Pasted%20image%2020231221134417.png)

### Local class 
![Pasted image 20231221134440](slides/Pasted%20image%2020231221134440.png)

### Anonymous inner class 
![Pasted image 20231221134511](slides/Pasted%20image%2020231221134511.png)

## Local classes and variable scope : 
![Pasted image 20231221135127](slides/Pasted%20image%2020231221135127.png)

![Pasted image 20231221135142](slides/Pasted%20image%2020231221135142.png)

![Pasted image 20231221135200](slides/Pasted%20image%2020231221135200.png)
![Pasted image 20231221135207](slides/Pasted%20image%2020231221135207.png)

## Inheritance and Polymorphism 

![Pasted image 20231221135532](slides/Pasted%20image%2020231221135532.png)

![Pasted image 20231221135544](slides/Pasted%20image%2020231221135544.png)

![Pasted image 20231221135555](slides/Pasted%20image%2020231221135555.png)


![Pasted image 20231221135608](slides/Pasted%20image%2020231221135608.png)

![Pasted image 20231221135616](slides/Pasted%20image%2020231221135616.png)

![Pasted image 20231221135643](slides/Pasted%20image%2020231221135643.png)


![Pasted image 20231221135838](slides/Pasted%20image%2020231221135838.png)

![Pasted image 20231221135846](slides/Pasted%20image%2020231221135846.png)

Why Java doesn't support Multiple Inheritance - Then it should handle so much complexities. One of many problem is Diamond Dependency Problem. 

![Pasted image 20231221140134](slides/Pasted%20image%2020231221140134.png)

![Pasted image 20231221140145](slides/Pasted%20image%2020231221140145.png) 


![Pasted image 20231221140342](slides/Pasted%20image%2020231221140342.png)

![Pasted image 20231221140352](slides/Pasted%20image%2020231221140352.png)


## Method Overriding
![Pasted image 20231221140701](slides/Pasted%20image%2020231221140701.png)

![Pasted image 20231221140717](slides/Pasted%20image%2020231221140717.png)
This will not work. 


![Pasted image 20231221140731](slides/Pasted%20image%2020231221140731.png)

However, you can make it stronger. Protected -> Public is valid. 

![Pasted image 20231221140842](slides/Pasted%20image%2020231221140842.png)
Conveying our intent to the compiler! 


## Inheritance Example

![Pasted image 20231221141028](slides/Pasted%20image%2020231221141028.png)



![Pasted image 20231221141056](slides/Pasted%20image%2020231221141056.png)

## Encapsulation revisited

![Pasted image 20231221141309](slides/Pasted%20image%2020231221141309.png)
If run method uses seats, it will work in sub class as well.

![Pasted image 20231221141359](slides/Pasted%20image%2020231221141359.png)

![Pasted image 20231221141412](slides/Pasted%20image%2020231221141412.png)


## Constructors calls with Inheritance

![Pasted image 20231221141451](slides/Pasted%20image%2020231221141451.png)

B b = new B(); 
Output : 
A's constructor called
B's constructor called

![Pasted image 20231221141558](slides/Pasted%20image%2020231221141558.png)


![Pasted image 20231221141636](slides/Pasted%20image%2020231221141636.png)


![Pasted image 20231221141809](slides/Pasted%20image%2020231221141809.png)B b = new B(5); 
Output : 
A's constructor called
B's constructor called 5 



![Pasted image 20231221142018](slides/Pasted%20image%2020231221142018.png)


## Abstract Class

![](slides/Pasted%20image%2020231221212310.png)


![](slides/Pasted%20image%2020231221212325.png)


![](slides/Pasted%20image%2020231221212343.png)


![](slides/Pasted%20image%2020231221212401.png)


![](slides/Pasted%20image%2020231221212420.png)

## Abstract Methods


![](slides/Pasted%20image%2020231221212651.png)


![](slides/Pasted%20image%2020231221212716.png)


## Final Keyword with Inheritance 


![](slides/Pasted%20image%2020231221212815.png)

![](slides/Pasted%20image%2020231221212841.png)


## Interfaces

![](slides/Pasted%20image%2020231221213128.png)

![](slides/Pasted%20image%2020231221213142.png)

![](slides/Pasted%20image%2020231221213202.png)

## Usage of Interfaces

![](slides/Pasted%20image%2020231221213329.png)


![](slides/Pasted%20image%2020231221213357.png)

![](slides/Pasted%20image%2020231221213439.png)

![](slides/Pasted%20image%2020231221213619.png)

## Default Methods in Interfaces 

![](slides/Pasted%20image%2020231221213835.png)

![](slides/Pasted%20image%2020231221214249.png)

![](slides/Pasted%20image%2020231221214314.png)

![](slides/Pasted%20image%2020231221214329.png)

## Interfaces Summary 

![](slides/Pasted%20image%2020231221214410.png)


![](slides/Pasted%20image%2020231221214554.png)


## Polymorphism 
Means Many Forms

![](slides/Pasted%20image%2020231221215223.png)


![](slides/Pasted%20image%2020231221215232.png)

No need to create unnecessary methods


![](slides/Pasted%20image%2020231221215306.png)

Instance move (Lion) move method will be called. 
You can only assign, child class object to parent class reference. Vice versa is not possible. 
You can't call Lion only methods, when you assign lion object to animal.


![](slides/Pasted%20image%2020231221215318.png)



![](slides/Pasted%20image%2020231221215657.png)

![](slides/Pasted%20image%2020231221215711.png)


![](slides/Pasted%20image%2020231221215746.png)

Lion's method will be called. 


## Polymorphism with interfaces 

![](slides/Pasted%20image%2020231221220006.png)

![](slides/Pasted%20image%2020231221220031.png)

Now using car, you can call only drive method, no matter how many methods present in SportsCar. 

## Casting 

![](slides/Pasted%20image%2020231222110818.png)

![](slides/Pasted%20image%2020231222110834.png)



![](slides/Pasted%20image%2020231222110958.png)



## Is-A relationship 

![](slides/Pasted%20image%2020231222111648.png)


![](slides/Pasted%20image%2020231222111706.png)

Fish is a Animal
Bird is a Animal
Lion is a Animal


![](slides/Pasted%20image%2020231222111739.png)

SportsCar is a Drivable car

## The Object class

![](slides/Pasted%20image%2020231222112034.png)

![](slides/Pasted%20image%2020231222112040.png)

![](slides/Pasted%20image%2020231222112054.png)


![](slides/Pasted%20image%2020231222112105.png)



## The toString method 

![](slides/Pasted%20image%2020231222112419.png)

![](slides/Pasted%20image%2020231222112428.png)


![](slides/Pasted%20image%2020231222112439.png)


## The Equals method 

![](slides/Pasted%20image%2020231222113034.png)


![](slides/Pasted%20image%2020231222113045.png)

This is return false, even though all the member variable values are same. 


![](slides/Pasted%20image%2020231222113202.png)

Still you can't use == , but rather you can use .equals method. 

![](slides/Pasted%20image%2020231222113246.png)


![](slides/Pasted%20image%2020231222113533.png)



## Exception Handling 

![](slides/Pasted%20image%2020231222113751.png)


![](slides/Pasted%20image%2020231222113758.png)

![](slides/Pasted%20image%2020231222113804.png)


![](slides/Pasted%20image%2020231222113814.png)

![](slides/Pasted%20image%2020231222114039.png)

![](slides/Pasted%20image%2020231222114049.png)


![](slides/Pasted%20image%2020231222114054.png)

![](slides/Pasted%20image%2020231222114103.png)


![](slides/Pasted%20image%2020231222114113.png)


## Try Catch Block

![](slides/Pasted%20image%2020231222114327.png)

![](slides/Pasted%20image%2020231222114336.png)



## Execution flow in a Try-Catch block 


![](slides/Pasted%20image%2020231222114650.png)


![](slides/Pasted%20image%2020231222114701.png)



![](slides/Pasted%20image%2020231222114709.png)


![](slides/Pasted%20image%2020231222114732.png)


![](slides/Pasted%20image%2020231222114835.png)


## Throw and the call stack 

![](slides/Pasted%20image%2020231222115310.png)


![](slides/Pasted%20image%2020231222115319.png)


![](slides/Pasted%20image%2020231222115331.png)



![](slides/Pasted%20image%2020231222115344.png)


## Exception Types and Hierarchies

![](slides/Pasted%20image%2020231222115938.png)

Runtime Exception -> Unchecked exception 
Error -> Unchecked exception. 
Unchecked exception need not be surrounded by try catch block. 
But Exception needs to be surrounded by try catch block. 

## Custom Exception Classes 

![](slides/Pasted%20image%2020231222120528.png)

![](slides/Pasted%20image%2020231222120547.png)


![](slides/Pasted%20image%2020231222120601.png)


![](slides/Pasted%20image%2020231222120627.png)

![](slides/Pasted%20image%2020231222120644.png)


## Throwable and Inherited Methods 

![](slides/Pasted%20image%2020231222120853.png)


![](slides/Pasted%20image%2020231222120903.png)


![](slides/Pasted%20image%2020231222120932.png)


## Exception Handling Best Practices 

![](slides/Pasted%20image%2020231222121443.png)


![](slides/Pasted%20image%2020231222121451.png)


![](slides/Pasted%20image%2020231222121817.png)
