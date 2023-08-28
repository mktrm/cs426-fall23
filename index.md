---
layout: home
title: CS-426
nav_exclude: true
seo:
  type: Course
  name: ' Computer Security'

toc: true
toc_label : "On this page"
toc_hmin: 2
toc_hmax: 6
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }


This 3-credits undergraduate course covers the basics of computer security.  We will cover a wide range of topics from both offensive and defensive sides, including systems security and exploitation (e.g., buffer overflows), sandboxing and isolation, side channels, network security, cryptography, privacy and anonymity, and legal and ethical issues. Together, we will learn how to build *secure* computer systems, we will understand security best practices, and we will get to know security failures in existing and emerging computer networks and systems.

By the end of the course, you will have the basic knowledge to reason about common security attacks and defenses, you will become familiar with security engineering best practices, and you will learn how to write better and more secure software, protocols, and systems, and you will have rudimentary skills in security research.
I hope that you will have fun taking this course as much as I will enjoy teaching it!


**Catalog Description:** The course focuses on the principles and foundations of building secure computer systems and on security and privacy challenges in existing and emerging computer networks and systems.
The course compares and analyzes security and privacy threats and architectures from an adversarial standpoint to understand how to build more secure protocols that can withstand ever-adaptive attacks.





## Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Lectures
Lectures are M/W/F from 9:30 am to 10:20 am, [Robert Heine Pharmacy Building 164](https://www.google.com/maps/dir//Robert%20E.%20Heine%20Pharmacy%20Building+575%20Stadium%20Mall%20Drive+West+lafayette+47906?_ga=2.225282650.1948742483.1691952653-526511082.1665511938){:target="_blank"}.

Updated Office Hours on BrightSpace (See [Course Calendar](https://purdue.brightspace.com/d2l/le/calendar/832199/home/list){:target="_blank"}).

## Prerequisite 
The formal prerequisite is undergraduate level CS 25100 minimum grade of C and undergraduate level CS 25200 minimum grade of C [may be taken concurrently] or undergraduate level ECE 46900 Minimum Grade of C or undergraduate level EE 46900 Minimum Grade of C. However, to complete the assignments in this course, you will need to be able to write code in Python, C, and (some) C++, and have some understanding of x86 assembly, JavaScript, PHP, and SQL. We will not teach these in lecture; you are expected to learn them on your own or ask for help in office hours.


## Textbook
There is no official textbook for the class. Slides will be provided and reading materials for each topic will be posted before the lectures. 
However, the following resources are going to be useful: 

- Security Engineering – Ross Anderson, Third Edition
- Hacking: The Art of Exploitation by Jon Erickson

We try to be clear about what is okay to skim and what will be helpful to read deeply (See [Agenda](#agenda-tentative)).


## Format 
Course format is lectures three days a week. Attendance is not optional. The slides will be available for download before each lecture (See [Agenda](#agenda-tentative)). 

{: .note }
A quick reminder: **Active engagement** and **re-enforcement** are keys to successful and effective learning. Therefore, we will have plenty of activities during lectures. These activities also help you to meet and interact with other students. Moroever, assignments, and grading are designed to help with re-enforcement and active engagement.


## Online Discussion
Discussions, Q&A, peer-to-peer instruction, etc. take place on our [edstem](https://purdue.brightspace.com/d2l/le/content/832199/viewContent/14037232/View){:target="_blank"}. Use the link in [Brightspace](https://purdue.brightspace.com/d2l/le/content/832199/viewContent/14037232/View) to join the class on edstem. You are encouraged to post questions, help answer other students' questions, and provide feedback and suggestions to your instruction staff. Constructive criticism is always welcome. 

{: .warning }
While the instruction staff will do their best to answer any question as soon as possible, be aware (and plan ahead) that instruction staff will not be available 24/7. 



## Grading

An ideal assessment should evaluate learning outcomes, thus your grade should not depend on other student's performance in class (i.e., no bell curve). 
We will use the following scale for your final grade:

<div class="table-responsive">
<table class="table grade-table">
  <tbody><tr>
    <th>A+<br><small>&gt;96.7</small></th>
    <th>A<br><small>[93,96.7)</small></th>
    <th>A-<br><small>[90,93)</small></th>
    <th>B+<br><small>[86.7,90)</small></th>
    <th>B<br><small>[83.3,86.7)</small></th>
    <th>B-<br><small>[80,83.3)</small></th>
    <th>C+<br><small>[76.7,80)</small></th>
    <th>C<br><small>[73.3,76.7)</small></th>
    <th>C-<br><small>[70,73.3)</small></th>
    <th>D<br><small>[60,70)</small></th>
    <th>F<br><small>[0,60)</small></th>
  </tr>
</tbody></table>
</div>

{:.warning}
We reserve the right to modify these ranges and the following tentative grading breakdown as the course proceeds. 


### Weekly Check-in (5%)
During lectures, we will have interactive question and answer activities in the class. We will use [Hotseat](https://purdue.brightspace.com/d2l/le/content/832199/viewContent/13837914/View) for polls and discussions. 
These are opportunities for you to check your understanding and for us to go back and help explain concepts more thoroughly that may be confusing folks.
These in-lecture polls will not be graded for correctness or attendance.
However, on each Wednesday (from 2nd week onward), we will collect all of the poll questions of the week and release a mini-quiz on BrightSpace. The quiz must be completed by midnight (campus time) the following Thursday. **So, you will have at least 24 hours to complete them.**

These quizzes are primarily for you, to help you stay on track and to check your own understanding. Therefore, **we will not grade them for correctness**. If you complete the quiz, you will earn full points for that week. However, if your raw score on a quiz is low, come to discussion sections or office hours and get help!

### Homework (60%)
These are longer form assignments that include both programming and a non-programming conceptual section. You are welcome to discuss homework problems with other students or in groups, however, you must complete your final writeup alone.

Homework submission will be via the [Gradescope](https://www.gradescope.com/courses/582792){:target="_blank"}. If you are enrolled in the class you should see the class in your Gradescope account. Regrade requests will also be handled via Gradescope. The window for regrades will be no more than one week after graded homework is returned.

We will have 5 homework sets. Generally they will be released on Mondays and you will have 2-3 weeks to submit. See the tentative schedule for more information on the schedule of the homework assignments ([Agenda](#agenda-tentative)). Homework 1 will be worth 8% and the remaining homework (Homework 2-5) will each be worth 13% of the final grade, making the total Homework grade 8 + 4 * 13 = 60% of your final grade. 

### Midterm (15%)
This course will have one midterm exam.
The midterm is scheduled to be in class on Wed Oct 18. 

### Final (20%)
The final exam will be cumulative over all of the course content.

The registrar has assigned: TBD as the final exam time slot for this course.


## Late Assignments
You will have 3 late days during the whole semester for late homework. You will also have 3 late days for weekly check-ins. You can use your late days however you wish to. Note that the granularity of this is *days*. That means, if you submit your homework any time in the next 24 hours after the deadline, you are using one of your late days. 



## Academic Integrity
Cheating WILL be taken seriously. It is not fair to honest students to take cheating lightly, nor is it fair to the cheater to let him/her go on thinking that is a reasonable alternative in life. 

The following is not considered cheating:

- discussing the homeworks with other students (with the writeup done separately, later).


The following is:

- Discussing homework with someone who has already completed the problem, or looking at their completed write-up.
- Using homework solutions from the web, previous versions of the class, or anywhere else.
- Receiving, providing, or soliciting assistance from another student during a test.

{: .danger}
Penalties -- anyone copying information or having information copied on a homework, or an exam, or any other violation of class policy, will receive an F in the class and will not be allowed to drop.  They will be reported to their college dean.  If you can prove non-cooperative copying took place, your grade may be restored, but you must prove it to the dean.

<!-- ## Useful Refrences

- [MIPS Refrence Sheet](https://canvas.ucsd.edu/files/4734326/download?download_frd=1)
- [Modified MIPS Refrence Sheet For Exams](https://canvas.ucsd.edu/files/4772975/download?download_frd=1)
- [Guide on How to Draw Textual Pipeline Diagram](https://canvas.ucsd.edu/files/4812863/download?download_frd=1)
- [Empty Word Template for Pipeline Diagram](https://canvas.ucsd.edu/files/4812864/download?download_frd=1) -->


<!-- ## Homework Assignments

HW1 | [pdf](https://canvas.ucsd.edu/files/4740428/download?download_frd=1) | [docx](https://canvas.ucsd.edu/files/4740427/download?download_frd=1) | [submit](https://canvas.ucsd.edu/courses/28054/assignments/342802) | [solutions](https://canvas.ucsd.edu/files/4772303/download?download_frd=1)

HW2 | [pdf](https://canvas.ucsd.edu/files/4754073/download?download_frd=1) | [docx](https://canvas.ucsd.edu/files/4754071/download?download_frd=1) | [submit](https://canvas.ucsd.edu/courses/28054/assignments/343742) | [solutions](https://canvas.ucsd.edu/files/4778597/download?download_frd=1)

HW3 | [pdf](https://canvas.ucsd.edu/files/4772646/download?download_frd=1) | [docx](https://canvas.ucsd.edu/files/4772645/download?download_frd=1) | [submit](https://canvas.ucsd.edu/courses/28054/assignments/345016) | [solutions](https://canvas.ucsd.edu/files/4776310/download?download_frd=1)

HW4 | [pdf](https://canvas.ucsd.edu/files/4794176/download?download_frd=1) | [docx](https://canvas.ucsd.edu/files/4794175/download?download_frd=1) | [submit](https://canvas.ucsd.edu/courses/28054/assignments/346570)  -->

## University Policies and Statements 

Please see [Brightspace](https://purdue.brightspace.com/d2l/le/content/832199/Home) for complete list of university policies and statements. 



## Agenda (Tentative!)

This is a tentative schedule and we may change it as the course proceeds. 

{% for module in site.modules %}
{{ module }}
{% endfor %}


## DISCLAIMER
The details in this syllabus may change (e.g. schedule, grading policy, assignments, etc.). We will update this syllabus in the event of changes as the course progresses. We will send announcements in the case of significant changes. It is your responsibility to check for the course announcements. 

## Credit
This page uses materials from many other instructors including Deian Stefan, Dave Tian, Aniket Kate, Pat Pannuto and Dean Tullsen. 
