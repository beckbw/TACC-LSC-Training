# Best Practices in Data Management

### Course Objectives

This course is designed as an introduction to managing data on high performance computing clusters. It is intended to teach users to be self-sufficient and proactive in managing their own data in order to (1) increase their productivity, (2) maximize the usage of the existing storage, (3) decrease accidental or unintentional data loss, and (4) prevent disruption of the file system or compute nodes to the point where it may affect others. This course is intended for people who have beginner to intermediate familiarity with a command line interface, and have active accounts on an HPC cluster (e.g. at TACC or the Host Institution).

This course is divided into five modules:

 1. [Overview of HPC Data Management](#mod1)
 2. [Navigating a File System](#mod2)
 3. [Moving and Backing up Data](#mod3)
 4. [Tips and Tricks for Maximizing File System Usage](#mod4)
 5. [Advanced Topics](#mod5)
 

### Instructional Objectives

This course should be taught in a room equipped with computers and internet access. Rooms not equipped with computers will work if the students bring their own laptops and have internet access. Students should also have an existing allocation on a TACC or Host Institutions resource. Students without an allocation can still participate in most components if they have a Mac / Linux laptop, or a Windows laptop with Putty installed and access to a Linux server.


### Specific Learning Objectives

| <a name="mod1"></a>Module 1: Overview of HPC Data Management |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Why do we need best practices in data management? </li><li> Types of file systems used in HPC (NFS, GPFS/Lustre, LTFS, RAID). </li><li> Specific examples of storage infrastructures (TACC, Host Institution). </li><li> Active vs. inactive data. </li><li> Staging data for compute, analysis, long term storage. </li></ul> |
| **Students should be able to...** |
| <ul><li> List multiple reasons for good data management. </li><li> Describe the similarities and differences of distributed and parallel file systems. </li><li> Determine whether data is backed up or vulnerable. </li><li> Differentiate between active and inactive data. </li><li> Identify the appropriate storage spaces for data at different stages of its life cycle. </li></ul> |
| **Assessment activities:** |
| <ul><li> Small group discussion: why do we need best practices in data management? </li><li> From an infrastructure-scale diagram, identify which disks are designed for computation, software installs, long term storage, etc. </li></ul> |

<br>

| <a name="mod2"></a>Module 2: Navigating a File System |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Introduction to file system limitations (file size, number of files). </li><li> Determining the size and age of a file. </li><li> Determining the size of a directory, local disk usage (`du, du -h`). </li><li> Total amount of free disk space (`df, df -h`). </li><li> Checking your quota (`quota, lfs quota`). </li></ul> |
| **Students should be able to...** |
| <ul><li> Recognize file size and number limitations for a given file system. </li><li> Measure and report the size and age of a file and directory. </li><li> Measure and report disk usage. </li><li> Measure and report the total amount of free disk space. </li><li> Find different storage system mounted to a HPC cluster. </li><li> Determine their disk quota for various file systems. </li></ul> |
| **Assessment activities:** |
| <ul><li> On the command line, find different storage spaces on TACC and/or Host Institution HPC resources (e.g. Lonestar). </li><li> On the command line, determine the free disk space, as well as disk usage, age, and size for various files and directories. </li></ul> |

<br>

| <a name="mod3"></a>Module 3: Moving and Backing up Data |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> How old is your data and when is it time to archive it? </li><li> o	Zipping and archiving files and directories (`gzip, gzip -r9, gunzip, tar -czf, tar -xzf`). </li><li> Transferring data from point to point (`rsync, scp, sftp,` WinSCP). </li><li> Staging data on Ranch (TACC) or Host Institution tape filesystem for archiving. </li></ul> |
| **Students should be able to...** |
| <ul><li> Judge whether it is appropriate to keep active or archive data. </li><li> Zip and unzip files with gzip / gunzip. </li><li> Compress and extract archives with tar. </li><li> Transfer data efficiently between systems. </li><li> Stage data on a tape file systems for transferring to and from. </li></ul> |
| **Assessment activities:** |
| <ul><li> Create zip files at various levels of compression and compare their file size vs. time required to zip. </li><li> Copy data from one place to another with `scp` vs. `scp –C` and report speedup. </li></ul> |

<br>

| <a name="mod4"></a>Module 4: Tips and Tricks for Maximizing File System Usage |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> Best practices in directory organization. </li><li> Get rid of duplicate copies of data and duplications within data (dedupe). </li><li> Share files with colleagues instead of duplicating them (permissions; access control lists). </li><li> Don’t install common software in your home directory. </li></ul> |
| **Students should be able to...** |
| <ul><li> Differentiate organized vs. unorganized data. </li><li> Describe strategies to keep data well organized. </li><li> Remove duplicate copies of data where appropriate. </li><li> Set the correct permissions for sharing data where appropriate. </li></ul> |
| **Assessment activities:** |
| <ul><li> Dedupe some sample data? </li><li> Tinker with file and directory permissions using chmod and access control lists. </li></ul> |

<br>

| <a name="mod5"></a>Module 5: Advanced Topics |
| --- |
| |
| **Topics covered in this module:** |
| <ul><li> How to care for sensitive data (HIPAA, ITAR, FIZMA). </li><li> More complicated / big data transfers (globus; gridftp). </li><li> Data repositories and how long should you keep research related data? </li><li> iRODS data management on Corral including metadata and provenance. </li></ul> |
| **Students should be able to...** |
| <ul><li> Recite (the importance of) HIPAA, ITAR, and FIZMA regulations. </li><li> Identify whether data falls under HIPAA, ITAR, or FIZMA protection. </li><li> Transfer data from point to point using globus. </li><li> Judge the appropriate length of time for retaining data. </li><li> Use iRODS to transfer / find data / metadata. </li></ul> |
| **Assessment activities:** |
| <ul><li> Load the iRODS module and play around with icommands. </li></ul> |


<br>
&copy; 2015 Texas Advanced Computing Center




