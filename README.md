# goFAQ
The Go programming language introduction in the form of questions and answers.

## What is the purpose of GoFAQ?

This document is created using my own Go notes. The official [Go website](https://golang.org/) has very good documentation, including [FAQ](https://golang.org/doc/faq).  

I'm trying to keep my notes simple and concise. I believe these notes will help beginners to get familiar with Go quickly. Contributions and suggestions are most welcomed!

Note: I've just started learning Go (June '17). This document will grow as I learn more.

## What is Go?

Go is an open source programming language (which means source code for its compiler, libraries and tools is freely available to anyone. Go here (pun intended): https://github.com/golang).  

Go is a compiled (intended to be fast compiled), statically typed language (similar to C, C++, Java). It has garbage collection (automatic memory management). It has built-in support for writing concurrent programs. 

By the way, one of the shortest complete sentences in the English language is 'Go.'.

## Who created the Go Programming language and when?

Go was conceived in September 2007 by Robert Griesemer, Rob Pike and Ken Thompson at Google. It was publicly announced in November 2009. Go version 1 was released on 28th March 2012.

## What were the main motivations/goals to create another programming language?
* Fast compilation
* Easy to use dependency management
* Utilize the emergence of multicore processors by providing buit-in easy to use concurrency features
* Simple type system. (making it simple by not supporting type heirarchy)

## How to try Go programming?

As a starter, use the [Go playground](https://play.golang.org/). Recently, there is another similar [un-official service](https://goplay.space/).

You can also download and install the required tools on you local machine from [Go website](https://golang.org/).

## How is Go compared to C++ and Java?

This comparison is only meant for showing how concise (but yet, powerful) Go compared to other languages. Please do not translate your C++ or Java programming thinking while writing Go programs. 

Feature                      | Go               | C++              | Java             |
:---                         |:---:             |:---:             |:---:             |
Statically typed             |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Object Oriented Programming  |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Variadic function            |:white_check_mark:|:white_check_mark:|:white_check_mark:|
Keyword ```struct```         |:white_check_mark:|:white_check_mark:|                  |
<span>&lambda;</span> functions/Closures |:white_check_mark:|:white_check_mark:|                  |
In-built concurrency support |:white_check_mark:|                  |                  |
Implicit ```implements```    |:white_check_mark:|                  |                  |
Designed for fast compilation|:white_check_mark:|                  |                  |
Anonymous functions          |:white_check_mark:|                  |                  |
datatype ```rune```          |:white_check_mark:|                  |                  |
Garbage collection           |:white_check_mark:|                  |:white_check_mark:|
Interface                    |:white_check_mark:|                  |:white_check_mark:|
Keyword ```while```          |                  |:white_check_mark:|:white_check_mark:|
Keyword ```do { } while```   |                  |:white_check_mark:|:white_check_mark:|
Keyword ```class```          |                  |:white_check_mark:|:white_check_mark:|
Generics                     |                  |:white_check_mark:|:white_check_mark:|
Type Inheritance             |                  |:white_check_mark:|:white_check_mark:|
Exceptions handling          |                  |:white_check_mark:|:white_check_mark:|
Function overloading         |                  |:white_check_mark:|:white_check_mark:|
Explict ```implements```     |                  |:white_check_mark:|:white_check_mark:|
Operator overloading         |                  |:white_check_mark:|                  |
keywords ```final, abstract```|                 |                  |:white_check_mark:|
keywords ```virtual, friend```|                 |:white_check_mark:|                  |
keyword ```this```           |                  |:white_check_mark:|:white_check_mark:| 

## What is concurrency? Is it same as parallelism? How to achieve concurrency in Go programs? 

Concurrency is the composition of independently executing computations. It is not parallelism. On a single processor your program can be concurrent, but it cannot be parallel.  

Go has in-built features _channel_ and _goroutines_ to write concurrently running function executions. _goroutines_ are analogus to background invocation of shell command using ```&```. It is independently executing function launched by using a ```go``` keyword.

A _channel_ provides a connection between two goroutines allowing them to communicate. _Channels_ are first class values in Go, which means you can pass them to function, return them from function, or you can assign them to a variable. _Channels_ are defined using ```chan``` keyword and initialize using ```make``` function. ```<--``` is used to send (e.g. ```channel_variable_name <- data```) and receive (e.g. ```data := <- channel_variable_name```) values from the _channel_. The sending and receiving on channel are blocking operation. 

Go concurrency slogan,
> Don't communicate by sharing memory, share memory by communicating.

## How to write reusable libraries in Go?

## How to define a type in Go?

## How to create a constant value in Go?

## What is difference between function and method in Go?

## What all different types Go can support?

## How to implement polymorphic behavior in Go?

## How to handle files in Go?

## How to handle commandline arguments in Go?

## Does go support exception handling?

## How to format Go program?

## How to test Go program?

## How to create an array in Go?

## How to create a map in Go?

## What are different methods available for string manupulation?

## What are the basics of web programming in Go?

## Which popular companies use Go in production?

## What are the other references you would recommend?



