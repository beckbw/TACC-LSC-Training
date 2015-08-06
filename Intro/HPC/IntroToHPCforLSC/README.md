# Intro to High Performance Computing for Life Sciences

### Course Objectives 

**This course is designed to introduce skills required to perform computational research in the life sciences.**
* An overview of different compute and storage resources are described, with a focus on those available at TACC or Host Institutions.
 * Students will learn and practice commands in a Linux terminal, the text editor VIM, and basic shell scripting.
 * The workshop will also cover essential topics for the life sciences in high performance computing including environment variables, modules, and batch job submission.
* **Intended Audience**
 * This ~3-hour workshop is intended for people who have little to no experience with a command line interface, but intend to use a Linux workstation or HPC cluster for life science research.

This course is divided into five modules:

 1. Overview of Compute and Storage Resources (15 min)
 2. Linux Command Line Basics (45 min)
 3. Text Editing with VIM (30 min)
 4. Simple Shell Scripting (30 min)
 5. Environment, Modules, Job Submission (30 min)


### Instructional Objectives

This course is taught as an interactive workshop. Students will actively engage in course discussion, and participate with working examples in a Linux terminal. As such, it is necessary that students have access to a command line interface for the course. It should be taught in a room equipped with computers and internet access. Rooms not equipped with computers will work if the students bring their own laptops and have internet access. Students should also have an existing allocation on a TACC or Host Institution resource. Students without an allocation can still participate in most components of the workshop if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.


### Specific Learning Objectives

| Module 1: Overview of Compute and Storage Resources (15 min) |
| ---------------------------------------------------------------------------------------- |
| &#8226; What is high performance computing and why is it useful? |
| &#8226; Compute resources at TACC (Lonestar, Stampede, Maverick, Corral, Ranch). |
| &#8226; Compute resources at MD Anderson (Shark, Nautilus). |
|  |
| **Students should be able to…** |
| &#9702; Describe possible applications for HPC in the life sciences. |
| &#9702; Choose the correct resource at TACC for their research needs. |
| &#9702; Choose the correct resource at MD Anderson for their research needs. |

<br>

| Module 2: Linux Command Line Basics (45 min) |
| ---------------------------------------------------------------------------------------- |
|  &#8226; Brief introduction to the Linux operating system. |
|  &#8226; Looking and moving around (`pwd, ls, mkdir, cd, rmdir`). |
|  &#8226; Creating and manipulating files (`touch, rm, mv, cp, vim`). |
|  &#8226; Looking at the contents of files (`cat, more, less, head, tail`). |
|  &#8226; More files commands (`ln, chmod, grep, tar, gzip`). |
|  &#8226;	Network and file transfers (`hostname, whoami, ssh, scp, rsync`). |
|  &#8226;	Miscellaneous commands (`man, which, diff, df, du, date, history, logout`). |
|  &#8226;	Shortcuts (`Tab, Up Arrow, Ctrl+c, Ctrl+d, ./, ../, ~/, >, >>, *, |, &`) |
|  |
|	**Students should be able to…** |
| &#9702; List benefits and capabilities of a command line interface. |
| &#9702; Use all of the commands covered in this module. |
| &#9702; Find documentation for unknown commands and flags. |

<br>
**BREAK (5 min)**
<br><br>

| Module 3: Text Editing with VIM (30 min) |
| ---------------------------------------------------------------------------------------- |
| &#8226;	Switching back and forth between insert mode (IM) vs. normal mode (NM) (`i, o, O, Esc`). |
| &#8226;	IM: Entering text as a typical text editor. |
| &#8226;	NM: Navigating a file (`<arrow keys>, hjkl, 0, $, gg, G, Ctrl+u. Ctrl+d`). |
| &#8226;	NM: Deleting, coping, and pasting text (`x, dw, dd, yy, p, P, <number><command>`). |
| &#8226;	NM: Searching for text (`/pattern, n, N`). |
| &#8226;	NM: The command line (`:, :<line number>, :%s/find/replace/gc, :read <file>`). |
| &#8226;	NM: Saving and quitting (`:w, :wq, :q, :q!`). |
| &#8226;	NM: Other useful things to know (`u, Ctrl+r, .`) |
|  |
| **Students should be able to…** |
|	&#9702; Open, edit, and save documents with VIM. |
|	&#9702; Switch back and forth between insert mode and normal mode. |
|	&#9702; Navigate to different parts of a file quickly. |
|	&#9702; Search for a specific string of text. |
|	&#9702; Find and replace text. |

<br>

| Module 4: Simple (`bash`) Shell Scripting (30 min) |
| ---------------------------------------------------------------------------------------- |
| &#8226;	The body of a simple shell script – header, comments, commands, exit. |
| &#8226;	Assigning variables, manipulating variables. |
| &#8226;	Conditionals with `if` / `elif` / `else`. |
| &#8226;	Loop control with `while` and `for`. |
|  |
| **Students should be able to…** |
| &#9702; Create a simple shell script with a header, comments, and commands. |
|	&#9702; Change permissions and execute a shell script on the command line. |
|	&#9702; Write and explain if / else statements, for loops, and while loops. |

<br>
**BREAK (5 min)**
<br><br>

| Module 5: Environment, Modules, Job Submission (30 min) |
| ---------------------------------------------------------------------------------------- |
| &#8226;	Environment variables – purpose, printing, and defining (`echo, env, export`). |
| &#8226;	Modules – listing, loading, and unloading. |
| &#8226;	Automating environment variables, module commands, and aliases in `.bash_profile`. |
| &#8226;	Batch job submission, commands dependent on system (`qsub, showq, qdel`). |
|  |
|	**Students should be able to…** |
|  &#9702;	Display their current environment variables. |
|  &#9702;	Change existing and create new environment variables. |
|  &#9702;	List modules currently loaded in their environment. |
|  &#9702;	Load and unloaded modules. |
|  &#9702;	Describe the effects of a module load command. |
|  &#9702;	Automate module and environment commands in the .bash_profile. |
|  &#9702;	Write batch job submission scripts. |
|  &#9702;	Submit jobs to a queue. |
|  &#9702;	Monitor jobs in a queue and delete jobs from a queue. |

<br>


&copy; 2015 Texas Advanced Computing Center


