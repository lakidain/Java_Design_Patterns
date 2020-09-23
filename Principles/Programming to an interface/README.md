# Programming to an interface

Programming to an interface is beneficial to the clients:
They don't need to know the types of objects they use (if the object is adhered to the interface), neither the classes that implement these objects.

As an example in the code provided, the main class: Computer, wich executes in runtime, don't need to know if the object who uses display is of type Project or Monitor, it just know that because they implement the interface displayModule they can use the method display.

This reduces the implementation dependencies between systems. 
All this is summed up in using polymorphism so that the code is not locked to a concrete class.
