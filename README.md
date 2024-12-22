# Template Function Example in C++

A simple demonstration of function templates in C++ showing how a single function can work with multiple data types.

## Description

This program implements a template function `add()` that can perform addition operations on different data types. It demonstrates the power of generic programming in C++ through templates.

### Key Features
- Generic function template implementation
- Support for multiple data types
- Type-safe operations
- Pass by reference parameters

## Function Template Structure

```cpp
template<class T>
T add(T &a, T &b)
{
    T result = a+b;
    return result;
}
