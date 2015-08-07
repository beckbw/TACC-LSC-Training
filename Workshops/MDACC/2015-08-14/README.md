# Intro to High Performance Computing for Life Sciences

### Course Objectives 

This workshop is designed to introduce skills required to perform computational research in the life sciences. First, an overview of different compute and storage resources are described, with a focus on those available at TACC or MD Anderson. Students will learn and practice commands in a Linux terminal, the text editor VIM, and basic shell scripting. The workshop will also cover essential topics for the life sciences in high performance computing including environment variables, modules, and batch job submission. This ~3-hour workshop is intended for people who have little to no experience with a command line interface, but intend to use a Linux workstation or HPC cluster for life science research.

This workshop is divided into five modules:

 1. Overview of Compute and Storage Resources (15 min)
 2. Linux Command Line Basics (45 min)
 3. Text Editing with VIM (30 min)
 4. Simple Shell Scripting (30 min)
 5. Environment, Modules, Job Submission (30 min)


### Instructional Objectives

This course is taught as an interactive workshop. Students will actively engage in course discussion, and participate with working examples in a Linux terminal. As such, it is necessary that students have access to a command line interface for the course. It should be taught in a room equipped with computers and internet access. Rooms not equipped with computers will work if the students bring their own laptops and have internet access. Students should also have an existing allocation on a TACC or Host Institution resource. Students without an allocation can still participate in most components of the workshop if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.



### Specific Learning Objectives

TABLE

<br/>


| <a name="mod1"></a>Module 2: Linux Command Line Basics |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Brief introduction to the Linux operating system. </li><li> Looking and moving around (`pwd, ls, mkdir, cd, rmdir`). </li><li> Creating and manipulating files (`touch, rm, mv, cp, vim`). </li><li> Looking at the contents of files (`cat, more, less, head, tail`). </li><li> More files commands (`ln, chmod, grep, tar, gzip`). </li><li> Network and file transfers (`hostname, whoami, ssh, scp, rsync`). </li><li> Miscellaneous commands (`man, which, diff, df, du, date, history, logout`). </li><li> Shortcuts (`Tab, Up Arrow, Ctrl+c, Ctrl+d, ./, ../, ~/, >, >>, *, |, &`). </li></ul> |
| **Students should be able to...** |
| <ul><li> List benefits and capabilities of a command line interface. </li><li> Use all of the commands covered in this module. </li><li> Find documentation for unknown commands and flags. </li></ul> |
| **Assessment activities:** |
| <ul><li> `Exercise01.tar:` Renaming directories for better organization. </li><li> `Exercise02.tar:` Manipulating existing files (word list and fasta). </li></ul> |

<br/>
**BREAK (5 min)**
<br/><br/>

| <a name="mod2"></a>Module 3: Text Editing with VIM |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Switching back and forth between insert mode (IM) vs. normal mode (NM) (`i, o, O, Esc`). </li><li> IM: Entering text as a typical text editor. </li><li> NM: Navigating a file (`<arrow keys>, hjkl, 0, $, gg, G, Ctrl+u. Ctrl+d`). </li><li> NM: Deleting, coping, and pasting text (`x, dw, dd, yy, p, P, <number><command>`). </li><li> NM: Searching for text (`/pattern, n, N`). </li><li> NM: The command line (`:, :<line number>, :%s/find/replace/gc, :read <file>`). </li><li> NM: Saving and quitting (`:w, :wq, :q, :q!`). </li><li> NM: Other useful things to know (`u, Ctrl+r, .`). </li></ul> |
| **Students should be able to...** |
| <ul><li> Open, edit, and save documents with VIM. </li><li> Switch back and forth between insert mode and normal mode. </li><li> Navigate to different parts of a file quickly. </li><li> Search for a specific string of text. </li><li> Find and replace text. </li></ul> |
| **Assessment activities:** |
| <ul><li> Learn by practice! Dive headfirst into Module 4! </li><li> Other practice tools available: vimtutor, vim-adventures.com. </li></ul> |

<br>

| <a name="mod3"></a>Module 4: Simple (`bash`) Shell Scripting |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> The body of a simple shell script – header, comments, commands, exit. </li><li> Assigning variables, manipulating variables. </li><li> Conditionals with `if` / `elif` / `else`. </li><li> Loop control with `while` and `for`. </li></ul> |
| **Students should be able to...** |
| <ul><li> Create a simple shell script with a header, comments, and commands. </li><li> Change permissions and execute a shell script on the command line. </li><li> Write and explain if / else statements, for loops, and while loops. </li></ul> |
| **Assessment activities:** |
| <ul><li> Exercise03.tar: Pipeline common commands to set up a project. </li><li> Exercise04.tar: Write some simple control structures. </li></ul> |

<br/>
**BREAK (5 min)**
<br/><br/>

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


