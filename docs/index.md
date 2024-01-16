
# 16-745: Optimal Control & Reinforcement Learning

[Piazza](https://piazza.com/cmu/spring2024/16745/home){ .md-button } [Canvas](https://canvas.cmu.edu/courses/39938
){ .md-button } [Github](https://github.com/Optimal-Control-16-745){ .md-button } [YouTube](https://www.youtube.com/@roboticexplorationlab3724/videos){ .md-button }


Welcome to 16-745 Optimal Control and Reinforcement Learning at Carnegie Mellon University!


## Course Description

This is a course about how to make robots move through and interact with their environment with speed, efficiency, and robustness. We will survey a broad range of topics from nonlinear dynamics, linear systems theory, classical optimal control, numerical optimization, state estimation, system identification, and reinforcement learning. The goal is to provide students with hands-on experience applying each of these ideas to a variety of robotic systems so that they can use them in their own research.

**Prerequisites:** Strong linear algebra skills, experience with a high-level programming language like Python, MATLAB, or Julia, and basic familiarity with ordinary differential equations.

## Teaching Staff

<div style="display: flex; align-items: center;">
    <!-- Left side: Image -->
    <img src="/images/headshots/zac.png" alt="Person's Image" style="max-width: 100px; margin-right: 20px;">

    <!-- Right side: Bio -->
    <div style="margin-top: -30px;"> 
        <h2>Zachary Manchester</h2>
        <p style="margin-top: -10px;"> 
            Instructor <br> <a href = "mailto: zacm@cmu.edu">zacm@cmu.edu</a>
        </p>
    </div>
</div>


<div style="display: flex; align-items: center;">
    <!-- Left side: Image -->
    <img src="/images/headshots/kevin.png" alt="Person's Image" style="max-width: 100px; margin-right: 20px;">

    <!-- Right side: Bio -->
    <div style="margin-top: -30px;"> 
        <h2>Kevin Tracy</h2>
        <p style="margin-top: -10px;"> 
            Head Teaching Assistant <br> <a href = "mailto: ktracy@cmu.edu">ktracy@cmu.edu</a>
        </p>
    </div>
</div>

<div style="display: flex; align-items: center;">
    <!-- Left side: Image -->
    <img src="/images/headshots/jj.png" alt="Person's Image" style="max-width: 100px; margin-right: 20px;">

    <!-- Right side: Bio -->
    <div style="margin-top: -30px;"> 
        <h2>JJ Lee</h2>
        <p style="margin-top: -10px;"> 
            Teaching Assistant <br> <a href = "mailto: jeonghunlee@cmu.edu">jeonghunlee@cmu.edu</a>
        </p>
    </div>
</div>

<div style="display: flex; align-items: center;">
    <!-- Left side: Image -->
    <img src="/images/headshots/fausto.png" alt="Person's Image" style="max-width: 100px; margin-right: 20px;">

    <!-- Right side: Bio -->
    <div style="margin-top: -30px;"> 
        <h2>Fausto Vega</h2>
        <p style="margin-top: -10px;"> 
            Teaching Assistant <br> <a href = "mailto: fvega@andrew.cmu.edu">fvega@andrew.cmu.edu</a>
        </p>
    </div>
</div>

<div style="display: flex; align-items: center;">
    <!-- Left side: Image -->
    <img src="/images/headshots/sam.png" alt="Person's Image" style="max-width: 100px; margin-right: 20px;">

    <!-- Right side: Bio -->
    <div style="margin-top: -30px;"> 
        <h2>Sam Schoedel</h2>
        <p style="margin-top: -10px;"> 
            Teaching Assistant <br> <a href = "mailto: sschoede@andrew.cmu.edu">sschoede@andrew.cmu.edu</a>
        </p>
    </div>
</div>

## Logistics 

- Lectures will be held Tuesdays and Thursdays 5:00--6:20 PM Eastern time in TEP 1403. Lectures will also be live streamed on zoom and recorded for later viewing.
- Recitation will be held Fridays at based on survey.
- Office hours will be based on survey.
- Homework assignments will be due by 11:59 PM Eastern time on Wednesdays. Two weeks will be given to complete each assignment.
- GitHub will be used to distribute assignments and GradeScope will be used for submissions.
- [Piazza](https://piazza.com/cmu/spring2024/16745/home) will be used for general discussion and Q&A outside of class and office hours.
- There will be no exams. Instead, students will form groups of up to five to complete a project on a topic of their choice.

## Learning Objectives 
By the end of this course, students should be able to do the following:

1. Analyze the stability of dynamical systems
2. Design LQR controllers that stabilize equilibria and trajectories
3. Use offline trajectory optimization to design trajectories for nonlinear systems
4. Use online convex optimization to implement model-predictive control
5. Understand the effects of stochasticity and model uncertainty
6. Directly optimize feedback policies when good models are unavailable

## Learning Resources

There is no textbook required for this course. Video recordings of lectures and lecture notes will be posted online. Additional references for further reading will be provided with each lecture. Relavent (free) background material is available in the [background](background.md) section of this website.

## Homework

Four homeworks will be assigned during the semester. Students will have at least two weeks to complete each assignment. All homework will be distributed and collected using GitHub. Solutions and grades will be returned within one week of homework due dates.

## Grading

Grading will be based on:

| Weight | Criteria|
|------|-------|
|50% | Project |
|40% | Homework |
|10% | Quizzes/participation |

Attendance during lectures is not required to earn a full participation grade. Students can also participate through any combination of office hours, Piazza discussions, project presentations, and by offering constructive feedback about the course to the instructors.

## Project Guidelines

Students should work in groups of 1--5 to complete a substantial final project. The goal is for students to apply the coarse content to their own research. Project proposals will be solicited on the first homework and topics will be selected in consultation with the instructors.

Project grades will be based on a short presentation given during the last week of class and a final report submitted via Google drive by May 10 [Anywhere on Earth](https://time.is/Anywhere_on_Earth). Reports should be written in the form of a 6 page (plus references) ICRA or IROS conference paper using the standard [two-column IEEE format](https://www.ieee.org/conferences/publishing/templates.html). Sections should include an abstract, introduction and/or background to motivate your problem, 2--3 main technical sections on your contributions, conclusions, and references. Grading will be based on the following criteria:

| Weight | Criteria|
|------|-------|
|10% | Class presentation |
|10% | Adherence to IEEE formatting and length requirements |
|10% | Innovation & Creativity: Is what you did new/cool/interesting? Convince me. |
|30% | Clarity of presentation: Can I understand what you did from your writing + plots? |
|40% | Technical correctness: Are your results reasonable? Is your code correct? |

## Course Policies

**Late Homework:** Students are allowed a budget of 6 late days for turning in homework with no penalty throughout the semester. They may be used together on one assignment, or separately on multiple assignments. Beyond these six days, no other late homework will be accepted.


**Accommodations for Students with Disabilities:** If you have a disability and are registered with the Office of Disability Resources, I encourage you to use their online system to notify me of your accommodations and discuss your needs with me as early in the semester as possible. I will work with you to ensure that accommodations are provided as appropriate. If you suspect that you may have a disability and would benefit from accommodations but are not yet registered with the Office of Disability Resources, I encourage you to contact them at [access@andrew.cmu.edu](mailto:access@andrew.cmu.edu).


**Statement of Support for Students' Health \& Well-Being:** Take care of yourself. Do your best to maintain a healthy lifestyle this semester by eating well, exercising, avoiding drugs and alcohol, getting enough sleep, and taking some time to relax. This will help you achieve your goals and cope with stress.

If you or anyone you know experiences any academic stress, difficult life events, or feelings like anxiety or depression, we strongly encourage you to seek support. Counseling and Psychological Services (CaPS) is here to help: call 412-268-2922 and visit [http://www.cmu.edu/counseling](http://www.cmu.edu/counseling). Consider reaching out to a friend, faculty, or family member you trust for help getting connected to the support that can help.


*If you or someone you know is feeling suicidal or in danger of self-harm, call someone immediately, day or night:*

*CaPS: 412-268-2922*

*Re:solve Crisis Network: 888-796-8226*

*If the situation is life threatening, call the police:*

*On campus: CMU Police: 412-268-2323*

*Off campus: 911*

If you have questions about this or your coursework, please let me know. Thank you, and have a great semester.


## Schedule

| Week | Dates | Topics | Assignments |
|------|-------|--------|-------------|
| 1    | Jan 16 <br> Jan 18 | Course Overview, & Dynamics Intro <br> Stability, Discrete-Time Dynamics | Survey <br> HW0 Out |
| 2    | Jan 23 <br> Jan 25 | Optimization Intro <br> Numerical Optimization Pt. 1 | HW0 Due <br> HW1 Out |
| 3    | Jan 30 <br> Feb 1  | Numerical Optimization Pt. 2 & Optimal Control Intro <br> Pontryagin, Shooting Methods, & LQR Intro | |
| 4    | Feb 6 <br> Feb 8    | LQR as a QP & Riccati Equation <br> Dynamic Programming & Intro to Convexity | HW 1 Due <br> HW 2 Out |
| 5    | Feb 13 <br> Feb 15  | Convex Model-Predictive Control <br> Intro to Trajectory Optimization, Iterative LQR, & DDP | |
| 6    | Feb 20 <br> Feb 22  | DDP with Constraints and Free Final Time <br> Direct Trajectory Optimization, Collocation, & SQP | HW2 Due <br> HW3 Out |
| 7    | Feb 27 <br> Feb 29  | Attitude Intro: SO(3) & Quaternions <br> Optimizing with Attitude | |
| 8    | Mar 5 <br> Mar 7    | <span style="color:red">No Class</span> <br> <span style="color:red">No Class</span> | |
| 9    | Mar 12 <br> Mar 14  | LQR with Attitude, Quadrotors, & Contact Intro <br> Trajectory Optimization for Hybrid Systems | HW3 Due <br> HW4 Out |
| 10   | Mar 19 <br> Mar 21  | Data-Driven Methods & Iterative Learning Control <br> Stochastic Optimal Control & LQG | |
| 11   | Mar 26 <br> Mar 28  | Robust Control & Minimax DDP <br> RL from an Optimal Control Perspective | HW4 Due | 
| 12   | Apr 2 <br> Apr 4    | Practical Tips & Tricks, Control History <br> Case Study: How to Land a Rocket | |
| 13   | Apr 9 <br> Apr 11   | Case Study: How to Drive a Car <br> <span style="color:red">No Class</span> | |
| 14   | Apr 16 <br> Apr 18  | Case Study: How to Walk <br> TBD | |
| 15   | Apr 23 <br> Apr 25  | Project Presentations <br> Project Presentations | |


<!-- | Week | Dates | Topics | Assignments |
|-------|---------|------------------|---------|
| 1 | Jan 16 <br> Jan 18 | Course Overview, & Dynamics Intro <br> Stability, Discrete-Time Dynamics | Survey <br> HW0 Out |
| 2 | Jan 23 <br> Jan 25 | Optimization Intro <br> Numerical Optimization Pt. 1 | HW0 Due <br> HW1 Out | -->

<!-- \begin{center}
\begin{tabular}{l l}
	Prof. Zac Manchester & \textbf{Email:} \href{mailto:zacm@cmu.edu}{zacm@cmu.edu} \\
	TA: Kevin Tracy & \textbf{Email:} \href{mailto:ktracy@cmu.edu}{ktracy@cmu.edu}
	\\
	TA: Jeong Hun (JJ) Lee & \textbf{Email:} \href{mailto:jeonghunlee@cmu.edu}{jeonghunlee@cmu.edu}
	\\
	TA: Swaminathan (Swami) Gurumurthy & \textbf{Email:} \href{sgurumur@andrew.cmu.edu}{sgurumur@andrew.cmu.edu}
	\\
	TA: Mrinal Verghese & \textbf{Email:} \href{mverghes@andrew.cmu.edu}{mverghes@andrew.cmu.edu}
\end{tabular}
\end{center}

\section*{Logistics}

\begin{itemize}
	\item Lectures will be held Tuesdays and Thursdays 5:00--6:20 PM Eastern time in Room 160 in Hall of Arts. Lectures will also be live streamed on zoom and recorded for later viewing.
	\item Recitation will be held Fridays at \todo{based on survey}.
	\item Office hours will be \todo{based on survey}.
	\item Homework assignments will be due by 11:59 PM Eastern time on Wednesdays. Two weeks will be given to complete each assignment.
	\item GitHub will be used to distribute assignments and GradeScope will be used for submissions.
	\item \href{https://piazza.com/cmu/spring2023/16745/home}{Piazza} will be used for general discussion and Q\&A outside of class and office hours.
	\item There will be no exams. Instead, students will form groups of up to five to complete a project on a topic of their choice.
\end{itemize} -->

<!-- For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples

### Codeblocks

Some `code` goes here.

### Plain codeblock

A plain codeblock:

```
Some code here
def myfunction()
// some comment
```

#### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def whatever()
```

#### With a title

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### Highlighting lines

``` py hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emojs

:smile: 

:fontawesome-regular-face-laugh-wink:

:fontawesome-brands-twitter:{ .twitter }

:octicons-heart-fill-24:{ .heart }

## Math 

$$ \begin{align} a = \begin{bmatrix} A \\ B \end{bmatrix} \end{align} $$

here is some text with some inline $x=4$ stuff in here -->
