# correct_cpp_hello_world

Branch|[Travis CI](https://travis-ci.org)|[Codecov](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/correct_cpp_hello_world.svg?branch=master)](https://travis-ci.org/richelbilderbeek/correct_cpp_hello_world)|[![codecov.io](https://codecov.io/github/richelbilderbeek/correct_cpp_hello_world/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/correct_cpp_hello_world/branch/master)

[Correct C++](https://github.com/richelbilderbeek/correct_cpp) chapter 'Hello world'.

## Goal

 * Write a ['Hello world' program](https://github.com/richelbilderbeek/cpp/blob/master/content/CppHelloWorld.md)

## Prerequisites

 * Understand [how this course works](https://github.com/richelbilderbeek/correct_cpp/blob/master/how_this_course_works.md)

## Exercise

Write a 'Hello world' program. 

You'll start with:

```c++
main()
{
  // Your code here
}
```

The text should literally be `Hello world`, followed by newline. 

 * Use (and prefer [1]) [std::cout](https://github.com/richelbilderbeek/cpp/blob/master/content/CppStdCout.md) 
 * Do not use [std::endl](https://github.com/richelbilderbeek/cpp/blob/master/content/CppStdEndl.md) [2]

## External links

 * [Download the Qt Creator file `main.pro`](https://raw.githubusercontent.com/richelbilderbeek/correct_cpp/master/shared/main.pro)

## References

 * [1] [C++ Core Guidelines: SL.io.3: Prefer iostreams for I/O](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rio-streams)
 * [2] [C++ Core Guidelines: SL.io.50: Avoid endl](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rio-endl)
