1. What is a class constructor and why is it needed?
   - A class constructor is a special method of a class that gets called automatically when an instance of the class (an object) is created. It typically has the same name as the class. Constructors are used to initialize the object's properties or to perform any setup steps required for the object to be in a consistent state before use. Constructors can be overloaded to allow objects to be initialized in different ways.

2. What is the meaning of the following access modifiers: “public”, “private”, “protected”, and “default”?
   - public: The member (method or variable) is accessible from any other class.
   - private: The member is accessible only within the class it is declared. It cannot be accessed from outside the class.
   - protected: The member is accessible within its own package (like default) and also by subclasses of its class in other packages.
   - default (no modifier): The member is accessible only within classes in the same package.

3. What is the meaning of the following non-access modifiers: “final” and “abstract”?
   - final: When applied to a class, it means the class cannot be subclassed. When applied to a method, it means the method cannot be overridden by subclasses. When applied to a variable, it means the variable's value cannot be modified (it becomes a constant).
   - abstract: This modifier can be applied to classes and methods. An abstract class cannot be instantiated on its own, and it exists to be subclassed. An abstract method does not have an implementation in the class where it is declared, and it must be implemented by subclasses unless the subclass is also abstract.

4. What is a Java package?
   - A Java package is a namespace that organizes a set of related classes and interfaces. Conceptually you can think of packages as being similar to different folders on your computer. Packages are used to avoid name conflicts and to control access, making it easier to manage large software projects. Packages can be nested by using dot notation in the package name (e.g., `com.example.project`).
