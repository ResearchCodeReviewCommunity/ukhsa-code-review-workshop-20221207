---
marp: true
theme: gaia
class:
 - invert
paginate: true
---

<!--
_class:
 - lead
 - invert
-->

# Code Review During Research: A Community Effort Towards Guidelines

Matthew Bluteau, UKAEA
on behalf of the RCRC

---

<style scoped>
/* Styling for centering (required in default theme) */
p {
  text-align: center;
}
</style>

## Code reviews at the time of publication

![width:700px](img/codecheck_logo.svg "A caption?")

* What about code quality?


<!--

- CODECHECK does code review at the time of publication. It's relevant for
  reproducibility and checking state of a codebase.
- But what if the code is unreadable/unmaintanable? It's too late for
  a rewrite.

-->

---

## Code review *during research*

![bg right:60%](img/pexels-christina-morillo-1181471.jpg)

<!--

- There is a need for code review /during research/. 
- A different kind of code review: informal, low-stakes and frequent. Something you
  would with colleagues once a week.
- Focus on code quality. Does not replace publication-time review -
  but is complementary.

-->

---

## Code Review benefits researchers themselves

- Learning and knowledge transfer
  - Dissemination of good practices.
  - Continuous peer learning.
- Collaboration
  - Group awareness, cohesion and trust
  - Makes it easier for people to join a team... and leave it.

<!--

- Code review during research has benefits beyond better code quality.
- Learning and knowledge transfer
  + Mentoring and dissemination of experience and good practices.
  + More experienced programmers are exposed to new patterns and
    approaches.
- Collaboration
  + Regular meetings and discussions increases group awareness, trust
    and cohesion.
  + Specific technical knowledge is spread. Easier for newcomers,
    reduce impact of leavers.

-->

---

## Code Review is common software practice...

... in the software industry and open source communities.

. . .

Code review is very rare in academia

- Lack of awareness
- Lack of guidance
- Lack of incentives
- Lack of confidence

<!--

- Code review is common in the software industry and open source
  communities, but very rare in research.
- Lack of awareness and guidance on how to do code review in a
  research context. Most material out there is targeted at the
  software industry and open source projects.
- Establishment of code review culture will probably struggle with
  lack of incentives for code quality and lack of confidence.

-->

---

<style scoped>
/* Styling for centering (required in default theme) */
p {
  text-align: center;
}
</style>
#### Research Code Review Community Group 2 (Code Review During Research)

![h:450](img/photos.jpg)

<!--
::: notes

- UK/US based group of researchers and RSEs.
- Started as one of the working groups of the Code Review Community.
- In practice, guidelines as website. Living document that is open to
  contributions.

-->

---

## Guidelines as a website

<iframe src="https://dev-review.readthedocs.io/en/latest/" width="100%" height="85%"></iframe>

---

## Code review guidelines

Principles

- Suited for "lone coder"
- Short, and predictable time commitment
- Informal and low stakes
- Accessible to beginner programmers

<!--

- Suited for lone, perhaps isolated, research developpers.
- Short, fixed duration. Can fit into a busy schedule with possiblity
  of iteration.
- Informal and low stakes.
- Accessible to less experienced programmers (e.g. resaercher how
  would not think of themselves as programmers).

-->

---

## Code review guidelines

The four steps

1. Find a reviewer
2. Meet and agree on objectives
3. Perform code review
4. Finalise

