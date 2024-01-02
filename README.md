# Programming the IoT - Book Exercise Tasks

This project captures the Lab Module exercises and associated requirements designed to align to each chapter in my O'Reilly Media book, [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401). Lab Module exercises align to each chapter, and can be found here:

 - [Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1)

# What You'll Find In This Project

There are dozens of exercises listed, each part of building a simple, end-to-end IoT solution - step by step. This content is based on the course I created for teaching introductory IoT concepts in a lab-based University course.

There are three primary repositories that provide the core content for this project: [python-components](https://github.com/programming-the-iot/python-components), [java-components](https://github.com/programming-the-iot/java-components), and of course [book-exercise-tasks](https://github.com/programming-the-iot/book-exercise-tasks).

The combination of these repositories, coupled with the [Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1) I mentioned previously, represent the lab exercises for the lab-based introductory IoT course I described. The principles and concepts associated with each milestone and chapter are explained in greater detail within my upcoming book [Programming the Internet of Things](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401).

If you're a student in Connected Devices, you'll find a fourth repository containing document templates (README files) for each Lab Module in [book-exercise-docs](https://github.com/programming-the-iot/book-exercise-docs). These templates will help you document your technical approach for each Lab Module and the Semester Project.

## Links, Exercises, Updates, Errata, and Clarifications

Please see the following links to access exercises, errata / clarifications, and the e-book:
 - [Programming the IoT Kanban Board](https://github.com/orgs/programming-the-iot/projects/1)
 - [Errata and Clarifications](https://labbenchstudios.com/programming-the-iot-book/programming-the-iot-1st-edition/)
 - [Programming the Internet of Things Book](https://learning.oreilly.com/library/view/programming-the-internet/9781492081401/)

# How Exercises are Organized

The requirements contained within this repository are captured as a simple list of dozens of tasks and activities - some are documentation-specific while most are programming-specific - and labeled according to activity category, chapter, and implementation order.

## About Lab Modules, Milestones and Labels

Each Lab Module listed below represents a single milestone, which maps to the like-named chapter in the book. Each has its own Kanban column and contains multiple exercises pertaining to the module:
  - [Lab Module 01: Setup](https://github.com/programming-the-iot/book-exercise-tasks/issues/167)
  - [Lab Module 02: Create Initial Apps](https://github.com/programming-the-iot/book-exercise-tasks/issues/202)
  - [Lab Module 03: Data Simulation](https://github.com/programming-the-iot/book-exercise-tasks/issues/170)
  - [Lab Module 04: Hardware Emulation](https://github.com/programming-the-iot/book-exercise-tasks/issues/172)
  - [Lab Module 05: Data Management](https://github.com/programming-the-iot/book-exercise-tasks/issues/174)
  - [Lab Module 06: MQTT Client - CDA](https://github.com/programming-the-iot/book-exercise-tasks/issues/177)
  - [Lab Module 07: MQTT Client - GDA](https://github.com/programming-the-iot/book-exercise-tasks/issues/180)
  - [Lab Module 08: CoAP Server](https://github.com/programming-the-iot/book-exercise-tasks/issues/183)
  - [Lab Module 09: CoAP Clients](https://github.com/programming-the-iot/book-exercise-tasks/issues/186)
  - [Lab Module 10: Edge Integration](https://github.com/programming-the-iot/book-exercise-tasks/issues/189)
  - [Lab Module 11: Cloud Integration](https://github.com/programming-the-iot/book-exercise-tasks/issues/193)
  - [Lab Module 12: Semester Project](https://github.com/programming-the-iot/book-exercise-tasks/issues/195)
  
Each exercise within a given Lab Module has at least one label, intended to assist with categorizing the work to be done, as follows:
  - [build](https://github.com/programming-the-iot/book-exercise-tasks/labels/build): Build and / or DevOps related task (e.g., checkout a new branch).
  - [configuration](https://github.com/programming-the-iot/book-exercise-tasks/labels/configuration): Configuration related task (e.g., install some software).
  - [documentation](https://github.com/programming-the-iot/book-exercise-tasks/labels/documentation): Documentation related task (e.g., write-up your approach).
  - [exercise](https://github.com/programming-the-iot/book-exercise-tasks/labels/exercise): Required exercise related task (i.e., you should implement this).
  - [additional](https://github.com/programming-the-iot/book-exercise-tasks/labels/additional): Additional exercise task (i.e., if you're a student in my class, you should implement this, although it is currently optional).
  - [integration](https://github.com/programming-the-iot/book-exercise-tasks/labels/integration): Test and integration related task (e.g., test connection between apps).
  
## About Naming and Numbering Conventions

Exercises and notes are named according to the following convention:

*{project name}-{category}-{lab module #}-{sequence #}*

This naming convention is designed to help you navigate through the requirements in each Lab Module sequentially, building your solution in a step-by-step manner. The naming breakdown is as follows:
  - project name:
    - PIOT: The project name (Programming the Internet of Things).
  - category:
    - DOC: General documentation that provides a summary overview of the section or lab module.
    - INF: An informational note.
    - STU: A student-specific requirement, usually documentation-related (this is relevant if enrolled in the Connected Devices course, for example).
    - CFG: A configuration requirement.
    - CDA: A Constrained Device App (CDA)-specific requirement.
    - GDA: A Gateway Device App (GDA)-specific requirement.
    - INT: An integration requirement that may depend upon other requirements specific to those labeled as CFG, CDA and / or GDA.
  - lab module #:
    - 01 - 12: Each Lab Module aligns to a Chapter in the book.
  - sequence #:
    - 001 - 099: Depicts the order in which the requirements should be implemented. Note that sequence #'s 000 and 100 are reserved, as indicated in the NOTE below.

The structure of each chapter's notes and requirements are sequenced based on the ordered guidelines listed below:
  - FIRST: Read the information (INF) notes to help guide you through the exercises.
    - Example (INF): PIOT-INF-01-001 is the first (001) note in Chapter 01 associated with Programming the IoT (PIOT), and is for informational (INF) purposes.
  - SECOND: If you're a student in a PIOT-specific course (e.g. Connected Devices), read through the STU category requirements to prepare for each exercise. Else, skip to the THIRD guideline.
    - Example (STU): PIOT-STU-02-001 is the first (001) student-specific task in Chapter 02 associated with Programming the IoT (PIOT). It applies to the entire chapter.
  - THIRD: Read and implement the configuration (CFG) requirements to prepare for each exercise.
    - Example (CFG): PIOT-CFG-06-001 is the first (001) configuration-specific task in Chapter 06 associated with Programming the IoT (PIOT). It applies to the entire chapter.
  - FOURTH: Read and implement each exercise related to the Constrained Device App (CDA) and / or the Gateway Device App (GDA).
    - Example (CDA): PIOT-CDA-01-001 is the first (001) CDA task in Chapter 01 associated with Programming the IoT (PIOT). It only applies to the Constrained Device App (CDA).
    - Example (GDA): PIOT-GDA-05-002 is the second (002) GDA task in Chapter 05 associated with Programming the IoT (PIOT). It only applies to the Gateway Device App (GDA), and should be implemented after PIOT-GDA-05-001.
  - FIFTH: Read and implement any integration exercise(s) to verify your functionality is working properly.
    - Example (INT): PIOT-INT-07-001 is the first (001) integration task in Chapter 07 associated with Programming the IoT (PIOT). It should be implemented AFTER all INT, CFG, CDA, and GDA related tasks.

NOTE: As alluded to previously, an exception to the numbering sequence scheme is made for build-specific tasks related to the CDA and GDA. The initial build requirement (check out a new branch) is numbered '000' for each component (e.g., PIOT-CDA-02-000) and should be implemented before any other component-specific requirement, and '100' for the final build requirement (e.g., PIOT-CDA-02-100), which should be implemented after all other component-specific requirements.

# Other Things to Know

## Pull Requests

PR's are currently disabled.

## Updates

Much of the tasks and issues representing requirements within this repository will continue to evolve, so you may want to check back regularly for potential updates. Please note that this repository is still under active development - you'll likely find typos and other errata.

# License

Please see [LICENSE and USAGE information in PIOT-DOC-LIC](https://github.com/programming-the-iot/book-exercise-tasks/issues/165) for more information.

*Documentation - Usage and License*

This project's [written instructions and non-source code documentation](https://github.com/orgs/programming-the-iot/projects/1) - including this README.md file, all [Issues](https://github.com/programming-the-iot/book-exercise-tasks/issues), and the Notes, Instructions and Cards contained within the [Kanban board](https://github.com/orgs/programming-the-iot/projects/1) - are available under the following license:

 - Documentation: Copyright &copy; 2020 - 2024 by [Andrew D. King](https://andyking.me). Licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/ " target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0 <img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img height="24" style="!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a>
 - See [LICENSE](https://github.com/programming-the-iot/book-exercise-tasks/blob/default/LICENSE) for details.

*Source Code Solutions and Examples - Usage and License*

This project's [written instructions](https://github.com/orgs/programming-the-iot/projects/1) and [Issues](https://github.com/programming-the-iot/book-exercise-tasks/issues) documents contain sample source codes representing examples and solutions. Unless otherwise represented, these inline source codes (Java and Python) are available under the following license:

 - Inline Source Codes: Copyright &copy; 2020 - 2024 [Andrew D. King](https://andyking.me). Licensed under [The MIT License](https://opensource.org/licenses/MIT)
 - See [LICENSE-CODE](https://github.com/programming-the-iot/book-exercise-tasks/blob/default/LICENSE-CODE) for details.

Please refer to the referenced [python-components](https://github.com/programming-the-iot/python-components) and [java-components](https://github.com/programming-the-iot/java-components) repositories for their respective usage licenses, including any external dependencies and associated references.

# References

## Tools and Specifications

- [CoAP RFC 7252](https://tools.ietf.org/html/rfc7252)
  - Reference: Z. Shelby, K. Hartke, and C. Bormann. The Constrained Application Protocol (CoAP). IETF Proposed Standard RFC 7252, 2014. Available: https://tools.ietf.org/html/rfc7252.
- [JSON](https://tools.ietf.org/html/rfc8259)
  - Reference: T. Bray. The JavaScript Object Notation (JSON) Data Interchange Format. IETF Internet Standard RFC 8259, 2017. Available: https://tools.ietf.org/html/rfc8259.
- [MQTT v 3.1.1](https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html)
  - Reference: A. Banks, R. Gupta. MQTT Version 3.1.1. OASIS Standard, 2014. Available: https://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html.
- [Redis](https://redis.io/)
  - Reference: S. Sanfilippo. Redis. (2006 - 2020) [Online]. Available: https://github.com/redis/redis.
- [Sense-Emu](https://sense-emu.readthedocs.io/en/v1.1/)
  - Reference: The Raspberry Pi Foundation. Sense HAT Emulator. (2016) [Online]. Available: https://sense-emu.readthedocs.io/en/v1.0/.
- [Wireshark](https://www.wireshark.org/)
  - Reference: G. Combs et al. Wireshark. (2020) [Online]. Available: https://gitlab.com/wireshark/wireshark.

## Sample code and dependencies

For tasks and issues related to [python-components](https://github.com/programming-the-iot/python-components), please see [python-components references](https://github.com/programming-the-iot/python-components#references)

For tasks and issues related to [java-components](https://github.com/programming-the-iot/java-components), please see [java-components references](https://github.com/programming-the-iot/java-components#references)
