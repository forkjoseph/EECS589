# EECS 589: Advanced Computer Networks

## Administrivia
* Catalog Number: 33534
* Lectures/Discussion: 1010 DOW, TuTh 4:00PM - 6:00PM

### Team

| Member (uniqname) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Peter Honeyman](http://www.citi.umich.edu/u/honey/) (honey) | Faculty | FIXME: 4820 BBB. **By appointments only.**
| [HyunJong (Joseph) Lee](http://leelabs.org/) (hyunjong) | GSI | FIXME: BBB Learning Center, F 2:00 PM - 4:00 PM |

## Course Description
This is a graduate level course on computer networking focusing on advanced
topics and is a must for anyone interested in doing research in computer
networks. This class examines the current and emerging research topics in
computer networking. Topics covered include network protocols, network
measurement, Internet routing, peer to peer networks, network security,
wireless, and sensor networks. 

The course consists of both a reading/lecture/discussion component and a project
component. Emphasis of the course is on topics in wide-area networks, wireless
networks, and measurement methodologies for Internet and wireless experiments.
Significant emphasis will be put on security and network management issues
related to computer networks, as these are becoming increasingly important given
the growing number attacks and complexity of networks.  We focus both on the
existing technologies also on why some of them are not sufficient because of
technology trends or changes in fundamental assumptions. As an example, early
designers of Internet assumed cooperative behavior of end nodes. The state of
the art of millions of compromised hosts completely changes this assumption and
today's landscape on the Internet. We will read about 50 research papers on the
most recent topics of computer networking.

Students are expected to carry out a research project including analysis,
design, and implementation components when appropriate on a novel subject.  The
class projects can be either of the following types: algorithm design applied to
networked system, implementation of a novel networking system, measurement of
existing network protocols, and simulation of a proposed network algorithm. We
emphasize problems that are real and solutions that will make a difference,
ideally can be deployed. The lecture will be conducted in an interactive
fashion. I will lead the discussion for the first few meetings of the class, but
I expect everyone to participate. For the remainder of the class, I expect each
student (can be in groups) to present a paper. Students will read and review
papers before class.  You will be graded for the reviews, class discussions, and
project scope, effort, and results.

### Prerequisites
Students are expected to have good programming skills and must have taken at
least one undergraduate-level systems-related course (from operating systems,
databases, distributed systems, and networking).

### Textbook
This course has no textbooks. We will read recent papers from top venues to
understand trends in networking research.

## Tentative Schedule and Reading List
* **Mandatory**: Unless otherwise specified.
* **Optional**: Can skip, but should skim.
* **Companion**: Mandatory for presenters and critics. Optional for the rest.


| Date  | Readings                       | Presenter|
| ------| -------------------------------| ---------| 
| Jan 9 | Introduction                   | [Peter](Slides/FIXME)| 
|       | **Background** | | 
| Jan 14| [Internet Anycast: Performance, Problems and Potential](http://www.cs.umd.edu/projects/droot/anycast_sigcomm18.pdf) | | 
|       | [B4 and After: Managing Hierarchy, Partitioning, and Asymmetry for Availability and Scale in Google's Software-Defined WAN](https://dl.acm.org/citation.cfm?id=3230545) | |
| Jan 16| [Networking across Boundaries: Enabling Communication through the Water-Air Interface](http://www.mit.edu/~fadel/papers/TARF-paper.pdf) | |
|				| [Polymorphic Radios: A New Design Paradigm for Ultra-Low Power Communication](https://people.cs.umass.edu/~dganesan/papers/SIGCOMM18-Polymorphic.pdf) | | 
| Jan 21| No class (MLK Day)! | | 
| Jan 23| [Understanding PCIe Performance for End Host Networking](https://www.cl.cam.ac.uk/research/srg/netos/projects/pcie-bench/neugebauer2018understanding.pdf) | | 
|				| [Revisiting Network Support for RDMA](https://people.eecs.berkeley.edu/~radhika/irn.pdf) | | 
| Jan 28| [Inferring Persistent Interdomain Congestion](http://cseweb.ucsd.edu/~snoeren/papers/congestion-sigcomm18.pdf) | | 
| Jan 30| | |
| Feb 04| | |
| Feb 06| | |
| Feb 11| | |
| Feb 13| | |
| Feb 18| | |
| Feb 20| | |
| Feb 25| | |
| Feb 27| | |
| Mar 04| Spring break | |
| Mar 06| Spring break | |
| Mar 11| | |
| Mar 13| | |
| Mar 18| | |
| Mar 20| | |
| Mar 25| | |
| Mar 27| | |
| Apr 01| | |
| Apr 03| | |
| Apr 08| | |
| Apr 10| | |
| Apr 15| | |
| Apr 17| | |
| Apr 22| | |

## FIXME: Grading
|                         | Assignment Track | Research Track |
| ------------------------| ----------------:| --------------:|
| Paper Summary           | 20%              | 20%
| Paper Presentation      | 20%              | 20%
| Participation           | 10%              | 10%
| Assignment 1            | 15%              | -
| Assignment 2            | 15%              | -
| Assignment 3            | 20%              | -
| Research Proposal       | -                | 10%
| Mid-Semester Checkpoint | -                | 15%
| Final Report            | -                | 25%


## Policies

### Honor Code
[The Engineering Honor Code](http://honorcode.engin.umich.edu/) applies to all activities related to this course.

### FIXME: Groups
All activities of this course will be performed in **groups of 3 students** for the Assignment track.
Exceptions may be made for the Research track. 

[Declare your group's membership and paper preferences](https://goo.gl/qzMjq4) by September 11, 2017. 
After this date, we will form groups from the remaining students.

### FIXME: Paper Presentation
The course will be conducted as a seminar. 
Only one group will present in each class.
Each group will be assigned to present a paper at least once throughout the semester. 
Presentations should last **at most 45 minutes** without interruption.
However, presenters should expect questions and interruptions throughout. 
In the presentation, you should:

* Motivate the paper and provide background.
* Present the high level idea, approach, and/or insight (using examples, whenever appropriate). 
* Discuss technical details so that one can understand the key details without carefully reading it.
* Explain the difference between this paper and related work.
* Raise questions throughout the presentation to generate discussion.

*The slides for a presentation must be emailed to the instructor team at least 24 hours prior to the corresponding class.* 
You should use [this template](Slides/Template.pptx) for making your slides in powerpoint.

### FIXME: Paper Summaries
Review must be uploaded to **[https://hotcrp.eecs589.org](https://hotcrp.eecs589.org)**

Each group will also be assigned to write one or more paper summaries. 
The paper summary assigned to a group may not be the same paper they have presented.

A paper summary must address the following four questions in sufficient details (2-3 pages):

* What is the problem addressed by the paper, and why is this problem important?
* What is the hypothesis of the work?
* What is the proposed solution, and what key insight guides their solution?
* What is one (or more) drawback or limitation of the proposal, and how will you improve it?

*The paper summary of a paper must be emailed to the instructor team within 24 hours after its presentation.* 
**Late reviews will not be counted.** 
You should use [this template](Summaries/Template.md) for writing your summary.
Allocate enough time for your reading, discuss as a group, write the summary carefully, and finally, include key observations from the class discussion.

Because you do not have to write summaries/reviews for each paper, you cannot avoid reading a paper. 
Everyone is expected to have read all the papers. 
Being able to critically judge others' work is crucial for your understanding. 


### FIXME: Participation
You are expected to attend all lectures (you may skip up to 2 lectures due to legitimate reasons), and more importantly, participate in class discussions.

### FIXME: Assignment Track
If your group chooses the assignment track, you will have to complete two assignments on popular big data frameworks Apache Spark and TensorFlow.
The third assignment will likely be different for each group with specific goals, and this will resemble a small research exploration project.
Details of the assignments will be available over time.
Tentative deadlines for the assignments are October 11, November 13, and December 11.

### FIXME: Research Track
If your group chooses the research track, you will have to complete substantive work an instructor-approved problem and have original contribution. 
Surveys are not permitted as projects; instead, each project must contain a survey of background and related work. 
You must meet the following milestones (unless otherwise specified in future announcements) to ensure a high-quality project at the end of the semester:

* Turn in a 2-page draft proposal (including references) by September 27. Remember to include the names and Michigan email addresses of the group members. 
* Keep revising your initial idea and incorporate instructor feedback. However, your team and project proposal must be finalized and approved on or before October 11.
* Each group must submit a 4-page mid-semester progress report and present mid-semester progress during class hours on the week of November 13.
* Each group must present their final results during a presentation or poster session on December 11.
* **Each group must turn in an 8-page final report and your code via email on or before 11:59PM EST on December 15.** The report must be submitted as a PDF file, with formatting similar to that of the papers you've read in the class. The self-contained (i.e., include ALL dependencies) code must be submitted as a zip file. Each zip file containing the code must include a README file with a step-by-step guide on how to compile and run the provided code.


#### Acknowledgement
This course syllabus is heavily influenced by Mosharf's [EECS 598](https://github.com/mosharaf/eecs598/blob/f17-bigdata/README.md).
