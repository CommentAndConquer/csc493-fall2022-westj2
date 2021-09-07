## CSC493: R04: Software Design<sup>1</sup>

## Overview
You have created the <code>requirements.md</code> file that should have started to outline the requirements for your project.

## Documentation

You have two tasks to complete before next time:
- Complete agile report
- Complete the Preliminary Software Requirements Specification (SRS) which you began last time. You will add a file called design.md.

<code>README.md</code>
- Project name
- [Project proposal (including purpose)](r01-project-concept.md)
- [Vision](r02-scope.md)
- [Scope](r02-scope.md)
- Prerequisites
- Built With
- Author name
- Acknowledgments
- [Concept (linked to concept.md)](r01-project-concept.md)
  - Goals
  - Context
  - Novelty
  - Functionality
  - Audience
  - Challenges
  - Measures
  - Motivation
  - Future Extensions
  - *Other (Optional)*
- [Requirements (linked to requirements.md)](r03-requirements.md)
  - formal list of requirements
- **[Design (linked to design.md)](r04-design.md)**

This week’s new work will move from the planning and analysis phase to beginning to the design phase of the software project.

It is well understood by strong software developers that the functional elements of a program should not
ever be allowed to become too large. If any component of a program grows beyond the size where it's
readily comprehensible as a unit, it can too easily conceal errors. Thus, any software with large
components is likely to be harder to read, harder to test, and harder to debug. The design process
clarifies exactly how the developer plans to implement the design specifications, i.e. how the software is
to be written, and with which small components. In particular, the main work of this first part of the
design phase is to present an architectural model of the software components.

Create a new file called design.md.

Ultimately, the software architectural design must be:

- a simplified description of the entire planned project system which abstracts the essentials and ignores the non-essentials;
- defines the major software components (classes, methods, etc);
- uses a hierarchical presentation which makes the system simple to understand;
- shows the flow of control and data through the system;
- is organized according to consistent conventions;
- can be used for reasoning about the software system.

Any architectural software design which satisfies the above criteria may be used. Many
software developers use schematic designs of the planned software components as part of
their modeling description, but this is not required. It is acceptable to list the planned
software components with brief descriptions as long as the control hierarchy and
interactions among the components are also made clear.

**Note: For next time, you only need to begin this work. You will be fleshing out more details in over the next week.
So, feel free to use a very high level design for next time.**

You should also have a relative link to design.md from README.md. Test this link and make sure it works.


---
# To Submit
In addition to creating the <code>design.md</code> file, update <code>README.md</code> with any improvements.

<sub>1. Adapted from [https://github.com/pearcej/pearcej.github.io/edit/master/csc493/r04-design.md](https://https://github.com/pearcej/pearcej.github.io/edit/master/csc493/r04-design.md)</sub>
