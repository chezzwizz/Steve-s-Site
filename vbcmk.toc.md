# Visual Basic .Net Custom Types
## Classes
  In the OOP paradigm, classes are used to define object constructs that have	associated methods and
  properties which are used by the programmer to interact with an instansiated class in the program.

  In Visual Basic, the class constuct is similar to other OOP languages in how it is defined. The
  `Class` keyword is used to declare a custom object template type. To declare a class within a given
  _decleration space_, one would type the following:

  ```
    Class C
      ' Class properties and methods are defined in this space known as the
      ' decleration space.
    End Class
  ```

## Structures

## Enums

## Concepts

  1. __fully qualified name__: The identifier of an object to include the decleration context identifiers.
  1. __type signature__: The fully qualified identifier (name) of a type with modifiers and parameter
     declerations.
  1. __decleration space__: The range of context associated with a set of definitions and declerations.
  1. __decleration context__: The "parent" or containing decleration space in  which other decleration
     spaces are created.
  1. __decleration__: The point in the program at which the unique signature is specified, but not necessarily
     associate with a value. In Visual Basic, the `Dim` (Declare In Memory) keyword is used	to specify a
     decleration. This operation creates a "blank" area in memory	that is the size of the specified type based
     on the _type signature_ of an object.
  1. __definition__: The point at which a declared object is assigned a value. When a variable is defined, the
     memory that was _declared_ previously gets modified to represent the data which conforms to the constraints
     of the specified _signature_.
