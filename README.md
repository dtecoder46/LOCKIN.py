# LOCKIN.py
A task management app that helps you limit procrastination

# Guide to LOCKIN/Algorithm

## How to run

Assuming you're already at the GitHub repo, clone the repo and open it in the code editor of your choice. Then, ...

## Inputting tasks/subtasks

Before running the program, the user must write their tasks and subtasks in a YAML file. YAML is quite simple. The core of YAML is the key-value pair. You must write your tasks/subtasks in this form. If you have separate categories, put a hastag in between the two blocks.

~~~yaml
task1: not done
task2: not done
etc: etc
#
task1: not done
task2: not done
etc2: etc2
~~~

Once you are ready, run the program.

## Building the calendar

When the program is run, the program reads in the YAML content. Then, the key-value pairs are transformed into three separate dictionaries: one for standard tasks, one for relaxation, and one for exercise.

## LOCKIN Menu