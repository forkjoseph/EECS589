# EECS 589: Advanced Computer Networks

## Administrivia
* Catalog Number: XXXX
* Lectures/Discussion: EECS 3166, MW: 4:30 PM – 6:00 PM

### Team

| Member (uniqname) | Role | Office Hours |
| :---------------- | :--- | :----------- |
| [Peter Honeyman](http://peter.honeyman.org/) (honey) | Faculty | FIXME: 4820 BBB. **By appointments only.**
| [HyunJong (Joseph) Lee](http://leelabs.org/) (hyunjong) | GSI | FIXME: BBB Learning Center, F 2:00 PM - 4:00 PM |

## FIXME: Course Description
This class will introduce you to the key concepts and the state-of-the-art in big data systems and encourage you to think about either building new tools or how to apply an existing one in your own research. 

Since datacenters and cloud computing form the backbone of modern big data systems, we will start with high-level overviews of the two and discuss emerging trends in both software and hardware. 
We will then take a deep dive into the big data systems landscape, focusing on different types of problems. 
Our journey will cover topics from top conferences such as SOSP, OSDI, NSDI, SIGCOMM, SIGMOD, and EuroSys on SQL queries, log analysis, machine learning activities, graph processing, approximation queries, stream processing, interactive analysis, and deep learning.

### Prerequisites
EECS 489 or undergraduate introductory class to networking required. Background
in system programming, statistics and probability are helpful. Please refer to
[this class from
Princeton](http://www.cs.princeton.edu/courses/archive/spring14/cos461/syllabus.html)
for an overview of the background networking material. See also the Schedule
tab of [this course from
GaTech](http://gtnoise.net/classes/cs6250/spring2014/#tab2) for short video
overviews of many introductory networking concepts.

Undergraduates must receive explicit permission from the instructor to enroll, if space permits.


### Textbook
This course has no textbooks. 
We will read recent papers from top venues to understand trends in computer
networks and networking systems.

## Tentative Schedule and Reading List
* **Mandatory**: Unless otherwise specified.
* **Optional**: Can skip, but should skim.
* **Companion**: Mandatory for presenters and critics. Optional for the rest.


| Date  | Readings                       | Presenter|
| ------| -------------------------------| ---------| 
| Jan 9 | Introduction                   | [Peter](Slides/FIXME)| 
|       | **Background** | | 
| Jan 14| [Internet Anycast: Performance, Problems and Potential]() | | 
|       | [B4 and After: Managing Hierarchy, Partitioning, and Asymmetry for Availability and Scale in Google's Software-Defined WAN]() | |
| Jan 16| [Networking across Boundaries: Enabling Communication through the Water-Air Interface]() | |
|				| [Polymorphic Radios: A New Design Paradigm for Ultra-Low Power Communication]() | | 
| Jan 21| No class (MLK Day)! | | 
| Jan 23| [Understanding PCIe Performance for End Host Networking]() | | 
|				| [Revisiting Network Support for RDMA]() | | 
| Jan 28| [Inferring Persistent Interdomain Congestion]() | | 
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

### Groups
All activities of this course will be performed in **groups of 3 students** for the Assignment track.
Exceptions may be made for the Research track. 

[Declare your group's membership and paper preferences](https://goo.gl/qzMjq4) by September 11, 2017. 
After this date, we will form groups from the remaining students.

### Paper Presentation
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

### Paper Summaries
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

### Participation
You are expected to attend all lectures (you may skip up to 2 lectures due to legitimate reasons), and more importantly, participate in class discussions.

### Assignment Track
If your group chooses the assignment track, you will have to complete two assignments on popular big data frameworks Apache Spark and TensorFlow.
The third assignment will likely be different for each group with specific goals, and this will resemble a small research exploration project.
Details of the assignments will be available over time.
Tentative deadlines for the assignments are October 11, November 13, and December 11.

### Research Track
If your group chooses the research track, you will have to complete substantive work an instructor-approved problem and have original contribution. 
Surveys are not permitted as projects; instead, each project must contain a survey of background and related work. 
You must meet the following milestones (unless otherwise specified in future announcements) to ensure a high-quality project at the end of the semester:

* Turn in a 2-page draft proposal (including references) by September 27. Remember to include the names and Michigan email addresses of the group members. 
* Keep revising your initial idea and incorporate instructor feedback. However, your team and project proposal must be finalized and approved on or before October 11.
* Each group must submit a 4-page mid-semester progress report and present mid-semester progress during class hours on the week of November 13.
* Each group must present their final results during a presentation or poster session on December 11.
* **Each group must turn in an 8-page final report and your code via email on or before 11:59PM EST on December 15.** The report must be submitted as a PDF file, with formatting similar to that of the papers you've read in the class. The self-contained (i.e., include ALL dependencies) code must be submitted as a zip file. Each zip file containing the code must include a README file with a step-by-step guide on how to compile and run the provided code.


#### Acknowledgement
This course syllabus is heavily influenced by Mosharf's [EECS 598](https://github.com/mosharaf/eecs598/blob/f17-bigdata/README.md)
