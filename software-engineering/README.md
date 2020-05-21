# Software Engineering @ Integral

This document aims to explain the steps you could experience during our
interview process.

We are not the biggest fans of the traditional interview process, largely
because of the lack of information parity between the candidate and the company.
Therefore, expect plenty of dialogue throughout the entire process. Hopefully
both of us will have the information we need to know to make the right decision.

## Table of Contents
- [Software Engineering @ Integral](#software-engineering--integral)
  * [Table of Contents](#table-of-contents)
  * [Software Engineering Practices, Summarized](#software-engineering-practices-summarized)
    + [Practice Definition](#practice-definition)
      - [Test-Driven Development](#test-driven-development)
      - [Simple Design](#simple-design)
  * [Interview Process](#interview-process)
    + [Coding Exercise](#coding-exercise)
      - [Definition](#definition)
      - [Requirements](#requirements)
        * [Two Hour Time Limit](#two-hour-time-limit)
        * [Technical Requirements](#technical-requirements)
      - [Success Criteria Hints](#success-criteria-hints)
      - [Submission](#submission)
    + [Remote Pairing Exercise](#remote-pairing-exercise)
    + [Project Pairing](#project-pairing)

## Software Engineering Practices, Summarized

We expect Integral software engineers to practice incremental development
leveraging fast feedback loops.

From our experience, the engineering practices prescribed by extreme programming
(XP) best enables such style of development. Most obvious practices you would
experience working at Integral are test-driven development (TDD), simple design,
and pair programming.

Unsurprisingly, during our interview process, we would be discussing and
assessing elements of these practices throughout the interview process.

### Practice Definition

Since XP's introduction, several of the practices noted above have acquired
divergent definitons. Without going into the merit of or reasons for the other
definitions, here is our definitions for these practices.

#### Test-Driven Development

When we mention TDD, we are thinking of the process best described by Martin
Fowler ([bliki entry][fowler-tdd]):

> 1. Write a test for the next bit of functionality you want to add.
> 1. Write the functional code until the test passes.
> 1. Refactor both new and old code to make it well structured.

Specific types of _tests_ are intentionally left undefined in this process as
different situations require different type of tests.

[fowler-tdd]: https://martinfowler.com/bliki/TestDrivenDevelopment.html

#### Simple Design

When we talk about simple design, we are referring to the four characteristics
of design as expressed by Kent Beck ([Martin Fowler's explanation is wonderful
as usual][fowler-simple-design]):

> 1. Passes the tests
> 1. Reveals intention
> 1. No duplication
> 1. Fewest elements

Note that the characteristics are stated in priority order. In other words,
what's the use of a beautiful design if the software does not work? Once the
software works, however, design becomes a large factor in the software's
evolvability. Hence the focus on keeping the design as simple as possible (but
no simpler).

[fowler-simple-design]: https://martinfowler.com/bliki/BeckDesignRules.html

## Interview Process

1. Connect with Integral. Either reach out to us at careers@integral.io, or we
   reach out to you.
1. Speak with our recruiter to learn about our company and for us to learn about
   yourself.
1. Complete the coding exercise (clarified below).
1. Remote pair program on your code submssion with one of our engineers.
1. <s>On-site</s> Pair with us on a production/production-like codebase.

### Coding Exercise

The coding exercise provides a medium for us to chat about software engineering.
It also serves as the foundation for the next step in the process.

Therefore, we aim to select an exercise that has enough "meat" for discussions,
while respecting everyone's time and obligations beyond interviewing.

#### Definition

Please implement the [following kata][interview kata] and follow the guidelines
specified below.

Here's a [starter project][kata starter] that may help kickstart the exercise.

[interview kata]:
  https://github.com/integral-io/katas/tree/master/social-networking
[kata starter]: https://github.com/integral-io/katas/tree/master/starter/java

#### Requirements

##### Two Hour Time Limit

Please spend a **maximum** of two (2) hours on doing the kata. As stated above,
we want to respect your time and obligations outside of the interview process.
Additionally, the subsequent step involves pairing with one of our engineers on
your code submission for the kata. Keep these two things in mind. Please do not
feel the pressure to complete the kata.

To re-iterate, please spend maximum 2 hours on doing the kata. The evaluation of
your code submission **does not depend on completing the kata**.

##### Technical Requirements

- Interfaces: User-facing interfaces (i.e. Web, Console, etc.) are not
  necessary.
- Language: Use any version of Java with a build system (i.e. Maven or Gradle).
- Dependencies: Use any dependencies necessary.

#### Success Criteria Hints

Ultimately, we would like you to implement the features focusing on **writing
the best code** you can produce.

Submissions that illustrate the technical practices defined above, however,
would increase the probably of you moving forward in the interview process.

To re-iterate the practices:

- Follow TDD in building the features. Do not forget the refactoring step.
- Follow simple design. Be prepared to justify code that is seemingly complex.
  The justification just may be a learning opportunity for the interviewer!

#### Submission

Add the code to your own Github account and send us the link.

### Remote Pairing Exercise

Once your code has been submitted, we would have an opportunity to discuss and
remote pair on the kata starting with the code you have submitted.

Expect the discussion to be conversational, covering topics such as:

- Your thoughts on the exercise
  - What you liked about the exercise
  - What frustrated or confused you about the exercise
- How did you approach the problem?
  - What influenced your design?
  - What are the changes you want to make but wasn't able to because of the time
    constraint?

These are not meant to be exhaustive nor is it guaranteed that we would talk
about all of them.

### Project Pairing

<s>Come into our office.</s> Meet the team. Experience the environment. Pair
with our engineers!

Usually, we invite candidates into our office because we believe the candidates
should experience the day-to-day of working on a project at Integral. However,
given the current situation with the pandemic, these pairing sessions will be
conducted over video call until further notice.
