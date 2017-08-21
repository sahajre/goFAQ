# goFAQ
The Go programming language introduction in the form of questions and answers.

## What is the purpose of GoFAQ?

This document is created using my own Go notes. The official [Go website](https://golang.org/) has very good documentation, including [FAQ](https://golang.org/doc/faq).  

I'm trying to keep my notes simple and concise. I believe these notes will help beginners to get familiar with Go quickly. Contributions and suggestions are most welcomed!

Note: I've just started learning Go (June '17). This document will grow as I learn more.

## What is Go?

Go is an open source programming language (which means source code for its compiler, libraries and tools is freely available to anyone. Go here (pun intended): https://github.com/golang).  

Go is a compiled (desinged for fast compilation), statically typed language (similar to C, C++, Java). It has garbage collection (automatic memory management). It has built-in support for writing concurrent programs. 

Other Gyan: One of the shortest complete sentences in the English language is 'Go.'.

## Who created the Go Programming language and when?

Go design was started in September 2007 by Robert Griesemer, Rob Pike and Ken Thompson at Google. It was publicly announced and also open sourced in November 2009. Go version 1 was released on 28th March, 2012.

## What were the main motivations/goals to create another programming language?
* Fast compilation
* Easy to use dependency management
* Utilize the emergence of multicore processors by providing buit-in easy to use concurrency features
* Simple type system. (trying to make it simple by not supporting type heirarchy)
* Developer productivity

## How to try Go programming?

As a starter, use the [Go playground](https://play.golang.org/). There is another similar [un-official service](https://goplay.space/).

You can also download and install the required tools on you local machine from [Go website](https://golang.org/).

## How is Go compared to C++ and Java?

This comparison is only meant for showing how concise Go compared to other languages. Please do not translate your C++ or Java programming thinking while writing Go programs. 

Feature                      | Go               | C++              | Java             |
:---                         |:---:             |:---:             |:---:             |
Statically typed             |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Object oriented programming  |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Variadic function            |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Defining constants           |:white_check_mark:|:white_check_mark:|:white_check_mark:|
```interface```              |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Statically compiled          |:white_check_mark:|:white_check_mark:|                  |
```struct```                 |:white_check_mark:|:white_check_mark:|                  |
<span>&lambda;</span> functions/Closures |:white_check_mark:|:white_check_mark:|      |
In-built concurrency support |:white_check_mark:|                  |                  |
Implicit ```implements```    |:white_check_mark:|                  |                  |
Designed for fast compilation|:white_check_mark:|                  |                  |
Anonymous functions          |:white_check_mark:|                  |                  |
datatype ```rune```          |:white_check_mark:|                  |                  |
A case body breaks automatically|:white_check_mark:|               |                  |
Function can return multiple values|:white_check_mark:|            |                  |
Declaring multiline strings using ```\````|:white_check_mark:|            |                  |
can return the address of a local variable|:white_check_mark:|     |                  | 
Arrays are values (assigning copies all the elements) |:white_check_mark:||           |
The size of an array is part of its type|:white_check_mark:||           |
```&``` address-of operator  |:white_check_mark:|:white_check_mark:|                  |
Garbage collection           |:white_check_mark:|                  |:white_check_mark:|
Pointers                     |:white_check_mark:|:white_check_mark:|                  |
```while```                  |                  |:white_check_mark:|:white_check_mark:|
```do { } while```           |                  |:white_check_mark:|:white_check_mark:|
```class```                  |                  |:white_check_mark:|:white_check_mark:|
```try { } catch() { }```    |                  |:white_check_mark:|:white_check_mark:|
Generics                     |                  |:white_check_mark:|:white_check_mark:|
Type inheritance             |                  |:white_check_mark:|:white_check_mark:|
Function overloading         |                  |:white_check_mark:|:white_check_mark:|
Explict ```implements```     |                  |:white_check_mark:|:white_check_mark:|
```;``` at the end of lines  |                  |:white_check_mark:|:white_check_mark:|
``?:`` Ternary operator      |                  |:white_check_mark:|:white_check_mark:|
Operator overloading         |                  |:white_check_mark:|                  |
Arrow (```->```) dereferencing|                 |:white_check_mark:|                  |
```final, abstract```        |                  |                  |:white_check_mark:|
```virtual, friend```        |                  |:white_check_mark:|                  |
```this```                   |                  |:white_check_mark:|:white_check_mark:| 
```static```                 |                  |:white_check_mark:|:white_check_mark:| 
Default function arguments   |                  |:white_check_mark:|                  |
Pointer arithmetic           |                  |:white_check_mark:|                  |  


## What is concurrency? Is it same as parallelism? How to achieve concurrency in Go programs? 

## How to write reusable libraries in Go?

## What are the different data types supported in Go?

## How to define a type in Go?

## How the scope of variable works in Go?

## How to create a constant value in Go?

## What is the difference between function and method in Go?

## How to implement polymorphic behavior in Go?

## How to handle files in Go?

## How to handle commandline arguments in Go?

## Does go support exception handling?

## How to format Go program?

## How to test Go program?

## How to create an array in Go?

## How to create a map in Go?

## What are different methods available for string manipulation?

## What are the basics of web programming in Go?

## Which popular companies use Go in production?

## What are the other references you would recommend?

Higly recommended:


Recommended:


