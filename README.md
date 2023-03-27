# oops
# What is class?
A C++ class combines data and methods for manipulating the data into one. Classes also determine the forms of objects. The data and methods contained in a class are known as class members. A class is a user-defined data type. To access the class members, we use an instance of the class. You can see a class as a blueprint for an object.

# Private and Public Keywords
You must have come across these two keywords. They are access modifiers.
### Private:
When the private keyword is used to define a function or class, it becomes private. Such are only accessible from within the class.

### Public:
The public keyword, on the other hand, makes data/functions public. These are accessible from outside the class.

#### What is a Private Class?
Class members marked as private can only be accessed by functions defined within the class. Any object or function defined outside the class cannot access such members directly. A private class member is only accessed by member and friend functions.

### What is a Protected Class?
Class members marked as protected have an advantage over those marked as private. They can be accessed by functions within the class of their definition. Additionally, they can be accessed from derived classes.

# Constructors and Destructors
### What is Constructors?
Constructs are special functions that initialize objects. The C++ compilers calls a constructor when creating an object. The constructors help to assign values to class members. Of course, this is after they have been allocated some memory space.

### What is Destructors?
Destructors on the other hand help to destroy class objects.

The constructor name must be similar to the class name. Constructors do not have a return type.

The constructor can be defined inside or outside the class body. If defined outside the class body, it should be defined with the class name and the scope resolution operator (::).
