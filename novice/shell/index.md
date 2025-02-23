---
layout: lesson
root: ../..
title: The Unix Shell
---

>
>####Registration: [Please visit the OIT website ](http://training.oit.duke.edu/research)
>
>####Place: The Edge Workshop Room, Bostock Library, Duke University
>
>####Time: 9:00 AM - 12.00 PM, Oct 27th 2015
>
>
> This Duke-OSG event is being run by the [open science grid (OSG)](http://opensciencegrid.org/), in collaboration with⋅
> [Software Carpentry](http://software-carpentry.org)⋅
> and <a href="https://rc.duke.edu/author/mdelongduke-edu/">Duke Research Computing</a>.  The⋅
> Open Science Grid (OSG) is a national scale distributed infrastructure for⋅
> scientific computing.  Software Carpentry's mission is to help scientists and engineers⋅
>  become more productive by teaching them basic lab skills for computing
>  like program design, version control, data management, and task automation. Duke Research Computing offers⋅
> services that are useful to research computing “as it is practiced” across Duke and⋅
> often in collaboration with researchers at other institutions.
>

The Unix shell has been around longer than most of its users have been alive.
It has survived so long because it's a power tool
that allows people to do complex things with just a few keystrokes.
More importantly,
it helps them combine existing programs in new ways
and automate repetitive tasks
so that they don't have to type the same things over and over again.
Use of the shell is fundamental to using a wide range of other powerful tools 
and computing resources (including "high-performance computing" supercomputers).
These lessons will start you on a path towards using these resources effectively.

### Setup Instructions

*    We will do all the exercises on `login.duke.ci-connect.net`. 
*    If you do not have an account on `duke.ci-connect`, [please sign up](https://duke.ci-connect.net/signup). 
*    You have an account on `duke.ci-connect but forgot the password, [click here](http://duke.ci-connect.net/password). 
*    You also need `SSH` installed on your laptop.  For details, follow [this link](http://swc-osg-workshop.github.io/2015-10-27-duke/setup.html)

### Prerequisites
 This lesson guides you through the basics of file systems and the
 shell.  If you have stored files on a computer at all and recognize
 the word “file” and either “directory” or “folder” (two common words
 for the same thing), you're ready for this lesson.

#### NOTE
 If you're already comfortable manipulating files and directories,
 searching for files with `grep` and `find`, and writing simple loops
 and scripts, you probably won't learn much from this lesson.

### Getting ready

 You need to download some files to follow this lesson. Log into your account 
on <code>login.duke.ci-connect.net</code> and download the zipped filesystem using wget:

~~~
$ wget http://swc-osg-workshop.github.io/2015-10-27-duke/data/filesystem.zip
~~~
{:class="in"}

Alternatively, if you are doing these exercises on your local desktop or laptop, you can download 
the filesystem by clicking [this link](../../data/filesystem.zip).⋅

Unpack the zipped files - on Windows or a Mac, you can probably just double-click or click the downloaded
file to unpack it. On linux you can type in a command like

~~~
$ unzip filesystem.zip
~~~
{:class="in"}


### Topics

1.  [Introducing the Shell](00-intro.html)
2.  [Files and Directories](01-filedir.html)
3.  [Creating Things](02-create.html)
4.  [Pipes and Filters](03-pipefilter.html)
5.  [Loops](04-loop.html)
6.  [Shell Scripts](05-script.html)
7.  [Finding Things](06-find.html)

