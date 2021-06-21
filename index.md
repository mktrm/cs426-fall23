---
layout: home
title: CSE-141
nav_exclude: true
seo:
  type: Course
  name: 'Introduction to Computer Architecture Lab'

toc: true
toc_label : "On this page"
toc_hmin: 2
toc_hmax: 6
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }



This course covers the basics of modern processor design and operation. Together, we will learn Instruction Set Architectures (ISAs), computer system performance, pipelining, branch prediction, memory-hierarchy design,  and processor security considerations.
By the end of the course, you will have the basic knowledge to reason about details of real-world processors (e.g., some of the differences between Apple M1 and, for example, Intel Core i7). I hope that you will have fun taking this course as much as I will enjoy teaching it!


This course is designed to run alongside [CSE 141L](#). We expect that you are enrolled in both.




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

## Meetings
Lectures are M/Tu/W/Th from 11:00 to 12:20 US/Pacific, on [Zoom](https://canvas.ucsd.edu/courses/28054/external_tools/628).

Updated Office Hours on Canvas (See [Course Calendar](https://canvas.ucsd.edu/calendar?include_contexts=course_28054)).


## Textbook
Computer Organization and Design MIPS Edition, The Hardware/Software Interface, Fifth Edition (Patterson & Hennessy) (ISBN-13: 978-0124077263, ISBN-10: 0124077269)
The textbook is required for this course. The pre-class readings are recommended, but not required.
You will get more out of lecture if you have completed the pre-class reading. 
We try to be clear about what is okay to skim and what will be helpful to read deeply (See [Agenda](#agenda-tentative)).

### Other Recommended Reading

- Hennessy & Patterson, "Computer Architecture: A Quantitative Approach", Morgan Kaufmann
    - A more advanced treatment of many of the same topics in the textbook, as well as a lot more breadth.
- Synthesis Lectures on Computer Architecture
    - This contains a number of truly outstanding (and very recent and up-to-date) books on computer architecture, any of which you can download free while in the UCSD domain. In particular, see the books on Processor Microarchitecture (most useful for this class), Performance Evaluation Methods, Memory System, and Multithreading Architectures.

## Format 
Course format is lectures over Zoom, four days per week. Attendance is strongly recommended, but not required. All the lectures will be recorded and will be posted a few hours after the lectures. The slides will be available for download before each lecture (See [Agenda](#agenda-tentative)). 

{: .note }
A quick reminder: Effective learning comes from **active engagement** and **re-enforcement**. Therefore, we will have plenty of activities during lectures. These activities also help you to meet and interact with other students, which is particularly important for our new remote world. Moroever, assignments, and grading are designed to help with re-enforcement and active engagemnet.


## Online Discussion
Discussions, Q&A, peer-to-peer instruction, etc. take place on our [Piazza](#). You are encouraged to post questions, help answer other students' questions, and provide feedback and suggestions to your instruction staff. Constructive criticism is always welcome. 

{: .warning }
While the instruction staff will do their best to answer any question as soon as possible, be aware (and plan ahead) that instruction staff will not be available 24/7. Also, we are told that Piazza uses student data for marketing. But, unfortuently, I could not find any good alternative to replicte the same discussion expericene. So, please keep the privacy issue in mind when using it.



## Grading

An ideal assesment shoud evaluate learning outcomes, thus your grade should not depend on other student's performance in class (i.e., no bell curve). 
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
This table might be revisited later in the class.


### Weekly Check-in (5%)
During lectures, we will have interactive question and answer activities via Zoom polls.
These are opportunities to check your understanding and for us to go back and help explain concepts more thoroughly that may be confusing folks.
These in-lecture polls will not be graded for correctness or attendance.
However, on each Wednesday, we will collect all of the poll questions of the week and release a mini-quiz on Canvas. The quiz must be completed by midnight (campus time) the following Thursday.

These quizzes are primarily for you, to help you stay on track and to check your own understanding. Therefore, **we will not grade them for correctness**. If you complete the quiz, you will earn full points for that week. However, if your raw score on a quiz is low, come to discussion sections or office hours and get help!

### Homework (20%)
These are longer form assignments, designed to test your individual understanding. You are welcome discuss homework problems with other students or in groups, however, you must complete your final writeup alone.

Homework submission will be via the [Gradescope](https://canvas.ucsd.edu/courses/28054/external_tools/80) module in Canvas. Regrade requests will also be handled via Gradescope. The window for regrades will be no more than one week after graded homework is returned.

Generally, homework will be released every Thursday and due the following Thursday, at midnight. We expect to release a homework assignment every week, with exceptions for the final week, which should result in 4 homework assignments.

### Midterm (30%)
This course will have one midterm exam.
We recognize that students may be attending class from all around the world. For this reason, we plan to offer the midterm as a ninety minute exam to be completed during a twelve hour window.
We will offer the midterm from 8am–8pm on Tuesday, July 13th. The exam will include everything coverd by the end of the lecture on Thursday July 8th.

### Final (45%)
The final exam will be cumulative over all of the course content.

The registrar has assigned: 07/31/21, 03:00 PM - 05:59 PM as the final exam time slot for this course.

Again, we recognize that students may be attending class from all around the world. For this reason, we will offer the final as a three hour exam to be completed any time in a twelve hour window.

We will offer the final from 8am–8pm on Saturday, July 30th. We will schedule an extra review session and a couple of office hours in the week before the final.

Note that the final exam will be on **Saturday**.
We recognize that Saturday can be a challenging day for some people to block off time, however, we also need to respect that folks have exams in other courses and the purpose of a harmonized exam schedule is to not conflict with those exams.

If you absolutely cannot make Saturday work, please contact Kazem directly before July 15th.

## Late Assignments
You will have 1 late days during the whole summer session for late homeworks. You will also have 1 late days for weekly check-ins. You can use your late days however you wish to.

## Academic Integrity  
Cheating WILL be taken seriously. It is not fair to honest students to take cheating lightly, nor is it fair to the cheater to let him/her go on thinking that is a reasonable alternative in life. 

 > "Don't test me on this one." ~Prof. Dean Tullsen


The following is not considered cheating:

- discussing the homeworks with other students (with the writeup done separately, later).


The following is:

- Discussing homework with someone who has already completed the problem, or looking at their completed write-up.
- Using homework solutions from the web, previous versions of the class, or anywhere else.
- Receiving, providing, or soliciting assistance from another student during a test.

{: .danger}
Penalties -- anyone copying information or having information copied on a homework, or an exam, or any other violation of class policy, will receive an F in the class and will not be allowed to drop.  They will be reported to their college dean.  If you can prove non-cooperative copying took place, your grade may be restored, but you must prove it to the dean.




## Agenda (Tentative)

{% for module in site.modules %}
{{ module }}
{% endfor %}


## DISCLAIMER
Due to our unusual circumstances, the details in this syllabus may change (e.g. schedule, grading policy, assignments, etc.). We will update this syllabus in the event of changes as the course progresses.

## Credit
This page heavily uses materials from Pat Pannuto and Dean Tullsen. 
