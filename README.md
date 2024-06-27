# Writing-A-Software-Ebook

My Intentions
- For now, I want this to be a learning experience where I can reinforce my knowledge as a software developer and aspiring pen tester
- I am involving myself with pen testing and CTFs which requires knowledge of effective techniques. I thought this would be a great opportunity to reinforce those ideas
- This project will constantly be updated as I grow more experienced as a software developer and pen tester

## Title: 

Avoiding Complexity: A Jump Start Guide for Every Software Developer

## Introduction: 

Complexity
- the state or quality of being intricate or complicated

This project involves creating my own Ebook about software. The goal is to document my knowledge as a software developer and aspiring pen tester in order to avoid complexity. I have learned the hard way that programming tasks (such as debugging) can take hours if not done properly. Specifically, not knowing the basic debugging process or commands adds further unnecessary complexity. This in turn wastes time and resources. Therefore, the goal of this Ebook is to jump start developers so they can focus on what truly matters-which is learning.

The sentiment behind this Ebook is to combat our tendency to feed into bad habits. Unless you are a well versed software developer with many years in the job force, we tend to be okay with what works- although there are tools or resources to make life easier. I want to expose developers to those tools or resources so they don't waste time. 

[ *Bad Habits + Ignorance = Complexity = Wasted Time & Resources* ]

This guide may seem more helpful for pen testers. But as of now, I feel like these topics are indispensable for every software developer. It will be  useful as one goes more into the OS and learn topics such as threading. Without a strong jump start, complexity increases significantly.

The primary sources of complexity includes
- setting up an initial environment
- easy-to-use terminal interface (must be visually pleasing to the user)
- recalling commands (this includes gdb commands for debugging)
- effective debugging (use of gdb extensions and other tools)

*I may add to this list as I learn more from other projects

## Setting Up an Initial Environment
I have wasted countless hours trying to setup a working environment. This involves installing dependencies and ensuring the lifetime of a product through patches and updates. To be honest, it is not fun spending hours figuring out why you cannot execute a C program. Also, it hurts the learning experience as you don't see the fruits of your labor. Instead you see error after error just because an environment is not set correclty. This is where virtual evrionments come in.

Virtual environments not only hides the clutter of the computers that you use everyday but it also gives you isolated operating systems for varying cases. Want to set an a virtual machine with many reverse tools. You can. Want to set a simple Ubuntu machine for pen testing. You can. Want to reverse your virtual machine to a previous, stable state. You can. Want to avoid fallback from running a malcious binary on your system. Use an isolated virtual machine.

The benefits far exceed the cost of setting up your own environment. In many cases you can upload preconfigured virtual machines.

You may argue that I am lazy or this practice does not reflect real world practices. But think about how much more you will learn if you avoid all this initial overhead and clutter.

My college uses a ssh connection so why can't I make my own environment also.

## Easy-To-Use Terminal Interface

## Recalling Commands
cat 
-  reads each File parameter in sequence and writes it to standard output

ls -la
- ls: Lists directory contents
- l: Uses the long listing format. This provides detailed information about each file and directory, including permissions, number of links, owner, group, size, and timestamp of last modification
- a: Lists all entries, including hidden files (those starting with a dot)

pwd
- print working directory

## Effective Debugging

### GDB Extensions
[gef](https://github.com/hugsy/gef)

### Workflow
