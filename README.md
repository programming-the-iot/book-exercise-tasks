# About book-exercise-tasks

This project captures the requirements of the key chapter-by-chapter exercises found within my upcoming book, [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401). You can view the exercises using the Kanboan board I created, which organizes each into a grouping of milestones and chapters related to the structure of the book.

[Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1)

# What You'll Find In This Project

There are dozens of exercises listed, each part of building a simple, end-to-end IoT solution - step by step. This content is based on the course I created for teaching introductory IoT concepts in a lab-based University course.

There are three primary repositories that provide the core content for this project: [python-components](https://github.com/programming-the-iot/python-components), [java-components](https://github.com/programming-the-iot/java-components), and of course [book-exercise-tasks](https://github.com/programming-the-iot/book-exercise-tasks).

The combination of these repositories, coupled with the [Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1) I mentioned previously, represent the lab exercises for the lab-based introductory IoT course I described. The principles and concepts associated with each milestone and chapter are explained in greater detail within my upcoming book [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).

These exercises are intended for learning purposes only, and to help you gain further understanding of how a simple IoT system functions.

# How Exercises are Organized

The requirements contained within this repository are captured as a simple list of dozens of tasks and activities - some are documentation-specific while most are programming-specific - and labeled according to activity category, chapter, and implementation order.

## About Milestones and Labels
- Each item listed below represents a single milestone and Kanban column, and contains multiple exercises. These are also aligned to each chapter in the book:
  - [Chapter 01: Setup](https://github.com/orgs/programming-the-iot/projects/1#column-9974937)
  - [Chapter 02: Create Initial Apps](https://github.com/orgs/programming-the-iot/projects/1#column-9974938)
  - [Chapter 03: Data Simulation](https://github.com/orgs/programming-the-iot/projects/1#column-10488379)
  - [Chapter 04: Hardware Emulation](https://github.com/orgs/programming-the-iot/projects/1#column-10488386)
  - [Chapter 05: Data Management](https://github.com/orgs/programming-the-iot/projects/1#column-10488421)
  - [Chapter 06: MQTT Client - CDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488434)
  - [Chapter 07: MQTT Client - GDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488499)
  - [Chapter 08: CoAP Server](https://github.com/orgs/programming-the-iot/projects/1#column-10488501)
  - [Chapter 09: CoAP Clients](https://github.com/orgs/programming-the-iot/projects/1#column-10488503)
  - [Chapter 10: Edge Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488510)
  - [Chapter 11: Cloud Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488514)
  - [Chapter 12: Semester Project](https://github.com/orgs/programming-the-iot/projects/1#column-10488565)
  
- Each exercise within a given milestone has at least one label, intended to assist with categorizing the work to be done, as follows:
  - [build](https://github.com/programming-the-iot/book-exercise-tasks/labels/build): Build and / or DevOps related task (e.g. checkout a new branch).
  - [configuration](https://github.com/programming-the-iot/book-exercise-tasks/labels/configuration): Configuration related task (e.g. install some software).
  - [documentation](https://github.com/programming-the-iot/book-exercise-tasks/labels/documentation): Documentation related task (e.g. write-up your approach).
  - [exercise](https://github.com/programming-the-iot/book-exercise-tasks/labels/exercise): Exercise related task (e.g. implement the specific requirements listed).
  - [optional](https://github.com/programming-the-iot/book-exercise-tasks/labels/optional): Optional exercise task (e.g. you can choose to implement this).
  - [integration](https://github.com/programming-the-iot/book-exercise-tasks/labels/integration): Test and integration related task (e.g. test connection between apps).
  
## About Naming and Numbering Conventions
- Each entry is named according to the following convention: PIOT-{category}-{chapter}-{number}.
  - PIOT: The project name (Programming the Internet of Things).
  - component: This will be one of the following:
    - INF: An informational note
    - STU: A student-specific requirement, usually documentation-related (this is relevant if enrolled in the Connected Devices course, for example)
    - CFG: A configuration requirement
    - CDA: A Constrained Device App (CDA)-specific requirement
    - GDA: A Gateway Device App (GDA)-specific requirement
    - INT: An integration requirement that may depend upon other requirements specific to those labeled as CFG, CDA and / or GDA
- The structure of each chapter's notes and requirements are sequenced based on the ordered guidelines listed below:
  - FIRST: Read the information (INF) notes to help guide you through the exercises.
    - Example (INF): PIOT-INF-01-001 is the first (001) note in Chapter 01 associated with Programming the IoT (PIOT), and is for informational (INF) purposes.
  - SECOND: If you're a student in a PIOT-specific course (e.g. Connected Devices), read and implement the configuration (STU) requirements to prepare for each exercise. Else, skip to the THIRD guideline.
    - Example (STU): PIOT-STU-02-001 is the first (001) student-specific task in Chapter 02 associated with Programming the IoT (PIOT). It applies to the entire chapter.
  - THIRD: Read and implement the configuration (CFG) requirements to prepare for each exercise.
    - Example (CFG): PIOT-CFG-06-001 is the first (001) configuration-specific task in Chapter 06 associated with Programming the IoT (PIOT). It applies to the entire chapter.
  - FOURTH: Read and implement each exercise related to the Constrained Device App (CDA) and / or the Gateway Device App (GDA).
    - Example (CDA): PIOT-CDA-01-001 is the first (001) CDA task in Chapter 01 associated with Programming the IoT (PIOT). It only applies to the Constrained Device App (CDA).
    - Example (GDA): PIOT-GDA-05-002 is the second (002) GDA task in Chapter 05 associated with Programming the IoT (PIOT). It only applies to the Gateway Device App (GDA), and should be implemented after PIOT-GDA-05-001.
  - FIFTH: Read and implement any integration exercise(s) to verify your functionality is working properly.
    - Example (INT): PIOT-INT-07-001 is the first (001) integration task in Chapter 07 associated with Programming the IoT (PIOT). It should be implemented AFTER all INT, CFG, CDA, and GDA related tasks.

NOTE: An exception to the numbering scheme is made for build-specific tasks related to the CDA and GDA. The initial build requirement (check out a new branch) is numbered '000' for each component (e.g., PIOT-CDA-02-000) and should be implemented before any other component-specific requirement, and '100' for the final build requirement (e.g., PIOT-CDA-02-100), which should be implemented after all other component-specific requirements.

# Other Things to Know

## Pull Requests
PR's are disabled while the codebase and documentation is being developed.

## Updates
Much of the tasks and issues representing requirements within this repository will continue to evolve, so you may want to check back regularly for potential updates. Please note that this repository is still under active development - you'll likely find typos and other errata.

# License
The requirements and notes listed in this repository: <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

The source code with the projects [python-components](https://github.com/programming-the-iot/python-components) and [java-components](https://github.com/programming-the-iot/java-components) are licensed separately, as per the LICENSE file located in each repository. Any dependencies referenced by these projects will have their own respective license and usage constraints. Please be sure to review each before using any of these repositories.

Copyright :copyright: 2020 Andrew D. King. All rights reserved.
