# Aung Myat, April 22nd, 2022
# Lab Report 2
[Home Page](https://ruff1ezzz.github.io/cse15l-lab-reports/index.html)

***

**Lab 3:**

## 0) Pair Programming

In **Lab 3**, first, I watched an informational video on pair programming.

[Link to the pair programming video](https://www.youtube.com/watch?v=vgkahOzFH2Q&ab_channel=Code.org)

## 1) Getting Started

Then, I had to watch another video on how the a programmer incrementally coded the MarkDown parsing implementation. 

[Link to the implementation video](https://youtu.be/k67e-Icw4ug)

Afterwards, I answered questions on about the video, such as:
* How many times did the programmer use the internet to look up how to do something?
* Around what was the largest number of lines of code written in between runs of the program?
* Around how many times did the programmer use autocomplete on a variable name? How many typos do you think this helped avoid?

## 2) Getting and Running the Code

Furthermore, I was prompted to fork, which is a complete copy of the repository that sits in your account, a given repository, which contained two files:

* MarkdownParse.java
* test-file.md

Repository to fork - [link](https://github.com/nidhidhamnani/markdown-parser)

After forking/cloing the repository, I made sure I can run it by using the commands form the video:

* `javac MarkdownParse.java`
* `java MarkdownParse test-file.md`

Then we added print statements in the code to check and answer the following questions:

1) How many different values does `currentIndex` have when the program is run on the given example? What are they?

ANS - `currentIndex` has 3 different values when the code runs. They are 0, 39, 64.

2) What is the purpose of the second argument to `indexOf`? What would be different if it wasn't provided?

ANS - The purpose of the second `indexOf`, is to start the search for the starting argument form the position of the second argument. If there isn't a second argument there, an infinite loop would occur when you run the program due to a missing bound.

## 3) Finding a breaking test

Afterwards, my parter and I tried to come up with different tests until we get something that has incorrect behaviors (an error, an infinite loop, prints the wrong URLs, etc).

We then commited a new file and write out our test case.

