# Runtime Polymorphism Using Virtual Functions and Abstract Classes

Object Oriented Programming Using C++ - Lab Manual, Ex.No 2 (Chennai Institute of Technology).

An abstract `Shape` class with a pure virtual `area()` function, implemented by `Circle`, `Rectangle` and `Triangle`. A base-class pointer calls the right `area()` at runtime.

## Build and run

```
g++ -std=c++17 main.cpp -o shapes
./shapes
```

## Output

```
Area of Circle: 78.5
Area of Rectangle: 24
Area of Triangle: 40
```
