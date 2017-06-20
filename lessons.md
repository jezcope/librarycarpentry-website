---
layout: page
title: Our lessons
permalink: /lessons/
---

This is our full list of current lessons, along with their status.

- [Lessons](#lessons)
- [What do the statuses mean?](#statuses)
- [Lesson development process](#lesson-development-process)
  - [New lesson expectations](#new-lesson-expectations)

## Lessons

{% include lessons.html %}

## Statuses

Core
: These lessons are mature and ready to be taught. The content is
well-established, but minor changes and improvements are always
welcome.

Beta
: These lessons are largely complete and should be ready to teach, and
would benefit from improvements based on the experience of instructors

Alpha
: These lessons are under active development and may not be ready to
teach without additional preparation and background knowledge.

All contributions are welcome, but if you would like to focus your
efforts where they are most needed, take a look at the alpha and
beta lessons.

## Lesson development process

Our recommended process for developing a new lesson is as follows:

1. Develop the initial content on github using the [lesson template][]
2. Introduce yourself and the lesson on our [gitter channel][] — there may well be willing volunteers to help with the content
3. Teach the lesson, collect feedback & improve the content
4. Propose your lesson for the incubator by making a pull request (PR) against [the Library Carpentry website][website], adding a link to your lesson repository as an *alpha* lesson
5. Discuss the lesson with the community and if necessary offer suggestions on how to improve the lesson; if the lesson is considered suitable material for the Library Carpentry curriculum a website maintainer will merge your PR into the main site
6. You and others will teach the lesson, collect feedback & improve the content
7. Propose your lesson for beta/core by making a pull request against [the Library Carpentry website][website], updating the status of your lesson
8. Discuss the lesson further with the community; when the lesson is ready, a website maintainer will merge your PR
9. Congratulations! Your lesson is now part of core LC

[lesson template]: https://github.com/swcarpentry/lesson-example
[website]: https://github.com/librarycarpentry/librarycarpentry.github.io
[gitter channel]: https://gitter.im/LibraryCarpentry/

### New lesson expectations

In order to maintain consistent quality and style in the Library Carpentry lessons, we have a community-driven set of expectations for what a good lesson should look like. These should guide the review process at steps 5 and 8 above. Lesson developers and reviewers should also read and follow [the guidelines in the Software Development instructor training manual][lesson dev].

[lesson dev]: http://swcarpentry.github.io/instructor-training/19-lessons/

All core lessons should:

1. have at least two active maintainers
2. include a short learner profile
3. include good quality learning objectives
4. be teachable in 3 hours under normal circumstances
