---
title: Programming Classes
author: Dave Rolsky
type: page
date: 2015-06-20T19:26:36+00:00
---
I offer the following classes at conferences, and can be persuaded to come to your company and teach them for sufficiently reasonable sums of money. [Contact me to discuss this further][1].

## Introduction to Go

There are a few million new languages making buzz on the Internet these days, and Go is one of them! Go hits a nice sweet spot between ease of coding, speed of execution, and modern features such as type inferencing, concurrency, and a minimalist but well-designed OO system.

In this class, I'll introduce you to Go basics including syntax, the type system, OO in Go, packages and package management, and concurrency.

This is a hands-on course. Each lecture section is followed by a hands-on exercise section where you put what you've just learned into practice. The instructor will work with each student individually as needed to help you get the most from these exercises.

This class is aimed at anyone who wants to learn Go. You must have experience programming in at least one other language, but no assumptions are made about what language that is, nor are you expected to be familiar with Go.

Students are expected to bring a laptop with the most recent version of Go installed and an editor of their choice. You will also be expected to follow the instructions in the [class's git repository][2] in order to obtain a copy of the class slides and exercises.

Here are what some past students of this class have said:

  * "Dave's Intro to Go class got me up and running with Go quickly. The many exercises throughout the day helped the material sink in." - John Thompson
  * "The class was engaging with a series of sections: learning a new concept, coding the concept and validating the code against pre-written tests." - Anonymous Student

### Class Outline

  * $GOPATH, Toolchain, and the Ecosystem
  * From Zero to Code 
      * Basic variables, types, and scope
      * Functions
      * Naming
      * If statements
      * Imports
  * More Types 
      * Strings, arrays, slices, and maps
      * Type conversion
      * Structs
      * Pointers
  * More Statements 
      * Loops and switch
  * Error Handling
  * Unit Testing with "go test"
  * Types, Interfaces, and OO in Go 
      * Methods, Constructors, and Accessors
      * Interfaces
      * Runtime type checking
      * Type assertion and type switch
  * Concurrency 
      * Goroutines
      * Channels
      * sync.WaitGroup
  * Go Package Management 
      * Importing packages
      * go get
      * dep
      * gopkg.in

<hr class="wp-block-separator" />

## Introduction to Moose

This is an interactive hands-on course all about Moose, an OO system for Perl 5 that provides a simple declarative layer of "sugar" on top of a powerful, extensible meta-model.

With Moose, simple classes can be created without writing any subroutines, and complex classes can be simplified. Moose's features include a powerful attribute declaration system, type constraints and coercions, method modifiers ("before", "after", and "around"), a role system (like mixins on steroids), and more. Moose also has a vibrant ecosystem of extensions as seen in the variety of MooseX:: modules on CPAN.

This course covers Moose's core features, goes in depth on many of them, and explores some of the more powerful MooseX:: modules available on CPAN.

This is a hands-on course. Each lecture section is followed by a hands-on exercise section where you put what you've just learned into practice. The instructor will work with each student individually as needed to help you get the most from these exercises.

This class is aimed at Perl programmers who understand object-oriented programming and want to learn how to do it with Moose. It is not suitable for Perl beginners or for people without any OO experience. OO experience in other languages besides Perl is sufficient, as long as you also have a good grasp of Perl syntax, particularly method call syntax.

Students are expected to bring a laptop with a recent version of Perl and the editor of their choice. You will also be expected to clone the [class's git repository][3] in order to obtain a copy of the class slides and exercises.

This class has consistently received excellent evaluations from students who've taken it:

  * "I thought Dave's class was outstanding. Well prepared and highly valuable content. This course was one of the best organized I've had the opportunity to take." - Chris Fedde
  * "It damn sure was a good use! It would've been a huge mistake not taking your class; Moose is a magnificent beast and I couldn't have picked a better primer." - Brian Fraser
  * "The class was great. There was a nice balance of material presented to hands-on experimentation, and alternating between lecture and exercises helped nail down concepts." - Philip Monsen
  * "I had never used Moose previously, but the class gave me enough to get started on using Moose. The slide deck was awesome, and the presenter's mix of exercises and talk was perfect. Since the conference, I've started baby steps into using Moose in some of my projects, with good success thus far." - Joelle Maslak

### Class Outline

  1. Moose Concepts
  2. Moose Classes
  3. Roles
  4. Basic Attributes
  5. Method Modifiers
  6. Types
  7. Advanced Attributes
  8. Bonus: A Brief Tour of MooseX

 [1]: mailto:dave@houseabsolute.com
 [2]: https://github.com/autarch/intro-to-go-class
 [3]: https://github.com/moose/intro-to-moose
