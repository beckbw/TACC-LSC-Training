# TACC Life Sciences Computing Training

### Welcome!

This github page is a repository of training materials and a past record of
workshops offered by the TACC Life Sciences Computing group. We are currently
exploring different methods for organizing and presenting these materials. Our
main objectives in using github are:

* Organize the course materials into an easily navigatable interface. 
* Present concise overviews of the course content.
* Provide a centralized repository of course files (links to large files) for
download.
* Store a chronicle of past course offerings (including institution, date, and
course files).

To aid in quality control and instructional alignment, Contributors will ensure
course overviews include:

* *Course Objectives*: General purpose of the course. 
* *Instructional Objectives*: The general format of the course and assessment
mechanisms.
* *Specific Learning Objectives*: Detailed topic deliverables that students will
be able to perform.

Contributors: please see extended instructions below.

### About this Repository

Everything in this repository falls under one of two categories, *Curriculum* or
*Workshops*:

* [Curriculum](Curriculum) is the catalog of all course offerings organized by
user experience, scope, and topic. Each course offering found in the curriculum
will include course objectives, instructional objectives, specific learning
objectives, as well as course materials including powerpoint slides, notes, and
tar balls of hands-on activities. These materials are used as a starting point
to create a Workshop.
* [Workshops](Workshops) are specific examples of past course offerings. They
are built around the materials and objectives of courses, or of a combination of
courses, from the Curriculum. Workshops also will include date and location of
the course offering, copies of the exact materials used, and additional
information or materials that may be relevant to the host institution and / or
presenter's teaching style.


### Curriculum

Materials for the Life Sciences Computing curriculum are organized
hierarchically in folders by user experience, scope, topic, training location,
and date.

* [Introductory](Introductory) courses are those in which limited prior
knowledge or experience is needed to easily undertake the training as well as
topics with a broad scope or impact.
* [Advanced](Advanced) courses generally assume a student will be aware of the
content of the Introductory courses and will  have a more targeted or specific
scope.


| Course Catalog |
| --- |
| |
| [Introductory](/Introductory) |
| <ul><li> [TACC Resources, Projects, &amp; Allocations](Introductory/TACC) </li><li> [UT System Research Cyberinfrastructure \(UTRC\)](Introductory/UTRC) </li><li> [Introduction to Linux](Introductory/IntroToLinux) </li><li> [Best Practices in Data Management](Introductory/DataManagement) </li><li> [Batch Job Submission](Introductory/JobSubmission) </li><li> [Computational Tools](Introductory/Tools) </li></ul> |
| [Advanced](/Advanced) |
| <ul><li> [Programming the Xeon Phi](Advanced/XeonPhi) </li><li> [Parallel Programming](Advanced/ParallelProg) </li><li> [Virtual Machines and Cloud Computing](Advanced/VirtualMachines) </li><li> [Software Applications](Advanced/Applications) </li></ul> |


### Workshops

| [Recent Workshops](/Workshops) |
| --- |
| <ul><li> Locations and times vary </li></ul> |


### Instructions for Contributors

###### Content location
In general Course Content developers should create broad scope, general interest, or basic knowledge courses in the `Introductory` section. Specific topics or ones of narrow scope such as a single software applications should be placed into `Advanced`. Content Developers should keep new topics or folders in a local repository fork until general review by all developers.<br/>
The exception to this is `Workshops`. Here developers are requested to create/merge folders for each institution (e.g. `UTSW`, `MDACC`) with a subfolder indicating the presentation date in YYYY-MM-DD format (e.g. `2015-08-15`) of delivered workshops constructed from the source materials provided in `Introductory` or `Advanced`. In this way, a historical chronicle is maintained for both Instructors and Students to reference.

###### Objectives

For each course created in any of `Introductory`, `Advanced`, or `Workshops`, developers are **REQUIRED** to include information about `Course`, `Instructional`, and `Specfic Learning Objectives`.
* *Course Objectives*:  General purpose of the course. 
* *Instructional Objectives*: The general format of the course and assessment mechanisms.
* *Specific Learning Objectives*: Detailed topic deliverables that students will be able to perform.

These COs, IOs, and SLOs aid in quality control and instructional alignment.
A template [`README.template.md`](/README.template.md) file is provided to insert into the overview of any developed course.

###### Accessory data/files

Accessory files, such as sample data, archives, and presentation slides (PPT, PDF) may be included in the related course folder if the file is less than 10MB. For accessory files greater than 10MB, a link to an external storage site should be included instead. For example, a publically shared file residing at https://utexas.app.box.com might be shared as:

>Download the sequence file for the protein actin from [1atn.fasta](https://utexas.box.com/shared/static/3v1bh67km84vyvyldurhh2p64r07g3p6.fasta).



<br>
&copy; 2015 Texas Advanced Computing Center

