# student-programme

Small project for Students to learn about the basics of Java in the Industry!

## Key things to remember

1. Google is your friend!  Forget how to change directory, list files or anything else in the command line?  Just Google the answer!

1. The student-programme mailing list is your friend! Google not giving you an answer? Or you want a deeper explanation, just ask there!

## README.md

This is a common file in all GitHub projects, it uses 
[GitHub Markdown formatting](https://help.github.com/articles/github-flavored-markdown)

# Getting started guide

## Command line

Remember the command line is what the industry uses and although it seems like a PITA to begin with, you **will** get used to it, but only if you practice!

The trickiest part will be adding the Git and Maven executables to your `PATH` so that **every** time you open up the command line it's available (we only set it temporarily in session II). Google questions like *"How do I add Maven to my PATH in Mac OS X"* and see if you can follow the instructions from there.

## Git / GitHub

So the first step is to remember how to use Git/Github!

1. Go to https://github.com/jClarity/student-programme
1. Fork the project so that you have your own remote repository at GitHub
1. Clone *your* repository to you local machine, e.g. For me (on the command line) I executed:

`git clone git@github.com:karianna/student-programme.git student-programme`

## Maven

The next step is to build the project using Maven.

1. Inside the student-programme directory see if you can build it using Maven, i.e. On the command line use:

`mvn clean install`

## Eclipse IDE

Once you've done all of that, then see if you can install the project into Eclipse.  You'll see a simple HelloWorld class and a Test which 'cheats' and just says "Yes I pass"!
