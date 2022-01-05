<p align="center">
<img src="https://static.javatpoint.com/tutorial/software-engineering/images/software-engineering-object-oriented-design.png" width="300"/>
</p>

## UNIT-1 `AN OVERVIEW OF OBJECT ORIENTED SYSTEM DEVELOPMENT`

**Object-oriented analysis and design** (OOAD) is a software engineering approach that models a system as a group of interacting objects. Each object represents some entity of interest in the system being modeled, and is characterized by its class, its state (data elements), and its behavior.
- Object is a combination of data and logic that represents some real world entity.
- `Data` are termed as `Attributes` and also _`Logic`_ is termed as _`Functions`_.  

- The primary tasks in object-oriented analysis (OOA) are −

   -  Identifying objects.
   -  Organizing the objects by creating object model diagram.
   -  Defining the internals of the objects, or object attributes.
   -  Defining the behavior of the objects, i.e., object actions.
   -  Describing how the objects interact.


### `BASIC DEFINITIONS`

### -> **Class** :
A class is a `blueprint` for creating objects. It can also be stated as a "template for the objects"
- It is a user-defined type that describes what a certain type of object will look like
- Collection of objects having same characteristic properties that exhibit common behavior is called lass. It is a `logical entity`.
- Class doesn't consume the space and is used for declaring and creating the objects.


### --> **Class Diagram** : 
The Class Digram is the main building block of object-oriented modeling 

- A class diagram resembles a flowchart in which classes are portrayed as boxes, each box having three rectangles inside. The top rectangle contains the name of the class; the middle rectangle contains the attributes of the class; the lower rectangle contains the methods, also called operations, of the class. 
- A Class Diagram is a diagram describing the structure of a system that represents 
   * Classes 
   * Attributes 
   * Operations(methods)
   * Relationship between the classes 

![class diagram](https://www.tutorialspoint.com/uml/images/notation_class.jpg)


### -> **OBJECT** :
Object is an `instance of a class`. An object in OOPS is nothing but a self-contained component which consists of methods and properties to make a particular type of data useful. An Object is anything, real or abstract, about which we store data and
those methods that manipulate the data.
- In an object-oriented system, everything is an object: numbers, arrays,
records, fields, files, forms, an invoice, etc.
- A object is an `entity`
    - It knows things (availability of attributes)
    -  It does things (provides methods)

### **Example** demonstration for the inter-relation between the terms "Class" and "Object" :
<p align="center">
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/C%2B%2B_OOPs_Example1.PNG" width="250" />
</p>

- here, `Class` is the thing or domain called 'Car' and is demonstrating how a normal car should look like
    - and there goes three different things, (_`Object`_) following how a 'Car' should be and with different attribute(color)

### -> **ENCAPSULATION** :
Encapsulation is the process of `binding` both attributes and methods together within a class. Or like bundling of data, along with the methods that operate on that data, into a single unit.
- This concept is also often used to hide the internal representation, or state, of an object from the outside.
- Internal details of a class can be hidden from outside and can give the control access to the internal state of the object.
- Encapsulation enables data hiding, `hiding irrelevant information` or like sensitive details, showing only relevant and important things required by the user.
- Often referred as preventing or `restricting the direct access` for the unauthorized parties.

<p align="center">
<img src="https://csharpcorner-mindcrackerinc.netdna-ssl.com/UploadFile/e881fb/learn-object-oriented-programming-using-C-Sharp-part-5/Images/Encapsulation.jpg" width="250" />
</p>

### -> **INHERITANCE** :
Mechanism of `deriving a class` from another class for a hierarchy of classes that share a set of attributes and methods. Or like basing an object or class upon another object or class, retaining similar implementation and methodology.
- A class can get some of its characteristics from a parent class and then add unique features of its own.
- The real advantage of inheritance is that we can build upon what we
already have and can reuse what we already have(`Reusability`)

<p align="center">
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20190704114709/Inheritance-3.jpg" width="250" />
</p>

### -> **POLYMORPHISM** :
Ability of any data to be processed in more than one form is known as "Polymorphism". Or like one operation can be used for different purposes.
- Poly means many and morph means form.  
