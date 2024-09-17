---
title: "Activity 10: Object-Oriented Programming OOP in TypeScript"
datePublished: Tue Sep 17 2024 05:47:32 GMT+0000 (Coordinated Universal Time)
cuid: cm160ihia001z0ajz1aefcfwu
slug: activity-10-object-oriented-programming-oop-in-typescript

---

## **Research and Study OOP Concepts in TypeScript:**

* Understand how TypeScript implements Object-Oriented Programming principles.
    
* Focus on TypeScript’s features, such as strong typing, access modifiers, and how these enhance OOP practices.
    
    ## **Explain the Core OOP Concepts in TypeScript:**
    
* For each OOP concept, provide the following details:
    
    * **Definition:** A brief explanation of the concept.
        
    * **Key Features:** The important characteristics of the concept.
        
    * **How it’s Implemented in TypeScript:** Explain how to implement this concept in TypeScript.
        
    * **Example Code in TypeScript:** Provide a code snippet demonstrating how the concept works in TypeScript.
        
    
* ## **The key OOP concepts to cover are:**
    
    ## **Class and Object:**
    
    * **Definition**: A **class** is a blueprint for creating objects that encapsulate data (properties) and behavior (methods). An **object** is an instance of a class.
        
    * **Key Features**:
        
        * Classes define the structure and behavior of objects.
            
        * Objects are concrete instances of classes.
            
    * **Implementation in TypeScript**:
        
        * TypeScript allows you to define classes using the **class** keyword, and you can create objects from these classes using the new keyword.
            
    
    **Code in TypeScript**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726550956845/ae4f9a21-c568-4ce2-ab18-44b354fc1c46.png align="center")
    
    ## **Encapsulation:**
    
    * **Definition**: **Encapsulation** is the concept of bundling data (properties) and methods that operate on the data within a single unit (class), and restricting access to certain components using access modifiers.
        
    * **Key Features**:
        
        * Protects the internal state of the object.
            
        * Allows controlled access through public methods.
            
    * **Access Modifiers in TypeScript**:
        
        * `public`: Accessible from anywhere.
            
        * `private`: Accessible only within the class.
            
        * `protected`: Accessible within the class and its subclasses.
            
    
    **Code in TypeScript**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551119591/e3bebbea-e1e3-445f-b249-f29eb35c582c.png align="center")
    
    ## **Inheritance:**
    
    * **Definition**: **Inheritance** allows a class (child) to inherit properties and methods from another class (parent).
        
    * **Key Features**:
        
        * Promotes code reuse.
            
        * Subclasses can extend and customize behavior from the parent class.
            
    * **Implementation in TypeScript**:
        
        * Use the `extends` keyword to create a subclass. Methods in the subclass can override methods in the parent class.
            
    
    **Code in TypeScript**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551264406/25f958ee-dd9b-47b6-baf4-5d4f73c88f9a.png align="center")
    
    ## **Polymorphism:**
    
    * **Definition**: **Polymorphism** allows one method to be used in different ways, or for different objects to be treated as instances of the same class.
        
    * **Types**:
        
        * **Method Overriding (Runtime Polymorphism)**: A subclass provides a specific implementation of a method defined in its superclass.
            
        * **Method Overloading (Compile-Time Polymorphism)**: TypeScript achieves this through optional parameters or union types, allowing different signatures for the same method.
            
    
    **Code in TypeScript (Method Overriding)**:
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551418808/a048b159-0818-4f03-9a37-5e0073e45504.png align="center")
    

**Code in TypeScript (Method Overloading)**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551561304/a104bbea-1e2b-49e4-8cf1-ba62a1aa49de.png align="center")

## **Abstraction:**

* **Definition**: **Abstraction** hides the implementation details and only exposes essential features.
    
* **Key Features**:
    
    * Achieved using abstract classes or interfaces.
        
    * Abstract classes provide partial implementation.
        
    * Interfaces define a contract without implementation.
        
* **Implementation in TypeScript**:
    
    * Abstract classes have abstract methods that must be implemented in derived classes.
        
    * Interfaces define method signatures without implementation.
        

**Code in TypeScript (Abstract Class)**:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551639995/5d880901-0acb-407a-a9fa-670c619f4be0.png align="center")

## **Additional OOP Concepts to Include:**

## **Interfaces:**

* **Definition**: An **interface** defines the structure of an object, specifying properties and methods without implementing them.
    
* **Key Features**:
    
    * Helps define a contract for classes or objects.
        
    * Promotes flexibility and abstraction.
        
    
    **Code in TypeScript:**
    
* ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551749956/12cd2953-6304-446b-b1fe-0677b1f59f00.png align="center")
    
    ## **Constructor Overloading:**
    
    * **Definition**: **Constructor overloading** in TypeScript is achieved using optional parameters, allowing a class constructor to accept different sets of arguments.
        
    * **Code in TypeScript**
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726551961536/70d5f3e7-2c1c-4cc4-b95f-4b63bcc101bb.png align="center")
        
    
    ## **Getters and Setters:**
    
    * **Definition**: **Getters** and **setters** are special methods that allow controlled access to properties in a class.
        
    * **Code in TypeScript**:
        
    * ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1726552029938/251f4ce4-b25d-49b3-a521-59f6a18a3b9c.png align="center")
        
    
    ### **Deliverables**:
    
    * **Detailed Explanation**: Each core OOP concept is explained in terms of its definition, features, and TypeScript implementation.
        
    * **Code Snippets**: Each section includes practical examples of how to implement OOP concepts in TypeScript, ensuring that readers understand how to apply them effectively.