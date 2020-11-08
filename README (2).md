# Welcome to Programming and Python

<img src="assets/cuts.jpg" width="500" />

Our journey into programming begins with the fundamentals of any modern programming language: basic data types, variables and control flow.

We'll be discussing the why these are fundamental topics to learn as a developer and how you can combine them to write your first programs.

But first, let's get the basics out of the way.

## What is Programming?

* **Programming** is the process of solving problems through code
   * We don't solve it just once, we solve it for good
   * Like writing down a recipe!
   * We write down this "recipe" with **code**
* **Code** is a general term for instructions that computers can understand and execute
   * In other words: "Programming Language"
   * There are many types of programming languages that exist. We're starting your journey with the Python language

## Programming Languages

There are two types of programming languages: **compiled languages** or **dynamic languages**. (Different programmers may prefer different terms, but they are all basically interchangable.)

### Compiled Languages / Lower-Level Languages

* Examples: Assembly, C, C++
* Generally interact directly with the computing hardware
* Requires the developer to manage the resources available on the physical computer through their code
* Useful when you have very limited resources or need a great deal of responsiveness/speed
* Requires a **compilation** step before the program can be used (Write :arrow_right: Compile :arrow_right: Run)
   * We can't immediate run the code - the computer can't just read the code, and needs to translate it to something it understands first (called **machine code**)
   * Compile means "build"
   * Write code, *then compile it (not quick!),* then run it
   * Find a bug? Fix it, *wait for the code to compile,* run it, repeat

<img src="assets/compiling.png" width="300" />

Source: [XKCD](https://xkcd.com/303/)

### Dynamic Languages / Higher-Level Languages

* Examples: Python, Ruby, JavaScript
* Hardware details are taken care of by the language, so that developers can solve more general problems
* More expressive, meaning it allows solutions to be written in terms of "what to accomplish" rather than describing each step of "how to accomplish it"
* Useful for creating programs that work across multiple platforms
* Are **interpreted** rather than **compiled**, saving a compilation step (Write :arrow_right: Run)
   * Write code, then immediately run it
   * Find a bug? Fix it, run it, repeat.
* Are themselves written in a lower-level language like C

Dynamic languages are also called **scripting languages**. What's the difference between **scripting** and **dynamic** languages? According to [this article](https://www.cio.com/article/2373686/the-differences-between-dynamic-scripting-languages-and--regular--languages-no-longer-matt.html), there is none! Those words can be used interchangeably.
    
> Meanwhile, somewhere in there, "scripting languages" turned into "dynamic languages;" if anybody makes a technical distinction between "scripting" and "dynamic," I don't know what it is.

## What is Python?

* High-level (not low-level)
* Dynamic (not compiled)
* Created with readability in mind
* General purpose - popular for many types of tasks:
   * Web development
   * Scientific computing
   * Numeric data processing
   * Scripting/Automating tasks
   * Even game development!
* Python 2 vs Python 3
   * We are using Python 3, the latest
   * Python 2 was officially retired on [Jan 1, 2020](https://pythonclock.org)

### When **NOT** to Use Python

Other programming languages exist - Python isn't great for everything!

* Mobile apps
* Huge programs
* High-performance games

# How To Run Python Programs

## Command Line

Running Python programs is pretty straightforward and is done from the command line:

```bash
python my_program_file.py
```

We'll be seeing lots of this soon. But first let's see another way of running Python programs.

## Python REPL

Another way to run Python programs is interactively, through the Python ***REPL***, which stands for **R**ead, **E**valuate, **P**rint, **L**oop (pronounced "**REH**-pull").

If you just run `python` on the command line (without specifying the name of a file), you are launched into a program that allows you to run Python statements interactively within the terminal instead of writing them in a file. 

This is the Python REPL, and it allow us to experiment with code and see what's possible.

Let's try it. Run the command `python` on its own to start the Python REPL:

![!Python REPL from the terminal](assets/python_repl.png)

Now you can type in some code and the Python REPL will automatically output the result. As a simple example, type in `1 + 1` and press enter. The Python REPL will respond by printing `2`.

Though this won't let you save your program to run again later, it's a great way to play around with code and see what's possible.

You can type `exit()` or hit `Ctrl-D` at any time to return back to the operating system shell.

### We Do: Python REPL Exercises

Start the Python REPL and try running each of these commands, one at a time.

Make sure you type them out yourself rather than copying and pasting. You'll learn much more that way.

* `5 + 1`
* `1`
* `5`
* `3 + 7 + 1`
* `5 * 3`
* `5 * 3 # multiplication uses the asterisk (*), not the letter x`

As you can see, Python can do math!

But what's happening in that last line of code? If you write a pound/number sign (`#`) Python ignores everything that comes after it until the end of the line. So you can (and should) use it to write useful **comments** throughout your code.

Comments make it easier for you to understand your code when you come back to it in future and no longer remember how it works. They also serve the same purpose for other people who might be trying to read your code.

Using the Python REPL to experiment with bits of Python code as you work on future assignments and projects is an excellent habit to get into!

---

# Python Practice Resources

Here are some great resources for daily practice problems:

* [https://www.hackerrank.com](https://www.hackerrank.com)
* [https://www.codewars.com](https://www.codewars.com)
* [https://www.coderbyte.com](https://www.coderbyte.com)
* [https://www.codefights.com](https://www.codefights.com)
* [https://projecteuler.net](https://projecteuler.net)
* [https://github.com/shannonturner/python-lessons](https://github.com/shannonturner/python-lessons)

---

# Additional Resources

* [Python For Beginners](http://www.pythonforbeginners.com/basics/python-variables)
