---
layout: default
---

Hey there!

I’m Taylor, a computer science student at North Carolina State University.
I’m currently taking:
- CSC 216/217: Software Development Fundamentals
- CSC 298: Research Methods in Computer Science

In high school, I took dual enrollment courses at Guilford College.
There, I took Intro to Programming, Operating Systems, and Scientific Computing.

I first started exploring computer science in high school.
From there, I embarked on a journey of learning as much as possible—from building functioning websites,
to experimenting with the Linux command line, to solving math problems with Julia.

Outside of coding, I enjoy playing tennis, writing with fountain pens, and riding my bike around town.

## Past Coding Projects
- [CreativeSpace]({% link _posts/projects/2021-04-09-creative-space-java.md %})
- [Family Feud]({% link _posts/projects/2022-04-01-family-feud.md %})

{% assign resumes = site.static_files | where_exp: "file", "file.path contains 'assets/documents/yangt-resume'" | reverse %}

See my resume [here]({{ resumes[0].path }}).

Other posts:
[Pens!]({% link _posts/personal/2022-09-10-pens.md %})
<!-- [Note to Self]({% link _posts/personal/2022-09-10-note-to-self.md %}) -->