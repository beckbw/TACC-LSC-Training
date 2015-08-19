# TACC Life Sciences Computing Training

### Welcome!

This github page is a repository of training materials and a past record of workshops offered by the TACC Life Sciences Computing group. We are currently exploring different methods for organizing and presenting these materials. Our main objectives in using github are:

* Organize the course materials into an easily navigatable interface. 
* Present concise overviews of the course content.
* Provide a centralized repository of course files (links to large files) for download.
* Store a chronicle of past course offerings including institution, date, and course files.


### About this Repository

Everything in this repository falls under one of two categories: `Curriculum` or `Workshops`.

* [Curriculum](Curriculum) is the catalog of all course offerings. Each course offering includes course objectives, instructional objectives, specific learning objectives, as well as course materials including powerpoint slides, notes, and tar balls of hands-on activities.
* [Workshops](Workshops) are actual past course offerings. They are built around the objectives and materials in the `Curriculum`. Some `Workshops` combine objectives and materials from several courses. `Workshops` also include additional
information or materials specific to the host institution and / or presenter's teaching style.

If you are a student, look below to start exploring the [`Curriculum`](#curr) or past [`Workshops`](#work). If you are a contributor, jump to [Instructions](Instructions.md) for preparing and uploading new content.


<a name="curr"></a>
### Curriculum

| [Curriculum](/Curriculum) |
| --- |
| |
| [Introductory](/Curriculum/Introductory) |
| <ul><li> [TACC Resources, Projects, &amp; Allocations](Introductory/TACC) </li><li> [UT System Research Cyberinfrastructure \(UTRC\)](Introductory/UTRC) </li><li> [Introduction to Linux](Introductory/IntroToLinux) </li><li> [Best Practices in Data Management](Introductory/DataManagement) </li><li> [Batch Job Submission](Introductory/JobSubmission) </li><li> [Computational Tools](Introductory/Tools) </li></ul> |
| [Advanced](/Curriculum/Advanced) |
| <ul><li> [Programming the Xeon Phi](Advanced/XeonPhi) </li><li> [Parallel Programming](Advanced/ParallelProg) </li><li> [Virtual Machines and Cloud Computing](Advanced/VirtualMachines) </li><li> [Software Applications](Advanced/Applications) </li></ul> |


<a name="work"></a>
### Workshops

| Recent [Workshops](/Workshops) |
| --- |
| |
| [University of Texas at Austin](/Workshops/UTexas) |
| <ul><li>[2015-05-18 - Intro to HPC for Life Sciences](/Workshops/UTexas/2015-05-18)</li></ul> |
| [MD Anderson Cancer Center](/Workshops/MDACC) |
| <ul><li>[2015-08-14 - Intro to HPC for Life Sciences](/Workshops/MDACC/2015-08-14)</li></ul> |


<a name="inst"></a>
### Instructions for Contributors

###### Content Location

In general, course content developers should create broad scope, general interest, or basic knowledge courses in the [Introductory](/Curriculum/Introductory) section of the `Curriculum`. Specialized topics, or topics of narrow scope such as software applications, should be placed into [Advanced](/Curriculum/Advanced). Content developers should keep new topics or folders in a local repository fork until general review by all developers. A template [`README.curriculum_template.md`](/Curriculum/README.curriculum_template.md) file is provided to insert into the overview of any newly developed course.

`Workshops` are solely the responsibility of the presenter to create. Here, the presenter of the `Workshop` is requested to create a new folder for the host institution (e.g. [UTSW](/Workshops/UTSW), [MDACC](/Workshops/MDACC)) with a subfolder indicating the presentation date in YYYY-MM-DD format (e.g. [2015-08-14](/Workshops/MDACC/2015-08-14)). This folder should contain objectives and materials from a delivered workshop, constructed from the source materials provided in Introductory or Advanced. In this way, a historical chronicle is maintained for both instructors and students to reference.  A template [`README.workshop_template.md`](/Workshops/README.workshop_template.md) file is provided to insert into the overview of any newly scheduled Workshops.


###### Objectives

For each course created in the `Curriculum` or `Workshops`, developers are **REQUIRED** to include information about course, instructional, and specfic learning objectives. These COs, IOs, and SLOs aid in quality control and instructional alignment.

* *Course Objectives*:  General purpose of the course. 
* *Instructional Objectives*: The general format of the course and assessment mechanisms.
* *Specific Learning Objectives*: Detailed topic deliverables that students will be able to perform.


###### Accessory Files

Accessory files, such powerpoint slides (PPT or PDF), notes, and tar balls of hands-on activities may be included in the related course folder if the file is less than 10MB. For accessory files greater than 10MB, a link to an external storage site should be included instead. For example, a publically shared file residing at https://utexas.app.box.com might be shared as:

>Download the sequence file for the protein actin from [1atn.fasta](https://utexas.box.com/shared/static/3v1bh67km84vyvyldurhh2p64r07g3p6.fasta).



<br>
&copy; 2015 Texas Advanced Computing Center

