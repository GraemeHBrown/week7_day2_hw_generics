# Introduction to Generics

## Learning Objectives
- Know what generics are
- Understand when we would use generics
- Understand how to make a simple generic class

## Task
As an introduction to generics either:
- watch the following video: [Intro to Generics video](https://www.youtube.com/watch?v=rmF2csiNg14&feature=youtu.be)
- read `generics.md` in the `generics` directory

Answer the following questions:
1. What is one benefit of using generics in Java classes?  
  -It allows flexibility in terms of type.  Type can be decided when an instance is created rather than in the class definition.

2. Name an example of a generic class that we have used in Java?
  -ArrayList<E> is a generic as it can contain different types.

3. What is the syntax for declaring a generic class?
      public class Box<T> {

          // T stands for "Type"
          private T t;

          public void set(T t) {
            this.t = t;
          }

          public T get() {
            return t;
          }
      }
4. At what point does the generic type get specified?
  -compile time
5. Can generic types be of primitive type?
  -No generic types can only be instantiated with reference types.
6. Can a generic class take more than one type parameters?
  -yes it can have multiple type parameters
