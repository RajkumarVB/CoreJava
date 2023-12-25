<!-- vscode-markdown-toc -->
* 1. [Java - Platform Independent (WORA - Write Once Run Anywhere)](#Java-PlatformIndependentWORA-WriteOnceRunAnywhere)
* 2. [JDK vs JRE vs JVM](#JDKvsJREvsJVM)
* 3. [Advantage of this model](#Advantageofthismodel)
* 4. [JIT - Just In Time Compiler](#JIT-JustInTimeCompiler)
* 5. [Five design goals of Java](#FivedesigngoalsofJava)
* 6. [Compiling & Running a Java program without an IDE](#CompilingRunningaJavaprogramwithoutanIDE)
* 7. [JShell](#JShell)
* 8. [Disecting a Java Program](#DisectingaJavaProgram)
* 9. [Variable declaration and assignment](#Variabledeclarationandassignment)
* 10. [Primitive types](#Primitivetypes)
* 11. [Literals](#Literals)
* 12. [Strong static typing](#Strongstatictyping)
* 13. [Type casting](#Typecasting)
* 14. [Casting and lossy conversion](#Castingandlossyconversion)
* 15. [Precision loss in numeric operations](#Precisionlossinnumericoperations)
* 16. [Automatic Type Promotion](#AutomaticTypePromotion)
* 17. [Arrays](#Arrays)
* 18. [Multidimensional Arrays](#MultidimensionalArrays)
* 19. [Operators](#Operators)
* 20. [Blocks and Variable Scoping](#BlocksandVariableScoping)
* 21. [Flow/ Control Statements](#FlowControlStatements)
* 22. [Revisiting variable scoping](#Revisitingvariablescoping)
* 23. [Object Oriented Programming](#ObjectOrientedProgramming)
* 24. [Class Syntax and Object creation](#ClassSyntaxandObjectcreation)
* 25. [Object references](#Objectreferences)
* 26. [Things to remember](#Thingstoremember)
* 27. [Variable Shadowing and this reference](#VariableShadowingandthisreference)
* 28. [Constructors](#Constructors)
* 29. [Calling a Constructor from Constructor](#CallingaConstructorfromConstructor)
* 30. [Instance arguments and copy constructors](#Instanceargumentsandcopyconstructors)
* 31. [Constructor Object Argument](#ConstructorObjectArgument)
* 32. [Copy Constructor Pattern](#CopyConstructorPattern)
* 33. [Passing objects as method arguments](#Passingobjectsasmethodarguments)
* 34. [Packages](#Packages)
* 35. [The Import statement](#TheImportstatement)
* 36. [Access Modifiers](#AccessModifiers)
* 37. [The Static keyword](#TheStatickeyword)
* 38. [The final modifier](#Thefinalmodifier)
* 39. [Nested Classes](#NestedClasses)
	* 39.1. [Static inner class](#Staticinnerclass)
	* 39.2. [Inner class](#Innerclass)
	* 39.3. [Local class](#Localclass)
	* 39.4. [Anonymous inner class](#Anonymousinnerclass)
* 40. [Local classes and variable scope :](#Localclassesandvariablescope:)
* 41. [Inheritance and Polymorphism](#InheritanceandPolymorphism)
* 42. [Method Overriding](#MethodOverriding)
* 43. [Inheritance Example](#InheritanceExample)
* 44. [Encapsulation revisited](#Encapsulationrevisited)
* 45. [Constructors calls with Inheritance](#ConstructorscallswithInheritance)
* 46. [Abstract Class](#AbstractClass)
* 47. [Abstract Methods](#AbstractMethods)
* 48. [Final Keyword with Inheritance](#FinalKeywordwithInheritance)
* 49. [Interfaces](#Interfaces)
* 50. [Usage of Interfaces](#UsageofInterfaces)
* 51. [Default Methods in Interfaces](#DefaultMethodsinInterfaces)
* 52. [Interfaces Summary](#InterfacesSummary)
* 53. [Polymorphism](#Polymorphism)
* 54. [Polymorphism with interfaces](#Polymorphismwithinterfaces)
* 55. [Casting](#Casting)
* 56. [Is-A relationship](#Is-Arelationship)
* 57. [The Object class](#TheObjectclass)
* 58. [The toString method](#ThetoStringmethod)
* 59. [The Equals method](#TheEqualsmethod)
* 60. [Exception Handling](#ExceptionHandling)
* 61. [Try Catch Block](#TryCatchBlock)
* 62. [Execution flow in a Try-Catch block](#ExecutionflowinaTry-Catchblock)
* 63. [Throw and the call stack](#Throwandthecallstack)
* 64. [Exception Types and Hierarchies](#ExceptionTypesandHierarchies)
* 65. [Custom Exception Classes](#CustomExceptionClasses)
* 66. [Throwable and Inherited Methods](#ThrowableandInheritedMethods)
* 67. [Exception Handling Best Practices](#ExceptionHandlingBestPractices)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

![img.png](slides/img.png)
<br></br>

![img.png](slides/img1.png)
<br></br>

![img.png](slides/img2.png)
<br></br>

##  1. <a name='Java-PlatformIndependentWORA-WriteOnceRunAnywhere'></a>Java - Platform Independent (WORA - Write Once Run Anywhere)
![img.png](slides/img_1.png)
<br></br>

![img.png](slides/img_2.png)
<br></br>

![img.png](slides/img_3.png)
<br></br>


##  2. <a name='JDKvsJREvsJVM'></a>JDK vs JRE vs JVM
![img.png](slides/img_4.png)
<br></br>

![img.png](slides/img_5.png)
<br></br>

![img.png](slides/img_6.png)
<br></br>

![img.png](slides/img_7.png)
<br></br>


##  3. <a name='Advantageofthismodel'></a>Advantage of this model 
- WORA, once you got the byte code, you can run it on any machine where the JRE/JVM is installed.
- Security, JVM acts as a Sandbox. JVM will not let you run anything

##  4. <a name='JIT-JustInTimeCompiler'></a>JIT - Just In Time Compiler
![img.png](slides/img_8.png)
<br></br>


##  5. <a name='FivedesigngoalsofJava'></a>Five design goals of Java
![img.png](slides/img_9.png)
<br></br>


##  6. <a name='CompilingRunningaJavaprogramwithoutanIDE'></a>Compiling & Running a Java program without an IDE 
![img.png](slides/img_10.png)
<br></br>


##  7. <a name='JShell'></a>JShell
![img.png](slides/img_11.png)
<br></br>


##  8. <a name='DisectingaJavaProgram'></a>Disecting a Java Program
![img.png](slides/img_12.png)
<br></br>

![img.png](slides/img_13.png)
<br></br>


##  9. <a name='Variabledeclarationandassignment'></a>Variable declaration and assignment
![img.png](slides/img_14.png)
<br></br>

![img.png](slides/img_15.png)
<br></br>

![img.png](slides/img_16.png)
<br></br>


##  10. <a name='Primitivetypes'></a>Primitive types  
![img.png](slides/img_17.png)
<br></br>

![img.png](slides/img_18.png)
<br></br>


##  11. <a name='Literals'></a>Literals 
A way to specify value inline 
<br></br>
![img.png](slides/img_19.png)
<br></br>

![img.png](slides/img_20.png)
<br></br>

![img.png](slides/img_21.png)
<br></br>

![img.png](slides/img_22.png)
<br></br>

![img.png](slides/img_23.png)
<br></br>


##  12. <a name='Strongstatictyping'></a>Strong static typing
- Java is a strongly typed language
![img.png](slides/img_24.png)
<br></br>

![img.png](slides/img_25.png)
<br></br>

- What is static typing?
![img.png](slides/img_26.png)
<br></br>

![img.png](slides/img_27.png)
<br></br>


##  13. <a name='Typecasting'></a>Type casting
- Conversion in number types
![img.png](slides/img_28.png)
<br></br>

![img.png](slides/img_29.png)
<br></br>

![img.png](slides/img_30.png)
<br></br>

![img.png](slides/img_31.png)
<br></br>

![img.png](slides/img_32.png)
<br></br>

![img.png](slides/img_33.png)
<br></br>


##  14. <a name='Castingandlossyconversion'></a>Casting and lossy conversion
![img.png](slides/img_34.png)
<br></br>

- Casting object references(Covered later)

##  15. <a name='Precisionlossinnumericoperations'></a>Precision loss in numeric operations
![img.png](slides/img_35.png)
<br></br>


##  16. <a name='AutomaticTypePromotion'></a>Automatic Type Promotion
![img.png](slides/img_36.png)
<br></br>

 - What happens when one expression has multiple types?
 - Ans : Automatic type promotion
![img.png](slides/img_37.png)
<br></br>

 - In an expression, if one int is present, every value will be converted to int
 - In an expression, if one long is present, every value will be converted to long
 - In an expression, if one double is present, every value will be converted to double

##  17. <a name='Arrays'></a>Arrays
![img.png](slides/img_38.png)
<br></br>

![img.png](slides/img_39.png)
<br></br>

![img.png](slides/img_40.png)
<br></br>

![img.png](slides/img_41.png)
<br></br>

![img.png](slides/img_42.png)
<br></br>


##  18. <a name='MultidimensionalArrays'></a>Multidimensional Arrays
![img.png](slides/img_43.png)
<br></br>

![img.png](slides/img_44.png)
<br></br>


##  19. <a name='Operators'></a>Operators
![img.png](slides/img_45.png)
<br></br>

![img.png](slides/img_46.png)
<br></br>

![img.png](slides/img_47.png)
<br></br>

![img.png](slides/img_48.png)
<br></br>

![img.png](slides/img_49.png)
<br></br>

![img.png](slides/img_50.png)
<br></br>

![img.png](slides/img_51.png)
<br></br>

![img.png](slides/img_52.png)
<br></br>


##  20. <a name='BlocksandVariableScoping'></a>Blocks and Variable Scoping
- Curly braces forms a **Block**
- Local variables -> **Local** to scope  

![img.png](slides/img_53.png)
<br></br>

![img.png](slides/img_54.png)
<br></br>


##  21. <a name='FlowControlStatements'></a>Flow/ Control Statements
![img.png](slides/img_55.png)
<br></br>

![img.png](slides/img_56.png)
<br></br>

![img.png](slides/img_57.png)
<br></br>

![img.png](slides/img_58.png)
<br></br>

![img.png](slides/img_59.png)
<br></br>

![img.png](slides/img_60.png)
<br></br>

![img.png](slides/img_61.png)
<br></br>

![img.png](slides/img_62.png)
<br></br>

![img.png](slides/img_63.png)
<br></br>

![img.png](slides/img_64.png)
<br></br>

![img.png](slides/img_65.png)
<br></br>

![img.png](slides/img_66.png)
<br></br>

![img.png](slides/img_67.png)
<br></br>

![img.png](slides/img_68.png)
<br></br>

![img.png](slides/img_69.png)
<br></br>

![img.png](slides/img_70.png)
<br></br>

![img.png](slides/img_71.png)
<br></br>

![img.png](slides/img_72.png)
<br></br>

![img.png](slides/img_73.png)
<br></br>


##  22. <a name='Revisitingvariablescoping'></a>Revisiting variable scoping 
![img.png](slides/img_74.png)
<br></br>

![img.png](slides/img_75.png)
<br></br>

![img.png](slides/img_76.png)
<br></br>


##  23. <a name='ObjectOrientedProgramming'></a>Object Oriented Programming
 - Models **"things"** in the real or business world
 - State and Behavior
 - Objects - Referred to as instances or class instances
![img.png](slides/img_77.png)
<br></br>

![img.png](slides/img_78.png)
<br></br>

![img.png](slides/img_79.png)
<br></br>


##  24. <a name='ClassSyntaxandObjectcreation'></a>Class Syntax and Object creation
![img.png](slides/img_80.png)
<br></br>

![img.png](slides/img_81.png)
<br></br>

![img.png](slides/img_82.png)
<br></br>

![img.png](slides/img_83.png)
<br></br>

![img.png](slides/img_84.png)
<br></br>


##  25. <a name='Objectreferences'></a>Object references
![img.png](slides/img_85.png)
<br></br>

 - myNewCar, neighborCar are **Reference variables**

![img.png](slides/img_86.png)
<br></br>

![img.png](slides/img_87.png)
<br></br>


##  26. <a name='Thingstoremember'></a>Things to remember
![img.png](slides/img_88.png)
<br></br>

![img.png](slides/img_89.png)
<br></br>


##  27. <a name='VariableShadowingandthisreference'></a>Variable Shadowing and this reference
![img.png](slides/img_90.png)
<br></br>

- The **this** reference -> Refers to the instance the method will be run on.

![img.png](slides/img_91.png)
<br></br>


##  28. <a name='Constructors'></a>Constructors
![img.png](slides/img_92.png)
<br></br>

![img.png](slides/img_93.png)
<br></br>

![img.png](slides/img_94.png)
<br></br>

![img.png](slides/img_95.png)
<br></br>


##  29. <a name='CallingaConstructorfromConstructor'></a>Calling a Constructor from Constructor
![img.png](slides/img_96.png)
<br></br>


##  30. <a name='Instanceargumentsandcopyconstructors'></a>Instance arguments and copy constructors
![img.png](slides/img_97.png)
<br></br>

 - Instance variable can be references too. 

![img.png](slides/img_98.png)
<br></br>

 - Method parameters/arguments can be reference variable too. 

##  31. <a name='ConstructorObjectArgument'></a>Constructor Object Argument
![img.png](slides/img_99.png)
<br></br>


##  32. <a name='CopyConstructorPattern'></a>Copy Constructor Pattern
![img.png](slides/img_100.png)
<br></br>

 - Interview Question - What is a copy constructor?
 - Copy constructor is just one application of the constructor
 - For instance, you could pass the reference variable of different class and use one data member.

##  33. <a name='Passingobjectsasmethodarguments'></a>Passing objects as method arguments
![img.png](slides/img_101.png)
<br></br>

- Java has only call by value

![img.png](slides/img_102.png)
<br></br>

![img.png](slides/img_103.png)
<br></br>

![img.png](slides/img_104.png)
<br></br>


##  34. <a name='Packages'></a>Packages
![img.png](slides/img_105.png)
<br></br>

![img.png](slides/img_106.png)
<br></br>

 - Let's say you have two packages, a.b and a.b.c, a.b.c doesn't belong to a.b. Both are two different packages.

![img.png](slides/img_107.png)
<br></br>


##  35. <a name='TheImportstatement'></a>The Import statement
 - Import required to use a class from a different package. 
 - Or else you have to use Fully Qualified Name(packagename.ClassName)
![img.png](slides/img_108.png)
<br></br>

![img.png](slides/img_109.png)
<br></br>


##  36. <a name='AccessModifiers'></a>Access Modifiers
 - Encapsulate and restrict access to member variables and methods in Classes
 - What are the access modifiers in Java?
![img.png](slides/img_110.png)
<br></br>

![img.png](slides/img_111.png)
<br></br>

![img.png](slides/img_112.png)
<br></br>

![img.png](slides/img_113.png)
<br></br>

![img.png](slides/img_114.png)
<br></br>

![img.png](slides/img_115.png)
<br></br>


##  37. <a name='TheStatickeyword'></a>The Static keyword
 - When you need to define a class member as independent from any object instance
 - Make a class member associate with the class, not instance.

![img.png](slides/img_116.png)
<br></br>

![img.png](slides/img_117.png)
<br></br>

![img.png](slides/img_118.png)
<br></br>

![img.png](slides/img_119.png)
<br></br>

![img.png](slides/img_120.png)
<br></br>

![img.png](slides/img_121.png)
<br></br>

![img.png](slides/img_122.png)
<br></br>


##  38. <a name='Thefinalmodifier'></a>The final modifier

![Pasted image 20231221133543](slides/Pasted%20image%2020231221133543.png)
<br></br>

If we didn't initialize i variable, we can assign once. 

![Pasted image 20231221133632](slides/Pasted%20image%2020231221133632.png)
<br></br>

![Pasted image 20231221133650](slides/Pasted%20image%2020231221133650.png)
<br></br>

![Pasted image 20231221133701](slides/Pasted%20image%2020231221133701.png)
<br></br>

![Pasted image 20231221133714](slides/Pasted%20image%2020231221133714.png)
<br></br>

![Pasted image 20231221133721](slides/Pasted%20image%2020231221133721.png)
<br></br>

![Pasted image 20231221133727](slides/Pasted%20image%2020231221133727.png)
<br></br>


##  39. <a name='NestedClasses'></a>Nested Classes 

###  39.1. <a name='Staticinnerclass'></a>Static inner class

![Pasted image 20231221134345](slides/Pasted%20image%2020231221134345.png)
<br></br>

###  39.2. <a name='Innerclass'></a>Inner class 
![Pasted image 20231221134417](slides/Pasted%20image%2020231221134417.png)
<br></br>

###  39.3. <a name='Localclass'></a>Local class 
![Pasted image 20231221134440](slides/Pasted%20image%2020231221134440.png)
<br></br>

###  39.4. <a name='Anonymousinnerclass'></a>Anonymous inner class 
![Pasted image 20231221134511](slides/Pasted%20image%2020231221134511.png)
<br></br>

##  40. <a name='Localclassesandvariablescope:'></a>Local classes and variable scope : 
![Pasted image 20231221135127](slides/Pasted%20image%2020231221135127.png)
<br></br>

![Pasted image 20231221135142](slides/Pasted%20image%2020231221135142.png)
<br></br>

![Pasted image 20231221135200](slides/Pasted%20image%2020231221135200.png)
<br></br>
![Pasted image 20231221135207](slides/Pasted%20image%2020231221135207.png)
<br></br>

##  41. <a name='InheritanceandPolymorphism'></a>Inheritance and Polymorphism 

![Pasted image 20231221135532](slides/Pasted%20image%2020231221135532.png)
<br></br>

![Pasted image 20231221135544](slides/Pasted%20image%2020231221135544.png)
<br></br>

![Pasted image 20231221135555](slides/Pasted%20image%2020231221135555.png)
<br></br>


![Pasted image 20231221135608](slides/Pasted%20image%2020231221135608.png)
<br></br>

![Pasted image 20231221135616](slides/Pasted%20image%2020231221135616.png)
<br></br>

![Pasted image 20231221135643](slides/Pasted%20image%2020231221135643.png)
<br></br>


![Pasted image 20231221135838](slides/Pasted%20image%2020231221135838.png)
<br></br>

![Pasted image 20231221135846](slides/Pasted%20image%2020231221135846.png)
<br></br>

Why Java doesn't support Multiple Inheritance - Then it should handle so much complexities. One of many problem is Diamond Dependency Problem. 

![Pasted image 20231221140134](slides/Pasted%20image%2020231221140134.png)
<br></br>

![Pasted image 20231221140145](slides/Pasted%20image%2020231221140145.png) 
<br></br>


![Pasted image 20231221140342](slides/Pasted%20image%2020231221140342.png)
<br></br>

![Pasted image 20231221140352](slides/Pasted%20image%2020231221140352.png)
<br></br>


##  42. <a name='MethodOverriding'></a>Method Overriding
![Pasted image 20231221140701](slides/Pasted%20image%2020231221140701.png)
<br></br>

![Pasted image 20231221140717](slides/Pasted%20image%2020231221140717.png)
<br></br>
This will not work. 


![Pasted image 20231221140731](slides/Pasted%20image%2020231221140731.png)
<br></br>

However, you can make it stronger. Protected -> Public is valid. 

![Pasted image 20231221140842](slides/Pasted%20image%2020231221140842.png)
<br></br>
Conveying our intent to the compiler! 


##  43. <a name='InheritanceExample'></a>Inheritance Example

![Pasted image 20231221141028](slides/Pasted%20image%2020231221141028.png)
<br></br>



![Pasted image 20231221141056](slides/Pasted%20image%2020231221141056.png)
<br></br>

##  44. <a name='Encapsulationrevisited'></a>Encapsulation revisited

![Pasted image 20231221141309](slides/Pasted%20image%2020231221141309.png)
<br></br>
If run method uses seats, it will work in sub class as well.

![Pasted image 20231221141359](slides/Pasted%20image%2020231221141359.png)
<br></br>

![Pasted image 20231221141412](slides/Pasted%20image%2020231221141412.png)
<br></br>


##  45. <a name='ConstructorscallswithInheritance'></a>Constructors calls with Inheritance

![Pasted image 20231221141451](slides/Pasted%20image%2020231221141451.png)
<br></br>

B b = new B(); 
Output : 
A's constructor called
B's constructor called

![Pasted image 20231221141558](slides/Pasted%20image%2020231221141558.png)
<br></br>


![Pasted image 20231221141636](slides/Pasted%20image%2020231221141636.png)
<br></br>


![Pasted image 20231221141809](slides/Pasted%20image%2020231221141809.png)B b = 
<br></br>new B(5); 
Output : 
A's constructor called
B's constructor called 5 



![Pasted image 20231221142018](slides/Pasted%20image%2020231221142018.png)
<br></br>


##  46. <a name='AbstractClass'></a>Abstract Class

![](slides/Pasted%20image%2020231221212310.png)

<br></br>


![](slides/Pasted%20image%2020231221212325.png)

<br></br>


![](slides/Pasted%20image%2020231221212343.png)

<br></br>


![](slides/Pasted%20image%2020231221212401.png)

<br></br>


![](slides/Pasted%20image%2020231221212420.png)

<br></br>

##  47. <a name='AbstractMethods'></a>Abstract Methods


![](slides/Pasted%20image%2020231221212651.png)

<br></br>


![](slides/Pasted%20image%2020231221212716.png)

<br></br>


##  48. <a name='FinalKeywordwithInheritance'></a>Final Keyword with Inheritance 


![](slides/Pasted%20image%2020231221212815.png)

<br></br>

![](slides/Pasted%20image%2020231221212841.png)

<br></br>


##  49. <a name='Interfaces'></a>Interfaces

![](slides/Pasted%20image%2020231221213128.png)

<br></br>

![](slides/Pasted%20image%2020231221213142.png)

<br></br>

![](slides/Pasted%20image%2020231221213202.png)

<br></br>

##  50. <a name='UsageofInterfaces'></a>Usage of Interfaces

![](slides/Pasted%20image%2020231221213329.png)

<br></br>


![](slides/Pasted%20image%2020231221213357.png)

<br></br>

![](slides/Pasted%20image%2020231221213439.png)

<br></br>

![](slides/Pasted%20image%2020231221213619.png)

<br></br>

##  51. <a name='DefaultMethodsinInterfaces'></a>Default Methods in Interfaces 

![](slides/Pasted%20image%2020231221213835.png)

<br></br>

![](slides/Pasted%20image%2020231221214249.png)

<br></br>

![](slides/Pasted%20image%2020231221214314.png)

<br></br>

![](slides/Pasted%20image%2020231221214329.png)

<br></br>

##  52. <a name='InterfacesSummary'></a>Interfaces Summary 

![](slides/Pasted%20image%2020231221214410.png)

<br></br>


![](slides/Pasted%20image%2020231221214554.png)

<br></br>


##  53. <a name='Polymorphism'></a>Polymorphism 
Means Many Forms

![](slides/Pasted%20image%2020231221215223.png)

<br></br>


![](slides/Pasted%20image%2020231221215232.png)

<br></br>

No need to create unnecessary methods


![](slides/Pasted%20image%2020231221215306.png)

<br></br>

Instance move (Lion) move method will be called. 
You can only assign, child class object to parent class reference. Vice versa is not possible. 
You can't call Lion only methods, when you assign lion object to animal.


![](slides/Pasted%20image%2020231221215318.png)

<br></br>



![](slides/Pasted%20image%2020231221215657.png)

<br></br>

![](slides/Pasted%20image%2020231221215711.png)

<br></br>


![](slides/Pasted%20image%2020231221215746.png)

<br></br>

Lion's method will be called. 


##  54. <a name='Polymorphismwithinterfaces'></a>Polymorphism with interfaces 

![](slides/Pasted%20image%2020231221220006.png)

<br></br>

![](slides/Pasted%20image%2020231221220031.png)

<br></br>

Now using car, you can call only drive method, no matter how many methods present in SportsCar. 

##  55. <a name='Casting'></a>Casting 

![](slides/Pasted%20image%2020231222110818.png)

<br></br>

![](slides/Pasted%20image%2020231222110834.png)

<br></br>



![](slides/Pasted%20image%2020231222110958.png)

<br></br>



##  56. <a name='Is-Arelationship'></a>Is-A relationship 

![](slides/Pasted%20image%2020231222111648.png)

<br></br>


![](slides/Pasted%20image%2020231222111706.png)

<br></br>

Fish is a Animal
Bird is a Animal
Lion is a Animal


![](slides/Pasted%20image%2020231222111739.png)

<br></br>

SportsCar is a Drivable car

##  57. <a name='TheObjectclass'></a>The Object class

![](slides/Pasted%20image%2020231222112034.png)

<br></br>

![](slides/Pasted%20image%2020231222112040.png)

<br></br>

![](slides/Pasted%20image%2020231222112054.png)

<br></br>


![](slides/Pasted%20image%2020231222112105.png)

<br></br>



##  58. <a name='ThetoStringmethod'></a>The toString method 

![](slides/Pasted%20image%2020231222112419.png)

<br></br>

![](slides/Pasted%20image%2020231222112428.png)

<br></br>


![](slides/Pasted%20image%2020231222112439.png)

<br></br>


##  59. <a name='TheEqualsmethod'></a>The Equals method 

![](slides/Pasted%20image%2020231222113034.png)

<br></br>


![](slides/Pasted%20image%2020231222113045.png)

<br></br>

This is return false, even though all the member variable values are same. 


![](slides/Pasted%20image%2020231222113202.png)

<br></br>

Still you can't use == , but rather you can use .equals method. 

![](slides/Pasted%20image%2020231222113246.png)

<br></br>


![](slides/Pasted%20image%2020231222113533.png)

<br></br>



##  60. <a name='ExceptionHandling'></a>Exception Handling 

![](slides/Pasted%20image%2020231222113751.png)

<br></br>


![](slides/Pasted%20image%2020231222113758.png)

<br></br>

![](slides/Pasted%20image%2020231222113804.png)

<br></br>


![](slides/Pasted%20image%2020231222113814.png)

<br></br>

![](slides/Pasted%20image%2020231222114039.png)

<br></br>

![](slides/Pasted%20image%2020231222114049.png)

<br></br>


![](slides/Pasted%20image%2020231222114054.png)

<br></br>

![](slides/Pasted%20image%2020231222114103.png)

<br></br>


![](slides/Pasted%20image%2020231222114113.png)

<br></br>


##  61. <a name='TryCatchBlock'></a>Try Catch Block

![](slides/Pasted%20image%2020231222114327.png)

<br></br>

![](slides/Pasted%20image%2020231222114336.png)

<br></br>



##  62. <a name='ExecutionflowinaTry-Catchblock'></a>Execution flow in a Try-Catch block 


![](slides/Pasted%20image%2020231222114650.png)

<br></br>


![](slides/Pasted%20image%2020231222114701.png)

<br></br>



![](slides/Pasted%20image%2020231222114709.png)

<br></br>


![](slides/Pasted%20image%2020231222114732.png)

<br></br>


![](slides/Pasted%20image%2020231222114835.png)

<br></br>


##  63. <a name='Throwandthecallstack'></a>Throw and the call stack 

![](slides/Pasted%20image%2020231222115310.png)

<br></br>


![](slides/Pasted%20image%2020231222115319.png)

<br></br>


![](slides/Pasted%20image%2020231222115331.png)

<br></br>



![](slides/Pasted%20image%2020231222115344.png)

<br></br>


##  64. <a name='ExceptionTypesandHierarchies'></a>Exception Types and Hierarchies

![](slides/Pasted%20image%2020231222115938.png)

<br></br>

Runtime Exception -> Unchecked exception 
Error -> Unchecked exception. 
Unchecked exception need not be surrounded by try catch block. 
But Exception needs to be surrounded by try catch block. 

##  65. <a name='CustomExceptionClasses'></a>Custom Exception Classes 

![](slides/Pasted%20image%2020231222120528.png)

<br></br>

![](slides/Pasted%20image%2020231222120547.png)

<br></br>


![](slides/Pasted%20image%2020231222120601.png)

<br></br>


![](slides/Pasted%20image%2020231222120627.png)

<br></br>

![](slides/Pasted%20image%2020231222120644.png)

<br></br>


##  66. <a name='ThrowableandInheritedMethods'></a>Throwable and Inherited Methods 

![](slides/Pasted%20image%2020231222120853.png)

<br></br>


![](slides/Pasted%20image%2020231222120903.png)

<br></br>


![](slides/Pasted%20image%2020231222120932.png)

<br></br>


##  67. <a name='ExceptionHandlingBestPractices'></a>Exception Handling Best Practices 

![](slides/Pasted%20image%2020231222121443.png)

<br></br>


![](slides/Pasted%20image%2020231222121451.png)

<br></br>


![](slides/Pasted%20image%2020231222121817.png)

<br></br>
