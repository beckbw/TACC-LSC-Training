# Intro to High Performance Computing for Life Sciences

### Course Objectives 

This course is designed to introduce skills required to perform computational research in the life sciences. First, an overview of different compute and storage resources are described, with a focus on those available at TACC or Host Institutions. Students will learn and practice commands in a Linux terminal, the text editor VIM, and basic shell scripting. The workshop will also cover essential topics for the life sciences in high performance computing including environment variables, modules, and batch job submission. This ~3-hour workshop is intended for people who have little to no experience with a command line interface, but intend to use a Linux workstation or HPC cluster for life science research.

This course is divided into five modules:

 1. Overview of Compute and Storage Resources (15 min)
 2. Linux Command Line Basics (45 min)
 3. Text Editing with VIM (30 min)
 4. Simple Shell Scripting (30 min)
 5. Environment, Modules, Job Submission (30 min)


### Instructional Objectives

This course is taught as an interactive workshop. Students will actively engage in course discussion, and participate with working examples in a Linux terminal. As such, it is necessary that students have access to a command line interface for the course. It should be taught in a room equipped with computers and internet access. Rooms not equipped with computers will work if the students bring their own laptops and have internet access. Students should also have an existing allocation on a TACC or Host Institution resource. Students without an allocation can still participate in most components of the workshop if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.


### Learning Objectives

| Module 1: Overview of Compute and Storage Resources (15 min) |
| --- |
| * What is high performance computing and why is it useful? |
| * Compute resources at TACC (Lonestar, Stampede, Maverick, Corral, Ranch). |
| * Compute resources at MD Anderson (Shark, Nautilus). |
|  |
| Students should be able to… |
| …describe possible applications for HPC in the life sciences. |
| …choose the correct resource at TACC for their research needs. |
| …choose the correct resource at MD Anderson for their research needs. |








| Module 2: Linux Command Line Basics (45 min) |
| --- |
|  * Brief introduction to the Linux operating system. |
|  * Looking and moving around (pwd, ls, mkdir, cd, rmdir). |
|  * Creating and manipulating files (touch, rm, mv, cp, vim). |
|  * Looking at the contents of files (cat, more, less, head, tail). |
|  * More files commands (ln, chmod, grep, tar, gzip). |
|  *	Network and file transfers (hostname, whoami, ssh, scp, rsync). |
|  *	Miscellaneous commands (man, which, diff, df, du, date, history, logout). |
|  *	Shortcuts (Tab, Up Arrow, Ctrl+c, Ctrl+d, ./, ../, ~/, >, >>, *, |, &, \) |
|  |
|	Students should be able to… |
| …list benefits and capabilities of a command line interface. |
| …use all of the commands covered in this module. |
| …find documentation for unknown commands and flags. |


BREAK (5 min)

| Module 3: Text Editing with VIM (30 min) |
| --- |
| *	Switching back and forth between insert mode (IM) vs. normal mode (NM) (i, o, O, Esc). |
| *	IM: Entering text as a typical text editor. |
| *	NM: Navigating a file (<arrow keys>, hjkl, 0, $, gg, G, Ctrl+u. Ctrl+d). |
| *	NM: Deleting, coping, and pasting text (x, dw, dd, yy, p, P, <number><command>). |
| *	NM: Searching for text (/pattern, n, N). |
| *	NM: The command line (:, :<line number>, :%s/find/replace/gc, :read <file>). |
| *	NM: Saving and quitting (:w, :wq, :q, :q!). |
| *	NM: Other useful things to know (u, Ctrl+r, .) |

*	Students should be able to…
  *	…open, edit, and save documents with VIM.
  *	…switch back and forth between insert mode and normal mode.
  *	…navigate to different parts of a file quickly.
  *	…search for a specific string of text.
  *	…find and replace text.


| Module 4: Simple (bash) Shell Scripting (30 min) |
| --- |
| *	The body of a simple shell script – header, comments, commands, exit. |
| *	Assigning variables, manipulating variables. |
| *	Conditionals with if / elif / else. |
| *	Loop control with while and for. |

*	Students should be able to…
  *	…create a simple shell script with a header, comments, and commands.
  *	…change permissions and execute a shell script on the command line.
  *	…write and explain if / else statements, for loops, and while loops.

BREAK (5 min)

| Module 5: Environment, Modules, Job Submission (30 min) |
| --- |
| *	Environment variables – purpose, printing, and defining (echo, env, export). |
| *	Modules – listing, loading, and unloading. |
| *	Automating environment variables, module commands, and aliases in .bash_profile. |
| *	Batch job submission, commands dependent on system (qsub, showq, qdel). |



*	Students should be able to…
  *	…display their current environment variables.
  *	…change existing and create new environment variables.
  *	…list modules currently loaded in their environment.
  *	…load and unloaded modules.
  *	…describe the effects of a module load command.
  *	…automate module and environment commands in the .bash_profile.
  *	…write batch job submission scripts.
  *	…submit jobs to a queue.
  *	…monitor jobs in a queue and delete jobs from a queue.







