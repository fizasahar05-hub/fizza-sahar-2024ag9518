# fizza-sahar-2024ag9518
This repository contains simple C# programs that explain the concept of Inheritance in Object-Oriented Programming.
The examples show how base (parent) classes and derived (child) classes work together.
The purpose of this project is to help students understand inheritance in an easy and practical way.
Core Concepts of Inheritance
1.Base Class (Parent Class): This is the class whose members are inherited. It defines the common characteristics and behaviors that its derived classes will share.
2.Derived Class (Child Class): This is the class that inherits from the base class. It can add new members (fields and methods), override the inherited members to provide a specialized implementation, or simply use the inherited members as they are.
3.: Syntax for Inheritance: In C#, you use a colon (:) followed by the name of the base class when declaring a derived class.4.protected Access Modifier: Members declared as protected in a base class are accessible within the base class itself and in any of its derived classes. They are not directly accessible from outside the class hierarchy. This is often used to provide access to members that derived classes might need while still restricting external access.
5.virtual and override Keywords:
The virtual keyword is used in the base class to declare a method or property that can be overridden (reimplemented) in a derived class.
The override keyword is used in the derived class to provide a specific implementation for a virtual member inherited from the base class.
6.base Keyword: Within a derived class, the base keyword is used to access members of the base class. This is particularly useful when you override a method but still want to call the base class's implementation. It's also used to call the constructor of the base class from the derived class's constructor.
7.Constructors in Inheritance: When you create an instance of a derived class, the constructor of the base class is executed first (implicitly or explicitly using base(...)). This ensures that the base class is properly initialized before the derived class's initialization takes place.
8.Single Inheritance: C# supports single inheritance, meaning a class can inherit directly from only one base class. However, you can achieve a form of multiple inheritance through interfaces.
![WhatsApp Image 2025-12-27 at 1 12 29 PM](https://github.com/user-attachments/assets/e15a5828-676c-4872-b4c5-afe990b47d95)
![WhatsApp Image 2025-12-27 at 1 12 30 PM (1)](https://github.com/user-attachments/assets/6132da30-eef7-482f-96f9-c0491a9006eb)
![WhatsApp Image 2025-12-27 at 1 12 30 PM (1)](https://github.com/user-attachments/assets/802dd284-da38-40b7-9e88-21f9d39a7240)
