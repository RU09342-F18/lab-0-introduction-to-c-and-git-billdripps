# Lab Exercise 0: Introduction to C, Git, and the MSP430
This lab is meant to be a gentle introduction to working with the code provided over github, adding your own code, C programming, and getting your launchpads to work. The due date for this Lab exercise is the date of submission for the Milestone project.

## Assignment
The overall goal of this exercise is to generate a "math.c" and "math.h" file that can eventually be placed into an example UART Calculator code. You will be responsible for generating the function as prototyped in the "math.h" file provided, and includes the capability to add, substract, multiply, integer divide, and modulus. This hopefully will be a simple task, and you will not need to worry about getting this specific code to run on your processor.  So what you need to do to complete this is:
1. Generate a new repository to work in from Github classroom (if you are reading this, you most likely have done this).
2. Run the example code provided to ensure that you can communicate over UART to your launchpads.
3. Import the assignment files and generate a math.c file from the provided prototype in the corresponding math.h
4. Upload your code with documentation back to your repository.
5. Update your README.md files with documentation similar to those found in the assignment files.


## Lab "Report"
Good news! You do not have to write a lab report on what you do in this lab. Instead, we would rather see you develop your documentation skills so that the code you develop can be used by yourself and others in the future. What this means is that you will have to learn how to write what you are reading right now, a README.md. You are responsible for each set of code (.c and .h file) to generate documentation on the software, its use, and how it works.

### Jekyll Markdown
You might notice a file in your repository with a .yml configuration. This is a configuration file for the built in Github Pages generator to utilize. With each of your repositories, you can actually generate a website for free. Other than the website, you may notice in your repository page that the text below the files are formatted. This also comes from that markdown. There are a ton of guides on how to use Github markdown and it requires no experience with HTML, such as [Mastering Markdown](https://guides.github.com/features/mastering-markdown/).

### Documenting your Code
While a README will provide people a quick look at what is in your repository and maybe cover how to use the functions/library, you still need to thoroughly document your code. I can't stress enough how important it is to really become proficient at writing and document your code. Later on this semester, your documentation skills will be put to the ultimate test, so you need to practice while you can. What I would consider good code documentation is:
* Does it tell a user who wrote it, when it was written, last time it was updated?
* Does it tell a user what libraries it is dependent on?
* Can someone who has never seen your code before _CLEARLY_ understand what your code is doing?
* Can someone who has to integrate your code into their project understand the expected input formats and what outputs there are?

In terms of a target audience (since some of you will like to think this way) you are writing for someone who has been searching on Google on how to do what the assignment is. For this preliminary assignment it might seem trivial, but as the semester moves on, you will be dependent on each others code in order to perform a particular complicated task.

## Submitting Code and Documentation
Since we are utilizing GitHub Classroom, it is your job to push your final commits to this repository before the deadline laid out in the milestone. Once this deadline has passed, whatever code is on your repository will be treated as your submission. This means that the labs and the milestones are all due at the same time.

### "But I ran out of time. I was busy with other classes."
You have to realize these lab exercises are all self paced. Note the deadline. You theoretically have 5 weeks to do something that really should only take you a few hours each. If you can not manage your time in such a way to finish these labs, you seriously need to consider your commitment to the program and to your schoolwork in general. These lab exercises are meant to only take at most 5-8 hours a week, which is one day, or a little more than 1 hour a day. Not to mention the fact that you have the internet, tutorials, forums, documentation, app notes, etc. and these labs are designed to make you use these resources. We do not want you to re-invent the wheel. We want you to understand the wheel and begin to build customized applications with the wheel. If you are spending hours debugging a simple piece of code, you need to take a step back and tell yourself "I am not the first person to do this." This will put you in a better mindset and hopefully let your rethink the problem.

### Why Self Paced?
I am going to say it now, there are going to be a handful of you that will not get sleep within 48 hours of the due date of a milestone cause you didnt't think the labs will be difficult. So are we setting you up for failure? Not really, only those who really do not know how to manage time and do not take this class seriously will fail. The true reason and motivation to implementing self paced labs is to facilitate those who want to take the exercise further. Some of you will finish this lab in under an hour. And you might think "What would make this better? Maybe I could..." and you take your own time and you become truly invested in the project. THIS is what we want to see. Nothing would make us happier than to see people when asked to implement a simple calculator come back and say "Well why don't you have XXX? Can this be done with YYY".


## Grading Scheme
Currently, your repository will be graded on the following pillars:
* Does your code work?
* Is your code documented and the quality of documentation?
* How easy is it to utilize/implement your code?

## "Why are we using GIT? Can't we just use Blackboard or something?"
The main reason we are utilizing git is so we can generate libraries of example code and drivers for you to use in the future and show to potential employers what you have done. It also provides you easy ways to manage code-bases using built-in feature such as versioning and branches. We know at first if you have never used GIT that it is going to seem like way too much of a hassle for what it is worth; but let me tell you, people last year were saved because they were able to go back to previous versions of their code base.

### Git Tools
For GIT, I recommend two main tools that you should grab:
* GIT Bash
* GITKraken
Each of these will allow you to access you repository on your machine and perform all of the basic GIT tasks required. While you can get away with just one of these tools, it is really helpful to learn how to manage a repository both via command line and by a GUI program. Both of these tools are available for free.

#### Git Bash
Git bash will allow you to access and manage repositories through your command line or terminal. You need to go to [git](https://git-scm.com/downloads) for any OS. What this puts on your machine is the ability to utilize GIT repositories as well as add certain functions to your right-click if you are a Windows user. For MacOS and Linux, you already have a unix terminal built into the OS so you are just adding the GIT functionality. From here, you are able to start out with any tutorials you can find or are provided to you.

#### GitKraken
For this GUI, you will need to head over to [Axisoft](https://www.gitkraken.com/download) to get the client. This client is available for Windows, Mac, and Linux. Once you have installed it, it is pretty simple to get started: [GitKraken Setup Tutorial](https://youtu.be/ZKkMwTeAij4)
