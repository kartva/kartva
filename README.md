I'm interested in designing performant and delightful software. I love open-source and have contributed a bunch. Feel free to [contact me](mailto:sendtokartavya@gmail.com) if you'd like to chat about something I've worked on or might find interesting. I can be found IRL most easily at [Hack Nights](https://events.purduehackers.com/) at Purdue University.

### Work / Open-Source Contributions
I will be interning at Neuralink in the fall. I previously worked on [icu4x](https://github.com/unicode-org/icu4x), an open-source i18n library by the Unicode consortium, and [Librarian](https://github.com/kartva/Librarian), a bioinformatics quality control tool. I've contributed feature patches to [Rust Analyzer](https://github.com/rust-lang/rust-analyzer/), [Rust Clippy](https://github.com/rust-lang/rust-clippy/), [Wine](https://gitlab.winehq.org/wine/wine), [OpenSearch](https://github.com/opensearch-project/) and [Zola](https://github.com/getzola/zola/).

### Research
I'm broadly interested in programming languages, distributed systems and operating systems. My current work is in creating optimizations for [Mergeable Replicated Datatypes](https://www.cs.purdue.edu/homes/suresh/papers/oopsla19-mrdt.pdf).

### A chronological ordering of stuff I've done / am doing
#### Spring 2025
- I'm working on [a guide to Optimize Purdue CS](https://gist.github.com/kartva/30c528420d68869dbcf376cd028fe038). It is ~5000 words and counting. At least two academic advisors plan to share it with their students in upcoming years!
- I [taught](https://www.linkedin.com/posts/kartav_i-taught-the-interpreters-workshop-at-purdue-activity-7300388870053838851-2TAR?utm_source=share&utm_medium=member_desktop&rcm=ACoAACrdg7QBiV4HxrGNebdp4vL6WEUQ0w-6RpI) the [Interpreters workshop for Purdue Hackers](https://github.com/kartva/ph-interpreters).
- (Relevant) classes:
  - Graduate Programming Languages. Assignments include proving the correctness of a compiler against a reference interpreter and proving type soundness of the simply-typed lambda calculus in Coq / Rocq. The course is based on books from the [Software Foundations](https://softwarefoundations.cis.upenn.edu/) series.
  - Graduate Theoretical Computer Science Toolkit. Topics include convex analysis and optimization, spectral methods, concentration inequalities, and discrete Fourier analysis.
  - Graduate Hardware Security. Projects include:
    - Hacking the ZBT WE526 (WE1626) router.
    - Writing a Trusted Execution Environment for a Risc-V softcore.
    - Using a Chipwhisperer Nano for side-channel attacks.
  - Graduate Software Engineering for Robots. Assignments include working with ROS2 and MoveIt. Our final project will be deployed on two Franka 3 robot arms!
  - Compilers with Tiark Rompf (of Scala fame). Assignments include lots of compilers written in Scala for a Scala-like language to x86.

#### Fall 2024
- I created [keymashed](https://github.com/kartva/keymashed/), an interactive exhibit at Purdue Hacker's [BURST](https://burst.purduehackers.com/). It contains interesting things, like:
  - a JPEG-like lossy codec written from scratch.
  - a realtime video streaming protocol and associated netcode.
- [filed a bug report for the Linux kernel's memory management subsystem](https://marc.info/?t=172402767200002&r=1&w=2).
- employed as a Research Assistant working with [Prof. Suresh Jagannathan](https://www.cs.purdue.edu/homes/suresh/) working on optimizing MRDTs.
- employed as a Teaching Assistant for Data Structures.
- employed as a developer teaching assistant for Programming in C. I created test modules for course assignments.
- (Relevant) classes:
  - Programming Languages. Assignments included:
    - writing lots of interpreters in OCaml (I enjoyed all of them).
    - writing an interpreter for a functional language with type inference and checking.
    - verifying simple programs in Dafny.
  - Systems Programming. Assigments included:
    - a malloc implementation. I made mine robust enough to run Chrome.
    - writing a shell with pipes, quoting, subshells, stream redirection (in C).
    - HTTP/1.1 web server with authorization, cgi-bin modules and dynamic module loading (in C).
    - (team project) a graphical system monitor (à la `top`). (in C++ and ImGui).
  - Analysis of Algorithms. Assignments included:
    - proving the correctness of dynamic programming and greedy algorithms.
    - creating information compression schemes and comparing against entropy.
    - proving the NP-completeness of given problems via reduction to a known NP-complete problems.
  - Independent Study in Embedded Systems with [Prof. Douglas Comer](https://en.wikipedia.org/wiki/Douglas_Comer), of TCP/IP fame.
    - designed audio streaming system with Raspberry Pis for concurrent audio playback.
    - wrote an [RTP](https://en.wikipedia.org/wiki/Real-time_Transport_Protocol)-like protocol for streaming audio over UDP.
- Went to the [Midwest Programming Languages Summit](https://pl.cs.uchicago.edu/PLSummit/2024/) at UChicago and met many interesting people!
- Attended every [PurPL (Purdue Programming Languages)](https://purduepl.github.io/) weekly seminar.

#### Summer 2024
- Google Summer of Code contributor for [icu4x](https://github.com/unicode-org/icu4x). Mentored by Younies Mehmoud from Google; almost all my coworkers ended up being Google employees. [Final report here.](https://gist.github.com/kartva/ff139f31876a42a0934ef84755596b2e)
- Summer Undergraduate Research Fellow at Purdue University studying [Mergeable Replicated Datatypes](https://www.cs.purdue.edu/homes/suresh/papers/oopsla19-mrdt.pdf) using [Irmin](https://irmin.org/) and OCaml.

#### Spring 2024
- I wrote [a clean inter-process communication program using POSIX shared memory](https://github.com/kartva/memtalk).
- I participated in the [Open Source Contributor Initiative by OpenSearch](https://opensearch.org/blog/Receive-mentorship-from-Amazon-engineers-and-accelerate-your-career-in-Tech/) and worked on the Performance Analyzer component in OpenSearch using Java.
- (Relevant) classes:
  - Competitive Programming 2: topics included segment trees, hashing, tries, graph algorithms, and combinatorics.
  - Computer Architecture: topics included assembly code, digital logic, processor architecture and _so much caching_
    - [I wrote a just-in-time compiler in Rust for ARMv8 assembly](https://github.com/kartva/k-lox-jit) as part of an honors project. It jitted on function call granularity and cached the generated assembly for future invocations.
  - Data Structures: topics included Big-O notation, heaps, binary trees, linked lists, tries, sorts, hashing, graphs, etc.
  - Linear Algebra
- Attended every [PurPL (Purdue Programming Languages)](https://purduepl.github.io/) weekly seminar.

#### Fall 2023
- (Relevant) classes:
  - Programming in C
  - Foundations of Computer Science / Discrete Math
  - Honors Multivariable Calculus
  - Independent study in the C++11 memory model with [Prof. Suresh Jagannathan](https://www.cs.purdue.edu/homes/suresh/). I explored tactics for designing performant and correct lock-free algorithms. _Report available on request (until I get around to publishing it)._
- Attended nearly every [PurPL (Purdue Programming Languages)](https://purduepl.github.io/) weekly seminar.
 
#### Before University
- I started working on Librarian with the Babraham Bioinformatics Institute in 2020. My work on Librarian was [published here](https://f1000research.com/articles/11-1122/v2) first in 2022, and then the revision in 2024.
- I briefly worked with [Trestle Labs](https://www.trestlelabs.com/) on computer vision using OpenCV in winter 2023.
- I was a competitive programmer and qualified for the Indian National Olympiad of Informatics (INOI) in 2020, 2021 and 2022. I studied [Antti Laaksonen's Competitive Programmer's Handbook](https://github.com/pllk/cphb/tree/master), from which I was inspired to write my first blog post on segment trees.

My [blog](https://desmondwillowbrook.github.io/blog/) - it's not completely up to date.
