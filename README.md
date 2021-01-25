# Embedded Systems Circle Roadmap
This is a learning path for embedded software.

# Contents
- [About us](#about-us)
- [Why Embedded Systems?](#why-embedded-systems?)
- [What is an Embedded System?](what-is-an-embedded-system?)
- [Roadmap](#roadmap)

# About us

We're a committee among other technical committees in [CAT Reloaded](https://www.facebook.com/CATReloaded). It was established on March 3, 2020. I start by communicating with some pros in the Embedded software field to find a learning path, and here is it.

---

# Why Embedded Systems?

One of the more surprising developments of the last few decades has been the ascendance of computers to a position of prevalence in human affairs. Today there are more computers in our homes and offices than there are people who live and work in them. Yet many of these computers are not recognized as such by their users. These computers konwn as embedded computers.

---

# What is an Embedded System?

See [this](https://www.youtube.com/watch?v=U8Zv25P1M6w) to know the definition of embedded systems and [this](https://www.youtube.com/watch?v=KDs3qlvmcvY) for more details about the market and positions.

---

# Roadmap

**Roadmap version**: `1.0`

- [Prerequisites](#prerequisites)
- [Intro Materials](#intro-materials)
- [C Programming](#c-programming)
  - [C Basics](#c-basics)
  - [Advanced C](#advanced-c)
- [Data Structures Algorithms](#data-structures-and-algorithms)
- [Microcontroller Interfacing](#microcontroller-interfacing)
  - [AVR](#avr)
  - [ARM Cortex](#arm-cortex)
- [RTOS](#rtos)
  
---

## Prerequisites

- [Micro-controller Interfacing](#microcontroller-interfacing) assumes the student has already taken a course on [digital logic](https://github.com/DrWaleedAYousef/Teaching/tree/master/DigitalDesign) and [computer organization](https://www.youtube.com/playlist?list=PLhwVAYxlh5dvB1MkZrcRZy6x_a2yORNAu). If you don't have enough time, this [course](https://www.coursera.org/learn/build-a-computer) will be good for now.
- [RTOS](#rtos) assumes the student has already taken a course on [operating systems](http://pages.cs.wisc.edu/~remzi/Classes/537/Spring2018/)

## Intro Materials

Before you start learning embedded systems you need to equip yourself in the following fields:

1. Fundamentals of Electrical.
2. Fundamentals of Analog Electronics.

### [Introduction to Electrical Engineering and Computer Science](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/index.htm)
This course provides an integrated introduction to electrical engineering and computer science, taught using substantial laboratory experiments with mobile robots. Some programming experience is good, but not necessarily required. The [Python Tutorial](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-01sc-introduction-to-electrical-engineering-and-computer-science-i-spring-2011/python-tutorial/) is designed to get students up to speed with Python, while a course like [Python for Everybody](https://www.py4e.com/lessons) may be useful for students will little or no programming experience.

**Topics covered**:
`fundamental design principles of modularity and abstraction`
`making mathematical models of real systems`
`modern software engineering`
`linear systems analysis` 
`electronic circuits`
`decision-making`


### [Introduction to Computer Science and Programming in Python](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/index.htm)
This course is intended for students with little or no programming experience. It aims to provide students with an understanding of the role computation can play in solving problems and to help students, regardless of their major, feel justifiably confident of their ability to write small programs that allow them to accomplish useful goals. The class uses the Python 3.5 programming language.

**Topics covered**:
`computation`
`imperative programming`
`basic data structures and algorithms`
`and more`

### [Analog Electronics](https://www.youtube.com/playlist?list=PLBlnK6fEyqRiw-GZRqfnlVIBz9dxrqHJS)
No prerequisites are required to start this course. This lecture series will cover the entire syllabus of Analog Electronics, starting from semiconductor materials to power amplifiers. **You can stop at Chapter 05: DC Biasing of Transistors.** The goal here is to **PRACTICE**. So, buy components and start playing.

**Topics covered**:
`Semiconductor Physics`
`Semiconductor Diode`
`Diode Applications`
`Bipolar Junction Transistors`
`DC Biasing of Transistors`

## C Programming

### *C Basics*
You'll learn the same topics covered in the [Introduction to Computer Science and Programming in Python](#introduction-to-computer-science-and-programming-in-python) but in C. So, the goal here is to learn C syntax and then the structure of the language. You will need to setup an IDE to run C code on it, I highly recommend [CLion](https://www.jetbrains.com/clion/).

### [C Programming: A Modern Approach by K N King](https://www.amazon.co.uk/C-Programming-Modern-Approach-King/dp/0393979504)
Chapters 1 to 7 the basic topics in the language. Chapters 8 to 20 covers the strucuture of the language. You'll need to practice alot, so, start do programming projects from the book and outside it.

**Topics covered**:
`what is C`
`formatted input/output`
`expressions`
`conditions and loops`
`data types`
`functions`
`arrays`
`pointers`
`strings`
`structures, unions, and enums`
`bit manipulations`
`and more`

### *Advanced C*
You'll learn core techniques for memory management using pointers.

### [Understanding and Using C Pointers: Core Techniques for Memory Management by Richard M. Reese](https://www.amazon.co.uk/Understanding-Using-Pointers-Richard-Reese/dp/1449344186)
Read the whole book and do a lot of practice.

**Topics covered**:
`dynamic memory allocation`
`pointers and functions`
`pointers and arrays`
`pointers and strings`
`pointers and structures`
`and more`

## Data Structures and Algorithms

“Bad programmers worry about the code. Good programmers worry about data structures and their relationships.”
— Linus Torvalds (creator of Linux)

Here you'll gonna learn the basic data structures like: stacks, queues, lists, and trees. Also you learn how to implement them in C.

### [CS214: Data Structures](https://www.youtube.com/playlist?list=PLoK2Lr1miEm-5zCzKE8siQezj9rvQlnca)
You'll find the course assignments [here](https://github.com/DrWaleedAYousef/Teaching/tree/master/DataStructures) and the book [here](https://drive.google.com/file/d/1kyp1kVFv3QIKyKJ7NawX93BjGy5Qmpt6/view?usp=sharing).

Along with this course, take an [introduction to discrete mathematics](https://www.youtube.com/playlist?list=PLoK2Lr1miEm_WKBBBHUQJRXaumduqkM4S) to follow up with the lecturer. Discrete math is a MUST to understand the lectures from 15 to 21, so take it in parallel with data structures course.

**Topics covered**:
`encapsulation and ADT`
`stacks`
`queues`
`lists`
`linear search`
`binary search`
`analysis of algorithms`
`trees`
`graphs`

After this course I highly recommend you to do a large-scale project. check [this](https://github.com/rby90/Project-Based-Tutorials-in-C).

### [Divide and Conquer, Sorting and Searching, and Randomized Algorithms](https://www.coursera.org/learn/algorithms-divide-conquer)
You'll learn techniques on analyzing your code, and learn some classic algorithms like: divide and conquer, sort, search, ans so on.

**Topics covered**:
`"big-oh" notation`
`asymptotic analysis`
`Divide-and-conquer basics`
`QuickSort`
`Linear-time selection`
`graphs`
`cuts`
`contraction algorithm`

## Microcontroller Interfacing
Here is the real start on learning embedded systems. The first thing here is to choose a micro-controller to work with. You MUST practice everything you learn here. I recommend working with AVR microcontrolleres.


### *AVR*

### [Make: AVR Programming: Learning to Write Software for Hardware by Elliot Williams ](https://www.amazon.co.uk/Make-Programming-Learning-Software-Technology/dp/1449355781)
The book is divided into three parts:

Part 1: covers the material you’ll need to know for most AVR projects. 

Part 2: makes you a more efficient programmer of the chip and expands the universe of what you’ll think an AVR can do. You’ll start doing cool things with the internal hardware peripherals and some more sophisticated tricks in firmware using what you already know. 

Part 3: Once you’ve mastered the AVR itself, this last section of the book is dedicated to using modern communications protocols to interface with other devices, building the circuitry you need to drive motors and other electrical devices, and covering a few more of the features of the AVR that you may or may not need every day.

Along with the book you MUST read the datasheet of the device you use.

**Topics covered**:
`microcontrollers`
`avr`
`serial i/o`
`adc`
`hardware interrupts`
`timers and counters`
`pwm`
`motors`
`comunication protocols`
`and more`

### *ARM Cortex*
The goal here is to apply the same concepts you learn on AVR to a large-scale microcontroller like ARM.

### [Embedded Systems - Shape The World: Microcontroller Input/Output](https://www.edx.org/course/embedded-systems-shape-the-world-microcontroller-i)

### [Embedded Systems - Shape The World: Multi-Threaded Interfacing](https://www.edx.org/course/embedded-systems-shape-the-world-multi-threaded-in)


**Topics covered**:
`embedded systems using modular design and abstraction`
`build and test circuits with switches, LEDs, resistors, potentiometers, and liquid crystal displays`
`Synchronizing hardware and software input/output with switches, lights, sound, sensors. motors, and liquid crystal displays`
`finite state machine`
`debugging`
`how to read datasheet`
`traffic light controller`
`Implement an I/O driver and multi-threaded programming using interrupts`
`iot`
`and more`

## RTOS

**Soon**...

























