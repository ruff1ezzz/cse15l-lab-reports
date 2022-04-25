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

* `MarkdownParse.java`
* `test-file.md`

Repository to fork - [link](https://github.com/nidhidhamnani/markdown-parser)

After forking/cloing the repository, I made sure I can run it by using the commands form the video:

* `javac MarkdownParse.java`
* `java MarkdownParse test-file.md`

Then we added print statements in the code to check and answer the following questions:

1) How many different values does `currentIndex` have when the program is run on the given example? What are they?

**ANS** - `currentIndex` has 3 different values when the code runs. They are 0, 39, 64.

2) What is the purpose of the second argument to `indexOf`? What would be different if it wasn't provided?

**ANS** - The purpose of the second `indexOf`, is to start the search for the starting argument form the position of the second argument. If there isn't a second argument there, an infinite loop would occur when you run the program due to a missing bound.

## 3) Finding a breaking test

Afterwards, my parter and I tried to come up with different tests until we get something that has incorrect behaviors (an error, an infinite loop, prints the wrong URLs, etc).

We then commited a new file and write out our test case.

Shortly after, we had to answer another question - Why bother making a commit at this point? What benefit might that have in the future? How might it help a staff member who is answering your question on Piazza?

**ANS** - By making a commit, it allows us to see the history of our commit in our main repository and helps the staff member on Piazza to easily spot it in our github accounts by tracking what we did wrong step by step.

## 4) Improving the program

Then we started to perform incremental coding. Incremental coding means to start from a few lines, to minimize errors and to avoid debugging long lines of codes. With this practice my partner and I tried to develop a better program to parse markdown files.

![incremental](images/markdownediting.png)

We tried to come up with a better solution to eliminate edge cases such as having an extra paranthesis in side the website like the following:

`[https://www.goo(g)le.com]`

Although we couldn't completely find the solution, we learned the practices of incremental development and later we commited our effort into the main github to get a feedback from tutors.

## 5) Repeating the process

Finally, we repeated the same process of first finding a failed test and then performing incremental development to fully improve the program.

**Lab 2:**

I couldn't make it to this lab due to health reasons so I worked on it myself.

## 1) Your memory

Firstly, I re-tested the `MarkdownParse.java` file with the given `test-file.md` by entering the code `java MarkdownParse.java test-file.md` into the terminal. 