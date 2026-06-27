Why did you use inheritance?
I used inheritance to avoid repeating code and to share common properties and methods between related classes. For example, different types of vehicles can inherit from a base Vehicle class, allowing them to reuse common features while adding their own unique behaviors.

Why did you use interfaces?
I used interfaces to define abilities or behaviors that different classes can implement. For example, IFlyable and IDriveable allow any class to fly or drive regardless of its place in the inheritance hierarchy, making the design more flexible and easier to extend.

Can Helicopter inherit from both Vehicle and Airplane? Why or why not?
No. In C#, a class can inherit from only one base class because C# does not support multiple inheritance for classes. A Helicopter can inherit from either Vehicle or Airplane, but not both at the same time.

Why can Helicopter implement both IFlyable and IDriveable?
A Helicopter can implement both interfaces because C# allows a class to implement multiple interfaces. This means the helicopter can have both flying and driving capabilities without inheriting from multiple classes.

If a Submarine can both sail and dive, how would you design it?
I would create a Submarine class that inherits from Vehicle and implements two interfaces, such as ISailable and IDiveable. This design allows the submarine to share common vehicle features while providing its own implementations for sailing and diving behaviors.
