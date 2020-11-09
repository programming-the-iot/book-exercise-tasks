# About book-exercise-tasks

NOTE: Project under development.

This project captures the requirements of the key chapter-by-chapter exercises found within my upcoming book, [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401). These requirements also map into the sample open source template repositories written in Python and Java, and map into an overarching Kanban board, which represents the activities you can work through to design and build a basic end-to-end IoT solution.

# What You'll Find In This Project

There are a number of repositories that provide the core content for this project and the [Kanban-based task board](https://github.com/orgs/programming-the-iot/projects/1) which brings everything together as a grouping of chapter-by-chapter exercises detailing the activities discussed in my book [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401) chapter.

You can view the requirements board here: [Programming the IoT Kanban board](https://github.com/orgs/programming-the-iot/projects/1).

# How the Exercises are Structured

The requirements contained within this repository are captured as a simple list of dozens of activities, labeled according to activity category, and named according to the chapter, component, and implementation order they represent.

## About the milestones and category labels
- Each entry is mapped to one milestone, which aligns to a chapter in the book:
  - [Chapter 01: Setup](https://github.com/orgs/programming-the-iot/projects/1#column-9974937)
  - [Chapter 02: Create Initial Apps](https://github.com/orgs/programming-the-iot/projects/1#column-9974938)
  - [Chapter 03: Sensor & Actuator Sim](https://github.com/orgs/programming-the-iot/projects/1#column-10488379)
  - [Chapter 04: Hardware Emulation](https://github.com/orgs/programming-the-iot/projects/1#column-10488386)
  - [Chapter 05: Data Management](https://github.com/orgs/programming-the-iot/projects/1#column-10488421)
  - [Chapter 06: MQTT Client - CDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488434)
  - [Chapter 07: MQTT Client - GDA](https://github.com/orgs/programming-the-iot/projects/1#column-10488499)
  - [Chapter 08: CoAP Server](https://github.com/orgs/programming-the-iot/projects/1#column-10488501)
  - [Chapter 09: CoAP Clients](https://github.com/orgs/programming-the-iot/projects/1#column-10488503)
  - [Chapter 10: Edge Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488510)
  - [Chapter 11: Cloud Integration](https://github.com/orgs/programming-the-iot/projects/1#column-10488514)
  - [Chapter 12: Semester Project](https://github.com/orgs/programming-the-iot/projects/1#column-10488565)
  
- Each entry has at least one category label, as follows:
  - [build](https://github.com/programming-the-iot/book-exercise-tasks/labels/build): Build and / or DevOps related task (e.g. checkout a new branch).
  - [configuration](https://github.com/programming-the-iot/book-exercise-tasks/labels/configuration): Configuration related task (e.g. install some software).
  - [documentation](https://github.com/programming-the-iot/book-exercise-tasks/labels/documentation): Documentation related task (e.g. write-up your approach).
  - [exercise](https://github.com/programming-the-iot/book-exercise-tasks/labels/exercise): Exercise related task (e.g. implement the specific requirements listed).
  - [optional](https://github.com/programming-the-iot/book-exercise-tasks/labels/optional): Optional exercise task (e.g. you can choose to implement this).
  - [integration](https://github.com/programming-the-iot/book-exercise-tasks/labels/integration): Test and integration related task (e.g. test connection between apps).
  
## About the naming and numbering convention
- Each entry is named according to the following convention: PIOT-{component}-{chapter}-{number}.
  - PIOT: The project name (Programming the Internet of Things).
  - component: This will be one of the following:
    - INF: An informational note
    - CFG: A configuration requirement
    - CDA: A requirement specific to the Constrained Device App
    - GDA: A requirement specific to the Gateway Device App
    - INT: An integration requirement that may include requirements specific to those labeled as CFG, CDA and / or GDA
- The structure of each chapter's notes and requirements following the guidelines listed below, and should be followed in the order given:
  - FIRST: Read the information (INF) notes to help guide you through the exercises.
    - Example: PIOT-INF-01-001 is the first (001) note in Chapter 01 associated with Programming the IoT (PIOT), and is for informational (INF) purposes.
  - SECOND: Read and implement the configuration (CFG) requirements to prepare for each exercise.
    - Example (CFG): PIOT-CFG-06-001 is the first (001) configuration-specific task in Chapter 06 associated with Programming the IoT (PIOT). It applies to the entire chapter.
  - THIRD: Read and implement each exercise related to the Constrained Device App (CDA) and / or the Gateway Device App (GDA).
    - Example (CDA): PIOT-CDA-01-001 is the first (001) CDA task in Chapter 01 associated with Programming the IoT (PIOT). It only applies to the Constrained Device App (CDA).
    - Example (GDA): PIOT-GDA-05-002 is the second (002) GDA task in Chapter 05 associated with Programming the IoT (PIOT). It only applies to the Gateway Device App (GDA), and should be implemented after PIOT-GDA-05-001.
  - FOURTH: Read and implement any integration exercise(s) to verify your functionality is working properly.
    - Example (INT): PIOT-INT-07-001 is the first (001) integration task in Chapter 07 associated with Programming the IoT (PIOT). It should be implemented AFTER all INT, CFG, CDA, and GDA related tasks.

NOTE: An exception to the number scheme is for build-specific tasks related to the CDA and GDA. The initial build requirement (check out a new branch) is numbered '000' for each component (e.g. PIOT-CDA-02-000) and should be implemented before any other component-specific requirement, and '100' for the final build requirement (e.g. PIOT-CDA-02-100), which should be implemented after all other component-specific requirements.

# Other things to know

## Pull requests
PR's are disabled while the codebase is being developed.

## Updates
Much of the tasks and issues representing requirements within this repository will continue to evolve, so please check back regularly for potential updates.

# DISCLAIMER
DISCLAIMER: This repository is still under active development - you'll likely find typos and other errata.

# LICENSE
Please see [LICENSE](https://github.com/programming-the-iot/python-components/blob/alpha001/LICENSE) if you plan to use this code.

Copyright (c) 2020. Andrew D. King. All rights reserved.
