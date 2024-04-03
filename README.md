# Command Line Basics

## Introduction
Welcome to the Command Line Basics course! 🖥️ This guide will introduce you to the fundamentals of using the command line interface (CLI) on your computer's operating system. Whether you're a beginner or looking to refresh your skills, this course will help you navigate and utilize the command line effectively.

## A Brief History
The command line interface (CLI) has been around since the 1970s, providing users with a text-based method to interact with computer systems. Despite the rise of graphical user interfaces (GUI) in the 80s and 90s, the command line remains popular, especially among developers.

On your computer:

![Command Line Icon](commandline.png)
- On Mac, the command line is known as the Terminal.
- On Windows, it is known as the Command Prompt (or "CMD" for short).

Even with the prevalence of GUI applications, the command line offers several advantages:
- Automating tasks with minimal commands.
- Lower processing power consumption.
- Easier targeting of specific resources such as files and folders.
- A sense of empowerment reminiscent of movie hackers! 😎

## Getting Started
In this chapter, we will learn how to navigate the command line on your machine.

### Instructions
1. **Accessing the Command Line:**
    - For Mac users, open Spotlight with Command + Space and search for "Terminal".
    - For Windows users, download Git Bash to use the commands explored in this course. [Download here](https://git-scm.com/downloads).

2. **First Command: echo**
    - The `echo` command acts like a "print statement" and displays whatever text follows it.
    - Type the following command, replacing `...` with your name:
        ```
        $ echo Hi! My name is ...
        ```
    - Press Enter to see the command line print your name!

3. **Bonus (Mac Only): Text-to-Speech**
    - Mac users can use the `say` command for text-to-speech functionality.
    - Try running a command like:
        ```
        $ say Hi! My name is ...
        ```
    - Your computer will speak the text through the speakers!

## Next Steps
Now that you've dipped your toes into the command line, let's dive deeper into navigation and common commands. Stay tuned for the next chapter! 🚀

## Filesystem

### Directories

Your computer's filesystem is essentially a structure of folders and files. In the context of the command line, folders are referred to as directories.

![Filesystem diagram](diagram.png)

Inside any given directory, you may find:

- More directories (subdirectories)
- Files containing various types of content (text, images, videos)

### Print Working Directory: `pwd`

Navigating the filesystem via the command line can be overwhelming at first. It's easy to get lost.

The working directory represents your current location in the filesystem.

The `pwd` command comes in handy to display the current working directory.

```
$ pwd
/c/Users/Aditya/AppData/Roaming/SPB_Data
```

This output indicates that the current working directory is `/c/Users/Aditya/AppData/Roaming/SPB_Data`, which is a folder within the Users directory.

### Instructions

1. Open the command line.
2. Print the current working directory using the `pwd` command.

What is the working directory in the command line right now?
